# Quick Start Guide — Швидкий старт

**5-хвилинний гайд як я використовую свою промпт-систему**

---

## Крок 1: Збір інформації

Я зазвичай збираю таку інформацію:

1. **Тип кімнати:** living room / bedroom / kitchen / bathroom
2. **Стиль:** modern / scandinavian / industrial / minimalist / etc.
3. **Настрій:** cozy / bright / elegant / calm / etc.
4. **Бюджет:** budget-friendly / mid-range / luxury
5. **Кольори:** warm neutrals / cool tones / earthy / etc.
6. **Особливі вимоги:** reading corner / kitchen island / lots of plants / etc.

**Приклад:**
> "Хочу сучасну вітальню, щось затишне і світле. Бюджет середній. Люблю нейтральні кольори з зеленими акцентами."

---

## Крок 2: Відкрити мій шаблон

Відкриваю: `prompts/main_template.txt`

Знаходжу секцію з фігурними дужками {} - це змінні які треба замінити.

---

## Крок 3: Заповнити змінні

Я замінюю плейсхолдери на конкретні значення:

**Для прикладу вище:**

```
{ROOM_TYPE} → living room
{STYLE} → Modern
{MOOD} → cozy and bright  
{BUDGET_TIER} → mid-range
{COLOR_PALETTE} → neutral with green accents
{SPECIAL_REQUIREMENTS} → comfortable seating, plants
```

**Результат:** Отримаєте повний готовий промпт!

---

## Крок 4: Додати Negative Prompt

Відкриваю: `prompts/negative_template.txt`

Я зазвичай роблю так:
1. Беру **BASE** негативний промпт (обов'язково!)
2. Додаю секцію для **бюджету** (budget-friendly / mid-range / luxury)
3. Додаю секцію для **типу кімнати** (bedroom / kitchen / etc.)
4. Об'єдную все в один рядок через коми

---

## Крок 5: Згенерувати!

Я використовую:
- **Assembled Main Prompt** (з кроку 3)
- **Negative Prompt** (з кроку 4)
- **Вхідне зображення** порожньої кімнати

**Параметри які використовую:**
```
Strength: 0.8
Steps: 40
Variants: 3
Guidance: 7.5
```

---

## Крок 6: Перевірити якість

Я завжди використовую свій checklist: `QUALITY_CHECKLIST.md`

Швидка перевірка (30 секунд):

- ✅ Геометрія кімнати збережена?
- ✅ Масштаб меблів реалістичний?
- ✅ Відповідає стилю?
- ✅ Немає AI артефактів?

Якщо всі 4 ✅ = OK!

Якщо є проблеми → дивіться розділ "Якщо потрібен Regenerate" в QUALITY_CHECKLIST

---

## 🎯 Приклад повного Workflow

### Запит від клієнта:
> "Спальня в скандинавському стилі, світла, затишна, бюджетна"

### 1. Визначаємо змінні:
```
ROOM_TYPE = bedroom
STYLE = Scandinavian  
MOOD = bright and cozy
BUDGET_TIER = budget-friendly
COLOR_PALETTE = white and natural wood tones
SPECIAL_REQUIREMENTS = natural materials
```

### 2. Заповнюємо main_template.txt
(замінюємо всі {} на значення вище)

### 3. Складаємо negative prompt:
```
[BASE негативний] + 
[budget-friendly обмеження] + 
[bedroom обмеження]
```

### 4. Генеруємо з параметрами:
```
strength: 0.75
steps: 35
variants: 2
```

### 5. Перевіряємо результат
Чекліст пройдено? → Показуємо клієнту!

---

## 💡 Корисні поради

### Якщо не знаєте що писати:

**Для стилю:**
- Подивіться `style_library.md` - там описи всіх стилів

**Для кольорів:**
- Нейтральні: white, beige, grey, taupe
- Теплі: warm neutrals, earthy tones
- Холодні: cool greys, blues

**Для настрою:**
- Cozy, bright, calm, elegant, bold, fresh, relaxing

**Для прикладів:**
- Відкрийте `examples/README.md` - там 8 готових прикладів

---

## 🔍 Troubleshooting - Швидке вирішення проблем

| Проблема | Рішення |
|----------|---------|
| Геометрія змінилась | Промпт має секцію "CRITICAL" - переконайтесь що вона є |
| Меблі завеликі | Додайте "standard furniture dimensions" в промпт |
| Не той стиль | Подивіться style_library.md і додайте більше деталей |
| AI артефакти | Посильте negative prompt, збільште steps до 45-50 |
| Занадто дорого виглядає | Перевірте що в negative є luxury обмеження |
| Занадто дешево | Впевніться що budget tier правильний (не budget-friendly якщо треба mid/luxury) |

---

## 📁 Структура файлів - Що де шукати

```
├── README.md                    ← Повний опис системи
├── QUICK_START.md              ← ВИ ТУТ! Швидкий старт
├── FAQ.md                      ← Відповіді на часті питання
├── QUALITY_CHECKLIST.md        ← Як перевіряти результати
├── changelog.md                ← Історія змін та ітерацій
├── style_library.md            ← Описи стилів (довідник)
│
├── prompts/
│   ├── main_template.txt       ← ГОЛОВНИЙ промпт (заповнюй це!)
│   ├── negative_template.txt   ← Негативний промпт
│   ├── constraints.txt         ← Правила та обмеження (читати для розуміння)
│   └── quality_check.txt       ← Детальна перевірка (авто чи мануал)
│
└── examples/
    ├── README.md               ← Огляд всіх прикладів
    └── example_01-08.md        ← 8 готових прикладів
```

---

## ⚡ Express Mode (ще швидше!)

### Якщо треба дуже швидко:

1. Візьміть **найсхожіший приклад** з `examples/`
2. Змініть тільки **конкретні деталі** під ваш запит
3. Згенеруйте!

**Приклад:**
- Треба Modern Living → відкрити `example_01_modern_living.md`
- Скопіювати готовий промпт звідти
- Змінити тільки color_palette якщо треба інші кольори
- Done!

---

## 📞 Feedback Loop

Після кожної генерації:

1. **Що спрацювало?** → нотуйте для майбутнього
2. **Що не спрацювало?** → що треба змінити в промпті?
3. **Оновіть параметри** якщо треба (strength, steps)

Це допоможе швидше досягати якісних результатів!

---

## ✅ Checklist перед стартом

Перед першою генерацією переконайтесь:

- [ ] Маю вхідне зображення порожньої кімнати
- [ ] Знаю тип кімнати, стиль, бюджет
- [ ] Заповнив main_template.txt
- [ ] Склав negative prompt
- [ ] Готовий перевірити результат з QUALITY_CHECKLIST

Якщо всі ✅ → поїхали генерувати! 🚀

---

## 🎓 Наступні кроки

Після першої успішної генерації:

1. **Прочитайте changelog.md** - щоб зрозуміти чому промпт саме такий
2. **Вивчіть style_library.md** - щоб краще розуміти різні стилі
3. **Перегляньте всі 8 examples** - це дасть розуміння різних сценаріїв
4. **Експериментуйте з параметрами** - strength, steps для різних результатів

---

## 💬 Допомога

Якщо щось незрозуміло:

- **Загальні питання** → [README.md](README.md)
- **Часті питання** → [FAQ.md](FAQ.md) ⭐ Нове!
- **Як працювати зі стилями** → [style_library.md](style_library.md)
- **Приклади використання** → [examples/](examples/)
- **Історія та обґрунтування** → [changelog.md](changelog.md)
- **Технічні деталі промптів** → [prompts/constraints.txt](prompts/constraints.txt)

---

**Готово! За 5 хвилин можна згенерувати перший якісний результат! 🎨**

# Приклад #4 — Minimalist Bathroom (Mid-range)

## Користувацький Запит

"Хочу ванну кімнату в мінімалістичному стилі, щось спокійне і чисте. Світлі тони, можливо трохи натурального каменю. Бюджет середній."

## Вхідні Дані

**Тип кімнати:** Bathroom  
**Стиль:** Minimalist  
**Настрій:** Calm and clean  
**Бюджет:** Mid-range  
**Кольорова палітра:** Light tones, natural stone accents  
**Спеціальні вимоги:** Simple and functional design

**Посилання на вхідне зображення порожньої кімнати:**  
https://images.unsplash.com/photo-1584622650111-993a426fbf0a (empty bathroom)

## Згенерований Промпт

### Main Prompt:

```
Create a photorealistic interior design rendering of a bathroom in Minimalist style.

## Room Preservation (CRITICAL):
- Maintain the EXACT room geometry: preserve all existing walls, windows, doors, and architectural features from the input image
- Keep the same room dimensions, ceiling height, and floor area
- Do not add or remove structural elements
- Respect the natural light sources (windows placement and size)

## Style & Mood:
- Style: Minimalist
- Mood: Calm and clean
- Color palette: Light tones, natural stone accents

## Design Requirements:
- Budget tier: Mid-range
- Room type: Bathroom
- Special requirements: Simple and functional design

## Material & Finish Guidelines:
- Use realistic, commercially available materials appropriate for mid-range budget
- Ensure proper material scaling (tiles, wood planks, fabric patterns should be life-size)
- Apply physically accurate lighting and shadows
- Include subtle imperfections for photorealism (slight wear, natural variations)

## Furniture & Layout:
- Select furniture appropriate for bathroom function
- Maintain proper scale and proportions (standard furniture dimensions)
- Ensure practical arrangement with adequate walking space
- Include only necessary items (avoid overcrowding)

## Lighting:
- Use natural lighting from existing windows
- Add appropriate artificial lighting fixtures for bathroom
- Create realistic light behavior (soft shadows, ambient occlusion)
- Match lighting mood to calm and clean atmosphere

## Quality Standards:
- Photorealistic rendering quality
- Professional interior photography angle and composition
- No visible AI artifacts or distortions
- Coherent design that follows real-world interior design principles

## Context:
This is a mid-range renovation/design project for a bathroom, aiming to achieve a Minimalist aesthetic with a calm and clean atmosphere.
```

### Negative Prompt:

```
distorted geometry, warped walls, impossible architecture, curved floor, slanted ceiling, missing walls, extra walls, changed room shape, altered windows position, added doors, removed doors, unrealistic perspective, fish-eye distortion, oversized furniture, miniature objects, wrong scale, giant decorations, tiny windows, disproportionate elements, furniture too large for space, impractical layout, blurry textures, low resolution materials, repetitive patterns, obvious tiling, pixelated surfaces, plastic-looking materials, fake textures, unrealistic reflections, overexposed, underexposed, artificial HDR look, blown out highlights, crushed blacks, inconsistent lighting direction, multiple sun sources, unnatural shadows, watermark, signature, text, labels, UI elements, frame borders, distorted faces in photos/art, melted objects, merged furniture, duplicate items, floating objects, cluttered space, too many decorations, messy arrangement, random objects, incoherent style mixing, cheap-looking, tacky decor, unrealistic colors, fantasy elements, sci-fi objects, impossible structures, levitating furniture, transparent walls, glowing objects without light source, magical effects, extreme luxury, custom millwork, imported exotic materials, museum-quality art, soft furniture, carpets, bedroom items, kitchen appliances
```

### Generation Parameters:

```yaml
strength: 0.8
steps: 40
num_variants: 3
guidance_scale: 7.5
seed: random
```

## Design Intent Summary

"Спокійна мінімалістична ванна кімната у світлих тонах з натуральним камінням, де кожен елемент функціональний і необхідний, створюючи атмосферу чистоти та релаксації."

## Applied Constraints Checklist

- ✅ Збережено геометрію кімнати
- ✅ Застосовано mid-range бюджет
- ✅ Відповідає Minimalist стилю
- ✅ Використано вологостійкі матеріали
- ✅ Тільки необхідні елементи для ванної
- ✅ Світла палітра з natural stone

## Очікуваний Результат

**Що має вийти:**
- Велика біла раковина (можливо rectangular накладна)
- Душова кабіна зі скляною перегородкою
- Біла сантехніка (унітаз, біде якщо місце дозволяє)
- Світла плитка (біла, бежева, світло-сіра)
- Акцентна стіна з натурального каменю або текстурної плитки
- Мінімалістичні chrome або матові чорні змішувачі
- Вбудовані полиці або ніші
- Проста дзеркало (можливо з підсвіткою)
- Прихований або мінімалістичний стелевий світильник

**Матеріали:**
- Керамічна плитка (великого формату)
- Натуральний камінь (акценти)
- Скло
- Хром або матовий метал для фурнітури

## Що Спрацювало / Що Покращити

### ✅ Спрацювало:
- Minimalist стиль природно обмежує кількість елементів
- Calm and clean mood задає правильну атмосферу
- Natural stone accents додає текстури без перевантаження

### 🔧 Можна покращити:
- Якщо занадто порожньо, додати "built-in storage niches"
- Для більшого spa-відчуття: "spa-like atmosphere, rainfall showerhead"
- Якщо потрібна ванна замість душу, вказати це явно в special requirements

## Примітки

Ванна кімната - специфічний простір з чіткими функціональними вимогами. Важливо:
1. Використовувати тільки вологостійкі матеріали
2. Не додавати м'які меблі чи килими (це в негативному промпті)
3. Забезпечити достатнє освітлення
4. Зберегти розташування вікон (якщо є) для вентиляції

Мінімалізм тут працює добре, бо ванна не повинна бути перевантажена декором - функціональність на першому місці.

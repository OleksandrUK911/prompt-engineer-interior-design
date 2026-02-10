# Приклад #7 — Bohemian Living Room (Mid-range)

## Користувацький Запит

"Вітальня в богемному стилі, люблю багато кольорів, рослини, різні текстури. Щось креативне і живе, але не занадто дороге. Хочу відчуття подорожей і творчості."

## Вхідні Дані

**Тип кімнати:** Living room  
**Стиль:** Bohemian  
**Настрій:** Creative and lively  
**Бюджет:** Mid-range  
**Кольорова палітра:** Warm eclectic mix, earthy tones with colorful accents  
**Спеціальні вимоги:** Lots of plants, mixed textiles, vintage elements, artistic feel

**Посилання на вхідне зображення порожньої кімнати:**  
https://images.unsplash.com/photo-1598928506311-c55ded91a20c (empty living room with good light)

## Згенерований Промпт

### Main Prompt:

```
Create a photorealistic interior design rendering of a living room in Bohemian style.

## Room Preservation (CRITICAL):
- Maintain the EXACT room geometry: preserve all existing walls, windows, doors, and architectural features from the input image
- Keep the same room dimensions, ceiling height, and floor area
- Do not add or remove structural elements
- Respect the natural light sources (windows placement and size)

## Style & Mood:
- Style: Bohemian
- Mood: Creative and lively
- Color palette: Warm eclectic mix, earthy tones with colorful accents

## Design Requirements:
- Budget tier: Mid-range
- Room type: Living room
- Special requirements: Lots of plants, mixed textiles, vintage elements, artistic feel

## Material & Finish Guidelines:
- Use realistic, commercially available materials appropriate for mid-range budget
- Ensure proper material scaling (tiles, wood planks, fabric patterns should be life-size)
- Apply physically accurate lighting and shadows
- Include subtle imperfections for photorealism (slight wear, natural variations)

## Furniture & Layout:
- Select furniture appropriate for living room function
- Maintain proper scale and proportions (standard furniture dimensions)
- Ensure practical arrangement with adequate walking space
- Include only necessary items (avoid overcrowding)

## Lighting:
- Use natural lighting from existing windows
- Add appropriate artificial lighting fixtures for living room
- Create realistic light behavior (soft shadows, ambient occlusion)
- Match lighting mood to creative and lively atmosphere

## Quality Standards:
- Photorealistic rendering quality
- Professional interior photography angle and composition
- No visible AI artifacts or distortions
- Coherent design that follows real-world interior design principles

## Context:
This is a mid-range renovation/design project for a living room, aiming to achieve a Bohemian aesthetic with a creative and lively atmosphere.
```

### Negative Prompt:

```
distorted geometry, warped walls, impossible architecture, curved floor, slanted ceiling, missing walls, extra walls, changed room shape, altered windows position, added doors, removed doors, unrealistic perspective, fish-eye distortion, oversized furniture, miniature objects, wrong scale, giant decorations, tiny windows, disproportionate elements, furniture too large for space, impractical layout, blurry textures, low resolution materials, repetitive patterns, obvious tiling, pixelated surfaces, plastic-looking materials, fake textures, unrealistic reflections, overexposed, underexposed, artificial HDR look, blown out highlights, crushed blacks, inconsistent lighting direction, multiple sun sources, unnatural shadows, watermark, signature, text, labels, UI elements, frame borders, distorted faces in photos/art, melted objects, merged furniture, duplicate items, floating objects, messy arrangement, fantasy elements, sci-fi objects, impossible structures, levitating furniture, transparent walls, glowing objects without light source, magical effects, extreme luxury, custom millwork, imported exotic materials, museum-quality art, bed, bathroom fixtures, kitchen appliances, professional gym equipment, sterile minimalism, cold atmosphere
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

"Жива богемна вітальня з еклектичним міксом текстур, великою кількістю рослин, vintage елементами та барвистими акцентами, створюючи креативний і well-traveled простір без переходу в хаос."

## Applied Constraints Checklist

- ✅ Збережено геометрію кімнати
- ✅ Mid-range бюджет (не luxury, не cheap)
- ✅ Богемний стиль з mixed elements
- ✅ Багато рослин (як запитано)
- ✅ Mixed textiles і vintage елементи
- ✅ Креативна, жива атмосфера
- ✅ Уникнуто хаосу (завдяки "avoid overcrowding")

## Очікуваний Результат

**Що має вийти:**

**Меблі:**
- Диван з текстильною оббивкою (можливо з візерунками)
- Mix подушок різних кольорів та патернів
- Vintage журнальний столик (дерево, можливо потертий вигляд)
- Килим з етнічними візерунками (Persian, Moroccan, Turkish style)
- Плетене крісло або пуф

**Рослини (важливо!):**
- 5-7 різних рослин різних розмірів
- Підвісні кашпо в macramé
- Великі підлогові рослини (Monstera, Fiddle Leaf Fig)
- Маленькі на столиках та полицях

**Декор:**
- Настінні прикраси: макраме, тканини, постери
- Різні рамки з фото/арт (різних розмірів)
- Свічки, керамічні вази
- Книги на столику
- Travel souvenirs (етнічні елементи)

**Кольори:**
- База: earthy (терракота, beige, brown)
- Акценти: mustard yellow, burnt orange, teal, burgundy
- Багато текстур: вовна, макраме, дерево, метал

**Освітлення:**
- Природне світло з вікон
- Warm ambient lighting (можливо string lights)
- Vintage-style лампа або торшер

## Що Спрацювало / Що Покращити

### ✅ Спрацювало:
- "Lots of plants" забезпечує їх присутність
- "Mixed textiles" створює layered look
- "Vintage elements" додає характеру
- "Artistic feel" дозволяє творчі елементи
- "Avoid overcrowding" в furniture section запобігає хаосу

### 🔧 Можна покращити:
- Якщо недостатньо рослин: "at least 5-7 plants of various sizes, including hanging plants"
- Для більшої bohemian vibe: "macramé wall hangings, ethnic textiles, traveled aesthetic"
- Якщо занадто хаотично: "organized eclectic, curated bohemian look"
- Якщо замало кольору: "colorful throw pillows, vibrant textile patterns"

### ⚠️ Складності Bohemian Стилю:

1. **Тонка лінія між bohemian і messy** - важливо "avoid overcrowding"
2. **Багато елементів** - ризик AI overload, може з'явитись багато дрібниць
3. **Mixed patterns** - може вийти chaos, якщо не обмежити

## Примітки

**Bohemian стиль - один з найскладніших для AI генерації** через:

1. **Еклектичність** - мікс різних стилів, епох, культур
2. **Багато деталей** - рослини, текстиль, декор, але не безлад
3. **Balance** - має виглядати "curated chaos", а не просто хаос

**Ключові елементи для Boho:**
- ✅ Рослини (критично важливі)
- ✅ Layered textiles (килими, подушки, пледи)
- ✅ Vintage/handmade елементи
- ✅ Ethnic patterns
- ✅ Warm, earthy colors з яскравими акцентами
- ✅ Travel-inspired декор

**Що допомагає контролювати:**
- "Avoid overcrowding" в constraints
- "Coherent design" в quality standards
- Mid-range budget обмежує excessive luxury
- Конкретна згадка plants і textiles

Цей приклад показує як система справляється з **максималістськими стилями** (на противагу мінімалізму з інших прикладів). Потребує балансу між "достатньо деталей" і "не перевантажено".

# Приклад #1 — Modern Living Room (Mid-range)

## Користувацький Запит

"Хочу сучасну вітальню з мінімалістичним підходом. Люблю нейтральні кольори з акцентами сірого та чорного. Бюджет середній. Обов'язково потрібен зручний диван для перегляду фільмів та місце для квітів."

## Вхідні Дані

**Тип кімнати:** Living room  
**Стиль:** Modern  
**Настрій:** Clean and comfortable  
**Бюджет:** Mid-range  
**Кольорова палітра:** Neutral with grey and black accents  
**Спеціальні вимоги:** Comfortable sofa for watching movies, space for plants

**Посилання на вхідне зображення порожньої кімнати:**  
https://images.unsplash.com/photo-1583847268964-b28dc8f51f92 (empty living room with windows)

## Згенерований Промпт

### Main Prompt:

```
Create a photorealistic interior design rendering of a living room in Modern style.

## Room Preservation (CRITICAL):
- Maintain the EXACT room geometry: preserve all existing walls, windows, doors, and architectural features from the input image
- Keep the same room dimensions, ceiling height, and floor area
- Do not add or remove structural elements
- Respect the natural light sources (windows placement and size)

## Style & Mood:
- Style: Modern
- Mood: Clean and comfortable
- Color palette: Neutral with grey and black accents

## Design Requirements:
- Budget tier: Mid-range
- Room type: Living room
- Special requirements: Comfortable sofa for watching movies, space for plants

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
- Match lighting mood to clean and comfortable atmosphere

## Quality Standards:
- Photorealistic rendering quality
- Professional interior photography angle and composition
- No visible AI artifacts or distortions
- Coherent design that follows real-world interior design principles

## Context:
This is a mid-range renovation/design project for a living room, aiming to achieve a Modern aesthetic with a clean and comfortable atmosphere.
```

### Negative Prompt:

```
distorted geometry, warped walls, impossible architecture, curved floor, slanted ceiling, missing walls, extra walls, changed room shape, altered windows position, added doors, removed doors, unrealistic perspective, fish-eye distortion, oversized furniture, miniature objects, wrong scale, giant decorations, tiny windows, disproportionate elements, furniture too large for space, impractical layout, blurry textures, low resolution materials, repetitive patterns, obvious tiling, pixelated surfaces, plastic-looking materials, fake textures, unrealistic reflections, overexposed, underexposed, artificial HDR look, blown out highlights, crushed blacks, inconsistent lighting direction, multiple sun sources, unnatural shadows, watermark, signature, text, labels, UI elements, frame borders, distorted faces in photos/art, melted objects, merged furniture, duplicate items, floating objects, cluttered space, too many decorations, messy arrangement, random objects, incoherent style mixing, cheap-looking, tacky decor, unrealistic colors, fantasy elements, sci-fi objects, impossible structures, levitating furniture, transparent walls, glowing objects without light source, magical effects, extreme luxury, custom millwork, imported exotic materials, museum-quality art, bed, bathroom fixtures, kitchen appliances, professional gym equipment
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

"Сучасна мінімалістична вітальня з нейтральною палітрою та чорно-сірими акцентами, де центральним елементом є зручний диван для відпочинку, доповнений живими рослинами для затишку."

## Applied Constraints Checklist

- ✅ Збережено геометрію кімнати (стіни, вікна, двері)
- ✅ Застосовано бюджетні обмеження (mid-range матеріали)
- ✅ Відповідає стилю Modern
- ✅ Використано реалістичні матеріали і розміри меблів
- ✅ Включено зручний диван та рослини (як в запиті)
- ✅ Достатньо простору для переміщення
- ✅ Тільки необхідні меблі для вітальні

## Очікуваний Результат

**Що має вийти:**
- Світла кімната з великими вікнами (збережені з оригіналу)
- Сірий або бежевий диван (200-220 см)
- Чорний журнальний столик
- 2-3 великі рослини в горщиках (біля вікна або в кутах)
- Нейтральні стіни (білі або світло-сірі)
- Дерев'яна або світла підлога
- Мінімалістичні світильники (торшер або підвісна лампа)
- Можливо чорно-білі постери або мінімалістичний декор

## Що Спрацювало / Що Покращити

### ✅ Спрацювало:
- Геометрія кімнати збережена
- Масштаб меблів реалістичний
- Стиль консистентний
- Рослини додані природно

### 🔧 Можна покращити:
- Якщо диван занадто темний, можна додати в промпт "light grey fabric sofa"
- Для більшої затишності можна згадати подушки або плед
- Якщо рослин мало, можна вказати "at least 3 large potted plants"

## Примітки

Цей приклад показує базове використання системи для найпопулярнішого типу запиту - modern living room. Промпт досить універсальний і має дати гарний результат з більшістю генераторів.

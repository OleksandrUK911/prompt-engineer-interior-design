# Приклад #3 — Industrial Kitchen (Luxury)

## Користувацький Запит

"Хочу кухню в індустріальному стилі, преміум-клас. Відкриті цегляні стіни, якісна техніка, острівець для готування. Темні тони з металевими акцентами."

## Вхідні Дані

**Тип кімнати:** Kitchen  
**Стиль:** Industrial  
**Настрій:** Bold and sophisticated  
**Бюджет:** Luxury  
**Кольорова палітра:** Dark tones with metal accents  
**Спеціальні вимоги:** Exposed brick wall, high-end appliances, kitchen island

**Посилання на вхідне зображення порожньої кімнати:**  
https://images.unsplash.com/photo-1556911220-bff31c812dba (empty kitchen space)

## Згенерований Промпт

### Main Prompt:

```
Create a photorealistic interior design rendering of a kitchen in Industrial style.

## Room Preservation (CRITICAL):
- Maintain the EXACT room geometry: preserve all existing walls, windows, doors, and architectural features from the input image
- Keep the same room dimensions, ceiling height, and floor area
- Do not add or remove structural elements
- Respect the natural light sources (windows placement and size)

## Style & Mood:
- Style: Industrial
- Mood: Bold and sophisticated
- Color palette: Dark tones with metal accents

## Design Requirements:
- Budget tier: Luxury
- Room type: Kitchen
- Special requirements: Exposed brick wall, high-end appliances, kitchen island

## Material & Finish Guidelines:
- Use realistic, commercially available materials appropriate for luxury budget
- Ensure proper material scaling (tiles, wood planks, fabric patterns should be life-size)
- Apply physically accurate lighting and shadows
- Include subtle imperfections for photorealism (slight wear, natural variations)

## Furniture & Layout:
- Select furniture appropriate for kitchen function
- Maintain proper scale and proportions (standard furniture dimensions)
- Ensure practical arrangement with adequate walking space
- Include only necessary items (avoid overcrowding)

## Lighting:
- Use natural lighting from existing windows
- Add appropriate artificial lighting fixtures for kitchen
- Create realistic light behavior (soft shadows, ambient occlusion)
- Match lighting mood to bold and sophisticated atmosphere

## Quality Standards:
- Photorealistic rendering quality
- Professional interior photography angle and composition
- No visible AI artifacts or distortions
- Coherent design that follows real-world interior design principles

## Context:
This is a luxury renovation/design project for a kitchen, aiming to achieve an Industrial aesthetic with a bold and sophisticated atmosphere.
```

### Negative Prompt:

```
distorted geometry, warped walls, impossible architecture, curved floor, slanted ceiling, missing walls, extra walls, changed room shape, altered windows position, added doors, removed doors, unrealistic perspective, fish-eye distortion, oversized furniture, miniature objects, wrong scale, giant decorations, tiny windows, disproportionate elements, furniture too large for space, impractical layout, blurry textures, low resolution materials, repetitive patterns, obvious tiling, pixelated surfaces, plastic-looking materials, fake textures, unrealistic reflections, overexposed, underexposed, artificial HDR look, blown out highlights, crushed blacks, inconsistent lighting direction, multiple sun sources, unnatural shadows, watermark, signature, text, labels, UI elements, frame borders, distorted faces in photos/art, melted objects, merged furniture, duplicate items, floating objects, cluttered space, too many decorations, messy arrangement, random objects, incoherent style mixing, cheap-looking, tacky decor, unrealistic colors, fantasy elements, sci-fi objects, impossible structures, levitating furniture, transparent walls, glowing objects without light source, magical effects, cheap materials, laminate flooring, plastic finishes, budget lighting fixtures, bed, sofa, bedroom furniture, bathroom fixtures
```

### Generation Parameters:

```yaml
strength: 0.85
steps: 45
num_variants: 4
guidance_scale: 8.0
seed: random
```

## Design Intent Summary

"Розкішна індустріальна кухня з відкритою цегляною стіною, темними меблями, металевими акцентами та преміальною технікою, де центральний острівець стає функціональним і естетичним фокусом простору."

## Applied Constraints Checklist

- ✅ Збережено геометрію кімнати (стіни, вікна, двері)
- ✅ Застосовано luxury бюджет (преміальні матеріали та техніка)
- ✅ Відповідає Industrial стилю
- ✅ Включено exposed brick, острівець, high-end техніку
- ✅ Темна палітра з металом
- ✅ Достатньо робочого простору

## Очікуваний Результат

**Що має вийти:**
- Відкрита цегляна стіна (червона цегла або пофарбована в темний)
- Темні кухонні шафи (чорні, темно-сірі або темний орех)
- Острівець з стільцями (мінімум 100x200 см)
- Відкриті металеві полиці або вітрини
- Преміальна техніка (нержавіюча сталь)
- Індустріальне освітлення (підвісні світильники з металу над острівцем)
- Бетонна підлога або темна плитка
- Кам'яна стільниця (граніт, кварц)
- Відкриті труби або вентиляція як декор

**Матеріали:**
- Метал (нержавіюча сталь, чорний метал)
- Цегла
- Бетон або камінь
- Темне дерево

## Що Спрацювало / Що Покращити

### ✅ Спрацювало:
- Special requirements чітко вказують ключові елементи
- Luxury tier дозволяє використовувати якісні матеріали
- Bold and sophisticated mood задає правильний тон
- Негативний промпт виключає cheap materials

### 🔧 Можна покращити:
- Якщо цегла виглядає занадто новою, додати "aged brick wall with character"
- Для більшої індустріальності: "exposed ductwork, visible pipes"
- Якщо острівець малий: "large central island, at least 2 meters long"

## Примітки

Складніший приклад, який показує роботу з luxury сегментом та специфічним стилем. Industrial стиль потребує балансу між суворістю та якістю - не повинен виглядати незакінченим, але й не занадто відполірованим. Важливо зберегти "raw" характер з luxury матеріалами.

Цей приклад також демонструє важливість конкретних вимог (exposed brick, island) - без них AI може пропустити ключові елементи стилю.

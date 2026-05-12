# Design Document: Maximalist / Creative Redesign

## 1. Aesthetic Direction
- **Vibe**: High-energy, bold, and unforgettable. 
- **Inspiration**: Acid-house aesthetics, brutalist web design, and high-fashion digital editorials.
- **Goal**: Transform the generic "Leon" template into a cutting-edge creative agency showcase.

## 2. Visual Identity
### Color Palette
- **Primary Background**: `#09090b` (Obsidian Black)
- **Primary Accent**: `#ccff00` (Acid Green)
- **Secondary Accent**: `#00f3ff` (Electric Cyan)
- **Tertiary Accent**: `#ff0055` (Hot Pink)
- **Text**: `#ffffff` (Pure White) and `#a1a1aa` (Muted Gray)

### Typography
- **Headings**: `Syne`, sans-serif (Extra Bold/Bold) - Used for massive, high-impact statements.
- **Sub-headings**: `Space Mono`, monospace - Used for section labels and technical details.
- **Body**: `Inter` or `Manrope`, sans-serif - For high legibility in articles and descriptions.

## 3. Key UI Components & Layouts
- **The "Noise" Overlay**: A global fixed overlay with a subtle grain texture to add depth to the dark background.
- **Infinite Marquee**: Scrolling text section dividers (e.g., "SERVICES • SERVICES • SERVICES") to create constant motion.
- **Overlapping Hero**: The "Hello There!" heading will overlap with a background image or a decorative geometric shape.
- **Asymmetrical Grid**: The Services and Portfolio sections will move away from centered boxes to a staggered, "broken" grid layout.

## 4. Motion & Interactivity
- **Reveal Animations**: Use `clip-path` and `transform` to reveal content on scroll or load.
- **Hover Glitch**: Icons and buttons will have a subtle "color shift" or "glitch" effect on hover.
- **Magnetic Cursor (Optional/Future)**: A custom large circular cursor that reacts to interactive elements.

## 5. File Impact
- `index.html`: Structural overhaul to accommodate marquee wrappers, new font imports, and layered containers.
- `css/index-template.css`: Complete rewrite of variables, layout logic, and animation keyframes.

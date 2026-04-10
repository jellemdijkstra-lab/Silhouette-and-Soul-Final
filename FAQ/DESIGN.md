# Design System: Editorial Elegance

## 1. Overview & Creative North Star
**The Creative North Star: "The Silent Gallerist"**

This design system is built on the philosophy of intentional restraint. For a luxury fine art photography studio like 'Silhouette & Soul', the UI must never compete with the imagery. Instead, it should act as the white walls of a high-end gallery—structured, quiet, and profoundly premium. 

We move away from "standard" web patterns by embracing **Architectural Layouts**. This means using exaggerated white space, intentional asymmetry (e.g., off-center headings), and thin, needle-like strokes (0.5px) to define space. By strictly forbidding shadows and gradients, we lean into a "Flat-Premium" aesthetic where quality is communicated through typography, color harmony, and hairline precision rather than digital effects.

---

## 2. Colors & Tonal Depth
The palette is rooted in organic, earth-toned neutrals that evoke the tactile feel of heavy-stock cotton paper and darkroom chemicals.

### Core Palette
- **Charcoal (#1A1A1A):** Authority. Used for primary navigation, H1–H4 headings, and primary action states.
- **Dark Charcoal (#2C2C2C):** Depth. Reserved for immersive full-width sections to "frame" light photography.
- **Cognac (#8B6B4E):** The Signature. A sophisticated accent for text links and high-value CTAs.
- **Warm Sand (#C4A882):** The Guide. Used for eyebrows and step indicators.
- **Gold (#C9A96E):** The Detail. Reserved exclusively for star ratings and decorative accents against dark backgrounds.
- **Cream (#F7F0E8):** The Surface. A softer alternative to white, specifically for secondary containers like testimonials.
- **Off-white (#F5F5F2):** The Transition. Use this to subtly differentiate sections without a hard border.
- **Warm Border (#E8E4DF):** The Line. A 0.5px stroke used for delicate containment.

### The "No-Line" Hierarchy
While thin borders are permitted, they should be used sparingly. Hierarchy is primarily achieved through **Tonal Layering**:
- Place a `Cream (#F7F0E8)` card on a `White (#FFFFFF)` background to create a "soft lift" effect.
- Use `Dark Charcoal (#2C2C2C)` sections to interrupt a white scroll, creating a cinematic rhythm.
- **Strict Rule:** Never use 1px solid borders. Use 0.5px `Warm Border (#E8E4DF)` to maintain an editorial, "hairline" aesthetic.

---

## 3. Typography
Typography is the voice of this system. It balances the timeless romance of a serif with the modern clarity of a geometric sans.

### The Scale
- **Display (H1-H2):** *Cormorant Garamond, 400*. Use for hero statements. These should be large, airy, and occasionally italicized for emphasis.
- **Headings (H3-H4):** *Cormorant Garamond, 400*. Title-case.
- **Subheadings/Eyebrows:** *Jost, 500, ALL CAPS, 0.16em spacing*. Use `Warm Sand` or `Mid Grey`.
- **Body:** *Jost, 400*. Set in `Dark Grey (#444444)` for optimal readability. Leading should be generous (1.6 – 1.8x).
- **Captions:** *Jost, 400, 12px*. Use `Mid Grey (#777777)`.

### Narrative Hierarchy
The contrast between the tall, elegant *Cormorant Garamond* and the technical, spaced-out *Jost* creates a "Fashion Magazine" feel. Use Jost for anything functional (UI labels, buttons) and Cormorant for anything emotional (storytelling, quotes).

---

## 4. Elevation & Precision
In this system, depth is flat. We do not use Z-axis shadows to communicate importance.

- **The Stacking Principle:** Rather than shadows, importance is shown through scale and isolation. A "floating" element is simply a high-contrast container (e.g., a White card on a Dark Charcoal section) with a 0.5px `Warm Border`.
- **Corner Radius:** A strict 2px maximum radius applies to all containers and buttons. This sharpness mimics the edge of a physical photograph or a matted frame.
- **Negative Space:** Use a 12px/24px/48px/96px spacing scale. To create a "Premium" feel, double the expected padding on hero sections and card containers.

---

## 5. Components

### Buttons
Buttons are micro-labels, not chunky blocks.
- **Primary:** `Charcoal (#1A1A1A)` fill, white text, 2px radius. 
- **Outline:** 0.5px `Warm Border`, `Charcoal` text, 2px radius.
- **Typography:** *Jost, 9px-10px, ALL CAPS, 0.16em letter-spacing*.
- **Padding:** 12px top/bottom, 32px left/right.

### Testimonial Cards
- **Background:** `Cream (#F7F0E8)`.
- **Border:** 0.5px `Warm Border (#E8E4DF)`.
- **Structure:** Quote in *Cormorant Garamond*, Attribution in *Jost (500)*.

### Experience Cards
- **Background:** `White (#FFFFFF)`.
- **Placement:** Usually nested within `Dark Charcoal (#2C2C2C)` sections to create high-contrast "pop."
- **Border:** None (let the white against dark charcoal define the edge).

### Dividers
- **Weight:** 0.5px.
- **Color:** `Warm Border (#E8E4DF)`.
- **Usage:** Use vertical dividers to separate meta-data (e.g., Date | Location) and horizontal dividers to separate distinct editorial beats.

---

## 6. Do's and Don'ts

### Do
- **Do** use asymmetrical layouts (e.g., a large image on the left, with text starting 1/3rd from the right).
- **Do** use 0.5px dividers to separate navigation items.
- **Do** use "Warm Sand" for numbering (01, 02, 03) in process sections.
- **Do** ensure generous letter-spacing on all Jost-based labels.

### Don't
- **Don't** use pill-shaped buttons. If it's not a 2px radius, it's incorrect.
- **Don't** use shadows. If a card needs to stand out, change its background color or add a 0.5px border.
- **Don't** use gradients. Professional photography provides the texture; the UI remains flat.
- **Don't** use standard blue for links. Use `Cognac (#8B6B4E)`.
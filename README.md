# ✨ Wish Realm — WorldHub: Crisis in the Crudzaso Atlas

**"Where every hope becomes light... and every light becomes a story."**

Wish Realm unfolds as a sanctuary where fairies guard the glow of unspoken desires, suspended inside crystal capsules that drift through soft green light. Built entirely with **HTML + CSS**, this world blends forest‑magic aesthetics, semantic code structure, and responsive design into one enchanted — but technically solid — micro‑universe.

---

## 🌙 The Wish Keepers — Team Wish

| Member | Favorite Element |
|--------|------------------|
| Sebastian Vargas Ramírez | ✨ Stardust |
| Diego Alejandro Morales Montoya | 🌌 Void Essence |
| Daniela Quinto Ríos | 💫 Spirit Glow |
| Verónica Martínez Cadavid | 🌙 Moonlight |

Each keeper infused the realm with visual identity, narrative energy, or UI elements that shaped its final glow.

---

## 🌟 World Essence

Wish Realm imagines a quiet cosmic forest where every wish is catalogued inside floating “crystal cards.” These artifacts pulse with subtle magic — an effect reinforced through:

- Soft gradients and atmospheric glow  
- Floating animations simulating levitation  
- Light, airy card structures  
- Cursive ornamental titles balanced with friendly body text  
- A palette inspired by ethereal greens and moonlit cream tones  

Every design choice exists to preserve calmness, clarity, and mystic charm — while staying faithful to modern front‑end standards.

---

## 🎨 Magic‑Infused UI Elements

### 🌿 Color Alchemy (CSS Variables)

```
--color-1: #8fbc8f;
--color-2: #a9d18f;
--color-3: #c2e0a4;
--color-4: #e4f2b1;
--color-5: #f1f8e2;
```

These variables act as the realm’s chromatic spellbook — giving consistency, reusability, and easy future customization.

---

### 🌬 Typography Spellwork

- **Great Vibes** — ceremonial headers, fairy‑script energy  
- **Delius** — warm, soft, and readable for long-form text  

This pairing keeps the world whimsical without sacrificing accessibility.

---

### ✨ Animations (CSS Keyframes)

Your animations breathe life into the world:

#### **Glow**  
Simulates fairy lantern pulses.  
`@keyframes glow { ... }`

#### **Floating Text**  
Creates gentle motion for narrative emphasis.  
`@keyframes floatText { ... }`

#### **Crystal Card Drift**  
A hovering effect used across flip cards.  
`@keyframes floatCard { ... }`

All animations are lightweight and smooth across devices.

---

### 🎴 Crystal Flip Cards (Pure CSS — No JS)

One of Wish Realm’s most magical features is its flip‑card system.  
Implemented with:

```
transform-style: preserve-3d;
perspective: 1200px;
.flip-card-inner:hover {
    transform: rotateY(180deg);
}
```

This approach gives depth and interactivity without relying on JavaScript — ideal for clean, accessible UI design.

Uses include:

- Fairy categories  
- Wish chambers  
- Lore fragments  
- World rules  
- Character glimpses  

---

### 📐 Responsive Astral Layout

Wish Realm’s layout gracefully shifts between dimensions:

- A two‑column grid for wide screens  
- A single, scroll‑friendly column for mobile  
- Flip‑card grids that reorganize naturally  
- Carefully chosen font sizes for mobile readability  

This ensures the fantasy aesthetic remains intact across all viewports.

---

## 🧬 Semantic HTML Under the Enchantment

Your markup is structured with intention:

- **header** — world title and introduction  
- **main** — core content, narratives, and cards  
- **section** — thematic chapters of the world  
- **article** — self‑contained pieces of lore or UI content  
- **aside** — extra magical context or supplementary info  
- **footer** — team, credits, external links  

This semantic layout improves accessibility, SEO, and clarity for future developers.

---

## 🗂 Project Structure

```
WorldHub-AtlasCrudzaso-Wish/
│
├── index.html       # HTML structure & world narrative
├── styles.css       # Color palette, animations, layout, components
├── media/           # Images, icons, assets
├── README.md        # This documentation
└── .idea/           # IDE metadata
```

---

## 🚀 Viewing the Realm

- Repository link: [GitHub Repository](https://github.com/Choklitos21/WorldHub-AtlasCrudzaso-Wish)

- Webpage link: [Fairy Website](https://choklitos21.github.io/WorldHub-AtlasCrudzaso-Wish/)

__You will see the page with light or dark mode according to your browser, try change the browser configuration to check 
out both styles__

---

## 💻 Team participation
- 🐈 __Daniela Quinto Ríos__
  - I created the "Veiled Code of Faerie" section using interactive flip-cards to present the system rules, symbolizing the Fae world's dual nature (surface vs. truth). My key contributions were the implementation of 3D card-flip transformations on hover and several ambient CSS animations (like glow and soft float) to achieve a magical, ethereal feel. The content defines seven core laws, including Court Hierarchy and the Law of the Deal, with each list containing at least five detailed rules to establish a robust, yet mystically structured, world logic.
- 🐈‍⬛ __Verónica Martínez Cadavid__
  - Lorem
- ☕ __Diego Morales Montoya__
  - In charge of the “main” section, general styles for sections and articles.
    Responsible for merging branches so that they work correctly (when God wanted to help).
  - 
    Main work branches “feature/main” and “main.”
- 🎧 __Sebastian Vargas Ramirez__
  - Responsible for developing the main navigation bar, seamlessly integrating it with the decorative garland and ensuring smooth, consistent, and visually cohesive navigation across the site.

  - Fully implemented the responsive footer, including its structure, links, member section, styles, and hover behavior — maintaining accessibility and visual harmony on both desktop and mobile devices.

  - Developed the automatic dark mode using prefers-color-scheme, customizing colors, backgrounds, glow effects, cursors, cards, and scrollbars to preserve the project’s magical aesthetic in both light and dark themes.

  - Provided technical support and optimization throughout the project, improving styles, refining HTML structure, and ensuring global consistency across components, animations, and layout behavior.





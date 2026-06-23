# CSS Grid Layout - Track Mastery Playground 🚀

Welcome to my learning repository for CSS Grid Layout. This project visualizes everything I have learned about **Grid Tracks**, sizing units, and structural positioning.

---

## 📚 What I Learned & Implemented

### 1. Grid Template Columns & Rows
Defines the explicit columns and rows of the grid layout using fixed or flexible values.
*   **Code:** `grid-template-columns: 200px 200px 200px;`
*   **Concept:** Creates 3 fixed columns of 200px width each. It remains rigid regardless of screen resizing.

### 2. The Fractional Unit (`fr`)
A flexible unit that represents a fraction of the available space in the grid container.
*   **Code:** `grid-template-columns: 1fr 1fr 1fr;`
*   **Concept:** Divides the screen equally into 3 fluid columns, making the layout responsive.

### 3. Unequal Sizes (Proportional Layout)
Using different `fr` weights to assign proportional space to grid items.
*   **Code:** `grid-template-columns: 2fr 1fr 1fr;`
*   **Concept:** The first column takes up twice the space of the other two, perfect for a Main Content + Dual Sidebar layout.

### 4. Mixing Flexible and Absolute Sizes
Combining fixed units (`px`) with flexible units (`fr`) for hybrid layouts.
*   **Code:** `grid-template-columns: 500px 1fr 1fr;`
*   **Concept:** The first column stays locked at 500px (e.g., for a fixed sidebar or banner), while the remaining space is divided equally by the `fr` tracks.

### 5. The `repeat()` Function
A cleaner notation to avoid repetitive code when creating multiple tracks.
*   **Code:** `grid-template-columns: repeat(3, 1fr);`
*   **Concept:** Shorthand for writing `1fr 1fr 1fr`, keeping the CSS clean and scalable.

### 6. Implicit vs Explicit Grid (`grid-auto-rows`)
Understanding how CSS Grid handles content that goes beyond the defined structure.
*   **Explicit Grid:** Defined manually using `grid-template-rows`.
*   **Implicit Grid:** Automatically created by the browser when there are more items than expected.
*   **Code:** `grid-auto-rows: 150px;` ensures that any dynamically added row automatically gets a height of 150px.

---

## 🛠️ Tech Stack Used
*   HTML5 (Semantic Tags)
*   CSS3 (Grid Layout properties)

---
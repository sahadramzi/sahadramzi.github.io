# Visual Identity & Architecture: sahadramzi.github.io

A unified design specification for a personal portfolio website hosting long-form essays, technical articles, and project case studies. 

---

## 1. Typography System

The typography balance mirrors a blend of contemporary, fluid identity with an optimized, highly comfortable reading experience.

### Headings (Display & UI Titles)
*   **Font Family:** `Bricolage Grotesque`, sans-serif
*   **Characteristics:** Quirky, fluid geometry, expressive terminals.
*   **Usage:** H1, H2, H3 elements, big hero statements, and card titles.

### Body Text (Long-form Reading Options)
*   **Option A (Editorial / Serif):** `Domine`, serif
    *   *Characteristics:* Purpose-built for body text on screens; elegant, deep, classical book-like reading feel.
*   **Option B (Minimalist / Sans-Serif):** `Inter Tight`, sans-serif
    *   *Characteristics:* Crisp, tailored execution of classic Inter with tighter tracking, keeping long paragraphs incredibly clean and compact.
*   **Usage:** Essay paragraphs, project documentation, metadata, and core UI copy.

### Typographic Configurations
*   **Base Font Size:** `18px` (Desktop) / `16px` (Mobile)
*   **Line Height (Leading):** `1.65` to `1.75` for body paragraphs.
*   **Line Length (Measure):** Max-width limited to `650px` (approx. 60–75 characters per line) to eliminate eye strain.

---

## 2. Color Palette & Architecture
Derived explicitly from the brand asset tokens[cite: 1].

| Token | Hex Code | System Role | Architectural Application |
| :--- | :--- | :--- | :--- |
| **The Canvas** | `#EBEBEB` | Primary Background | Global page background[cite: 1]. Mutes screen glare compared to pure white. |
| **The Anchor** | `#222222` | Text & Structure | Primary body text color, dark headers, crisp borders[cite: 1]. |
| **The Editorial Core** | `#BC7A4E` | Secondary/Metadata | Subtitles, article dates, reading times, category tags[cite: 1]. |
| **The Interactive Layer** | `#86C133` | Interactive States | Button backgrounds, link hovers, active status indicators[cite: 1]. |
| **The Spotlight** | `#FCFF5C` | Accent/Highlight | Text highlighter utility background, subtle indicator dots[cite: 1]. |

---

## 3. UI Component Specifications

### Layout Structure
*   **Grid:** Clean, minimal Bento grid layouts for the project showcase section.
*   **Spacers:** Generous padding and margins (`2rem` to `4rem`) to let content breathe.
*   **Borders:** Fine, clean borders (`1px solid #222222` with low opacity) to segment blocks seamlessly.

### Accent Rules
*   **Contrast Guardrail:** Any text laid on top of `#86C133` or `#FCFF5C` must explicitly use `#222222` to maintain structural accessibility[cite: 1].
*   **Text Selection:** Custom CSS selection highlighting text using `#FCFF5C` with black text[cite: 1].
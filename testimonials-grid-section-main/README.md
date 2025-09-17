## 📖 Project Overview
This project is an implementation of the **[Frontend Mentor – Testimonials Grid Section](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7)** challenge.  
The goal was to recreate a responsive testimonials grid using Bootstrap, while applying utility classes and custom CSS to match the design as closely as possible.

---
## Approach & Customizations
- **Layout Strategy**:  
  The page is divided into two main columns: a **left column** (`col-9`) containing multiple testimonial cards, and a **right column** (`col-3`) containing a single card.  

- **Nested Rows**:  
  To arrange the cards in a staggered layout within the left column, a nested `.row g-4` was used. Cards inside this row have different column widths (`col-8` for large cards, `col-3` for smaller cards) to create a visual variation and maintain alignment.

- **Bootstrap Components & Utilities**:  
  - Used **cards** for testimonials.  
  - Applied utility classes like `p-*`, `m-*`, `text-*`, `mx-auto` for spacing and alignment.  

- **Custom CSS**:  
  - Google Font: `Barlow Semi Condensed` for typography.  
  - `.bg-violet` with background color and pattern.  
  - Card shadows and borders for depth.  
  - Fixed-size avatars with `object-fit: cover` for consistent appearance.  

---

## ⚡Challenge & Solutions
The main challenge was implementing the staggered testimonial layout while keeping spacing and alignment consistent:

1. **Grid Structure**  
   - Outer `<main class="container">` provides max width and padding.  
   - Primary `.row g-4` splits the page into **left (`col-9`)** and **right (`col-3`)** columns.  

2. **Nested Row for Left Column**  
   - The left column contains another `.row g-4` to arrange multiple cards in a staggered formation.  
   - Cards use varied column widths (`col-8` and `col-3`) to alternate sizes visually.  

3. **Spacing & Alignment**  
   - `g-4` ensures consistent gutters.  
   - `mx-auto` centers some cards within their columns.  
   - This combination allowed precise control of spacing without adding extra containers.  

By nesting rows inside a column, I achieved a flexible layout that closely matches the design while remaining responsive.

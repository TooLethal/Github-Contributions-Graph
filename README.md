# 📊 CSS + JavaScript Contribution Graph

A dynamic **HTML, CSS, and JavaScript project** that generates a random contribution graph inspired by GitHub’s activity heatmap. Each square represents a day’s contribution level, with colors changing based on intensity.

## ✨ Features
- **Randomized Data Generation**  
  - JavaScript function `generateRandomContributionStats()` creates 52 weeks × 7 days of contribution values.  
  - Levels: `0`, `3`, `5`, `10` (representing contribution intensity).  

- **Dynamic Graph Rendering**  
  - `makeGraph()` builds weekly `<ul>` lists and daily `<li>` squares dynamically.  
  - Each square is assigned a `data-value` attribute for styling.  

- **Color-Coded Levels**  
  - Default → Dark gray (`#161b22`)  
  - Level 3 → Dark Blue  
  - Level 5 → Blue  
  - Level 10 → Light Sky Blue  

- **Responsive Grid Layout**  
  - CSS Grid displays 52 columns (weeks) with 7 rows (days).  
  - Clean, compact design similar to GitHub’s contribution calendar.  

- **Customizable Variables**  
  - Colors and background defined with CSS variables for easy theme changes.  

## 🛠️ Tech Stack
- **HTML5**  
- **CSS3 (Grid + Variables)**  
- **JavaScript (DOM Manipulation)**  

## 🚀 Use Cases
- Visualizing contribution/activity data  
- Practicing DOM manipulation and CSS Grid  
- Creating GitHub-style dashboards or portfolio elements  
- Learning how to combine **data generation + visualization**  

## 📂 Project Structure
```
index.html   # Main HTML structure
style.css    # Graph styling and color levels
index.js     # Data generation and DOM rendering
```

---

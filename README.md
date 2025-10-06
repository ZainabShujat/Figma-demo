# 🎨 Figma Front-End Assignment — HTML & CSS Clone  
**By:** Zainab Shujat  
**Live Demo:** [https://zainabshujat.github.io/Figma-demo/](https://zainabshujat.github.io/Figma-demo/)  
**Repository:** [https://github.com/zainabshujat/Figma-demo](https://github.com/zainabshujat/Figma-demo)

---

## 📌 Project Overview
This project is a **pixel-perfect HTML & CSS clone** of the given Figma design (hero section + subsequent section).  
It was completed over three focused days of iterative work — adjusting layout structure, responsiveness, and design fidelity until it visually matched the reference on both desktop and mobile.

My goal was not only to recreate the design but to **demonstrate understanding of clean code practices**, responsive breakpoints, and accessibility considerations.

---

## 🛠️ Tech Stack & Tools
- **HTML5** — semantic structure using `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`  
- **CSS3** — flexbox & grid layouts, responsive units, pseudo-elements, transitions  
- **Figma** — for pixel inspection (font sizes, padding, margins)  
- **GitHub Pages** — for live deployment  

---

## 🎯 Key Implementation Details
- **Pixel Accuracy:**  
  Every font size, padding, and margin was matched to the Figma file using the Inspect tool for true 1:1 fidelity.  

- **Responsive Layout:**  
  Built fluid breakpoints for:
  - **Desktop:** ≥1024px  
  - **Tablet:** ~768–1024px  
  - **Mobile:** ≤640px  
  The layout adapts seamlessly; badges and hero visuals re-align without clipping or overflow.

- **Radial Background & Hero Composition:**  
  The pink radial glow behind the model image was recreated using CSS gradients and positioning.  
  Layering (`z-index`) and blur filters were used to match the Figma depth.

- **Mobile Optimization:**  
  Removed decorative elements (like the underline under “Deserves A”) on small screens to maintain clean text flow.  
  Adjusted hero composition for vertical stacking and ensured badges remained visible and centered.

- **Clean, Maintainable CSS:**  
  - CSS variables (`--primary`, `--page-bg`, `--circle-color`) for easy theme updates.  
  - Grouped related sections logically (`Header`, `Hero`, `Cards`, `Footer`).  
  - Responsive overrides at the bottom for clarity.  
  - Final file reformatted and comment-free for production.

- **Accessibility & UX Touches:**  
  - All images include descriptive `alt` attributes.  
  - Mobile navigation accessible via keyboard and screen readers.  
  - Hover states and subtle button glow animations to enhance interactivity.

---

## 🔍 Challenges & Solutions
| Challenge | Solution |
|------------|-----------|
| Getting the radial gradient and circle behind the model to match the Figma exactly | Tuned gradient coordinates, opacity, and blur using CSS variables |
| Underline overlapping text on mobile | Added conditional CSS + pseudo-element override for mobile devices |
| Mobile layout clipping badges | Set `overflow: visible` on hero containers and repositioned overlays |
| Maintaining visual consistency across browsers | Used normalized box-sizing and tested in Chrome, Firefox, and mobile Chrome |
| Clean final structure after multiple revisions | Refactored CSS, merged fixes, and removed duplicates for a single, production-ready file |

---

## 🚀 Final Result
- Fully responsive, pixel-aligned, and deployable static page.  
- No frameworks used — purely handcrafted **HTML + CSS**.  
- Validated for consistency and accessibility.

You can view the **final working demo here:**  
👉 [https://zainabshujat.github.io/Figma-demo/](https://zainabshujat.github.io/Figma-demo/)

---

## 🧠 Reflection
Over the past three days, this assignment became a great deep-dive into:
- Fine-tuning design precision directly from Figma.  
- Managing CSS specificity, pseudo-elements, and responsiveness.  
- Iteratively debugging visual differences through live deployment.  

It reinforced how **attention to detail and structured problem-solving** make even a static page feel production-ready.

---

## 🏁 How to Run Locally
```bash
git clone https://github.com/zainabshujat/Figma-demo.git
cd Figma-demo
# open index.html in any browser

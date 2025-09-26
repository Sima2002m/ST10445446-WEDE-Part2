 Simmy Investment, Trading & Co. Website

This is a 5-page responsive website project created for **Simmy Investment, Trading & Co.**.  
It includes: Home, About, Services, Enquiry, and Contact pages with consistent styling and responsive design.

---

 📂 Project Structure
- `index.html` → Home page with TradingView charts and tips
- `about.html` → Company background, mission, and vision
- `services.html` → Overview of provided services
- `enquiry.html` → Enquiry form for users
- `contact.html` → Contact form and company details
- `style.css` → Shared stylesheet for all pages

---

 🎯 Responsive Design (Assignment Part 2)

 **3.1 Breakpoints**
- Key breakpoints defined for **desktop (≥1024px)**, **tablet (≤1024px)**, and **mobile (≤768px)**.
- Used **CSS media queries** to adjust layouts, font sizes, and navigation.
- 
  ```css
  @media (max-width: 768px) {
    .market-updates { grid-template-columns: 1fr; }
    nav { flex-direction: column; }
  }
  ```

 **3.2 Relative Units**
- Used **`rem` and `em`** for font sizes and spacing.
- Used **percentages (%)** for widths to keep layouts flexible.
- 
  ```css
  h1 { font-size: 2.5rem; }
  .container { width: 90%; }
  ```

 **3.3 Responsive Images**
- All images use `max-width: 100%; height: auto;` to scale automatically.
- The design supports **`srcset`** and `<picture>` for optimized loading.

 **3.4 Test and Iterate**
- Website tested on **desktop, tablet, and mobile** using browser dev tools.
- Content adapts properly across different devices and resolutions.

---

 🚀 How to Run
1. Download and unzip the project.
2. Open `index.html` in your browser.
3. Navigate between pages using the top navigation menu.

---

 📝 Notes
- The website is for **educational purposes only** and not financial advice.
- TradingView charts require internet access to load.


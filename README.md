<div align="center">
  <img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/solid/file-invoice-dollar.svg" width="80" alt="Invoice Logo">
  
  # Thinkwell Enterprises · Offline Invoice Generator
  
  **A beautiful, lightning-fast, and 100% offline invoice generator that runs entirely in your browser.**
  
  <br />
  
  [![Made with HTML](https://img.shields.io/badge/Made%20with-HTML5-e34f26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
  [![Made with CSS](https://img.shields.io/badge/Made%20with-CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
  [![Made with JS](https://img.shields.io/badge/Made%20with-Vanilla%20JS-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
  [![Offline First](https://img.shields.io/badge/Offline-100%25-success?style=flat-square&logo=cachet)](https://github.com/)
  
</div>

---

## 🌟 The Ultimate Offline Invoice Maker

Tired of complex invoicing systems, monthly fees, and worrying about your business data being stored on third-party servers? 

The **Thinkwell Enterprises Offline Invoice Generator** solves all of that. It is a single-page web application designed to generate professional, print-ready PDF invoices. Your client information, bank details, and business data never leave your computer. 

*(Replace this placeholder with a screenshot of your app!)*
<!-- ![App Screenshot](path/to/your/screenshot.png) -->


## ✨ Key Features

* 🛡️ **100% Offline & Private:** Built entirely on Client-Side browser APIs (`localStorage`). Your financial data is securely maintained on your specific device. No database, no backend server.
* 📥 **CSV Database Exports:** Export your entire history of generated invoices to a `.csv` file with one click for external accounting or backup purposes.
* 🖨️ **Browser Native PDF Engine:** Creates mathematically perfect PDF invoices taking advantage of Chrome/Firefox/Safari's native high-resolution printing pipelines. No heavy PDF libraries required.
* 🧮 **Automated Tax & Discount Math:** Automatically calculates your multi-item Subtotals, Discounts (%), Taxes/GST (%), and extra Shipping costs in real time.
* 🎨 **Live Customization Engine:** Upload your business logo, select from hand-curated color palettes, and see changes in the Live Preview pane instantly.
* 📱 **Seamless Responsive UI:** Adapts seamlessly whether you are generating an invoice on a 4K Desktop or an iPhone. 


## 🚀 Getting Started

Because this application relies entirely on modern browser capabilities using Vanilla JavaScript, HTML, and CSS, getting started is practically instant.

### Local Usage (No Hosting Required)
1. Download or clone this repository:
   ```bash
   git clone https://github.com/your-username/SoloInvoice.git
   ```
2. Navigate to the downloaded folder.
3. Double-click the `index.html` file to open it in your default web browser (Chrome, Firefox, Safari, Edge).
4. Start generating invoices!

### Cloud Hosting for Global Access
If you want to access your generator from any computer, the project is instantly compatible with static website hosting providers:
* [GitHub Pages](https://pages.github.com/) *(Highly Recommended)*
* [Netlify](https://www.netlify.com/)
* [Vercel](https://vercel.com/)

Simply upload or drag-and-drop the directory into any of these platforms, and you'll have a live, secure `https://` link in seconds.


## 💾 Important: Data Persistence

Due to its 100% offline nature, the application saves your configurations, custom business addresses, and historical invoices directly inside your browser's persistent cache. 

> [!CAUTION]  
> If you clear your browser's "Cookies and Site Data", or if you generate invoices while in a Private/Incognito browsing window, **your data will be permanently wiped upon closing.**
> 
> *Always use the **"Export All as CSV"** utility in the Settings tab to backup your important records!*


## 🛠️ Architecture Details

Built from the ground up for maximum speed and simplicity without relying on heavy frontend frameworks like React or Angular.

- **Markup:** Semantic `HTML5` structure.
- **Styling:** Custom CSS design system utilizing CSS Grid, Flexbox, and CSS Custom Properties (Variables) for theme switching. Custom fonts supplied via Google Fonts (DM Sans, DM Mono, Syne).
- **Interactivity:** Vanilla Javascript (ES6+) utilizing `localStorage`, `FileReader API`, and `Blob URLs` for CSV generation.

---

<div align="center">
  <b>Designed and optimized by <a href="#">Thinkwell Enterprises</a></b>
  <br/>
  <i>Invoicing, un-complicated.</i>
</div>

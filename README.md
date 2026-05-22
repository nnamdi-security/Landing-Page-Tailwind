# ⚡ Nexus — Responsive Landing Page

A modern, fully responsive business landing page built with **HTML** and **Tailwind CSS** as part of a frontend development project.

---

## 📸 Preview

![Nexus Landing Page Preview](./UI_Template.png)

---

## 🔗 Links

- **Repository:** [github.com/nnamdi-security/Landing-Page-Tailwind](https://github.com/nnamdi-security/Landing-Page-Tailwind)

---

## 📋 Project Overview

Nexus is a dark-themed technology company landing page designed to showcase services, company information, and a contact form. The goal of this project was to faithfully recreate a provided UI design using semantic HTML and Tailwind CSS utility classes.

---

## 🗂️ Sections

| Section | Description |
|---|---|
| **Navigation Bar** | Fixed top nav with logo, links, and a CTA button. Includes a hamburger menu icon for mobile. |
| **Hero** | Full-width intro with headline, subtext, two CTA buttons, and a hero image. |
| **Services** | Three-column card grid highlighting Web Development, Mobile Apps, and Digital Marketing. |
| **About** | Two-column layout with an image, company description, and key stats (150+ projects, 98% satisfaction). |
| **Contact** | Split layout with contact info (email, phone, address) and a styled message form. |
| **Footer** | Logo, copyright notice, and social media icon links. |

---

## 🛠️ Built With

- **HTML5** — Semantic markup (`header`, `main`, `section`, `footer`)
- **Tailwind CSS** — Utility-first CSS framework for all styling
- **Font Awesome 7** — Icons used throughout the page
- **Google Fonts** — Inter font family

---

## 📐 Responsive Design

The layout is fully responsive across all screen sizes:

- **Mobile** — Single-column stacked layout, hamburger menu icon
- **Tablet** — Two-column grids where appropriate
- **Desktop** — Full multi-column layouts with side-by-side sections

Tailwind breakpoints used: `sm:`, `md:`, `lg:`

---

## 🎨 Color Palette

| Name | Hex |
|---|---|
| Dark Blue (background) | `#0f172a` |
| Blue Shade (cards) | `#1a2742` |
| Section Background | `#111c33` |
| Accent Blue | `#3b82f6` |
| Accent Green | `#22c55e` |
| Accent Purple | `#a855f7` |

---

## 📁 Project Structure

```
Landing-Page-Tailwind/
├── index.html
├── hero-image.png
├── about-image.png
└── css/
    └── output.css
```

---

## 🚀 Getting Started

To view the project locally:

1. **Clone the repository**
   ```bash
   git clone https://github.com/nnamdi-security/Landing-Page-Tailwind.git
   ```

2. **Navigate into the project folder**
   ```bash
   cd Landing-Page-Tailwind
   ```

3. **Open `index.html` in your browser**
   ```bash
   open index.html
   ```
   Or simply drag and drop the file into your browser.

> **Note:** If you plan to modify styles, make sure you have the [Tailwind CSS CLI](https://tailwindcss.com/docs/installation) set up to recompile `output.css`.

---

## 📚 What I Learned

- Structuring pages with semantic HTML elements
- Using Tailwind utility classes for layout, spacing, typography, and color
- Building responsive grids with `grid-cols` and flex layouts
- Applying hover effects and focus states with Tailwind variants (`hover:`, `focus:`)
- Using Tailwind's opacity modifier syntax (e.g. `bg-blue-500/20`)
- Mobile-first responsive design using Tailwind breakpoints

---

## 👤 Author

**nnamdi-security**
- GitHub: [@nnamdi-security](https://github.com/nnamdi-security)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

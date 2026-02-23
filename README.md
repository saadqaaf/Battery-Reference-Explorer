<div align="center">

# 🔋 Battery Chemistries Reference Explorer

**A comprehensive, interactive scientific overview of 200+ battery technologies across 24 categories.**

[![Live Demo](https://img.shields.io/badge/🌐_Live_Demo-Visit_Site-2ea44f?style=for-the-badge)](https://saadqaaf.github.io/Battery-Reference-Explorer/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)
[![HTML](https://img.shields.io/badge/Built_With-HTML5%20%2F%20Vanilla_JS-orange?style=for-the-badge&logo=html5)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Tailwind CSS](https://img.shields.io/badge/Styled_With-Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css)](https://tailwindcss.com/)

</div>

---

## 📖 About the Project

The **Battery Chemistries Reference Explorer** is a fast, single-page web application designed to consolidate vast amounts of scientific data on energy storage into one easily accessible format.

Spanning from historical cells (like the Voltaic Pile) to cutting-edge research (like Anode-Free Solid-State and Bioelectronic batteries), this tool helps **researchers, engineers, and students** quickly compare the formulas, advantages, disadvantages, and real-world applications of over **300 different battery chemistries** — all parsed instantly on the client side from an embedded dataset compiled from leading peer-reviewed journals.

---

## ✨ Features

- **Massive Database** — 300+ battery technologies organized into 24 major categories (e.g., Lithium-Based Secondary, All-Solid-State, Redox Flow, Multivalent Ion, Biological).
- **Interactive Sidebar** — Navigate instantly through main categories using an app-like, scrollable sidebar.
- **Real-Time Search** — Filter the entire data table live by typing chemistry formulas, common names, or specific applications.
- **Modern UI** — Clean, responsive interface that works flawlessly on desktop, tablet, and mobile devices.
- **Zero Build Step** — The entire application runs from a single `index.html` file. No npm, no Webpack, no server required.

---

## 🛠️ Built With

| Technology | Purpose |
|---|---|
| HTML5 & Vanilla JavaScript | Custom, lightweight CSV parsing and DOM manipulation |
| [Tailwind CSS](https://tailwindcss.com/) (CDN) | Rapid, modern, and responsive UI styling |
| [Lucide Icons](https://lucide.dev/) | Clean, scalable vector icons |

---

## 🚀 Getting Started

Since the project is completely self-contained, getting it running locally is incredibly simple.

**1. Clone the repository**

```bash
git clone https://github.com/saadqaaf/Battery-Reference-Explorer.git
```

**2. Open the file**

Simply double-click `index.html` to open it in your favorite web browser. That's it — no installation needed.

**3. Deploy to GitHub Pages (optional)**

To host your own live version, go to your repository **Settings → Pages → Set source to `main` branch**.

---

## 📝 Modifying the Data

The battery data is stored at the bottom of `index.html` inside a `<script type="text/template" id="csv-data">` tag in CSV format.

To add a new battery chemistry, simply append a new line in this format:

```
Chemistry Name,Formula & Description,Key Advantages,Key Disadvantages,Applications
```

> **Note:** Category section headers are created by leaving the last three columns empty.

---

## 📚 Data Sources

All data is compiled from scientific consensus as of 2025, referencing peer-reviewed literature including:

- *Journal of Power Sources*
- *Nature Energy*
- *ACS Energy Letters*
- *Advanced Energy Materials*
- *Electrochimica Acta*
- *Joule*

---

## 📄 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for more information.

---

<div align="center">

Made with ☕ and a genuine obsession with electrochemistry.

</div>

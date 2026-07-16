# 📐 Studio Resizer

A high-fidelity, client-side batch image processing tool designed with an Apple-inspired glassmorphism interface. **Studio Resizer** allows students, designers, and frontend engineers to rapidly scale, re-render, and export design assets to standard digital profiles with custom density settings.

🚀 **[Launch Live Web App](https://harsh-dev-live.github.io/px-resizer-tool/)**

---

## 👨‍💻 About The Developer
* **Developer:** Harsh (`harsh-dev-live`)
* **Role:** Frontend Developer
* **Connect with me:** [GitHub](https://github.com/harsh-dev-live) |

---

## ✨ Key Features

* **📦 Batch Processing & ZIP Packaging:** Upload multiple image assets simultaneously. The app processes them concurrently and packages them into a single `.zip` file using `JSZip`.
* **📐 Smart Target Profiles:** Built-in standard aspect ratio and dimension presets, ranging from **Avatar Cores (32×32)** to **4K Ultra Engines (3840×2160)**.
* **🎯 Custom Density Scaling (DPI/PPI):** Advanced render math calculations that automatically adjust width and height based on user-defined target output density.
* **🎨 High-Fidelity UI/UX:**
  * Apple iOS-inspired Light/Dark canvas gradients.
  * Real-time CSS backdrop blur filtering (saturate and blur) for realistic glass panels.
  * Sleek sliding preference panel with physical obfuscation (blur states) on background elements.
* **⚡ 100% Client-Side Canvas Engine:** Zero server overhead. Image resizing is executed instantly in the browser using high-quality rendering kernels (`imageSmoothingQuality: 'high'`).

---

## 🛠️ Tech Stack & Library Architecture

* **Markup:** Semantic HTML5 Structure
* **Styling:** CSS3 Custom Properties (CSS variables for dynamic theme transitions), modern Flexbox/Grid layouts, and hardware-accelerated cubic-bezier transitions.
* **Engine & Logic:** Vanilla ES6+ JavaScript (Asynchronous rendering loops, FileReaders, and HTML5 Canvas API).
* **External Dependencies:** [JSZip (v3.10.1)](https://stuk.github.io/jszip/) via CDN for client-side batch packaging.

---

## 🚀 How to Run Locally

Since this tool runs completely on the client side without needing a database or backend server, running it locally is incredibly easy.

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/harsh-dev-live/px-resizer-tool.git](https://github.com/harsh-dev-live/px-resizer-tool.git)

<div align="center">

# 🖼️ Responsive JavaScript Image Slider

A clean, responsive image carousel built with **HTML5, CSS3, and vanilla JavaScript**.

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=000)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Responsive](https://img.shields.io/badge/Responsive-Design-22C55E?style=for-the-badge&logo=googlechrome&logoColor=white)](#responsive-behaviour)

[![Repository Size](https://img.shields.io/github/repo-size/samusa099/Javascript-assignment?style=flat-square)](https://github.com/samusa099/Javascript-assignment)
[![Last Commit](https://img.shields.io/github/last-commit/samusa099/Javascript-assignment?style=flat-square)](https://github.com/samusa099/Javascript-assignment/commits/main)
[![Stars](https://img.shields.io/github/stars/samusa099/Javascript-assignment?style=flat-square)](https://github.com/samusa099/Javascript-assignment/stargazers)
[![Forks](https://img.shields.io/github/forks/samusa099/Javascript-assignment?style=flat-square)](https://github.com/samusa099/Javascript-assignment/forks)

</div>

---

## 📌 Project Overview

This repository contains a front-end assignment that demonstrates how to build an interactive horizontal image slider without using a JavaScript framework or external carousel library.

Users can navigate through the image collection using directional buttons, horizontal scrolling, or a draggable custom scrollbar. The interface automatically adapts for desktop, tablet, and mobile screens.

## ✨ Features

- Smooth previous and next slide navigation
- Draggable custom scrollbar
- Automatic navigation-button visibility
- Responsive layout for desktop, tablet, and mobile
- Touch-friendly horizontal scrolling
- Mobile scroll snapping
- Lightweight implementation with no framework dependencies
- Ten-image demonstration gallery

## 🧰 Technology Stack

| Technology | Purpose |
|---|---|
| **HTML5** | Page structure and slider markup |
| **CSS3** | Layout, styling, responsiveness, and scroll behaviour |
| **JavaScript (ES6)** | Slider navigation, drag interaction, and UI state |
| **Google Material Symbols** | Previous and next navigation icons |

## 📁 Project Structure

```text
Javascript-assignment/
├── images/
│   ├── img-1.jpg
│   ├── img-2.jpg
│   ├── ...
│   └── img-10.jpg
├── index.html
├── script.js
├── style.css
└── README.md
```

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/samusa099/Javascript-assignment.git
```

### 2. Open the project directory

```bash
cd Javascript-assignment
```

### 3. Run the project

Open `index.html` directly in a modern browser.

For a better local-development experience, serve the folder with a lightweight development server such as the **Live Server** extension in Visual Studio Code.

## 🎮 How to Use

- Select the **left** or **right** arrow to move through the gallery.
- Drag the scrollbar thumb to navigate to a specific position.
- Swipe or horizontally scroll on a touch-enabled device.
- Resize the browser window to observe the responsive layout.

## ⚙️ How It Works

The JavaScript module performs four main tasks:

1. Calculates the maximum horizontal scroll distance.
2. Scrolls the image list when a navigation button is selected.
3. Synchronizes the custom scrollbar thumb with the gallery position.
4. Hides navigation controls when the slider reaches either boundary.

## 📱 Responsive Behaviour

| Viewport | Behaviour |
|---|---|
| **Desktop** | Navigation buttons, draggable scrollbar, and full-size images |
| **Tablet** | Touch scrolling with reduced spacing and image dimensions |
| **Mobile** | Swipe navigation, hidden arrow controls, and scroll snapping |

## 🛠️ Customisation

### Add or replace images

Place image files inside the `images/` directory and update the image elements in `index.html`.

```html
<img class="image-item" src="images/your-image.jpg" alt="Descriptive alternative text" />
```

### Change image dimensions

Update the following rule in `style.css`:

```css
.slider-wrapper .image-list .image-item {
  width: 325px;
  height: 400px;
  object-fit: cover;
}
```

### Change the number of columns

Keep the CSS grid column count aligned with the number of gallery images:

```css
grid-template-columns: repeat(10, 1fr);
```

## ✅ Recommended Improvements

Potential future enhancements include:

- Keyboard navigation with arrow keys
- More descriptive image alternative text
- Touch and pointer events for unified drag support
- Automatic slide playback with pause controls
- Full-screen preview or lightbox mode
- GitHub Pages deployment for a public live demo

## 🙏 Attribution

This assignment is based on an image-slider implementation credited in the source code to **CodingNepal**. The repository is maintained as an educational front-end practice project.

## 👤 Author

**Siam Ahmad Musa**

[![GitHub](https://img.shields.io/badge/GitHub-samusa099-181717?style=for-the-badge&logo=github)](https://github.com/samusa099)

---

<div align="center">

Made for JavaScript front-end practice.

</div>

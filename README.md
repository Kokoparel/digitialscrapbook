# 🦋 Golden Truth — Digital Scrapbook

*"Without love, it cannot be seen."*

A beautiful, interactive web-based canvas inspired by the aesthetic and themes of *Umineko: When They Cry*. Just as witches gaze upon fragments (*kakera*) in the Meta-World to uncover the truth, this project provides a sophisticated workspace to drag, drop, and weave your own memories into elegant scrapbook pages. 

Built with pure HTML, CSS, and Vanilla JavaScript, **Golden Truth** allows you to assemble photos, text, and stickers, and export them as high-quality, textured PNGs fit for the Ushiromiya family archives.

## ✨ Features of the Game Board

* **The Meta-World Canvas:** A free-form, interactive workspace with smooth drag-and-drop functionality for all elements.
* **Summoning Fragments:** Easily upload, resize, and position local images (your memories) directly onto the canvas.
* **Weaving the Truth:** Add elegant typography (Headings, Body text, and Captions) using classic serif and sans-serif fonts. Double-click to edit your text directly on the board.
* **Endless Magic (Stickers):** A curated grid of emoji stickers that can be added, resized, and rotated to breathe life into your pages.
* **The Master's Control Panel:** A dynamic properties sidebar to adjust the opacity, rotation, size, and layering of any selected fragment.
* **Multiple Game Boards:** Create and manage multiple scrapbook pages within a single session without losing your place.
* **Sealing the Grimoire (Export):** Uses `html2canvas` to render the workspace into a high-resolution PNG, complete with a beautifully textured "cream paper" background and an elegant gold framing fit for the Golden Witch.

## 🛠️ The Magic (Tech Stack)

No complex spells or backend servers are required here. The project is built entirely on standard web technologies:

* **HTML5:** Semantic structure for the canvas and tools.
* **CSS3:** Custom styling featuring a refined, high-society aesthetic using CSS variables, Flexbox/Grid layouts, and Google Fonts (*Playfair Display* & *DM Sans*).
* **Vanilla JavaScript (ES6+):** Handles all state management, drag-and-drop logic, DOM manipulation, and export functionality—proving that pure JS is its own kind of endless magic.
* **[html2canvas](https://html2canvas.hertzen.com/):** The single external library used to capture the DOM and forge the final image file.

## 🚀 Entering the Golden Land

Because this is a static frontend application, setting it up is incredibly simple.

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Kokoparel/digitialscrapbook.git](https://github.com/Kokoparel/digitialscrapbook.git)
    cd digitialscrapbook
    ```

2.  **Open the application:**
    Simply open the `index.html` file in any modern web browser.
    *(Tip: Use a "Live Server" extension in VS Code for the best development experience).*

## 🖱️ How to Play

1.  **Gather Fragments:** Click the "Upload image" zone in the left sidebar to add photos to your canvas.
2.  **Declare Truths:** Click on the text styles or stickers in the sidebar to add them. Double-click any text to edit its contents.
3.  **Arrange the Board:** Click and drag any item to move it. Use the gold handle on the bottom right of images to resize them.
4.  **Refine the Magic:** Click an item to select it. Use the right sidebar to adjust its rotation, opacity, text color, or sticker size.
5.  **Turn the Page:** Use the top navigation bar to add new pages (`+`), switch between them, or discard them (`✕`).
6.  **Seal the Truth:** Click "↓ Download PNG" to save your current page as a styled, high-quality image.

## 🤝 Contributing

Fellow game masters and developers are welcome to contribute! Feel free to check the [issues page](https://github.com/Kokoparel/digitialscrapbook/issues) if you want to submit a pull request or suggest a new feature.

## ✍️ Author

**Farrel Athaillah Wijaya**
* GitHub: [@Kokoparel](https://github.com/Kokoparel)


# 🌐 LinkDeck: Custom Browser Homepage

**LinkDeck** is a customizable browser homepage that provides quick access to your favorite web apps and sites, organized into convenient categories. With a visually appealing layout and intuitive design, LinkDeck helps boost productivity and streamline your daily workflow.

🔗 **Live Site:** https://slightsmile.github.io/LinkDeck/

---

## ✨ Features

- 🗂 **Organized Categories**  
  Access featured projects and links grouped into:
  - 📁 Google Workspace  
  - 🤖 AI assistants
  - 📱 Social
  - 💻 Build & write
  - 🎬 Entertainment  
  - 🎮 Gaming  

- 🔗 **Visual Shortcuts**  
  Each link has a recognizable icon and a visible name. Featured projects include Mohi Uddin, TokenShelf, and GitHub Treasures.

- ⚡ **Lightweight Assets**
  Raster shortcut logos use WebP at twice their displayed size for sharp icons on high-density screens. Small SVG logos stay as vectors. The original background animation uses MP4 with a WebP still as its fallback; reduced-motion preferences show the still.

- 📱 **Responsive Design**  
  Three columns on wide screens, two on tablets, and a single column on phones. Shortcuts have generous tap targets and visible keyboard focus.

- 🛠 **Customizable**  
  Easily edit the homepage by modifying the HTML and adding your own icons or links.

---

## 🛠️ Technologies Used

- **HTML5** – Structure of the webpage  
- **CSS3** – Styling, layout, and responsiveness

---

## 🚀 Getting Started

### 1. Clone or Download the Repository

- Clone the repository:
```bash
git clone https://github.com/Slightsmile/LinkDeck.git
```
- Or download the ZIP and extract it.

### 2. Open the Homepage
- Open the index.html file in your web browser.

### 3. Customize Your Links
- Open index.html in a code editor.
- Add, remove, or change links and icons as needed.
- Place any new icon images in the /images folder.

### 4. Change the Appearance
- Replace `images/bg.mp4` to change the animated background and `images/bg.webp` to change its still-image fallback. Adjust the overlay in the `body::before` rule in `styles.css` to change its brightness.
- Edit the color variables at the top of styles.css to change the background, cards, text, and accent colors.
- Cards use translucent backgrounds so the animation remains visible. Adjust the alpha percentages in `--surface` and `.project-link` to change their transparency; `--outside-text` controls the brighter text outside the cards.
- The page uses local icons and system fonts, so it also works directly from index.html without a server or build step.

---

## 📁 File Structure
```
/linkdeck
│
├── index.html       # Main homepage file
├── styles.css       # Stylesheet for layout and appearance
├── /images          # Optimized shortcut icons, background video, and still fallback
└── README.md        # Project documentation
```

---

## 📜 License
This project is open source and available under the MIT License.
Feel free to use and modify it for personal use.

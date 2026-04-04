# LinkedIn Banner Generator

A lightweight, single-file web tool that generates a professional **1584x396px** LinkedIn banner tailored for a tech/AI professional profile.

Built with pure **HTML5**, **CSS3**, **JavaScript**, and **inline SVG** — no frameworks, no dependencies.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![SVG](https://img.shields.io/badge/SVG-FFB13B?style=flat&logo=svg&logoColor=black)

---

## Features

- **Dark-themed design** with subtle blue accent glow
- **SVG neural network art** with nodes and connection lines
- **Code watermark** overlay in JetBrains Mono font
- **Dual photo slots** with grayscale filters and gradient blending
- **Skill badges** — categorized as highlighted (blue) and secondary (dark)
- **Responsive scaling** — adapts to any screen size via JS
- **Google Fonts** — Inter for UI text, JetBrains Mono for code

---

## Tech Stack

| Technology | Usage |
|------------|-------|
| HTML5 | Semantic structure, image handling |
| CSS3 | Flexbox, gradients, filters, pseudo-elements, transforms |
| JavaScript | Responsive banner scaling via DOM manipulation |
| SVG | Inline vector graphics for neural network visualization |
| Google Fonts | Inter, JetBrains Mono |

---

## How to Use

1. Clone the repository
   ```bash
   git clone https://github.com/your-username/linkedin-banner.git
   cd linkedin-banner
   ```

2. Add your photos
   - Save your first photo as `photo1.jpeg` (appears on the left)
   - Save your second photo as `photo2.jpeg` (appears on the right)

3. Open `banner.html` in **Google Chrome**

4. Capture the banner
   - Press `F12` to open DevTools
   - Right-click the `.banner` element in the Elements panel
   - Select **Capture node screenshot**

5. Upload the screenshot as your LinkedIn banner

---

## Project Structure

```
linkedin-banner/
├── banner.html      # Single-file banner generator (HTML + CSS + JS)
├── photo1.jpeg      # Left photo slot (user-provided)
├── photo2.jpeg      # Right photo slot (user-provided)
├── .gitignore       # Ignores photo files
└── README.md
```

---

## Customization

You can easily customize the banner by editing `banner.html`:

- **Name & Title** — Update the `.name` and `.title-row` sections
- **Skills** — Add or remove `.skill` badges
- **Colors** — Change the accent color `#3b82f6` to your preference
- **Photos** — Adjust `object-position`, `filter`, and overlay gradients
- **Code Watermark** — Edit the `.code-watermark` text content
- **Tagline** — Modify the `.tagline` section



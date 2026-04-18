
# LinkedIn Banner Generator

A lightweight web tool to create a **professional LinkedIn banner (1584 × 396 px)** for tech and AI-focused profiles.

Built using **pure HTML, CSS, JavaScript, and inline SVG** — no frameworks or external dependencies.

---

## Overview

This project generates a modern, dark-themed LinkedIn banner featuring a clean tech aesthetic with subtle visual elements like neural network graphics, skill highlights, and dual image placeholders.

It is designed to help developers quickly create a strong personal branding banner without using design tools.

---

## Features

* Dark-themed professional layout with blue accent styling
* Inline SVG-based neural network illustration
* Code-style watermark using JetBrains Mono
* Dual image slots with smooth blending and grayscale effects
* Skill badges with clear visual hierarchy (primary & secondary)
* Fully responsive scaling using vanilla JavaScript
* Uses Google Fonts (Inter + JetBrains Mono)

---

## Tech Stack

| Technology   | Purpose                                         |
| ------------ | ----------------------------------------------- |
| HTML5        | Structure and layout                            |
| CSS3         | Styling, gradients, effects, and responsiveness |
| JavaScript   | Dynamic scaling and rendering logic             |
| SVG          | Neural network visualization                    |
| Google Fonts | Typography (Inter, JetBrains Mono)              |

---

## How to Use

1. Clone the repository

```bash
git clone https://github.com/your-username/linkedin-banner.git
cd linkedin-banner
```

2. Add your images

* Save your first image as `photo1.jpeg` (left side)
* Save your second image as `photo2.jpeg` (right side)

3. Open the file

* Open `banner.html` in any modern browser (recommended: Chrome)

4. Export the banner

* Open DevTools (`F12`)
* Right-click the banner element
* Select **“Capture node screenshot”**

5. Upload the exported image to LinkedIn as your banner

---

## Project Structure

```
linkedin-banner/
├── banner.html      # Main banner generator (single-file app)
├── photo1.jpeg      # Left profile image
├── photo2.jpeg      # Right profile image
├── .gitignore       # Ignores local images
└── README.md
```

---

## Customization

You can easily personalize the banner by editing `banner.html`:

- **Name & Title** — Update the `.name` and `.title-row` sections
- **Skills** — Add or remove `.skill` badges
- **Colors** — Change the accent color `#3b82f6` to your preference
- **Photos** — Adjust `object-position`, `filter`, and overlay gradients
- **Code Watermark** — Edit the `.code-watermark` text content
- **Tagline** — Modify the `.tagline` section

---

## License

This project is open source and available under the [MIT License](LICENSE).

# LinkedIn Banner Generator

A small browser-based tool for putting together a clean LinkedIn banner (1584 x 396 px). Mostly built with tech / AI profiles in mind.

I made this because I kept opening Figma every time I wanted to refresh my banner, which felt like overkill. So now it's just an HTML file you tweak and screenshot.

No build step, no dependencies. Open it and go.

---

## What it does

Generates a dark banner with a modern dev-ish look. Soft background, a bit of decorative SVG, two photo slots, and a row of skill tags in the middle.

It's locked to LinkedIn's banner dimensions, so you don't need to mess with sizing.

---

## Features

* Dark theme with a blue accent (one color to swap if you want a different vibe)
* Inline SVG background, small neural-network style graphic
* Faint code watermark for the developer feel
* Two photo slots with grayscale + edge fade
* Skill badges in two visual tiers
* Runs straight in the browser, no build step
* Inter + JetBrains Mono via Google Fonts

---

## Tech stack

* HTML, CSS, a few lines of vanilla JS
* Inline SVG for the visuals
* Google Fonts for typography

---

## How to use

1. Clone the repo

```bash
git clone https://github.com/AradhyaStuti/LINKEDIN-BANNER.git
cd LINKEDIN-BANNER
```

2. Drop in your photos

* `photo1.jpeg` shows up on the left
* `photo2.jpeg` shows up on the right

3. Open `banner.html` in a browser. Chrome works best for the next step.

4. Export the image

* Open DevTools (`F12`)
* Right-click on the `.banner` element in the inspector
* Pick **"Capture node screenshot"**

5. Upload that screenshot as your LinkedIn banner.

---

## Project structure

```
linkedin-banner/
├── banner.html
├── photo1.jpeg
├── photo2.jpeg
├── .gitignore
└── README.md
```

---

## Customization

Everything lives in `banner.html`, so it's all in one place:

* Change the name and titles in the text section
* Add or remove skill badges
* Swap the accent color (`#3b82f6` everywhere)
* Adjust the photo crop or filters
* Edit the watermark code snippet
* Change the tagline at the bottom

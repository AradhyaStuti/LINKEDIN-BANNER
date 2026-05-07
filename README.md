# My LinkedIn Banner

This is the banner I designed for my LinkedIn profile. 1584 x 396 px, built straight in HTML and CSS instead of being put together in Figma. I wanted to tweak it like code, not drag boxes around on a canvas.

## The look

Dark background with a faint blue glow behind the name. Two of my own photos sit on the left and right, blended into the edges with a slight grayscale so the colors don't fight the rest of the layout. A faint code snippet in the top-left and a big `</>` mark in the bottom-left corner give it a dev feel without being too on-the-nose.

The center has my name, my titles, and a row of skill tags. Inter for the name, JetBrains Mono for everything that should read as code.

## What's on it

* **Name** — Aradhya Stuti
* **Titles** — AI / ML Engineer · Full Stack Developer · IEEE Published Author
* **Skill tags** — Gen AI, Deep Learning, LLMs, RAG, MERN Stack, Python, Docker, Git/GitHub, CI/CD, REST APIs
* **Tagline** — Building intelligent systems, one model at a time

## Files

* `banner.html` — the banner itself, all in one file
* `photo1.jpeg` — left side photo
* `photo2.jpeg` — right side photo

## How I exported it

Opened `banner.html` in Chrome, hit `F12`, right-clicked on the `.banner` element in the inspector, picked **Capture node screenshot**. The PNG that comes out is exactly 1584 x 396 px, which is the image that's now on my LinkedIn profile.

## Why HTML and CSS

Honestly because spacing, fonts, and color are easier to control with code than with a design tool. Swapping a skill or changing the accent color is a one-line edit. And the result renders pixel-for-pixel the same every time, so no surprises when I re-export.

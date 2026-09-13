# Roshan Kumar — Portfolio

This is my personal portfolio website, built entirely from scratch using plain HTML, CSS, and JavaScript — no frameworks, no templates, no build tools.

## Live Site

https://fluenta.website

## What's on the site

### Header

The page opens with my name, "Roshan Kumar," at the top, followed by a horizontal divider line separating it from the content below.

### Contact section

A block containing three ways to reach me, each shown with its own icon:

- **Email** — a clickable `mailto:` link to iamaroshankumar@gmail.com
- **GitHub** — links to my GitHub profile at github.com/2006-Z
- **LinkedIn** — links to my LinkedIn profile

### UP section

A block related to Uttar Pradesh Police services, marked with the official UP Police emblem (shown in black and white) next to each link:

- **UP Application Screenshot** — see its own repo for details: https://github.com/2006-Z/UP-Application-Screenshot
- **UP Challan Download** — a planned second feature for downloading UP traffic challans. This link exists on the page but the feature itself hasn't been built yet.

### Project section

A block listing my other repositories, each shown with a small circular profile-style icon:

- **Cute** — github.com/2006-Z/Cute
- **Terminal** — github.com/2006-Z/Terminal
- **Fluenta** — github.com/2006-Z/Fluenta

## Layout

The Contact and UP blocks sit side by side at the top of the page, in a shared row. The Project block sits to their right, matching their size. Below all of this is a divider line.

## Tech stack

- **HTML** — page structure
- **CSS** — all styling, including layout, spacing, fonts (Times New Roman throughout), and the circular/grayscale icon treatment
- **JavaScript** — used only within the UP Application Screenshot tool's own page, not on this main page

No frameworks (React, Vue, etc.), no CSS libraries (Bootstrap, Tailwind, etc.), and no build step — the files can be opened or served exactly as they are.

## Files in this repo

- `index.html` — the main page
- `style.css` — all styles for the main page
- `up-logo.svg` — the UP Police emblem icon used in the UP section
- `alone-boy.png` — the icon used for the Project section repo links

Note: the UP Challan Download link points to `up-challan.html`, which doesn't exist yet — that page hasn't been built.

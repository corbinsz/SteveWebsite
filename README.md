# Steven Van Overmeiren — Mechanical Engineering Portfolio

A portfolio website Corbin Szenegeto built for Steven Van Overmeiren to showcase his mechanical engineering projects (solar car suspension, finite-element code, hydroponics, and others), resume, and contact page.

The writing, project photos, and documents belong to Steven Van Overmeiren.

## What Corbin built

A multi-page responsive static site, styled in ASU maroon and gold:

- Home, projects, resume, and contact pages
- A projects index of ten cards, each linking to a project detail page
- Four subsystem pages (chassis, front suspension, steering, and brakes) linked from the solar car mechanical systems page
- A projects dropdown in the navbar, and a hamburger menu on small screens
- Image galleries that become carousels (arrows, dots, keyboard, and swipe), plus a click-to-zoom lightbox
- Scroll-reveal animations and a navbar that tightens after you scroll
- Embedded PDF viewers and download links for the resume, finite-element reports, and wind-energy paper

## Tech

HTML, CSS, and vanilla JavaScript. There is no build step or framework. Plus Jakarta Sans is loaded from Google Fonts.

## File structure

```
index.html          Home
projects.html       Project index
resume.html         Resume
contact.html        Contact
styles.css          Layout, navigation, and page styles
script.js           Mobile menu, carousel, lightbox, and scroll effects
projects/           Project detail pages
assets/favicon.svg
assets/images/      Profile and project photos
assets/pdfs/        Resume and project reports
```

## View it locally

Open `index.html` in a browser, or serve the folder so PDF embeds load reliably:

```bash
python3 -m http.server
```

Then open `http://localhost:8000`.

Page links include the `.html` extension, so they resolve with that server and on any static host.

## Deploy

The site is a static folder and can be deployed to any static host. Publish the repository root as the site directory.

# Fickoland

**Live website: [fickoland.pl](https://fickoland.pl)**

A responsive website for Fickoland, a holiday cottage resort in Ponikiew near Wadowice and Lake Mucharskie, Poland. The site introduces the accommodation, helps visitors explore nearby attractions, and provides contact details and directions.

Designed and developed by **[Florian Ficek](https://github.com/Fl0rk3)** using HTML, SCSS, and vanilla JavaScript. The website content is in Polish; this README is in English.

## Features

- **Accommodation showcase** — photographs and descriptions of the cottages, bedrooms, living rooms, kitchens, bathrooms, and outdoor facilities.
- **Photo galleries** — four looping carousels powered by Splide, covering the cottages and their interiors.
- **Responsive layouts** — dedicated mobile and desktop styles, with a primary breakpoint between 1024px and 1025px.
- **Local attractions** — a separate page listing places to visit, distances or travel times, and links to attraction websites.
- **Contact and directions** — clickable phone and email links, an embedded Google Map, and links to accommodation listings and social media.
- **Smooth navigation** — animated scrolling to the accommodation section and navigation between the three pages.

## Tech Stack

| Technology | Role |
| --- | --- |
| HTML5 | Page structure, content, and metadata |
| SCSS / CSS3 | Shared and page-specific styles, responsive layouts, CSS Grid, Flexbox, and hover effects |
| Vanilla JavaScript | Gallery initialization, scrolling, and a viewport-height CSS variable |
| Splide | Looping image carousels |
| Smooth Scroll | Animated anchor navigation |
| Google Fonts | Typography |
| Google Maps embed | Resort location on the contact page |

The project is a static, multi-page website built with HTML, SCSS, and small JavaScript scripts.

## Project Structure

```text
fickoland/
|-- index.html          # Home page and accommodation galleries
|-- attractions.html    # Nearby attractions
|-- contact.html        # Contact details and embedded map
|-- gfx/                # Cottage photographs and other image assets
|-- scripts/
|   |-- slide.js         # Initializes the four Splide carousels
|   |-- scroll.js        # Configures smooth anchor scrolling
|   `-- viewport.js      # Sets the --vh CSS custom property
|-- styles/             # SCSS sources, compiled CSS, and source maps
`-- README.md
```

## Frontend Highlights

This project demonstrates practical frontend work for a hospitality website:

- Translating accommodation information into a clear, photo-focused page structure.
- Building distinct mobile and desktop experiences with shared styles and page-specific layouts.
- Using CSS Grid and Flexbox for hero sections, alternating image-and-text sections, and footer content.
- Integrating third-party UI libraries with small JavaScript scripts.
- Keeping a multi-page website deployable as static files without an application framework.

## Author

**Florian Ficek** — [GitHub profile](https://github.com/Fl0rk3)

## License

No license file is currently included in this repository. No open-source license is declared for the source code or image assets.

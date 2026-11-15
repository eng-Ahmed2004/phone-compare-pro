# Phone Compare Pro

A responsive phone comparison website built with plain HTML, CSS, and JavaScript. No frameworks and no build step.

**Live demo:** https://eng-ahmed2004.github.io/phone-compare-pro/

## Features

- **Browse and filter** phones by brand and price range
- **Sort** by price, battery capacity, or rating
- **Search** by name
- **Compare two phones** side by side, with the better value in each row highlighted
- **Favourites** saved in the browser with `localStorage`
- **Top-rated ranking** list
- **Dark mode** toggle
- **Responsive layout** with a mobile menu and scroll-reveal animations
- About, Contact, and Privacy pages

## Run it

Open `index.html` in a browser, or serve the folder locally:

```bash
git clone https://github.com/eng-Ahmed2004/phone-compare-pro.git
cd phone-compare-pro
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Project structure

```text
index.html     # Main page: filters, phone grid, comparison table, ranking
about.html     # About page
contact.html   # Contact page
privacy.html   # Privacy page
style.css      # Styles, light and dark themes
script.js      # Phone data, filtering, comparison, favourites
```

## Author

Ahmed Srour — [@eng-Ahmed2004](https://github.com/eng-Ahmed2004)

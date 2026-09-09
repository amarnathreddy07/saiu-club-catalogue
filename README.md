# SaiU Club Directory

A static Club Catalogue for Sai University. It presents club information by category, including activities, time commitment, experience requirements, representatives, and contact links.

## Project Structure

- `index.html` - Page structure and introductory content.
- `styles.css` - Layout, responsive styles, typography, colors, and animations.
- `script.js` - Category and club data plus dynamic rendering.
- `images/` - Logos and category illustrations used by the site.
- `data/` - Source CSV files containing club responses and contact details.

## Run Locally

No build step or package installation is required.

The simplest option is to open `index.html` directly in a browser.

## Updating Club Information

Club entries are stored in the `CLUBS` array in `script.js`. Each entry can include:

- Club name and category
- Tagline, description, activities, and audience
- Frequency, time commitment, experience, and selection details
- Representative, achievements, social links, and email address

Category names, colors, descriptions, and illustrations are defined in the `CATEGORIES` array in `script.js`.

## Updating Visuals

Add image assets to `images/` and reference them from the relevant category or club data. Category illustrations are SVG files named `category-<category>.svg`.

## Notes

This is a client-side project: the browser loads the HTML, CSS, and JavaScript files directly, and no backend is required.

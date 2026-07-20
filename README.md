# Homework. Module 6. Responsive Web Design

## Project Requirements

1. Continue working in the `goit-markup-hw-06` repository (or create it from the provided Template if required).
2. Implement the responsive layout according to the [Homework #6 design](https://www.figma.com/design/folOvI69KUmwYN47Njpr0O/Web-Studio--Version-5.1-?node-id=297046-1554).
3. Apply the **Mobile First** approach using media queries.
4. Set up GitHub Pages and ensure the live page link is available in the **About** section of the GitHub repository.
5. After pushing your changes, wait approximately **5 minutes** before submitting your work for review to allow GitHub Pages to finish deploying the latest version.

---

## Project Requirements

* [x] - All styles are written in their corresponding CSS files and are properly connected.
* [x] - File names do not contain Cyrillic characters or spaces. Only English letters, numbers, and words are used.
* [x] - No horizontal scrollbar appears when viewing the page on devices with widths starting from **320px**.
* [x] - Source code is formatted using `Prettier`.
* [x] - All images and text content are taken directly from the provided design mockup.
* [x] - The project uses the minified version of [`modern-normalize`](https://cdnjs.cloudflare.com/ajax/libs/modern-normalize/3.0.1/modern-normalize.min.css).
* [x] - The code follows the provided [coding guidelines](https://codeguide.co/).

---

## Responsive Layout

* [x] - The `<head>` section includes the `viewport` meta tag.
* [x] - The layout is implemented for three responsive breakpoints:
  * **320px**
  * **768px**
  * **1158px**
* [x] - All raster background and content images are responsive and support both **1x** and **2x** display densities.
* [x] - Responsive background images use the `min-resolution` media feature.
* [x] - Styles are written using the **Mobile First** approach with `min-width` media queries.
* [x] - Styles that apply only within specific viewport ranges are wrapped in appropriate media queries, such as:
  * `(min-width: ...) and (max-width: ...)`
  * `(max-width: ...)`
* [x] - Media queries do not contain unnecessary duplicate styles.
* [x] - Responsive images are implemented using `src` and `srcset` (do **not** use `<picture>` with `<source>`).

---

## Mobile Menu

* [x] - The mobile navigation menu is implemented as a separate markup block placed after the footer.
* [x] - All mobile menu styles are defined in `mobile-menu.css`.
* [x] - The mobile menu occupies the entire viewport width and height.
* [x] - The menu is hidden by default.
* [x] - Adding the `is-open` class displays the mobile menu.

---

## Styling Requirements

* [x] - On mobile devices, the header height is determined by the logo's vertical padding.
* [x] - The **Hero** section uses separate background images for:
  * Mobile (up to **320px**)
  * Tablet (up to **768px**)
  * Desktop (up to **1440px**)
* [x] - Each Hero background image has both **@1x** and **@2x** versions.
* [x] - Cards in the **Our Team** section maintain a fixed width of **264px** on mobile, tablet, and desktop layouts.
* [x] - The hover overlay on **Our Portfolio** cards is available at all viewport widths.


# Homework. Module 5. Forms & Tables

## Project Requirements

1. Create a repository named `goit-markup-hw-05` (you may use the provided Template repository).
2. Clone the repository and copy the files from the previous homework if you did not create it from the Template.
3. Add the HTML markup and CSS styling for the modal window, forms, and all decorative effects according to the Homework #5 design.
4. Set up GitHub Pages and add the link to the live page in the **About** section of the GitHub repository.
5. After pushing your changes, wait approximately **5 minutes** before submitting your work for review to allow GitHub Pages to finish deploying the latest version.

---

## Project Requirements

* [x] - All styles are written in their corresponding CSS files and are properly connected.
* [x] - File names do not contain Cyrillic characters or spaces. Only English letters, numbers, and words are used.
* [x] - Source code is formatted using `Prettier`.
* [x] - All images and text content are taken directly from the provided design mockup.
* [x] - The project uses the minified version of [`modern-normalize`](https://cdnjs.cloudflare.com/ajax/libs/modern-normalize/3.0.1/modern-normalize.min.css).
* [x] - The code follows the provided [coding guidelines](https://codeguide.co/).

---

## Modal Window

* [x] - The backdrop (dark semi-transparent overlay) is fully implemented and placed in `index.html` immediately after the footer.
* [x] - The backdrop covers **100%** of the viewport width and height and remains fixed to the viewport.
* [x] - The modal window is fully implemented and styled.
* [x] - The modal markup is placed after the footer.
* [x] - All modal styles are defined in `modal.css`.
* [x] - The modal window is centered both vertically and horizontally within the backdrop.
* [x] - A close button is implemented and positioned in the upper-right corner of the modal.
* [x] - The modal window and backdrop are hidden by default.
* [x] - Adding the `is-open` class to the backdrop displays both the backdrop and the modal window.
* [x] - Icons inside form inputs are vertically centered.

---

## Forms

* [x] - All form elements from the design are fully implemented in HTML.
* [x] - HTML tags are used according to their semantic meaning.
* [x] - The newsletter subscription form and all of its elements are implemented in the footer.
* [x] - The contact/request form and all of its elements are implemented inside the modal window.
* [x] - Every form input includes a `name` attribute.
* [x] - Each `name` attribute is descriptive and clearly identifies the purpose of the field.
* [x] - Every form input has an associated `<label>` element.
* [x] - Inputs include a `placeholder` attribute wherever placeholder text is present in the design.
* [x] - Form submission buttons use `type="submit"`.
* [x] - All new form icons are added to the existing `icons.svg` sprite.
* [x] - The `<textarea>` element has a fixed size and cannot be resized by the user.

---

## Styling Requirements

* [x] - The newsletter subscription form in the footer is styled according to the design.
* [x] - The form inside the modal window is styled according to the design.
* [x] - When an input receives focus, both its border and the corresponding icon change color as shown in the design.
* [x] - The native license agreement checkbox is visually hidden.
* [x] - The custom checkbox is implemented manually using an SVG checkmark from the `icons.svg` sprite.
* [x] - The custom checkbox follows the structure below:

```html
<div>
  <input name="" id="" />
  <label for="">
    <span>
      <svg width="" height="">
        <use href="" />
      </svg>
    </span>
    <span>
      I accept the terms and conditions of the
      <a href="#">Privacy Policy</a>
    </span>
  </label>
</div>
```

* [x] - The checkmark icon appears and disappears by changing its `opacity`, not by changing its color.
* [x] - Every SVG icon explicitly defines `width` and `height` attributes.
* [x] - The `fill` property is applied directly to the `<svg>` element.
* [x] - All hover and focus effects (color, background-color, border, box-shadow, etc.) use transitions with:
  * Duration: **250ms**
  * Timing function: `cubic-bezier(0.4, 0, 0.2, 1)`

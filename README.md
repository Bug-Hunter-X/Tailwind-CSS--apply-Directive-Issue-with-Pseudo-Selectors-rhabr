# Tailwind CSS @apply Directive Issue with Pseudo-Selectors

This repository demonstrates a bug where Tailwind CSS's `@apply` directive doesn't correctly apply styles when used with classes containing pseudo-selectors like `:hover` or `:focus`.

## Bug Description

The `@apply` directive is intended to apply the styles of a pre-defined utility class to another element. However, when the applied class includes a pseudo-selector, the styles associated with that pseudo-selector are not applied. This leads to unexpected behavior where hover or focus styles don't work as expected.

## Steps to Reproduce

1. Clone the repository.
2. Run `npm install` to install dependencies (if any).
3. Open `index.html` in your browser.
4. Observe that the hover and focus styles are not applied as expected.
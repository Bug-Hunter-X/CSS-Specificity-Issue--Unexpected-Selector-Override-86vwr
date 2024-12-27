# CSS Specificity Bug

This repository demonstrates an uncommon CSS specificity issue where a more specific selector is unexpectedly overridden by a less specific one due to the combined effect of element and class selectors.

## Bug Description

A `div.my-class` selector (element + class) with a higher specificity is unexpectedly overridden by the `div` selector (only element) because the specificity of selectors is influenced by their types and composition.

## How to Reproduce

1. Clone this repository.
2. Open `bug.css` and observe the code.
3. View the CSS in your browser; note that element `div` with class `my-class` displays blue instead of green.
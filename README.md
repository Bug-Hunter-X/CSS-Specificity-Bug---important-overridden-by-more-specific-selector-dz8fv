# CSS Specificity Bug: !important overridden by more specific selector

This repository demonstrates a subtle bug related to CSS specificity and the `!important` declaration. The `!important` flag usually overrides all other styles, but it is not above specificity. 

## The Bug

The bug lies in the interaction between `!important` and more specific selectors.  Even with `!important`, a more specific selector can still override the style.  The provided CSS demonstrates this scenario.

## The Solution

The solution involves understanding and adjusting the CSS specificity and avoiding `!important` unless necessary.  See the solution file for details.  Prefer more specific selectors over `!important`. 

## How to reproduce

1. Clone this repo
2. Open `bug.html` in a browser.
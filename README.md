# Uncommon HTML Bug: Unexpected Display Behavior

This repository demonstrates an uncommon bug related to unexpected behavior when manipulating the `display` property of an HTML element. The bug is subtle and may not be immediately apparent.

## Bug Description

The provided HTML code uses JavaScript to show and hide a div element.  However, if the element's initial display style is not explicitly set (i.e., it inherits from its parent), the toggle functionality may not work correctly in certain browsers or rendering contexts, resulting in inconsistent display behavior.

## How to Reproduce

1. Clone this repository.
2. Open `bug.html` in a web browser.
3. Click the "Show/Hide" button multiple times. Observe the inconsistent behavior.

## Solution

The `solution.html` file demonstrates a simple fix by setting the initial `display` style of the `div` element to `block` or `none`.

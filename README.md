# CSS Box-Shadow Issue with Inline Styles and Absolute Positioning

This repository demonstrates a CSS issue where the `box-shadow` property does not render correctly when applied inline to an element with `position: absolute`. The expected behavior is a visible box-shadow around the blue square. However, due to a quirk in how inline styles and absolute positioning interact, the shadow may be missing or improperly rendered.

The `bug.css` file contains the problematic code. The `solution.css` demonstrates a corrected version with the `box-shadow` property applied within a CSS class instead of inline.

## Solution

Avoid using inline styles for `box-shadow` or any complex CSS properties, especially when dealing with absolute positioning.  Apply styles via CSS classes for consistent and predictable results.  See `solution.css` for a working example.
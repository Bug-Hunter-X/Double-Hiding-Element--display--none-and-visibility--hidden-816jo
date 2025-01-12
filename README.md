# Double Hiding Element Bug in HTML

This repository demonstrates an uncommon bug in HTML related to hiding elements using both `display: none` and `visibility: hidden` in JavaScript.  Some browsers may interpret this inconsistently or throw an error.

The `bug.html` file shows the problematic code. The `solution.html` file provides a correct solution.

## Bug Description
The issue arises when attempting to hide an HTML element by setting both `style.display` to `'none'` and `style.visibility` to `'hidden'` simultaneously. While seemingly redundant, this combination can cause unpredictable behavior, particularly in older or less compliant browsers.
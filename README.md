# Silent `calc()` Errors in CSS

This repository demonstrates a subtle bug that can occur when using the CSS `calc()` function.  A syntax error within the `calc()` expression might not produce an obvious error message, leading to unexpected results.  The solution involves carefully checking the `calc()` syntax and using browser developer tools effectively.

## Bug Report

The `bug.css` file contains a simple CSS rule with a `calc()` function that has a syntax error. This error silently fails, producing no visible effect or clear error message in the browser console.  This can make debugging difficult.

## Solution

The `solution.css` file demonstrates the corrected code, fixing the syntax error in the `calc()` expression.  The corrected code produces the expected layout.
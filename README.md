# Typo in Arbitrary Value Causes Unexpected Behavior in Tailwind CSS

This repository demonstrates a common error in Tailwind CSS where a typo in an arbitrary value declaration can lead to unexpected behavior, such as elements ignoring specified dimensions.  The `bug.js` file shows the incorrect code, while `bugSolution.js` provides the corrected version.

## Bug Description

When using Tailwind's arbitrary value feature (e.g., `w-100px`), even a small typo can prevent Tailwind from correctly applying the style. This is often subtle and difficult to debug.

## How to Reproduce

1. Clone this repository.
2. Open `bug.js` and observe the unexpected behavior (the width is ignored).
3. Open `bugSolution.js` to see the corrected code.

## Solution

Carefully review your arbitrary value declarations in Tailwind. Even a minor typo (like an extra space or incorrect number) can cause issues. Double-check your syntax and ensure that you are using valid CSS units (px, em, rem, etc.).
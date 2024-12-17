# Uncommon HTML Bug: innerHTML and Mathematical Operations

This repository demonstrates a subtle bug related to the use of `innerHTML` in JavaScript within an HTML context. The bug highlights the importance of understanding how `innerHTML` handles mathematical operations.

## Bug Description
The `bug.html` file contains code that attempts to perform mathematical operations using `innerHTML`. This will lead to unexpected string concatenation instead of the expected numerical addition.

## Solution
The corrected code in `bugSolution.html` demonstrates the proper approach, using JavaScript to perform calculations separately before updating the `innerHTML` property. This ensures that the correct numerical results are displayed.

## How to Reproduce
1. Clone this repository.
2. Open `bug.html` in a web browser.  Observe the incorrect result.
3. Open `bugSolution.html` in a web browser. Observe the correct result.
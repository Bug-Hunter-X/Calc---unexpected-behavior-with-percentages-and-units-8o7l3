# CSS `calc()` Unexpected Behavior with Percentages and Units

This repository demonstrates an issue where the CSS `calc()` function produces unexpected results when combining percentage values with other units (like pixels).  The bug and solution are provided in separate CSS files.

## Bug (`bug.css`)
The `bug.css` file contains CSS code that showcases the unexpected calculation.  Observe the width of the element; it's not what is mathematically expected.

## Solution (`bugSolution.css`)
The `bugSolution.css` file illustrates a workaround to achieve the desired result.  It demonstrates how to restructure the calculation to avoid the unexpected outcome.

## Running the code
1. Clone this repository.
2. Open `bug.html` (you might need to create this simple html file which references the css file) in a web browser.
3. Compare the width of the element in both versions to see the difference.
# Unexpected CSS `calc()` Behavior Due to Spacing
This repository demonstrates an uncommon CSS bug related to incorrect spacing within the `calc()` function.  The bug arises from spaces placed before or after operators or values within `calc()`, leading to unexpected layout results.  The solution illustrates the correct usage of the `calc()` function to prevent these errors.  This is a subtle but important detail for ensuring consistent and predictable layouts.

## Bug
The `bug.css` file contains the erroneous CSS code.  The `calc()` function in this example contains unnecessary spaces, resulting in unpredictable results across different browsers and potentially leading to layout issues.

## Solution
The `bugSolution.css` file demonstrates the corrected CSS, showing the proper use of the `calc()` function without unnecessary spacing. This ensures accurate calculations and consistent layout.
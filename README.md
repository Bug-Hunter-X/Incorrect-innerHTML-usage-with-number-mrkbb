# Incorrect innerHTML Usage with Number

This example demonstrates an uncommon error in HTML. The code attempts to set the `innerHTML` property of a div element with a number (123) instead of a string. This leads to an empty div because the browser will not automatically convert the number to a string.  The solution shows the proper way to handle this.

## How to run
1. Save the code in two separate `.html` files (bug.html and solution.html) as described in the files.
2. Open `bug.html` in a web browser to see the error.
3. Open `solution.html` to see the correct implementation.
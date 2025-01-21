# Uncommon HTML Error: Deprecated Tag and Misused Inline Styles

This repository demonstrates an uncommon HTML error involving the use of a deprecated tag and misused inline styles. The code produces unexpected layout due to conflicting styles.

## Bug Description
The HTML file uses the deprecated &lt;font&gt; tag, which is considered bad practice.  Additionally, it has multiple style declarations within the style attribute resulting in unexpected rendering of the text.

## Solution
The solution replaces the &lt;font&gt; tag with semantically appropriate HTML elements like &lt;span&gt; and moves the styles to an external stylesheet for better maintainability and separation of concerns.

## How to run
1. Clone this repository
2. Open `bug.html` in your browser to see the error.
3. Open `bugSolution.html` to see the corrected code.
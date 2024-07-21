Longest Common Prefix Finder

Description

This project provides a web-based tool to find the longest common prefix string among a set of input strings. If no common prefix exists, the tool returns an empty string. The application checks for constraints on the input strings to ensure they are within acceptable limits.

Features

- Input strings as a comma-separated list.
- Validate the input strings to ensure they contain only lowercase English letters and are within acceptable length limits.
- Compute the longest common prefix string.
- Display the result directly on the webpage.

Usage

1. Open the HTML file in a web browser.
2. Enter a list of strings in the input field, separated by commas (e.g., flower,flow,flight).
3. Click the "Check" button to find the longest common prefix.
4. The result will be displayed below the button.

Constraints

- The number of input strings should be between 1 and 200.
- Each string must consist of only lowercase English letters and have a length between 0 and 200 characters.

Code Explanation

- The longestCommonPrefix function computes the longest common prefix string among an array of strings:
  - It validates the input to ensure that it meets the constraints.
  - It iteratively compares prefixes of the first string with each subsequent string to determine the longest common prefix.

- The HTML provides an input field for the user to enter strings and a button to trigger the prefix check.
- The result is displayed dynamically on the webpage when the button is clicked.

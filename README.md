# JavaScript Loose Comparison with Null and Zero

This repository demonstrates a common JavaScript error related to loose comparison (==) with null and 0 values.  The loose comparison operator does not distinguish between null and 0, potentially leading to unexpected results.  This example shows a function with explicit null checks for robust handling of null values.

## Bug

The `bug.js` file contains a function that performs addition, but the original implementation does not correctly handle `null` values, leading to unexpected results in certain cases.

## Solution

The `bugSolution.js` file provides a corrected implementation that explicitly handles `null` values, using strict equality (`===`) to ensure accurate comparisons and preventing unexpected behavior.
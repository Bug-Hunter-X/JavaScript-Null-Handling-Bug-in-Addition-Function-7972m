# JavaScript Null Handling Bug in Addition Function

This repository demonstrates a common yet subtle bug in JavaScript related to handling null values within an addition function.  The issue is not immediately obvious but could lead to unexpected behavior in various scenarios.  The `bug.js` file contains the buggy code, while `bugSolution.js` presents the corrected version.

## Bug Description

The `foo` function adds two numbers; however, it directly adds without adequately handling `null` input values which leads to unexpected results.

## Solution

The solution involves adding explicit null checks to prevent errors and ensure consistent behavior when `null` values are passed as arguments.
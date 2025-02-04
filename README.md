# Expo CLI Error: @expo/vector-icons Issues

This repository demonstrates a common but sometimes tricky error encountered when using the `@expo/vector-icons` package within an Expo project. The error is characterized by problems rendering icons, often due to incorrect imports, icon names, or package configuration. 

## Problem Description

The `bug.js` file showcases the problematic code that might lead to the error. This could involve incorrect import statements, misspelled icon names, or other configuration errors.  The error message may not be immediately clear. 

## Solution

The `bugSolution.js` file presents the corrected code, highlighting the changes necessary to resolve the icon rendering issue. This involves double-checking imports, verifying icon names against documentation, and ensuring the correct package installation and configuration.  Proper version management is also crucial.

## How to Reproduce

1. Clone this repository.
2. Run `npm install` or `yarn install`.
3. Run `expo start`.  You should initially observe the error in the `bug.js` example.
4. After correcting the code in `bugSolution.js`, the icons should render correctly.

## Note

Remember to consult the documentation for your chosen icon family for correct icon names and usage.
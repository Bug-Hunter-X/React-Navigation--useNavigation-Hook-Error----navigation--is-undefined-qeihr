# React Navigation: 'navigation' is undefined Bug

This repository demonstrates a common error in React Native applications using React Navigation: the `navigation` prop being undefined when using the `useNavigation()` hook.  The error arises from attempting to access navigation methods before the `navigation` context is fully established.

## Problem:

The `useNavigation()` hook in `bug.js` attempts to use `navigation.navigate()` before the navigation context is ready. This leads to a runtime error.

## Solution:

The solution in `bugSolution.js` demonstrates several approaches to correctly handle this situation, preventing the error.

## How to reproduce:

1. Clone this repository.
2. Run `npm install`.
3. Run the app. Observe the error.
4. Modify the code according to `bugSolution.js` to resolve the error.
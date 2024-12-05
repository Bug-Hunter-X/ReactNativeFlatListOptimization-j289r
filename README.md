# React Native FlatList Performance Issue: Duplicate or Missing Keys in `keyExtractor`

This repository demonstrates a common performance issue in React Native's `FlatList` component caused by incorrect or missing `keyExtractor` prop.  The issue is explained in detail in the `bug.js` file, highlighting the incorrect key selection.  The solution, provided in `bugSolution.js`, shows how to use a unique identifier for each item, leading to improved rendering performance and preventing visual glitches.  This example uses a simple array of objects; however, the same concept applies to more complex data structures.

## How to Reproduce

1. Clone this repository.
2. Run `npm install`.
3. Run `npx react-native run-android` (or `npx react-native run-ios`).
4. Observe the performance issues in the initial implementation and the improvement after applying the solution.
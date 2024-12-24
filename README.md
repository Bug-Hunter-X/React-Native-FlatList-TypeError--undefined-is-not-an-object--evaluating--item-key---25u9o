# React Native FlatList TypeError: undefined is not an object (evaluating 'item.key')

This repository demonstrates a common error encountered when using `FlatList` in React Native. The error, `TypeError: undefined is not an object (evaluating 'item.key')`, arises when the `renderItem` function returns `undefined` or throws an error, preventing proper access to item properties.

## Problem

The `renderItem` function in `FlatList` is crucial for rendering each item.  If it fails to return a valid React element, or returns `undefined`, this error occurs. This is often related to issues within data fetching, data processing, or conditional rendering within the `renderItem` function itself.  Incorrect data structures can also be the cause.
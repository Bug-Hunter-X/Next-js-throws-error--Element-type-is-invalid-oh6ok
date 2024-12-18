# Next.js - Element type is invalid Bug

This repository demonstrates a common Next.js error and its solution. The error occurs when an invalid element type is rendered, often due to a typo or incorrect component import.

## Bug Description

The bug is caused by trying to render an undefined component in the `pages/index.js` file. The component `MyComponent` is not correctly imported, leading to an `undefined` element type. 

## Solution

The solution involves correctly importing the `MyComponent` component and ensure it is properly defined. This prevents the undefined element error from occurring.
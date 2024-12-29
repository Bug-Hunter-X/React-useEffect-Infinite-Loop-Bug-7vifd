# React useEffect Infinite Loop Bug

This repository demonstrates a common React bug involving the `useEffect` hook and its dependency array.  The incorrect implementation leads to an infinite render loop. The solution showcases the correct way to use the `useEffect` hook to prevent this issue. 

## Bug Description:
The initial implementation is missing the count variable in the dependency array of the useEffect causing it to rerender infinitely because the count changes every time the button is clicked, triggering another rerender.

## Bug Solution:
The solution demonstrates the correct usage of the useEffect hook, including the `count` variable in the dependency array, resolving the infinite loop.

## How to reproduce
1. Clone this repo
2. Run `npm install`
3. Run `npm start`
4. Observe the infinite loop in console and the UI behavior
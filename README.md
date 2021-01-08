# Figma React Hook Example

Based on the official [Figma sample for react](https://github.com/figma/plugin-samples/tree/master/react), but changed the class components into functional components using hooks (introduced in React 16.8).

![Demo image](https://github.com/figma/plugin-samples/blob/master/_screenshots/webpack.png?raw=true)

Creates rectangles (same as the [Webpack sample plugin](https://github.com/figma/plugin-samples/blob/master/webpack)).

This demonstrates:

bundling plugin code using Webpack, and
using React with TSX.
The main plugin code is in `src/code.ts`. The HTML for the UI is in `src/ui.html`, while the embedded JavaScript is in `src/ui.tsx`.

These are compiled to files in `dist/`, which are what Figma will use to run your plugin.

To build:
```
$ npm install
$ npx webpack
```

# Notes
## Introduction to The Beginner's Guide to ReactJS
## Create HTML elements with React's createElement API
- `createElement` applies properties (class, text) to an element you want to create.
  - Additional children can be added after properties arguments.
[01-02-hello-world-react.html](https://github.com/caofontaine/TheBeginnersGuideToReact/blob/master/01-02-hello-world-react.html)
## Replace React createElement Function Call with JSX
- JSX: similar to HTML and behaves similarly
  - must be transpiled to React to work the sames as `createElement` (using Babel)
  - class resolves to className in JSX
  - Can use interpolation {} to use JS variables or expressions to populate values
  - Can use props object with self closing element to populate element.
    - `<div {...props} />`
	- Can also override props in several ways
	  - `<div {...props} className="x" />`
	  - `<div {...props}>Sup</div>`
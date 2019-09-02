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
[02-03-using-props-with-jsx.html](https://github.com/caofontaine/TheBeginnersGuideToReact/blob/master/02-03-using-props-with-jsx.html)
## Create a Simple Reusable React Element
- A variable that is capitalized to use a function that accepts arguments to reuse created elements.
  - `const Message = props => <div>{props.msg}</div>`
- Functions don't compose as well as JSX does.  
[03-02-convert-our-function-to-jsx.html](https://github.com/caofontaine/TheBeginnersGuideToReact/blob/master/03-02-convert-our-function-to-jsx.html)
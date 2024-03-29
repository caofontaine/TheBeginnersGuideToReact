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
## Validate Custom React Component Props with PropTypes
- Use `PropTypes` to validate type of props being passed.
- PropTypes module consider props optional. Use `isRequired` to run validator on required props.
- Class components can specify PropTypes the same, but more common to be declared a static property of a class.  
  
[04-03-props-in-class-based-components.html](https://github.com/caofontaine/TheBeginnersGuideToReact/blob/master/04-03-props-in-class-based-components.html)
## Conditionally Render A React Component
- Can logically determine what is rendered using if statement for ternary.  
  
[05-02-conditionally-render-a-react-component-with-jsx.html](https://github.com/caofontaine/TheBeginnersGuideToReact/blob/master/05-02-conditionally-render-a-react-component-with-jsx.html)
## Rerender a React Application
- Rerendering a React application does the minimal required DOM operations for the re-render.

[06-01-rerender-a-react-application.html](https://github.com/caofontaine/TheBeginnersGuideToReact/blob/master/06-01-rerender-a-react-application.html)
## Style React Components with className and In Line Styles
- Styles are written in object notation, with properties in camel-case.
- Libraries: Styled Components, Emotion, and Glamorous for solving styling problems in React.

[07-04-styling-components-more-boxes.html](https://github.com/caofontaine/TheBeginnersGuideToReact/blob/master/07-04-styling-components-more-boxes.html)
## Use Event Handlers with React

[08-03-event-handlers-onchange.html](https://github.com/caofontaine/TheBeginnersGuideToReact/blob/master/08-03-event-handlers-onchange.html)
## Use Compontent State with React

[09-04-component-state-adding-state.html](https://github.com/caofontaine/TheBeginnersGuideToReact/blob/master/09-04-component-state-adding-state.html)
## Stop Memory Leaks with componentWillUnmount Lifecycle Method in React
- `componentWillUnmount` clears anything needed to be cleared when the component is unmounted or removed from the DOM.

[10-04-component-state-adding-state.html](https://github.com/caofontaine/TheBeginnersGuideToReact/blob/master/10-04-component-state-adding-state.html)
## Use Class Components with React

[11-02-use-class-components-end-result.html](https://github.com/caofontaine/TheBeginnersGuideToReact/blob/master/11-02-use-class-components-end-result.html)
## Manipulate the DOM with React refs
- Use `ref` attribute to get access to a node in the DOM.

[12-02-manipulate-the-dom-with-react-refs-end-point.html](https://github.com/caofontaine/TheBeginnersGuideToReact/blob/master/12-02-manipulate-the-dom-with-react-refs-end-point.html)
## Make Basic Forms with React

[13-02-make-basic-forms-end-point.html](https://github.com/caofontaine/TheBeginnersGuideToReact/blob/master/13-02-make-basic-forms-end-point.html)
## Make Dynamic Forms with React

[14-02-make-dynamic-forms-end-point.html](https://github.com/caofontaine/TheBeginnersGuideToReact/blob/master/14-02-make-dynamic-forms-end-point.html)
## Controlling Form Values with React

[15-02-controlling-form-values-end-point.html](https://github.com/caofontaine/TheBeginnersGuideToReact/blob/master/15-02-controlling-form-values-end-point.html)
## Use the key prop when Rendering a List with React
[16-02-use-the-key-prop-when-rendering-a-list-better-example-start.html](https://github.com/caofontaine/TheBeginnersGuideToReact/blob/master/16-02-use-the-key-prop-when-rendering-a-list-better-example-start.html)

## Make HTTP Requests with React

## Build and deploy a React Application
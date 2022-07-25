# Lets-Eat-js-world

https://ecma-international.org/
https://www.typescriptlang.org/
https://developer.mozilla.org/en-US/docs/Web/JavaScript

```jsx
<script src="https://unpkg.com/react@17/umd/react.development.js"></script>
<script src="https://unpkg.com/react-dom@17/umd/react-dom.development.js"></script>
<script src="https://unpkg.com/@babel/standalone/babel.min.js"></script>

// This tag will be converted to React.js code by 'Babel'
<script type="text/babel">
	
	const root = document.getElementById("root");

	const Button = () => (
		<button
       style={{
         backgroundColor: "tomato",
       }}
       onClick={() => console.log("im clicked")}
     >
       Click me
     </button>
	);

	function Title() {
      return (
        <h3 id="title" onMouseEnter={() => console.log("mouse enter")}>
          HELLO
        </h3>
      )
	}

	const Container = () => (
		<div>
			<Button/>
			<Title/>
		</div>
	);

	ReactDOM.render(<Container/>, root);

</script>
```

```jsx
"use strict";

// This tag will be converted to React.js code by 'Babel'
const root = document.getElementById("root");

const Button = () => /*#__PURE__*/React.createElement("button", {
  style: {
    backgroundColor: "tomato"
  },
  onClick: () => console.log("im clicked")
}, "Click me");

function Title() {
  return /*#__PURE__*/React.createElement("h3", {
    id: "title",
    onMouseEnter: () => console.log("mouse enter")
  }, "HELLO");
}

const Container = () => /*#__PURE__*/React.createElement("div", null, /*#__PURE__*/React.createElement(Button, null), /*#__PURE__*/React.createElement(Title, null));

ReactDOM.render( /*#__PURE__*/React.createElement(Container, null), root);
```

## React.js vs JSX

properties

React.createElement()

가독성

HTML-like

## JSX to React.js

[Babel · The compiler for next generation JavaScript](https://babeljs.io/repl)

## Discriptions

….

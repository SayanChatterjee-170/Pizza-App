- index.js is the first file that Webpack expects

- <React.StrictMode> does only one thing i.e. during development it will (render our components twice). Also it checks that if we are using outdated parts of API 

- We write components using functions: Functions need to return some markup i.e. JSX and they should start with capital letters. 
- Each component can return only one element
- Inline style: {{}}
  >> first curly brace: {} => for JS mode
  >> {{2nd curly brace is for the JS object}}
  >> {{color:"red", fontSize: "12px"}} [key-value pair]
- We use className instead of class as 'class' is a reserved keyword in JS
- Props means passing data between components => we pass from parent component to child component. Props is an object
- For passing something not a string we use JS objects: {}
- React renders a component depending on the data and that UI will always be in sync with data. 
- Data is (Props + State). State is internal data that can be updated by the component's logic.
- props are objects i.e. reference types. props come from parent component => if we mutate the props, the parent component also gets updated
- For rendering lists, we use 'MAP' method
- Note: for everytime we use iteration, a 'key' is required.

 {isOpen && <p>Open</p>} --> if isOpen => false then entire expression is shortcircuited, if isOpen => true, then <p>Open</p> is returned!

- Always have pizzas>0 while doing conditional rendering
- Note: We cannot use if-else inside JS expressions. i.e. {}
- <> </> => react fragment
- What is React Fragment? ​ React Fragment is a feature in React that allows you to return multiple elements from a React component by allowing you to group a list of children without adding extra nodes to the DOM. To return multiple elements from a React component, you'll need to wrap the element in a root element.

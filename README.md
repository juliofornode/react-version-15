# React Basics

### React Syntax
* Load react and react-dom scripts in head
* Create div id="react-container"
* Create script in body
* ReactDOM.render(
* React.createElement('div', null, 'Hello World'),
* document.getElementById('react-container')

### Using JSX instead of JS and adding Babel to transpile it to JS
* Load babel
* Change script tag: type='text/babel'
* Change: React.createElement('div', null, 'Hello World')
* By: React.createElement(<div>'Hello World'</div>)

### Creating a React component
* var MyComponent = React.createClass({})
* render() {}
* return <div>Gelou Guorld</div>
* ReactDOM.render(<MyComponent />, document.getElementById('react-container'))

### Alternative ways to create a React component: ES6 classes
class MyComponent extends React.Component { render() }

### Alternative ways to create a React component: stateless functional component
const MyComponent = () => { return <div>...</div> }
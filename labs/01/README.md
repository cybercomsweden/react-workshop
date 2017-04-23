# Lab 1 - Create your first component

In this lab you will learn how to create a component. 

[Use this boilerplate to get started](https://codepen.io/damoberg/pen/OmXBKv)

Components can be created in 3 different ways:

```javascript
// 1
class MyComponent extends React.Component {
  render() {
    return <div>Cats</div>;
  }
}

// 2
const MyComponent = React.createClass({
  render() {
    return <div>Are</div>;
  }
})

// 3
const MyComponent = () => <div>Great!</div>;
```

Create a component that renders "Hello World".

## Helpful links
- [Component documentation](https://facebook.github.io/react/docs/react-component.html)
- [Finished solution - peak here](https://codepen.io/damoberg/pen/jmrQwo)

## Extra challange if you finish fast

Render the same component several times. Make the application render:

```
Hello World
Hello World
Hello World
Hello World
```

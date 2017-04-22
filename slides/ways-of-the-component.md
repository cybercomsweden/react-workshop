### Ways to create components

```javascript
class MyComponent extends React.Component {
  render() {
    return <div>Cats</div>;
  }
}

const MyComponent = React.createClass({
  render() {
    return <div>Are</div>;
  }
})

const MyComponent = () => <div>Great!</div>;
```

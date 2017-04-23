Update the state when an action is triggered

```javascript
class MyComponent extends React.Component {
  constructor(props) {
    super(props);
    this.state = { likes: 0 };
    this.addLike = this.addLike.bind(this);
  }
  addLike() {
    this.setState({ likes: this.state.likes + 1 });
  }
  render() {
    return <div>
      Likes: {this.state.likes}
      <button onClick={ this.addLike }>Add like</button>
    </div>
  }
}
```

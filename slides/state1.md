## How to use state

Initialised via the component constructor

```javascript
class MyComponent extends React.Component {
  constructor(props) {
    super(props);
    this.state = { likes: 0 }
  }

  render() {
    return <div>
      Likes: {this.state.likes}
      <button>Like</button>
    </div>
  }
}
```

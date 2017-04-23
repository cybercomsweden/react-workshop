## Passing `props` to components

```javascript
class Name extends React.Component {
  render() {
    return <div>{ this.props.first } { this.props.last }</div>;
  }
}

class Application extends React.Component {
  render() {
    return <div>
      All the names
      <Name first="Jim" last="Hopper" />
      <Name first="Mike" last="Wheeler" />
    </div>
  }
}
```

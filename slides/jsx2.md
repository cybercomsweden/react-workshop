### Full expressiveness of JavaScript in components

JavaScript statements are put inside of `{ }`

```javascript
function getName() {
  return 'John Doe';
}

const element = <div>My name is: { getName() }</div>
```

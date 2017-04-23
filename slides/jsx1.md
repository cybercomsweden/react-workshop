## Introducing JSX

Syntax extension to JavaScript

JSX is translated into React elements

```javascript
const element = <h1>Hello, world!</h1>;

// Gets translated into JavaScript

const element = React.createElement('h1', null, 'Hello, world!');
```

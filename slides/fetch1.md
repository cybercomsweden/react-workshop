## Using Fetch

### Simple GET request

```javascript
fetch('someUrl').then(response => {
  return response.json();
}).then(json => {
  ...
});
```

### Simple POST request

```javascript
fetch('someUrl', {
  method: 'POST'
}).then(response => {
  return response.json();
}).then(json => {
  ...
});
```

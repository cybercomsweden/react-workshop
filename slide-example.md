## Wat

```javascript
 const section = Object.assign({}, req.body.section, {
    id: sectionId,
    name: req.body.section.name.trim(),
    uri: uri,
    type: 'tree',
    landingPage: null,
  });
```

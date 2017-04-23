# Time to fetch some data

## Boilerplate 
[https://codepen.io/damoberg/pen/XRdQRE](https://codepen.io/damoberg/pen/XRdQRE)

## Test definition
We are about to fetch data for our React application using the `fetch()` feature (available in newser browsers).

- Add following url to the `fetch()` function 
```
https://api.github.com/repos/cybercomsweden/react-workshop/contents/random-json/us.json
```
- Add the component `JsonPrinter` to the render function in the `Application`
  - Dont forget to send in the state property `json` to the `JsonPrinter` as a property. 

## Need help? Check out the following links
- [Fetch API](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch)
- [Send in state propery as props](https://facebook.github.io/react/docs/state-and-lifecycle.html#adding-local-state-to-a-class)

___

## If above was too easy. Here's a new challenge

As you can see the JSON-file we are fetching contains an array of two people. Add a new component where you can print one person. Then iterate over the results in the render function in `Application` component calling the component for every person.

[How to iterate over an array in Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map)

___

## A finalized solution
[https://codepen.io/albinhallden/pen/aWNXJo](https://codepen.io/albinhallden/pen/aWNXJo)
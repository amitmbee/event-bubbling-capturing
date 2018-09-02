https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events#Event_bubbling_and_capture#Event_bubbling_and_capture

https://www.youtube.com/watch?v=3gNLqmqVWHo

# Event bubbling and Capturing

Bubbling is set by default in the following way

```js
DOMElement.addEventListener(event, handlerFunction, false);
```

To switch to event capturing mode,

```js
DOMElement.addEventListener(event, handlerFunction, true);
```

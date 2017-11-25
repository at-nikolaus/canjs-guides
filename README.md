# canjs-guides
A Collection of CanJS Related Guides

# How to use packery in a CanJS view via the viewModel

# How to use jquery-ui in a CanJS view via the viewModel

# How to use can-datepicker-component


# How to drive a can-components from a WebComponents
Allow registering each can-element with its own scope as they share attr they can interact as expected
via can-stache-bindings
```js

canViewCallbacks.tag("date-picker", function(el, tagData){
    let component = customElements.get('date-picker')
    el = new component(el)
});
```

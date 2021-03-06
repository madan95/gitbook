# React

**VDOM \(Virtual Document Object Model\)** - Another layer of DOM represented virtually. Any State change will be applied to VDOM, it is then compared to previous snapshot of the VDOM and then checked if UI changes are required & update real DOM only what needs to be updated. _**\(diffing\)**_

**Render in React** - In class based react render is the execution of render function which won't always update UI. In functional components, execution of whole functions is equivalent to render function. These render function is executed every-time state of a component changes.

**Re-Painting** - Any changes to real DOM \(UI\)

**Comparison** - React uses Shallow comparison [`Object.is`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/is) which is why it is better to avoid mutating data. 

{% embed url="https://felixgerschau.com/react-rerender-components" %}

{% embed url="https://svelte.dev/blog/virtual-dom-is-pure-overhead" %}








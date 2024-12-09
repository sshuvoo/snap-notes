## Referencing Values with Refs

### Why we need `useRef` in React?

When we want a component to “remember” some information, but we don’t want that information to trigger new renders, we can use a ref.

useRef hook in React is used to reference a value that’s not needed for rendering. It can be used to store a mutable value that persists across component renders, or create a mutable reference to a DOM element .

### When to use refs?

-  Storing timeout IDs
-  Storing and manipulating DOM elements
-  Storing other references that aren’t necessary to calculate the JSX.

```jsx
// You can imagine that inside of React
function useRef(initialValue) {
   const [ref] = useState({ current: initialValue });
   return ref;
}
```

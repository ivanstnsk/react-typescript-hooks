# react-typescript-hooks
A collection of React Hooks in Typescript

* [useMouseScroll](https://gist.github.com/ivanstnsk/e775d28ebd0dff06981cc7b65e2238d9)
```ts
// Example of usage
const [containerRef, scrollY] = useMouseScroll<HTMLDivElement>();
...
<div ref={containerRef}>content</div>
```

# react-typescript-hooks
A collection of React Hooks in Typescript

* [useMouseScroll](https://gist.github.com/ivanstnsk/e775d28ebd0dff06981cc7b65e2238d9)
```ts
// Example of usage
const [containerRef, scrollY] = useMouseScroll<HTMLDivElement>();
...
<div ref={containerRef}>content</div>
```

* [useWindowResize](https://gist.github.com/ivanstnsk/c3ba1edf00d07fab9afa3f61a95193a8)
```ts
// Example of usage
const [width, height] = useWindowResize(); 
```

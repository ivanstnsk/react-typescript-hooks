# react-typescript-hooks
A collection of React Hooks in Typescript

<p align="center">
  <img width="350" src="./logo.png">
</p>

* [useMouseScroll](https://gist.github.com/ivanstnsk/e775d28ebd0dff06981cc7b65e2238d9)
```ts
// Example of usage
const [containerRef, scrollY] = useMouseScroll<HTMLDivElement>();
...
<div ref={containerRef}>content</div>
```

* [useMouseHover](https://gist.github.com/ivanstnsk/08339e994662618568b0235d3b517055)
```ts
// Example of usage
const [buttonRef, buttonHovered] = useMouseHover<HTMLButtonElement>();
const color = buttonHovered ? 'red' : 'blue';

return (
  <button
    ref={buttonRef}
    style={{ color }}
  >
    click me
  </button>
);
```

* [useWindowResize](https://gist.github.com/ivanstnsk/c3ba1edf00d07fab9afa3f61a95193a8)
```ts
// Example of usage
const [width, height] = useWindowResize(); 
```

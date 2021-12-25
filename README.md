# CSS
# Open props
```CSS
main {
    display: flex;
    flex-flow: row wrap;
    align-items: flex-start;
    justify-content: space-around;
    max-inline-size: calc(var(--size-content-1) * 4);
    gap: var(--size-5);
    padding: var(--size-5);
}
```

# wrap class
```CSS
.wrap {
    display: flex;
    align-items: center;
    justify-content: center;
    height: 100vh;
    background: #34495e;
    color: aqua;
    font-family: monospace;
    font-size: 36px;
    &:before {
        content: "[";
    }
    &:after {
        content: "]";
    }
    &:before,
    &:after {
        color: #16a085;
        animation: flicker 3s infinite;
    }
} 
```
# Dark Mode
```CSS
@media(prefers-color-scheme:dark) {
     :root {
        color-scheme: dark;
    }
}
```

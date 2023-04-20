# CSS_Learn
- Positioning
+ Static positioning: default
+ Relative (common): relative to its position
+ Absolute: nearest positioned ancestor or top left corner
https://appbrewery.github.io/css-positioning/
z-index: (put on top or back)
+ Fixed: always stay the same position even scrolling down

```
  <link rel="stylesheet" href="./style.css">
```
- Web layout inspired by newspapers & magazine articles
- FLexbox is good for display "Overall page structure" (put all div in a container class)
```
.container {
display: flex;
gap: 10px;
}
```
| |
```
.container {
display: inline-flex;
gap: 10px;
flex-direction: column;
}
```
- flex-basic: <- can only target the children
```
.container > * {
flex-basic: 100px
}
```
- Ordering: every child has order 0. Who has bigger number will be on the left side-> 0 0 10 ....
```
flex-wrap
-max-width, min-width

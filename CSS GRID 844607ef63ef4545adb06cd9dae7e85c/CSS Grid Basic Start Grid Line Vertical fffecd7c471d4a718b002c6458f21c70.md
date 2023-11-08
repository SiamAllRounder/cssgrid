# CSS Grid Basic Start Grid Line Vertical

```css
.container{
    display: grid;
    grid-template-columns: repeat(5, 1fr);
 
    /* grid-template-rows: 100px 40px 100px; */
    grid-gap: 15px 10px;
    grid-auto-rows: 170px;
}
```

![Untitled](CSS%20Grid%20Basic%20Start%20Grid%20Line%20Vertical%20fffecd7c471d4a718b002c6458f21c70/Untitled.png)

```css
.container{
    display: grid;
    grid-template-columns: repeat(5, 1fr);
 
    /* grid-template-rows: 100px 40px 100px; */
    grid-gap: 15px 10px;
    grid-auto-rows: 170px;
}

.box-1 {
    grid-column-start: 1;
    grid-column-end: 4;
}
```

![Untitled](CSS%20Grid%20Basic%20Start%20Grid%20Line%20Vertical%20fffecd7c471d4a718b002c6458f21c70/Untitled%201.png)

```html
<div class="container">
      <div class="box-1">box1</div>
      <div class="box-2">box2</div>
      <div class="box-3">box3</div>
      <div class="box-4">box4</div>
      <div class="box-5">box5</div>
      <div class="box-6">box6</div>
     
    </div>
```

inspect and find out the lines with ease

![Untitled](CSS%20Grid%20Basic%20Start%20Grid%20Line%20Vertical%20fffecd7c471d4a718b002c6458f21c70/Untitled%202.png)

```css
.box-1 {
    /* grid-column-start: 1;
    grid-column-end: 4; */
    grid-column: 1 / 4;
}
```

![Untitled](CSS%20Grid%20Basic%20Start%20Grid%20Line%20Vertical%20fffecd7c471d4a718b002c6458f21c70/Untitled%203.png)

```css
.box-1 {
    /* grid-column-start: 1;
    grid-column-end: 4; */
    grid-column: 1 / 3;
}
```

![Untitled](CSS%20Grid%20Basic%20Start%20Grid%20Line%20Vertical%20fffecd7c471d4a718b002c6458f21c70/Untitled%204.png)

```css
.box-1 {
    /* grid-column-start: 1;
    grid-column-end: 4; */
    grid-column: 1 / 6;
}
```

![Untitled](CSS%20Grid%20Basic%20Start%20Grid%20Line%20Vertical%20fffecd7c471d4a718b002c6458f21c70/Untitled%205.png)

```css
.box-1 {
    /* grid-column-start: 1;
    grid-column-end: 4; */
    grid-column: 1 / -1;
}
```

![Untitled](CSS%20Grid%20Basic%20Start%20Grid%20Line%20Vertical%20fffecd7c471d4a718b002c6458f21c70/Untitled%206.png)

```css
.box-1 {
    /* grid-column-start: 1;
    grid-column-end: 4; */
    grid-column: 1 / -2;
}
```

![Untitled](CSS%20Grid%20Basic%20Start%20Grid%20Line%20Vertical%20fffecd7c471d4a718b002c6458f21c70/Untitled%207.png)

```css
.box-1 {
    /* grid-column-start: 1;
    grid-column-end: 4; */
    grid-column: 1 / -2;
    grid-row: 1/ 3;
}
```

![Untitled](CSS%20Grid%20Basic%20Start%20Grid%20Line%20Vertical%20fffecd7c471d4a718b002c6458f21c70/Untitled%208.png)
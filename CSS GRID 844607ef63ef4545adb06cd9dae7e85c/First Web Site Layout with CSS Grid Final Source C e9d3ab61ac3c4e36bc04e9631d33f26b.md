# First Web Site Layout with CSS Grid Final Source Code

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Css Grid 1</title>
    <link rel="stylesheet" href="a.css" />
  </head>
  <body>
    <div class="container">
      <div class="box-1">box1</div>
      <div class="box-2">box2</div>
      <div class="box-3">box3</div>
      <div class="box-4">box4</div>
      <div class="box-5">box5</div>
     
    </div>
  </body>
</html>
```

```css
.container {
    height: 100vh;
    display: grid;
    grid-template-columns: repeat(5, 1fr);
    grid-template-rows: 100px 50px 400px 100px;
}

.container div {
    background-color: #ddd;
    border: 1px solid black;
}

.box-1{ 
    grid-column: 1/ -1;
}
.box-2{ 
    grid-column: 1/ -1;
}
.box-3{
    grid-column: 1/ span 3;
}
.box-4{
    grid-column: 4/ span 2;
}
.box-5{
    grid-column: 1/ -1;
}
```

old

```css
.container{
    display: grid;
    grid-template-columns: repeat(5, 1fr);
 
    /* grid-template-rows: 100px 40px 100px; */
    grid-gap: 15px 10px;
    grid-auto-rows: 170px;
}

.box-1 {
    /* grid-column-start: 1;
    grid-column-end: 4; */
    grid-column: 1 / -2;
    grid-row: 1/ 3;
}

.container div {
    /* width: 100px;
    height: 100px; */
    background: orange;
    font-size: 25px;
    color: white;

}
```
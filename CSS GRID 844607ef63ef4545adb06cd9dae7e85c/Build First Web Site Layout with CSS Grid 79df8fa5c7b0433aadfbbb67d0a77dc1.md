# Build First Web Site Layout with CSS Grid

[web site layout - Google Search](https://www.google.com/search?q=web+site+layout&sca_esv=580323760&rlz=1C1ONGR_enBD1061BD1061&tbm=isch&sxsrf=AM9HkKmq10tWAZx5Fr791ADACA6-M6kyeA:1699406142941&source=lnms&sa=X&ved=2ahUKEwjQrOqbnbOCAxXISGwGHYYJAHoQ_AUoAXoECAEQAw&biw=1360&bih=619&dpr=1#imgrc=Pm8j5tbs4F4qOM)

![Untitled](Build%20First%20Web%20Site%20Layout%20with%20CSS%20Grid%2079df8fa5c7b0433aadfbbb67d0a77dc1/Untitled.png)

![Untitled](Build%20First%20Web%20Site%20Layout%20with%20CSS%20Grid%2079df8fa5c7b0433aadfbbb67d0a77dc1/Untitled%201.png)

![Untitled](Build%20First%20Web%20Site%20Layout%20with%20CSS%20Grid%2079df8fa5c7b0433aadfbbb67d0a77dc1/Untitled%202.png)

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
    display: grid;
    grid-template-columns: repeat(5, 1fr);
}

.container div {
    background-color: #ddd;
    border: 1px solid black;
}

.box-1{}
.box-2{}
.box-3{}
.box-4{}
.box-5{}
```

![Untitled](Build%20First%20Web%20Site%20Layout%20with%20CSS%20Grid%2079df8fa5c7b0433aadfbbb67d0a77dc1/Untitled%203.png)

![Untitled](Build%20First%20Web%20Site%20Layout%20with%20CSS%20Grid%2079df8fa5c7b0433aadfbbb67d0a77dc1/Untitled%204.png)

```css
.container {
    display: grid;
    grid-template-columns: repeat(5, 1fr);
}

.container div {
    background-color: #ddd;
    border: 1px solid black;
}

.box-1{ grid-column: 1/ -1;}
.box-2{}
.box-3{}
.box-4{}
.box-5{}
```

![Untitled](Build%20First%20Web%20Site%20Layout%20with%20CSS%20Grid%2079df8fa5c7b0433aadfbbb67d0a77dc1/Untitled%205.png)

```css
.container {
    display: grid;
    grid-template-columns: repeat(5, 1fr);
    grid-template-rows: repeat(3, 1fr);
}

.container div {
    background-color: #ddd;
    border: 1px solid black;
}

.box-1{ grid-column: 1/ -1;}
.box-2{}
.box-3{}
.box-4{}
.box-5{}
```

![Untitled](Build%20First%20Web%20Site%20Layout%20with%20CSS%20Grid%2079df8fa5c7b0433aadfbbb67d0a77dc1/Untitled%206.png)

```css
.container {
    display: grid;
    grid-template-columns: repeat(5, 1fr);
    grid-template-rows: repeat(3, 1fr);
    background-color: orange;
}

.container div {
    background-color: #ddd;
    border: 1px solid black;
}

.box-1{ grid-column: 1/ -1;}
.box-2{}
.box-3{}
.box-4{}
.box-5{}
```

![Untitled](Build%20First%20Web%20Site%20Layout%20with%20CSS%20Grid%2079df8fa5c7b0433aadfbbb67d0a77dc1/Untitled%207.png)

```css
.container {
    height: 100vh;
    display: grid;
    grid-template-columns: repeat(5, 1fr);
    grid-template-rows: repeat(3, 1fr);
    background-color: orange;
}

.container div {
    background-color: #ddd;
    border: 1px solid black;
}

.box-1{ grid-column: 1/ -1;}
.box-2{}
.box-3{}
.box-4{}
.box-5{}
```

![Untitled](Build%20First%20Web%20Site%20Layout%20with%20CSS%20Grid%2079df8fa5c7b0433aadfbbb67d0a77dc1/Untitled%208.png)

```css
.container {
    height: 100vh;
    display: grid;
    grid-template-columns: repeat(5, 1fr);
    grid-template-rows: repeat(3, 1fr);
}

.container div {
    background-color: #ddd;
    border: 1px solid black;
}

.box-1{ grid-column: 1/ -1;}
.box-2{}
.box-3{}
.box-4{}
.box-5{}
```

![Untitled](Build%20First%20Web%20Site%20Layout%20with%20CSS%20Grid%2079df8fa5c7b0433aadfbbb67d0a77dc1/Untitled%209.png)

```css
.container {
    height: 100vh;
    display: grid;
    grid-template-columns: repeat(5, 1fr);
    grid-template-rows: repeat(3, 1fr);
}

.container div {
    background-color: #ddd;
    border: 1px solid black;
}

.box-1{ grid-column: 1/ -1;}
.box-2{ grid-column: 1/ -1;}
.box-3{}
.box-4{}
.box-5{}
```

![Untitled](Build%20First%20Web%20Site%20Layout%20with%20CSS%20Grid%2079df8fa5c7b0433aadfbbb67d0a77dc1/Untitled%2010.png)

```css
.container {
    height: 100vh;
    display: grid;
    grid-template-columns: repeat(5, 1fr);
    grid-template-rows: repeat(3, 1fr);
}

.container div {
    background-color: #ddd;
    border: 1px solid black;
}

.box-1{ grid-column: 1/ -1;}
.box-2{ grid-column: 1/ -1;}
.box-3{grid-column: 1/ 3;}
.box-4{}
.box-5{}
```

![Untitled](Build%20First%20Web%20Site%20Layout%20with%20CSS%20Grid%2079df8fa5c7b0433aadfbbb67d0a77dc1/Untitled%2011.png)

```css
.container {
    height: 100vh;
    display: grid;
    grid-template-columns: repeat(5, 1fr);
    grid-template-rows: repeat(3, 1fr);
}

.container div {
    background-color: #ddd;
    border: 1px solid black;
}

.box-1{ grid-column: 1/ -1;}
.box-2{ grid-column: 1/ -1;}
.box-3{grid-column: 1/ span 3;}
.box-4{}
.box-5{}
```

![Untitled](Build%20First%20Web%20Site%20Layout%20with%20CSS%20Grid%2079df8fa5c7b0433aadfbbb67d0a77dc1/Untitled%2012.png)

```css
.container {
    height: 100vh;
    display: grid;
    grid-template-columns: repeat(5, 1fr);
    grid-template-rows: repeat(3, 1fr);
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
.box-5{}
```

![Untitled](Build%20First%20Web%20Site%20Layout%20with%20CSS%20Grid%2079df8fa5c7b0433aadfbbb67d0a77dc1/Untitled%2013.png)

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
.box-5{}
```

![Untitled](Build%20First%20Web%20Site%20Layout%20with%20CSS%20Grid%2079df8fa5c7b0433aadfbbb67d0a77dc1/Untitled%2014.png)

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

![Untitled](Build%20First%20Web%20Site%20Layout%20with%20CSS%20Grid%2079df8fa5c7b0433aadfbbb67d0a77dc1/Untitled%2015.png)
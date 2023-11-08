# CSS Grid Basic Start Grid Row Different OR Variable Size Variation

```css
.container{
    display: grid;
    grid-template-columns: 1fr 3fr 5fr;
 
    grid-template-rows: auto auto auto;
    grid-gap: 15px 10px;
}
```

![Untitled](CSS%20Grid%20Basic%20Start%20Grid%20Row%20Different%20OR%20Variabl%20672e3aeeb53c41d9b7fd7d543db6b4c9/Untitled.png)

```css
.container{
    display: grid;
    grid-template-columns: 1fr 3fr 5fr;
 
    grid-template-rows: 100px 40px 100px;
    grid-gap: 15px 10px;
}
```

![Untitled](CSS%20Grid%20Basic%20Start%20Grid%20Row%20Different%20OR%20Variabl%20672e3aeeb53c41d9b7fd7d543db6b4c9/Untitled%201.png)

```html
<div class="container">
      <div class="bix-1">box1</div>
      <div class="bix-2">box2</div>
      <div class="bix-3">box3</div>
      <div class="bix-4">box4</div>
      <div class="bix-5">box5</div>
      <div class="bix-6">box6</div>
      <div class="bix-7">box7</div>
      <div class="bix-8">box8</div>
      <div class="bix-9">box9</div>
      <div class="bix-10">box10</div>
      <div class="bix-11">box11</div>
      <div class="bix-12">box12</div>
    </div>
```

![Untitled](CSS%20Grid%20Basic%20Start%20Grid%20Row%20Different%20OR%20Variabl%20672e3aeeb53c41d9b7fd7d543db6b4c9/Untitled%202.png)

```html
<div class="container">
      <div class="bix-1">box1</div>
      <div class="bix-2">box2</div>
      <div class="bix-3">box3</div>
      <div class="bix-4">box4</div>
      <div class="bix-5">box5</div>
      <div class="bix-6">box6</div>
      <div class="bix-7">box7</div>
      <div class="bix-8">box8</div>
      <div class="bix-9">box9</div>
      <div class="bix-10">box10</div>
      <div class="bix-11">box11</div>
      <div class="bix-12">box12</div>
      <div class="bix-13">box13</div>
      <div class="bix-14">box14</div>
      <div class="bix-15">box15</div>
    </div>
```

![Untitled](CSS%20Grid%20Basic%20Start%20Grid%20Row%20Different%20OR%20Variabl%20672e3aeeb53c41d9b7fd7d543db6b4c9/Untitled%203.png)
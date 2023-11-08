# CSS Grid Basic Start Grid Column And Row Gap

```css
.container{
    display: grid;
    grid-template-columns: auto auto auto;
    grid-column-gap: 10px;
    /* grid-template-rows: auto auto auto; */
}
```

![Untitled](CSS%20Grid%20Basic%20Start%20Grid%20Column%20And%20Row%20Gap%20dae04e85b2e74777a125f2bb00ac3cca/Untitled.png)

```css
.container{
    display: grid;
    grid-template-columns: auto auto auto;
    grid-column-gap: 10px;
    grid-row-gap: 15px;
    /* grid-template-rows: auto auto auto; */
}
```

![Untitled](CSS%20Grid%20Basic%20Start%20Grid%20Column%20And%20Row%20Gap%20dae04e85b2e74777a125f2bb00ac3cca/Untitled%201.png)

```html
<div class="container">
      <div class="bix-1">box1</div>
      <div class="bix-2">box2</div>
      <div class="bix-3">box3</div>
      <div class="bix-4">box4</div>
      <div class="bix-5">box5</div>
      <div class="bix-6">box6</div>
    </div>
```

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
    </div>
```

![Untitled](CSS%20Grid%20Basic%20Start%20Grid%20Column%20And%20Row%20Gap%20dae04e85b2e74777a125f2bb00ac3cca/Untitled%202.png)

```css
.container{
    display: grid;
    grid-template-columns: auto auto auto;
    /* grid-column-gap: 10px;
    grid-row-gap: 15px; */
    /* grid-template-rows: auto auto auto; */
    grid-gap: 15px 10px;
}
```

![Untitled](CSS%20Grid%20Basic%20Start%20Grid%20Column%20And%20Row%20Gap%20dae04e85b2e74777a125f2bb00ac3cca/Untitled%203.png)

```css
.container{
    display: grid;
    grid-template-columns: auto auto auto;
 
    /* grid-template-rows: auto auto auto; */
    grid-gap: 15px 10px;
}
```

![Untitled](CSS%20Grid%20Basic%20Start%20Grid%20Column%20And%20Row%20Gap%20dae04e85b2e74777a125f2bb00ac3cca/Untitled%204.png)
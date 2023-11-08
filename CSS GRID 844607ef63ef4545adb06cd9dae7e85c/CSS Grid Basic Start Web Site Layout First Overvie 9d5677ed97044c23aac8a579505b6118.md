# CSS Grid Basic Start Web Site Layout First Overview

```html
<div class="container">
      <div class="bix-1">box1</div>
      <div class="bix-2">box2</div>
      <div class="bix-3">box3</div>
      <div class="bix-4">box4</div>
      <div class="bix-5">box5</div>
     
    </div>
```

```css
.container{
    display: grid;
    grid-template-columns: 1fr 3fr 5fr;
 
    grid-template-rows: 100px 40px 100px;
    grid-gap: 15px 10px;
    grid-auto-rows: 170px;
}
```

![Untitled](CSS%20Grid%20Basic%20Start%20Web%20Site%20Layout%20First%20Overvie%209d5677ed97044c23aac8a579505b6118/Untitled.png)

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

```css
.container{
    display: grid;
    grid-template-columns: repeat(3, 1fr);
 
    grid-template-rows: 100px 40px 100px;
    grid-gap: 15px 10px;
    grid-auto-rows: 170px;
}
```

![Untitled](CSS%20Grid%20Basic%20Start%20Web%20Site%20Layout%20First%20Overvie%209d5677ed97044c23aac8a579505b6118/Untitled%201.png)

[web site layout - Google Search](https://www.google.com/search?q=web+site+layout&sca_esv=580323760&rlz=1C1ONGR_enBD1061BD1061&tbm=isch&sxsrf=AM9HkKmq10tWAZx5Fr791ADACA6-M6kyeA:1699406142941&source=lnms&sa=X&ved=2ahUKEwjQrOqbnbOCAxXISGwGHYYJAHoQ_AUoAXoECAEQAw&biw=1360&bih=619&dpr=1#imgrc=Pm8j5tbs4F4qOM)

![Untitled](CSS%20Grid%20Basic%20Start%20Web%20Site%20Layout%20First%20Overvie%209d5677ed97044c23aac8a579505b6118/Untitled%202.png)
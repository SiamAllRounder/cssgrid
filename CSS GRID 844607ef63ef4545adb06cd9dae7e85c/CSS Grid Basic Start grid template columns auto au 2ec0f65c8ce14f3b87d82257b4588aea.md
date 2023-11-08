# CSS Grid Basic Start grid template columns auto auto display grid

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
      <div class="bix-1">box1</div>
      <div class="bix-2">box2</div>
      <div class="bix-3">box3</div>
      <div class="bix-4">box4</div>
      <div class="bix-5">box5</div>
      <div class="bix-6">box6</div>
    </div>
  </body>
</html>
```

```css
.container{
    display: grid;
    grid-template-columns: auto auto;
}

.container div {
    width: 100px;
    height: 100px;
    background: orange;
    font-size: 25px;
    color: white;

}
```

![Untitled](CSS%20Grid%20Basic%20Start%20grid%20template%20columns%20auto%20au%202ec0f65c8ce14f3b87d82257b4588aea/Untitled.png)

```css
.container{
    display: grid;
    grid-template-columns: auto auto auto;
}
```

![Untitled](CSS%20Grid%20Basic%20Start%20grid%20template%20columns%20auto%20au%202ec0f65c8ce14f3b87d82257b4588aea/Untitled%201.png)

```css
.container{
    display: grid;
    grid-template-columns: auto auto auto auto;
}
```

![Untitled](CSS%20Grid%20Basic%20Start%20grid%20template%20columns%20auto%20au%202ec0f65c8ce14f3b87d82257b4588aea/Untitled%202.png)

```css
.container{
    display: grid;
    grid-template-columns: 1fr 1fr 1fr 1fr;
}
```

![Untitled](CSS%20Grid%20Basic%20Start%20grid%20template%20columns%20auto%20au%202ec0f65c8ce14f3b87d82257b4588aea/Untitled%203.png)

```css
.container{
    display: grid;
    grid-template-columns: repeat(4, 1fr);
}
```

![Untitled](CSS%20Grid%20Basic%20Start%20grid%20template%20columns%20auto%20au%202ec0f65c8ce14f3b87d82257b4588aea/Untitled%204.png)

```css
.container{
    display: grid;
    grid-template-columns: repeat(5, 1fr);
}
```

![Untitled](CSS%20Grid%20Basic%20Start%20grid%20template%20columns%20auto%20au%202ec0f65c8ce14f3b87d82257b4588aea/Untitled%205.png)

```css
.container{
    display: grid;
    grid-template-columns: repeat(3, 1fr);
}
```

![Untitled](CSS%20Grid%20Basic%20Start%20grid%20template%20columns%20auto%20au%202ec0f65c8ce14f3b87d82257b4588aea/Untitled%206.png)
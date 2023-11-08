# CSS Grid Basic Start container divs without absolute width and height grid template columns auto auto auto

```css
.container{
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    /* grid-template-rows: auto auto auto; */
}

.container div {
    /* width: 100px;
    height: 100px; */
    background: orange;
    font-size: 25px;
    color: white;

}
```

![Untitled](CSS%20Grid%20Basic%20Start%20container%20divs%20without%20absolu%20ccade85e53684a718cece077738e4fe3/Untitled.png)

```css
.container{
    display: grid;
    grid-template-columns: auto auto auto;
    /* grid-template-rows: auto auto auto; */
}
```

![Untitled](CSS%20Grid%20Basic%20Start%20container%20divs%20without%20absolu%20ccade85e53684a718cece077738e4fe3/Untitled%201.png)
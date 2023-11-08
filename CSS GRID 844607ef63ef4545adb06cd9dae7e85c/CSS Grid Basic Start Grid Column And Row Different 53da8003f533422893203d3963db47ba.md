# CSS Grid Basic Start Grid Column And Row Different OR Variable Size Variation

```css
.container{
    display: grid;
    grid-template-columns: 200px 500px 100px;
 
    /* grid-template-rows: auto auto auto; */
    grid-gap: 15px 10px;
}
```

![Untitled](CSS%20Grid%20Basic%20Start%20Grid%20Column%20And%20Row%20Different%2053da8003f533422893203d3963db47ba/Untitled.png)

```css
.container{
    display: grid;
    grid-template-columns: 1fr 3fr 1fr;
 
    /* grid-template-rows: auto auto auto; */
    grid-gap: 15px 10px;
}
```

![Untitled](CSS%20Grid%20Basic%20Start%20Grid%20Column%20And%20Row%20Different%2053da8003f533422893203d3963db47ba/Untitled%201.png)

```css
.container{
    display: grid;
    grid-template-columns: 1fr 3fr 5fr;
 
    /* grid-template-rows: auto auto auto; */
    grid-gap: 15px 10px;
}
```

![Untitled](CSS%20Grid%20Basic%20Start%20Grid%20Column%20And%20Row%20Different%2053da8003f533422893203d3963db47ba/Untitled%202.png)
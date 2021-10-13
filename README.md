# CSS TRICKS

## CHECKLIST

- [x] BORDER STYLE
- [x] CENTER CONTENT
- [x] CURSOR STYLE
- [x] TEXT GRADIENT
- [x] TEXT SELECTION COLOR
- [x] WEBSITES TO LEARN

### BORDER STYLE

![](img/border.jpg)

### CENTER CONTENT

```
.content{
        width: 100%;
        height: 100vh;
        display: flex;
        justify-content: center;
        align-items: center;
}
```

### CENTER CONTENT => ALL ITEMS ON THE CENTER OF THE PAGE

```
      body{
          height: 100vh;
          margin: 0;
          display: flex;
          align-items: center;
      }
      .container{
        width: 100vw;
        display: flex;  
        justify-content: space-between;
    }
```

### CURSOR STYLE

![](img/cursor.jpg)

### CSS DEBUGGING - TRYING TO CATCH ANY BUG

```
*{
    border: 2px solid red;
}
```

### TEXT GRADIENT

```
.text-gradient{
    display: inline-block;
    color: transparent;
    background-image: linear-gradient(
        90deg,
        #fc87da 0%,
        #cb94ef 26%,
        #41e0e7 70%,
        #28f6c2 100%
    );
    -webkit-background-clip: text;
    background-clip: text;
}
```
### TEXT SELECTION COLOR

```
::selection{
    color: #000;
    background: #f4af38;
}

```

### WEBSITES TO LEARN

[Flex Box Froggy](https://flexboxfroggy.com/)

[Evelator Saga](https://play.elevatorsaga.com/)

[Fluke Out](https://flukeout.github.io/)

[CSS TRICKS](https://css-tricks.com/)
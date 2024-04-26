## How to center a div

```
<div class="container">
    
</div>
```


```
.container {
     background-color: red;
     height: 200px;
     width: 200px;
     position: absolute;
     top: 50%;
     left: 50%;
     transform: translate(-50%, -50%);
}
```

## How to center parent and child div

```

.parent
{
        background: red;
        height: 200px;
        width: 200px;
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
}

.child
{
     background: green;
     height: 100px;
     width: 100px;
     position: absolute;
     transform: translate(50%, 50%);   
}

```

```

<div class="parent">
    <div class="child">

    </div>
</div>

```

# cssbuttons
A tiny pure CSS (no Javascript) library for making custom colored Bootstrap-like buttons

## How to use
Just import the CSS, and add the `button` class to the element you want to use as a button.  
You can change the color by adding the `r`, `g` and `b` attributes:  
```
<button class="button" r="0" g="0" b="0" value="This is a black button">
<a href="#" class="button" r="0" g="0" b="0">Link as a button</a>
```


## Creating custom classes
If you wish to create a custom class, you can specify the color by using the variables in CSS:  
```
.button-black {
  --r: 0;
  --g: 0;
  --b: 0;
  /* other properties here */
}
```  
And then use it in your button:  
```
<button class="button button-black" value="Click here">
```

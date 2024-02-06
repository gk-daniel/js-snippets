## 
### [home](../README.md) / 01-key_based
## 

Welcome to the key base approach. This approach is based on the layout of the keys on the keyboard, namely qwer, asdf, and yxc, and divides all operations of JavaScript methods into set, get, add, del, check, and filter. How does this approach work? We can take a look at the example below.

#### 1. Keyboard

*<em> - The idea is to divide each row on the keyboard into a level and link it with the JavaScript structure: </em>*

<p align="center">
  <img src="../00-config/02-assets/keyboard.png" alt="Keyboard" style="border: 1px solid white; display: block; margin: 0 auto;" height="220" width="500">
</p>


So, we can end up with three levels and four columns: "qwer", "asdf", "yxcv".

I. Simple data types: qwer

This level can describe simple data types such as:

1. q - number
2. w - string
3. e - boolean
4. r - exceptions

II. Complex data types: asdf

This level can describe complex data types such as:

1. a - array
2. s - object
3. d - function
4. f - exceptions

III. Universal data types: yxcv

This level is intended for describing classes and methods that solve specific tasks.

*<em> - Navigate to the project directory using the cd command: </em>*

```bash
cd js-snippets
```

#### 2. Actions
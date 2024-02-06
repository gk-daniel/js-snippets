## 
### [home](../README.md) / 01-key_based
## 

Welcome to the key base approach. This approach is based on the layout of the keys on the keyboard, namely qwer, asdf, and yxc, and divides all operations of JavaScript methods into set, get, add, del, check, and filter. How does this approach work? We can take a look at the example below.

#### 1. Keyboard

*<em> - The idea is to divide each row on the keyboard into a level and link it with the JavaScript structure. So, we can end up with three levels and four columns: "qwer", "asdf", "yxcv". </em>*

<p align="center">
  <img src="../00-config/02-assets/keyboard.png" alt="Keyboard" style="border: 1px solid white; display: block; margin: 0 auto;" height="220" width="500">
</p>

*<em> I. Simple data types: qwer </em>*

1. q - number
2. w - string
3. e - boolean
4. r - exceptions

*<em> II. Complex data types: asdf </em>*

1. a - array
2. s - object
3. d - function
4. f - exceptions

*<em> III. Universal data types: yxcv </em>*

This level is intended for describing classes and methods that solve specific tasks.

#### 2. Actions
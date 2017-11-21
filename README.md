# Cross-Browser-Support

## JavaScript
* Do not use Array.includes(). This is not supported by IE. Use Array.indexOf instead.

## CSS
* left: -50% doesn't work. It needs to be an absolute number like left: 200px. If left is -50%, the absolute number is this element's width's 50%. For example 
  {
    width: 180px;
    left: -90px; // left: -50% would work on all browsers but IE.
  }
* When width is set to an absolute number like 100px, height does not get proportionally adjusted on IE, it needs to be set to an absolute number, too.


![truth](https://pics.me.me/give-respect-to-this-coz-if-this-wasnt-there-insta-12264452.png)

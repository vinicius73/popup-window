popup-window
============

Modification of the original plugin http://swip.codylindley.com/popupWindowDemo.html

```js
  $('a.element1').popupWindow({ 
    height:500, 
    width:800, 
    top:50, 
    left:50 
  });
  
  $('a.element2').popupWindow({ 
    height:500, 
    width:800, 
    centerBrowser: 1 
  });
  
  $('not-a#element').popupWindow({ 
    height:500, 
    width:800, 
    windowURL:'http://luizvinicius.com.br/', 
    windowName:'name', // or <element name="namewindow" ></element> 
    centerBrowser: 1 
  });
```

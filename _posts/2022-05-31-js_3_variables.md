# [JavaScript Variables](./js_3_variables.html)


#### [Back to Home](https://sagarkalyan1.github.io/javascript-tutorial/)




## 4 Ways to Declare a JavaScript Variable:
1. Using var
2. Using let
3. Using const
4. Using nothing


### Using Nothing - Js Variables
file: index.html (1.1)
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JS Variables</title>
    
</head>
<body>
    <h1 class="one">JS Variables</h1>
<div class="one">
    <p id="book-title"></p>
    <p id="book-year"></p>
    <p id="book-year2"></p>
</div>

    <script src="main.js"></script> 
</body>
</html>
```
file: main.js (1.2)

```js
title = "How to win friends and influence people!";
book_release_year = 2011;
book_release_year2 = "2011 + 9";


document.getElementById("book-title").innerHTML = title;
document.getElementById("book-year").innerHTML = book_release_year;
document.getElementById("book-year2").innerHTML = book_release_year2;
```



[Learn to code: Basics of JavaScript](https://solvprog.com)



#### [Back to Home](https://sagarkalyan1.github.io/javascript-tutorial/)

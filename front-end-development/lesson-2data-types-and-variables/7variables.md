# Variables
All of this datas you've worked with so far has been one time use only. We need a way to store data, so that you can use it or change it later.
> 之前都還沒把數字存起來，也還沒提到變數的概念，變數就像以前數學課上的一元一次方程式，我們設一個` x = 5`, 當` x + 1 `時就會等於` 5 + 1`。 

In JavaScript, variable stored data. And they're not limit to the storing just numerical values, you can store  any data into variable.


To do this, you can use variables.
Storing the value of a string in a variable is like packing it away for later use.

```var greeting = "Hello";```

Now, if you want to use "Hello" in a variety of sentences, you don't need to duplicate "Hello" strings. You can just reuse the greeting variable.

```greeting + " World!";```
>Returns: Hello World!

You can also change the start of the greeting by reassigning the variable greeting to a new string value.

```
greeting = "Hola";
greeting + " World!";
```
>Returns: Hola World!

# Naming conventions
When you create a variable, you write the name of the variable using camelCase (the first word is lowercase, and all following words are uppercase). Also try to use a variable name that accurately, but succinctly describes what the data is about.

>一般命名變數，我們會描述這個變數要存什麼，描述的內容就當作變數的名稱，名稱可能會由好幾個英文字組成。然而第一個英文單字我們會用小寫，接下來的字都用大寫，這個方式稱作camel case。描述盡可能精簡與準確。


```JavaScript
var totalAfterTax = 53.03; 
// uses camelCase if the variable name is multiple words

var tip = 8; 
// uses lowercase if the variable name is one word
// 如果只有一個單字就用小寫。
```


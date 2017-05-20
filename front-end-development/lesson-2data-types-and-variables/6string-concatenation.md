# String Concatenation

Strings are a collection of characters enclosed inside double or single quotes. You can use strings to represent data like sentences, names, addresses, and more. Did you know you can even add strings together? In JavaScript, this is called concatenating. Concatenating two strings together is actually pretty simple!
>我們可以把字串用 concatenation 連起來，最基本的方式就是用 `+` 號。

```"Hello," + " New York City"```
>Returns: "Hello, New York City"

# QUESTION 1
Type the code and practice using the addition + operator.

```"hello" + "world"?```
>Returns: "helloworld"


If you want to have a space in between two words, you need to explicitly add a space! It will not be added automatically for you.
>如果你要讓字串之間有空格，你要自己記得加空格。

# QUESTION 2
What do you think will happen when you type "Hello + 5*10" into the JavaScript console?

```"Hello + 5*10"```
>Returns: "Hello + 5*10"



# QUESTION 3 - Implicit type coercion

What do you think will happen when you type `"Hello" + 5*10` into the console?

```"Hello" + 5*10```
>Returns: "Hello50"

You've just discovered some peculiar behavior in JavaScript. It’s called `implicit type coercion` and it's a feature of JavaScript. 

JavaScript multiplies the 5*10 to become 50 and then changes the number 50 into the string "50", so you're adding together the same data type. 

This then gets combined with the string "Hello". You'll learn more about why this happens later in this lesson.
>你輸入 `"Hello" + 5*10` 會輸出 `"Hello50"`，這是 JavaScript 特有的 feature，叫做 `implicit type coercion`，發生的原因下面會再提到。
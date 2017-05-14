# console.log

Developer tools make you  debug or test your idea directly in the browser. If you're familiar with HTML or CSS, you may use developer tools to experience with the style of a webpage. But you can also use it with Javascript.

>如果你有學過點 HTML 或 CSS 你可能早就發現，你可以在 Chrome 裡開啟 Console 去改一些 HTML，改完之後網頁也會跟著變。然而你一樣可以去改 Javascript。

Developer tools are often used as **sandbox**. In other words, a place to mess around with any code without any long-term consequences. You can test and debug a piece of code you just learned.

>開發者工具又稱作 [Sandbox](https://zh.wikipedia.org/wiki/%E6%B2%99%E7%9B%92_(%E9%9B%BB%E8%85%A6%E5%AE%89%E5%85%A8))，換句話說就是隨便你執行任何 code，而且沒有後顧之憂。你可以把剛學的程式拿來跑。

Note that anytime you're using the console on these courses. We might see some warnings or errors from the sites we're visiting. That's okay. It's very common wii not affect the code that you write in the course.
> 課程中你可能會在拜訪其他網站時看到一些 error，這很常見而且不會影響我們在課堂中寫的 code。


# Run the Following Code in the Console:

`console.log` is used to display content to the **JavaScript console**.


```
console.log("hiya friend!");
```
>Prints: "hiya friend!"

We performed the `log` action on the debugging `console`.

The message you’ve logged is "hiya friend!". 
`hiya friend!` is a string (a sequence of characters).

# The Example of Loop (Optional)
Let’s use console.log to do something a little more interesting. Here’s a block of JavaScript code that loops through the numbers 0 through 9 and prints them out to the console:

```Javascript
for(var i =0; i<10 ; i++){
console.log(i)
};
```
>
Prints:
0
1
2
3
4
5
6
7
8
9

This is called a loop.

Based on this loop's settings, any code written inside the curly brackets `{...}` will be repeated 10 times. 

In this case, console.log is printing out the value of i each time the loop runs.  You will learn more about how and when to use loops later in this course.


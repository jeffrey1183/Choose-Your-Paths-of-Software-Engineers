# Indexing
Did you know that you can access individual characters in a string? To access an individual character, you can use the character's location in the string, called its index. 
>你知道對於每一個字串，我們其實是可以 access 每一個字嗎？我們可以依據字的位置，去數你要的字是第幾個，數出來的數字我們稱作 index ，要記住從 0 開始數。

Just put the index of the character inside square brackets (starting with [0] as the first character) immediately after the string. For example:
>確認 index 之後，使用上請在字串後面加上這種 `[]` 括號，裡面寫上 index，像下面這個案例：


```"James"[0];```
>Returns: "J"

Or more commonly, you will see it like this, using a variable:
>你可能更常看到這種：

```
var name = "James";
name[0];
```
>Returns: "J"

# A String are Indexed Starting from 0

Characters within a string are indexed starting from 0, where the first character is at position 0, to n-1, where the last character is at position n-1 (n represents the total number of characters within a string).
>index 從 0 開始數，總字數是 n，最後一個 character 就是 n-1

![](/assets/indexing_1.png)



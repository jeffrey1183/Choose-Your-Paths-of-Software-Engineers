#Escaping strings
There are some cases where you might want to create a string that contains more than just numbers and letters. For example, what if you want to use quotes in a string?

If you try to use quotes within a string, you will receive a `SyntaxError` like the one blow.

```
"The man whispered, "please speak to me.""
```
>Uncaught SyntaxError: Unexpected identifier

Because you need to use quotes to denote the beginning and end of strings, the JavaScript engine misinterprets the meaning of your string by thinking "The man whispered, " is the string. Then, it sees the remaining please speak to me."" and returns a SyntaxError.
>如果要在字串裡用引號該怎麼做呢？如果你直接上面的 `"The man whispered, "please speak to me.""`，為何會得到 SyntaxError呢？因為 JavaScript engine 會以為 `"The man whispered, "` 是一個字串，剩下的`please speak to me."" 他就看不出來是什麼拉。

# Escaping characters - Backslash character `( \ )`
In JavaScript, you use the backslash to escape other characters.

Escaping a character tells JavaScript to ignore the character's special meaning and just use the literal value of the character. This is helpful for characters that have special meanings like in our previous example with quotes "…".

Because quotes are used to signify the beginning and end of a string, you can use the backslash character to escape the quotes in order to access the literal quote character.

```"The man whispered, \"please speak to me.\""```
>Returns: "The man whispered, "please speak to me.""







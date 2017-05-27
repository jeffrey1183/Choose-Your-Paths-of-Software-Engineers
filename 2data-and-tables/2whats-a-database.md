#What's A Database
When you've written code before, you've used data structures such as variables, lists, [dictionaries](http://www.python-course.eu/dictionaries.php), and objects. These all let you store information while your program is running. You can build up complex data structures like a list of dictionaries. When your program exits, the structure will be gone in memory.
>如果你之前寫過程式，你應該會用 variable、list、dictionaries 這些資料結構去存資料。但當你關閉程式這些 variable 也會從記憶體消失。

You've probably worked with files. The files contain your own code. If you edit code in the text editor and save it, then quit the editor, you code doesn't vanish the way variable does, when the program exits. The file is persistent and durable, whereas in memory data is ephemeral(短暫的) or temporary. Programs can read and write files just fine, so why bother with databases?
>另外你應該有用過檔案存你的 code，如果你在編輯器存了檔案，然後關閉編輯器，檔案不會像 variable 那樣消失。檔案是可以保存的，不像記憶體裡的資料只是暫時性的。如此說來可以存起檔案就好了，為何還要 database 呢？



### How do we structure application data?

There are several databases. They have in common is that they give us the persistent
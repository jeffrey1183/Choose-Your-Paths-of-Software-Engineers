#Prerequisites and Requirements
If you can understand this code , you know enough Python for this course:

```Python
import random

def ChooseTwice(items):
    a = random.choice(items)
    b = random.choice(items)
    return a, b

names = ["Alice", "Bob", "Charlie", "Debra"]
(one, two) = ChooseTwice(names)
if one == two:
    print "%s is happy!" % one
else:
    print "%s likes %s!" % (one, two)
```


####You can use a command-line interface (terminal).
Some of the exercises in this course involve using a Unix-style command-line interface to enter commands, run Python programs, and navigate directories.

If you have taken our course on [Git and Github](https://www.udacity.com/course/how-to-use-git-and-github--ud775), the level of command-line use in this course is similar.

####You don't need to be a Web programmer. 
This course does include a small Web application and some HTML and JavaScript in examples, but you will not need to make changes in these languages.
>這門課接觸到的 Web application 會有 HTML, JavaScript 的 Code，但是不會要你修改。

####You don't need any previous database experience. 
This course is an entry-level introduction to relational databases.

You need a programming text editor (such as [Atom](https://atom.io)) installed on your computer. You should be able to use it to open and edit files of Python code.
>這門課不需要有任何跟 database 有關的經驗，只是要安裝程式編譯器，像 [Atom](https://atom.io)
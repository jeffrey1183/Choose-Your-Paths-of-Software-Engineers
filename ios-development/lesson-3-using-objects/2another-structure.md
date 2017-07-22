#Another Struct Example
Let's talk about another struct. This time we'll look at the `MazeLocation` struct. The `MazeLocation` struct is responsible for storing x- and y-coordinates for an object (like the Robot or the Star) in the maze.
>這邊來講 `MazeLocation` 這個 struct，這個 struct 主要儲存物件的 x 軸與 y 軸位置，例如儲存星星的座標位置 (0,1)。
![](/assets/anotherStruct_1.gif)
The MazeLocation of the Robot is (3, 2) and the MazeLocation of the Star is (0, 1).

It contains virtually no functionality, and it is primarily used as structured data (x- and y-coordinates) to be consumed by the app (i.e. the maze).We’ve described objects as consisting of data and functionality. In Swift, we call an object's data “properties” and its functionality “methods”.

* `Properties` are the values associated with an object
* `Methods` are the functionality associated with an object

From now on, we will use these terms, so be sure to take note of them.

>`MazeLocation`並沒有 function 僅僅是資料。在 Swift 裡我們稱 object 的 value 為 properties， function 為 method。接下來會一直看到這兩個詞。


It is one thing to try and imagine objects in a running program, but how do we use them?

The answer lies in the dot operator. It allows us to access the properties and methods of objects. You’ve seen the dot operator before when you helped the Robot reach the star. Remember that you sent instructions to the robot with code like this:

![](/assets/anotherStruct_2.gif)
Xcode can predict how to complete our instructions based on what is typed.

As soon as the dot was typed, Xcode revealed the robot's methods. The dot operator is what allowed us to call the `moveUp` method on the `Robot` object.


>實際在操作時我們用 `.`(dot operator) 去 access property 跟 objects，如果上面這個圖，Xcode 會帶出一些你可能會用的指令。

# Relationships
Let's introduce the next concept related to objects... relationships! Within a system like the Maze app, there are many kinds of relationships that exist between objects. For example, some objects “contain” other objects while other objects represent “a kind of” object. These are just two examples, but you can probably come up with your own!
>在一個 app 內， object 之間存在著一些關係。有的 object 包括其他 object，其他 object 只是其中一種 object。
![](/assets/anotherStruct_3.gif)
Relationships describe the nature of connections between objects.


From this diagram, we see that a maze “contains” `MazeCells`, `MazeActors`, and `MazeObjects`. Also, a `Robot` is “a kind of `MazeActor` and a `Star` is “a kind of `MazeObject`. Lastly, we have denoted the multiplicity of the “contains” relationships. Multiplicity sounds complicated, but it's really just a word used to describe how many objects are involved in a relationship. So for the Maze, there are many `MazeCells` and 1-to-many `MazeActors` and `MazeObjects`.
>在這個圖中 Maze 這個 app 有 `MazeCells`、`MazeActors` 、`MazeObjects` 這三種 object，`Robot` 是 `MazeActor` 的其中一種 object，`Star` 是 `MazeObject` 的其中一種 object。
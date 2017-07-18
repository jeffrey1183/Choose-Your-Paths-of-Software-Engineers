#Another Struct Example
Let's talk about another struct. This time we'll look at the MazeLocation struct. The MazeLocation struct is responsible for storing x- and y-coordinates for an object (like the Robot or the Star) in the maze.
>這邊來講 `MazeLocation` 這個 struct，這個 struct 主要處理物件在 app 內的 x 軸與 y 軸。
![](/assets/anotherStruct_1.gif)
The MazeLocation of the Robot is (3, 2) and the MazeLocation of the Star is (0, 1).

It contains virtually no functionality, and it is primarily used as structured data (x- and y-coordinates) to be consumed by the app (i.e. the maze).

We’ve described objects as consisting of data and functionality. In Swift, we call an object's data “properties” and its functionality “methods”.

* `Properties` are the values associated with an object
* `Methods` are the functionality associated with an object

From now on, we will use these terms, so be sure to take note of them.

It is one thing to try and imagine objects in a running program, but how do we use them?

The answer lies in the dot operator. It allows us to access the properties and methods of objects. You’ve seen the dot operator before when you helped the Robot reach the star. Remember that you sent instructions to the robot with code like this:

![](/assets/anotherStruct_2.gif)
Xcode can predict how to complete our instructions based on what is typed.

As soon as the dot was typed, Xcode revealed the robot's methods. The dot operator is what allowed us to call the moveUp method on the Robot object.

Let's introduce the next concept related to objects... relationships! Within a system like the Maze app, there are many kinds of relationships that exist between objects. For example, some objects “contain” other objects while other objects represent “a kind of” object. These are just two examples, but you can probably come up with your own!
![](/assets/anotherStruct_3.gif)
Relationships describe the nature of connections between objects.

From this diagram, we see that a maze “contains” `MazeCells`, `MazeActors`, and `MazeObjects`. Also, a `Robot` is “a kind of `MazeActor` and a `Sta`r is “a kind of `MazeObject`. Lastly, we have denoted the multiplicity of the “contains” relationships. Multiplicity sounds complicated, but it's really just a word used to describe how many objects are involved in a relationship. So for the Maze, there are many `MazeCells` and 1-to-many `MazeActors` and `MazeObjects`.
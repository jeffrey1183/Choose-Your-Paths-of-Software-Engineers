#Wrestling with the Swift Compiler

We’ve mentioned the importance of the Swift compiler for creating apps that will run on our device. We've also mentioned that the Swift compiler can be a little difficult to work with at times. We are going to see this first-hand now. Let’s go back to the `ControlCenter.swift` file, and look at the code inside `moveSimpleRobot`.
>我們提過 Swift compiler 有時會出現運行上的問題，現在我們直接來看 `ControlCenter.swift` 檔案內 `moveSimpleRobot` 這個 function，這個 function 主要用於移動在迷宮中的機器人。
![](/assets/wrestiling_1.png)

Notice that we’ve told the robot to move up. The syntax we’ve used for this is `robot.moveUp()`. But what happens if you accidentally forget how to write this instruction and instead write `robot.goUp()`?
>我們已經告訴機器人向上移動的語法是 `robot.moveUp()`，但如果我們把 `robot.moveUp()` 改成 `robot.goUp()` 會發生什麼事呢？

![](/assets/wrestiling_2.png)

If you try to build and run the project now, it fails! Instead, the Swift compiler and Xcode present some warning signs. As you write code, you’ll have to remember that the Swift compiler only understands a very limited set of vocabulary. This would be like if a musician was given a sheet of music with symbols they’d never seen before. When we give the compiler a new instruction that it doesn’t understand, it presents us with errors. If we change this back to the original, you’ll notice that the warnings go away.
>結果會跑不出來，Swift compiler 和 Xcode 會出現一些警告提示。當你寫程式時，你要記得 Swift compiler 遵循著一些語法就像音樂家演奏著音符，當 compiler 不了解時就會出現 error，結果你就只能改回程 `robot.moveUp()`


We’ll explore more Swift syntax and errors later. For now, let’s start thinking about how we can help our robot get from its original location to the star.
>後面會介紹更多語法和 error ，現在我們先想辦法讓機器人從原點走到星星。

#Prepare
Let’s stay out of Xcode for a second and make sure we can help solve the robot’s problem. We'll do this by writing an algorithm. An algorithm describes the steps we need to take to solve a problem. Right now, we know that the robot, the maze, and the star are positioned like this when the app starts:

![](/assets/wrestiling_3.png)

We will write our algorithm using pseudocode. Pseudocode is not real code, but is more like temporary notes or scratch work. Writing the pseudocode ahead of time will allow us to see any errors in our problem solution before we go through the trouble of writing actual code. The bigger the problem, the more time we can save by doing this.

Typically, writing algorithms in pseudocode can be done free-form (in other words, you can write whatever you want that assists you in solving the problem). But, for this exercise, try to write your pseudocode solution using only the following items:

* moveUp
* moveDown
* moveLeft
* moveRight

Here is an example algorithm. _Note: It does not actually solve the problem, so technically this is an incorrect algorithm._

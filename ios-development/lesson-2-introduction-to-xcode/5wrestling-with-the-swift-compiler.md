#Wrestling with the Swift Compiler

We’ve mentioned the importance of the Swift compiler for creating apps that will run on our device. We've also mentioned that the Swift compiler can be a little difficult to work with at times. We are going to see this first-hand now. Let’s go back to the `ControlCenter.swift` file, and look at the code inside `moveSimpleRobot`.
>我們提過 Swift compiler 有時會出現運行上的問題，現在我們直接來看 `ControlCenter.swift` 檔案內 `moveSimpleRobot` 這個 function，這個 function 主要用於移動在迷宮中的機器人。
![](/assets/wrestiling_1.png)

Notice that we’ve told the robot to move up. The syntax we’ve used for this is `robot.moveUp()`. But what happens if you accidentally forget how to write this instruction and instead write `robot.goUp()`?
>我們已經告訴機器人向上移動的語法是 `robot.moveUp()`，但如果我們把 `robot.moveUp()` 改成 `robot.goUp()` 會發生什麼事呢？

![](/assets/wrestiling_2.png)

If you try to build and run the project now, it fails! Instead, the Swift compiler and Xcode present some warning signs. As you write code, you’ll have to remember that the Swift compiler only understands a very limited set of vocabulary. This would be like if a musician was given a sheet of music with symbols they’d never seen before. When we give the compiler a new instruction that it doesn’t understand, it presents us with errors. If we change this back to the original, you’ll notice that the warnings go away.
>結果會 build 失敗，Swift compiler 和 Xcode 會出現一些警告提示。當你寫程式時，你要記得 Swift compiler 遵循著一些語法就像音樂家演奏著音符，當 compiler 不了解時就會出現 error。

Try the following:

* Produce a Swift compiler error by writing an instruction the robot did not understand (i.e. robot.goUp).
* Correct the error by changing the line of code back to robot.moveUp().

We’ll explore more Swift syntax and errors later. For now, let’s start thinking about how we can help our robot get from its original location to the star.
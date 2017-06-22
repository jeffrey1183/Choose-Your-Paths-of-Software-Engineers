#From Xcode to App
So what all happened when we hit the play button? Well, Xcode began working in the background to launch the Maze app on the iOS Simulator.


The Swift compiler makes this all happen. The Swift compiler is a piece of software that translates the Swift code we write into an executable app that a device like your phone, tablet, or watch can understand. The process by which the compiler translates your code into an executable app is known as building.
>當我們按下 play button，Maze 這個 App 就會開始在 iOS 模擬器運行，主要是靠 Swift compiler 完成這件事，compiler 把寫出來的 code 變成可運行在手機、平板、手錶都可運行的 App，這個讓程式碼運行的過程就叫 building。

![](/assets/fromXcode_1.gif)
The Swift compiler is used to translate Swift code into an executable app.
>Swift compiler 用來把 Swift code 變成可執行的 App

In order to build an app, we have to follow the compiler’s guidelines for code, or acceptable syntax. You can think of syntax as language rules. For example, imagine that your compiler only knows the language rules for Japanese. If you tried to talk to the compiler in German, the compiler wouldn't understand what you're saying. Therefore, your code must be written in perfect Japanese in order for the compiler to translate the code and finish the building process. Otherwise, the build will fail, and the app won't run.
>為了 build 一個 App，我們必須 follow compiler 的 guideline 去寫程式，也就是遵循程式的語法，可以想像成像英文有自己的語法。這裡舉了一個例子，如果編輯器是用日文寫的，如果你用德文跟他溝通一定行不通的!!因為他根本搞不懂你在說什麼。因此你的語法要很正確，讓 compiler 瞭解，不然 build 失敗就不能運行。

![](/assets/fromXcode_2.gif)
If syntax is invalid, then the build process cannot complete.
>如果語法無效，那就無法 build 成功。

After the compiler builds our code, we have an executable app file that contains all the information needed by a device to run your app. 


Note: We normally don’t see the app file since Xcode conveniently manages all of this in the background.

With the executable app complete, we move into the running phase where the app is installed and run on a device (or the iOS Simulator). You may already be familiar with the process if you've downloaded apps from the App Store; when you install an app from the App Store on a physical iOS device, the app is downloaded, and then run on your phone, tablet, or watch.
>build 成功的話，就有一個可運行的 app 檔案，裡面包含了運行在設備上所需要的所有資訊。我們通常不會看到 app file 因為都在 background 運行。
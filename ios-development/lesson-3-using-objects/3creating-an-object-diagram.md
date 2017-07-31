#Creating an Object Diagram
Let's pause for a moment and talk about how to create the object diagrams you've been seeing. We've broken this process into 3 steps: identify objects, relationships, and multiplicity.
>我們先暫停一下，先講如何 create 剛剛看到的 object diagrams，可分成三個步驟 
1. identify objects 
2. relationships 
3. multiplicity


If you've never created an object diagram from scratch, then it can be confounding the first time. However, making an object diagram should be a very natural process once you know how to identify objects. For many, you may already be identifying objects in everyday experiences and not even know it!
>如果你沒有畫過 object diagram 的草圖，第一次可能比較驚恐。

## [影片1 - Creating an Object Diagram Identifying Objects ](https://www.youtube.com/watch?v=dQFb_Ws6s64)

I'd like to take a moment and show you the process of  creating an object diagram. You might also hear this process referred to as object decomposition. That is, we're taking that's a big object like an app, and we're breaking it down into an individual components. Now there is no right or wrong way to do this. If a hundred people create an object diagram for an app, there might be 100 completely different diagrams.
>我們要花點時間來學怎麼畫 object diagram，也有人稱之為 object decomposition。如果我們把 app 想像成一個 object，我們把 app 拆解成許多 components，這個並沒有所謂的正確與錯誤，可能 100個人拆解，會拆解成 100 種完全不同的結果。

![](/assets/creatingAnObjectDiagram_1.png)

Also there is some formal and informal way to create them. A formal way might be creating an object diagram using the Universal Modeling Language or UML. And an example object diagram's given here on the left. Now the UML as the modeling language contains a bunch of standard symbols and icons that are helpful for laying out the components of a project. But for many, UML can be really bulky to work with. I am more the fan of informal approach that takes some ideas from UML, but it doesn't get bogged down in the nitty gritty details. And an example of a more informal object diagram is given here on the right.
>畫 object diagram 比較正式的方法是用 UML 去畫，就像左邊的圖一樣會用到一些標準符號，但 UML 比較麻煩。作者比較喜歡用較不正式但不拘泥於細節的方式去畫，像右圖一樣。
![](/assets/creatingAnObjectDiagram_2.png)

So for this example I'm going to take an app that you'll see later called Alien Adventure. This is the main screen  for the app. I can interact with it by tapping on the screen.
>這邊我們用一個 Alien Adventure 的 app 來舉例，下面是 app 的主畫面，我們可以透過點擊來跟 app 互動。

![](/assets/creatingAnObjectDiagram_3.png)

And we can see the robot will animate across the screen and there's multiple aliens. And the robot and the alien will have a discussion. If the robot answers the alien's question correctly, and then these little gadgets will appear in the lower left corner in the screen.
> 我們會在 app 看到機器人在畫面上移動，跟外星人對話，如果機器人答對外星人的問題，就會在螢幕的左下角出現徽章。
![](/assets/creatingAnObjectDiagram_4.png)

At this point we've already seen enough of this app to actually start the object decomposition process. I open the Google drawing to build the diagram. But you could use a piece of paper, a tool like draw.io and any tool you can put your ideas into a diagram.

The first thing we'll start with is the big object which is the app itself. Now the app isn't an actual object in code, but that's ok. We're going to use it as the starting point.
>我們現在開始進行 object decomposition 的過程，你可以畫在紙上或是用任何可以把 idea 變成 diagram 的工具。

In UML you typically refer to objects in their singular form. I might use a certain type of symbol for an object maybe a rectangle. And then a certain type of symbol for a struct like a rounded rectangle. What else did we notice in the App? What else could be considered part of the application? I can think of are the background, badges that appeared in the lower left hand corner. And there was a dialog bubble at the top, and it consisted of  multiple lines of text. 
>在 UML 較正式的寫法下，物件都用單數，像 alien，會用長方形代表物件，用圓邊的長方形代表結構。我還有想到一些物件會出現在 app 內，像是背景、左下角的徽章、泡泡對話框、幾行文字。

![](/assets/creatingAnObjectDiagram_5.png)

But there could also be objects that are behind the scenes. Things that we can't see, but still make some part of the application itself. For example, what about the concept of the game world? It's very creative, abstract thinging type of process. No two people probably  create the same object diagrams.

We're going to refine the diagram and think about how the objects are interconnected. We're also going to look to see if the objects have similarities because that's a big deal when designing apps. If some of objects share traits and other similar functionality, then we can take advantage later when we start writing code.

到: 秒：https://www.youtube.com/watch?v=KphWDw8w8rI




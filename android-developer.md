# 以下為之前的筆記，先移至這邊

Android 系統驅動著全球 14 億部、82% 以上智能手機，為世界各地的開發人員提供了令人難以置信的創新機會。未來第一次登錄互聯網的數十億人中大部分都將是通過移動設備。編寫 Android 應用，能夠為你提供去贏得這些用戶的最好機會，影響你的社區，甚至影響我們的世界。

我們將使用 Android Studio 軟件編寫應用，所以，為了學習本課程，你應該擁有一台可以運行 Android Studio 的電腦（詳細信息，請參閱 Android Studio 的[系統要求](http://developer.android.youdaxue.com/studio/index.html#Requirements)）。別擔心，你不需要提前安裝 Android Studio 軟件，作為課程的一部分，我們將提供詳細的安裝說明。

# 學習計劃

## 第 1 課 — 構建布局

在手機屏幕上布置你的應用。在這節課程中，你將學習使用 XML 標記語言布置 Android 應用。你將創建視圖，即顯示文本和圖像的 Android 應用布局基本構建塊。然後，你將在這些屏幕上對你的文本和圖像進行定位。這種高度互動課程，鼓勵通過優達學城 XML 自定義圖標程序中的編碼挑戰進行試驗。

## 習題集 1

為你的手機創建一個生日賀卡應用。你將首先安裝 Android Studio，一個專業開發人員用於編寫 Android 應用的專用程序。然後，從你的電腦中將你創建的簡單應用轉移到你的手機。之後，你將運用在第 1 課中學習到的所有概念構建你的生日賀卡應用，並安裝在你的手機上，向你的朋友和家人展示。

# Android Development Tips and Tricks {#ios-development-tips-and-tricks}

你將跟著 Kunal 和 Katherine 一起學習 Android 開發入門課程的第一部分。雖然在這一部分，你將不會學習 Java 語言，但是你將設置 Android Studio，並用到 XML。在開始學習之前，請閱讀一些有用的資源，這些資源將在你學習 Android 編程的過程中很有幫助。

## Android Studio

開發 Android 應用，最棒的一點就是所需的工具完全免費，容易使用。 Android 軟件開發套件 \(SDK\) 可以免費下載，Android Studio 也同樣如此，後者是開發 Android 應用的官方集成開發環境 \(IDE\)。開發者使用 Android Studio 通過各種程序包和庫編寫代碼及組裝應用。Android SDK 包含示例代碼、軟件庫、實用的編程工具，以及其他大量資源，幫助你構建、測試和調試 Android 應用。

開發 Android 應用的另一大優勢是可以輕松地提交應用。准備好將應用提交到 Google Play 商店後，注冊一個 Google Play 發布商帳號（需要通過 Google 電子錢包支付 25 美元），對照 Android 的發布檢查清單檢查應用，通過 Google Play Developer Console 提交應用，然後等待 Google 審核，並看到應用出現在 Play 商店中。過程簡單，易於操作。

## XML

程序員使用可擴展標記語言（簡稱 XML）來描述數據。XML 可以幫助專業 Android 開發者完成各種任務，例如設計用戶界面 \(UI\) 、布局和解析互聯網上的數據源。需要用 XML 實現的大部分功能都可以通過 Android Studio 完成，但是建議你掌握該標記語言的基礎知識。

# **名詞解釋**

* rounded corners \(圓邊的\)
* swipe off
* 滑手機的動作，有點像把應用程式關掉時，滑掉的動作
* 程式寫死的英文
* hard code
* 的英文是 backslash
* comment it out with a double forward slash\(就是這個//\)

## 閱讀文章- [如何成為一名 Android 開發者](http://blog.udacity.com/2015/05/become-android-developer.html)

上面的 tips 摘錄至 [如何成為一名 Android 開發者](http://blog.udacity.com/2015/05/become-android-developer.html), 是一篇相當值得看的文章。其他要點如下：

* App 改變以往的消費模式與企業。
* Android 是 open source，所有的 [source code](https://source.android.com/) 都可以瀏覽
* [Google Play Services](https://developer.android.com/google/play-services/index.html) 幫助開發者處理 App tasks \(e.g. sign in, authentication, location, and storage\) 讓開發者專注在 App 的核心功能

### Tools to Become an Android Developer

除了上面提到的 Android Studio 跟 XML 外, Java 和 基本的 SQL \(in order to organize the databases within Android apps\)

* SQL is a language for expressing queries to retrieve information from to databases. Once you can write it, there won’t be any questions you can’t ask of your data.

* Java is the most basic building block of Android development is the programming language Java.

* You’ll need to be comfortable with Java concepts like loops, lists, variables, and control structures

* 你需要 Android device 幫助你測試

###

###

#
課程摘要

* 這門課設計給沒寫過半行 code 的學習者，但還是要稍微熟悉電腦和手機的操作。
* 課程會建立簡單的 Android 應用

* 第一個 - 生日蛋糕卡片
* 第二個 - 咖啡 menu

* 學習寫 App 就像學習一門新語言，學習新的詞彙把他們都放在一起，撰寫句子創造 App

[![](https://lh5.googleusercontent.com/9SCHspntJAX7MDflzIWFckDAkwqEQgXjtRV5TtKO1bE9oo1kp6cvt5tIiRfIZK6ojHFO9kRM3nA-pT0oLPw-RgDj7ef2euvPmVrwY-YOKkD_HSeQgn77ie6VZcdS78D3WGPIxdVv)](http://developer.android.com/reference/android/widget/TextView.html#attr_android:textStyle)

### Select Views

* ImageView. TexView 和 button 基本介紹

* 其他像 checkbox, radio button

### Style Views

* 改字體顏色，抓圖

* 記得要注意圖片大小

### Position Views

* Positioning, 按鈕要放在哪個位置

* Padding and Margin

# Views & Layout

![](https://lh6.googleusercontent.com/SXwf28dOyiRuuw7eX-3oA0n14cXhA23SVufonAfi10_Ttd-5yixl-O0lagltx6siD70lD4a2WRhbGiKgUkkrn5t3IeMCMHCMMYAAMjiezLCq2d7hA8Attkr2MkjCoJ5KVvyruzrL)

* 什麼是 Views?

* A view is a rectangle on the screen that shows some content.

* 可以是 image, text, button 或是其他可以顯示在螢幕上的東西

* 什麼是 layout?

* layout 由一個一個views 組合而成

* 什麼是 user interface \(UI\)

* Everything about what you see and interact with in your app is called UI.

* **把畫面拆解成一塊一塊的，基本上有上面三種元素**

* **註冊 Signup 是個 button**

[https://classroom.udacity.com/nanodegrees/nd000/parts/00013454010/modules/0001345401075460/lessons/6784922120/concepts/42331586330923](https://classroom.udacity.com/nanodegrees/nd000/parts/00013454010/modules/0001345401075460/lessons/6784922120/concepts/42331586330923)
#
# A few industry favorites include

* [Stack Overflow](http://stackoverflow.com/)
* [Android Weekly](http://androidweekly.net/)
* [Android Dev subreddit](http://www.reddit.com/r/androiddev)
* [vogella tutorials](http://www.vogella.com/tutorials/android.html)
* [YouTube lessons](https://www.youtube.com/watch?v=TBWX97e1E9g&list=PLE7E8B7F4856C9B19)



## Google’s official

* [Android Developers site](https://developer.android.com/index.html)
* Especially the [Building Your First App](http://developer.android.com/training/basics/firstapp/index.html) module. If you’re more of a print learner, popular Android books include
* [_Head First Java_](http://www.amazon.com/Head-First-Java-2nd-Edition/dp/0596009208/ref=sr_1_6?ie=UTF8&qid=1408144218&sr=8-6&keywords=java+books)
* [_Android Programming: Pushing the Limits_](http://www.amazon.com/Android-Programming-Pushing-Erik-Hellman/dp/1118717376/ref=sr_1_2?ie=UTF8&qid=1408144123&sr=8-2&keywords=android+books)
* [_Java: A Beginner’s Guide_](http://www.amazon.com/Java-Beginners-Guide-Herbert-Schildt/dp/0071809252/ref=sr_1_1?ie=UTF8&qid=1408144218&sr=8-1&keywords=java+books)



工作相關的

As you start to think about attracting job opportunities, and selling yourself as a viable candidate, consider showcasing your Android work on [LinkedIn](https://www.linkedin.com/), [Xing](https://www.xing.com/en), through an online personal portfolio, or on sites like [Behance](https://www.behance.net/) and [GitHub](https://github.com/). Rub elbows, in person and virtually, with other Android developers and hiring managers or recruiters through meetups, conferences such as [droidcon](http://droidcon.com/), and digital networking hubs like[LinkedIn groups](https://www.linkedin.com/directory/groups/),[Twitter chats](http://tweetreports.com/twitter-chat-schedule/), and [Quora feeds](http://www.quora.com/search?q=android). You never know what you’ll learn, or who you’ll meet.

介紹 Android 裝置的網站

* https://www.android.com/intl/en\_us/work/



到31秒

#

# Vocabulary Glossary

* [連結](https://developers.google.com/android/for-all/vocab-words/)
* [整理文件](https://s3.cn-north-1.amazonaws.com.cn/static-documents/nd803/Android+for+All+－+Vocabulary+Glossary.pdf)








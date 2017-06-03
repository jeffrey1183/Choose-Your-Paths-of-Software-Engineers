#Quiz: Queries And Results
Earlier, I told you that database tables were a lot like the tables you might see in infographic or a reference book. There are some differences though. One of this is important when there are multiple answers to a question, which will often be the case just before we use a count or another aggregation. 
>之前有提到說 數據庫其實很像我們常看到的信息表格，不過有一些不同之處，其中一個重要的不同之處就是一個問題可能對應著多個答案，在我們使用 aggregation 前常常就會有這種情況。


This table is about animals and what they eat. Unlike some tables we've seen before, the left one sometimes has  the same value in some of cells and the right one with different values over here. This is how we say things like brown bears eat fish, meat and plants in database table. We spit that sentence out into multiple sentences which make multiple rows in the table.
>下面這個圖是關於動物會食用的食物，不像我們之前看到的表格左邊欄位會相同，右邊欄位都不同，以 brown bear 為例，我們就有三行，每一行列出 brown bear 的食物，這樣就會有很多列。

![](/assets/queriesAndResluts_1.png)

Why don't we just make multiple columns or put several values in one column separated with commas or something?
>那為何我們不用像下面這兩種方式呢？一種是把欄位增加，一種是用逗號把食物分開就好。
![](/assets/queriesAndResluts_2.png)
![](/assets/queriesAndResluts_3.png)
There are lots of reasons not to do that. If we tried using multiple columns with different foods each animal eats, we don't know how many columns to make in advanced. Some animals do eat a lot more kinds of foods than others after all. And what's more



In a relational database, when there are multiple answers to a question (like "What do brown bears eat?")

  they will usually appear as multiple rows in a table. 
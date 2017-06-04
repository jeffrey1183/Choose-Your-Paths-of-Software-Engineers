#Quiz: Queries And Results
Earlier, I told you that database tables were a lot like the tables you might see in infographic or a reference book. There are some differences though. One of this is important when there are multiple answers to a question, which will often be the case just before we use a count or another aggregation. 
>之前有提到說 數據庫其實很像我們常看到的信息表格，不過有一些不同之處，其中一個重要的不同之處就是一個問題可能對應著多個答案，在我們使用 aggregation 前常常就會有這種情況。


This table is about animals and what they eat. Unlike some tables we've seen before, the left one sometimes has  the same value in some of cells and the right one with different values over here. This is how we say things like brown bears eat fish, meat and plants in database table. We spit that sentence out into multiple sentences which make multiple rows in the table.
>下面這個圖是關於動物會食用的食物，不像我們之前看到的表格左邊欄位會相同，右邊欄位都不同，以 brown bear 為例，我們就有三行，每一行列出 brown bear 的食物，這樣就會有很多列。

![](/assets/queriesAndResluts_1.png)

Why don't we just make multiple columns or put several values in one column separated with commas or something?There are lots of reasons not to do that. If we tried using multiple columns with different foods each animal eats, we don't know how many columns to make in advanced. Some animals do eat a lot more kinds of foods than others after all. And what's more we want to be able to use counts and other aggregations. And those will only work if we have our data separated out into rows, not jammed together.
>那為何我們不用像下面這兩種方式呢？一種方式是把欄位增加，一種是用逗號把食物分開就好。原因有很多，像是如果我們增加食物的欄位，我們其實無法預測要增加幾欄，有些動物可以吃的食物比較多。另外如果我們要用 aggregation 的話，要一行一行分開的資料才能用，不能堆在一起。
![](/assets/queriesAndResluts_2.png)
![](/assets/queriesAndResluts_3.png)

Now let's take a look at a real database query against this table. Select food from diet where species equals orangutan. This looks almost like ordinary English, but this is actually an SQL database query. It's asking the database to return a particular data from the diet table. In a moment, we'll run this query using an actual database. But before we do, can you figure out which rows and columns from this table will return?
>Select food from diet where species equals orangutan 這一段看起來像英文語句但實際上就是 SQL database 的查詢語句，他在向資料庫的 diet table 要求一個資料。等一下我們會在實際的資料庫運行，但在那之前你可以預測一下，針對這個 query ，表內的哪些行跟列會出現在結果裡呢？

![](/assets/queriesAndResluts_4.png)

The result table will have one column and two rows.



In a relational database, when there are multiple answers to a question (like "What do brown bears eat?")

  they will usually appear as multiple rows in a table. 
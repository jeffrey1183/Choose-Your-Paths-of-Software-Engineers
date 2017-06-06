#How Queries Happen
Now we've seen some sort of information that we can store in a database table, let's talk about how our codes talks to a database. When our code fetches data out of a database, it does this by sending a query. In response, the database will send a result containing a new table with the data we ask for.
>現在我們來講講我們的程式碼是怎麼跟資料庫溝通的呢？我們是透過發送 query 到資料庫裡獲得資料，作為回應，database 會發一個新 table 其中包含我們要求的數據。
![](/assets/howQueryHappen_1.png)

Depending on the specifies of our environment our code might be talking to the database over the network.

![](/assets/howQueriesHappen_1.png) 

Or it might just be calling the library that keeps the database on the local disk.

![](/assets/howQueriesHappen_2.png)

Those design details would be important later but for now we can actually ignore them. The basic of database work the same no matter what the implementation is. So let's take a look at  running some queries in SQL against an actual database. Don't worry about this syntax right now, we'll see that in next lesson. Okay, here is the query we saw before, select food from diet where species equals orangutan. And we run it here is the result. Now, something to notice about the result is that it's a table. It has two rows, it has one column, the food column that we asked for. So running a query against the database isn't like returning a single value from a function, it's more like returning a list, even if there might only be one element. In fact, even if we ask the database for 2 plus 2 like this. The answer is still actually a table with one column and one row. If we ask the database for the answers to three arithmetic problems at once then we'll get back a table with1 a single row and three columns, each of them giving one of the answers. You might have noticed that these columns have rather unusual names, they all are question marks column question mark. If 
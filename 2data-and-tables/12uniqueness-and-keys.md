#Uniqueness And Keys
In a lot of databases, we're talking about unique entities out in the world. Like individual people or locations, or email accounts. If something is unique, there can't be two of them. So for instance, names are not unique, not even full names. There are a lot of people in the world named Jennifer Smith. But a particular person named Jennifer Smith is still a unique individual. You wouldn't want to give one person another person's grade or their parking tickets just because they share the same name. Whenever we want to ambiguously relate a row of one table to a row of another, to see they are about the same person or thing out in the world. We need to have a unique value to talk about that thing.
>在資料庫裡我們要處理很多唯一存在的東西，比如人、地點或是電子郵件。如果某樣東西是唯一的，那就不會有兩個，就像名字，世界上雖然有很多 Jennifer Smith，但每一個名叫 Jennifer Smith 的人都是獨一無二的個體，不會因為兩個人名字一樣，你的考試成績或是罰單就給了另一個人。如果我們要讓 table 有關聯，一定要確認內容指的是同一個人或同一樣東西，那個東西必須有唯一值。

In the cutest animal databases, we used a numerical ID for each animal picture, which we used to relate the votes table to it. That's pretty common choice. Just make up the unique number for your database. It's so common that most database system can do it for you. User IDs, comment IDs on forums and so on, are all examples of this.
![](/assets/unique_1.png)

In database terminology, a column and a table that uniquely identifies 

到1:11
#Related Tables
A Database usually has several tables in it. Here's how we might start for our image voting app.
>資料庫通常會有很多 table，我們或許可以這樣開始我們的投票 App 

![](/assets/relatedTables_1.png)

The first table presents pictures that people have uploaded of animals. The second presents people's votes.Fluffy, Master, George all are animals, whose pictures someone has uploaded. Because we might have two animals with the same names. We give each one numeric id here. The votes table says, which images have been displayed together for voting, and which one the user picked as the cutest. Here the app displayed Master the id 2, and George id 3 and the user voted for George. 2 and 3 were matched up and 3 was the winner. Note that in the vote table, the columns are called left, right and winner. But they matched up, to the column called id in the picture table. You can read every row as a sentence. In the pictures table, the sentences say Fluffy has id number 1 and the filename fluffsocute.jpg. Monster has the id number 2 and the filename monstie-basket.jpg and so forth.
>左邊的 table 代表已經上傳的動物圖片，Fluffy, Master, George 都是已經上傳圖片的動物，為了怕有一樣的動物名，我們還設了 id 。右邊則是投票情形，圖片會並排呈現給用戶投票，讓用戶選擇哪一個比較可愛。像第一列就是指，左邊是 id 為 2 的 Monster，右邊是 id 為 3 的 George，結果用戶選了 George。
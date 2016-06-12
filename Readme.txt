  Client、計算機 : 

運用助教所提供的code，合併到SocketSample裡實作，同時在裡面

建立好連線。每當要跑到result的介面十，就send result給server

，讓server可以顯示


  Server : 

在server多開一個connectThread，讓他可以隨時接收client所送來的

訊息，並且運用在顯示幕上面。


遇到問題 :

一開始不知道帶為什麼連線連不上去，後來發現是out沒有那它接收

socket的out，導致訊息發布出去。

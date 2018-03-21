# Socket programming in C++
---
**支援程式系統 : Windows (因為有system call指令)**  
起始畫面:  
> 先執行server_socket這個程式，再執行client_socket這個程式，就會跑出以下結果
![start](https://github.com/Zane2453/Socket-Cplus-Gobang/blob/master/pic/1.png)  

接著進入遊戲畫面:  
> 會建一個20*20的棋盤，並由server端先下
![start](https://github.com/Zane2453/Socket-Cplus-Gobang/blob/master/pic/2.png)

當其中一方輸入:  
> 此輸入會同步傳送到另一端，以便兩者同時刷新棋盤
![start](https://github.com/Zane2453/Socket-Cplus-Gobang/blob/master/pic/3.png)  


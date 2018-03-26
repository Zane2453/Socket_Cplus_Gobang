# Socket programming in C++

### **支援程式系統 : Windows (因為有system call指令)**  
起始畫面:  
> 先執行server_socket這個程式，再執行client_socket這個程式，就會跑出以下結果
![start](https://github.com/Zane2453/Socket-Cplus-Gobang/blob/master/pic/1.png)  

接著進入遊戲畫面:  
> 會建一個20*20的棋盤，並由server端先下
![start](https://github.com/Zane2453/Socket-Cplus-Gobang/blob/master/pic/2.png)

當其中一方輸入:  
> 此輸入會同步傳送到另一端，以便兩者同時刷新棋盤
![start](https://github.com/Zane2453/Socket-Cplus-Gobang/blob/master/pic/3.png)  

當有一方五子連線:  
> 顯示誰贏，並結束程式  
![start](https://github.com/Zane2453/Socket-Cplus-Gobang/blob/master/pic/4.png)  

判定勝利方式:  
> 不只直的連線，橫的或鞋的連線皆可  
![start](https://github.com/Zane2453/Socket-Cplus-Gobang/blob/master/pic/5.png)  

防呆:  
> 輸入1~20以外的範圍會出現”Out of range”  
![start](https://github.com/Zane2453/Socket-Cplus-Gobang/blob/master/pic/6.png)  

> 輸入A～T或a～t以外的字母會出現”Illegal character”  
![start](https://github.com/Zane2453/Socket-Cplus-Gobang/blob/master/pic/7.png)  

> 輸入已下過的位置會出現”Here has a piece”  
![start](https://github.com/Zane2453/Socket-Cplus-Gobang/blob/master/pic/8.png)  

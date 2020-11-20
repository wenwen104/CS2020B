# 1.觀念題與簡答題
```
::簡單說明底下重要觀念:
為強化學生對專業英文的學習，本次考試部分試題採英文命題，學生可以用中文作答

學習目標:本試題旨在訓練學生以 自己清楚的重點  說明 表達   對  某些觀念 的 認知。

答題架構:答題以  清楚簡單  為主,每一個主題或名詞請列  三~五點  重點
```

## 範例題目
```
CSS
```
### 範例參考解答:
```
1.CSS英文全名為Cascading Style Sheets
2.CSS是用來指定網頁上的內容在瀏覽器中將會如何顯示
3.網頁開發人員會使用 CSS 來指定色彩、位置、對齊方式、字型、背景圖片等屬性
```

# 期中考題目
```
1. bandwidth與 bps[相關題]
2. RFID
3. NFC
4. cellular network4
5. technology addiction
6. Crowdsourcing vs Crowdfunding[比較題]
7. metadata
8. CMS
9. DDos Attack
10. Botnet
11. RWD
12. SEO
```
### 用簡單的 自己理解 的 話 說明觀念
```


# 2.問答與申論題 :OSI Model 與 TCP/IP protocol
```
本題須清楚簡述底下主題:
1. 解釋 communication protocol(簡稱協定 protocol)

在任何物理媒介中允許兩個或多個在傳輸系統中的終端之間傳播資訊的系統標準

2. Why Layering? (為何要分層 ?)

目的是利用層次結構可以把開放系統的資訊交換問題分解各層可以根據需要獨立進行修改或擴充功能

3. 列出 OSI Model 與 TCP/IP protocol對應圖
   註 1: 需用中英文寫出各層的名稱
   註 2:須說明 OSI Model每一層的簡略功能
   
   https://giboss.pixnet.net/blog/post/26798748
   
應用層（Application Layer） 提供為應用軟體而設計的介面 例如：HTTP、HTTPS、FTP
表達層（Presentation Layer）數據轉換為能與接收者的系統格式相容並適合傳輸的格式
會議層（Session Layer） 負責在數據傳輸中設定和維護電腦網路中兩台電腦之間的通訊連接
傳輸層（Transport Layer）
網路層（Network Layer）
資料層（Data Link Layer）
實體層（Physical Layer）




4. 簡述 下列協定的功能 與特色並說明它們 運作在 TCP/IP的哪一層?
   (1)HTTP vs HTTPS (2) TELNET vs SSH (3)DNS (4)IP (5)ICMP
   
   
telnet：Telnet程式來連線到遠端伺服器並輸入帳密讓使用者可以遠端控制主機。因為傳輸的資料並未加密所以容易遭到竊取
SSH：是在不安全的網路上進行安全遠端登入和其他安全網路服務的協定(RFC 4251)，SSH由三個主要協定組成








5. TCP vs UDP
[1]英文全名   
```
Transmission Control Protocol   vs     User Datagram Protocol 

```
[2]須說明 reliable(可靠) vs un-reliable(不可靠)   
```
TCP是雙向傳輸 UDP是單向.TCP傳送東西.會有封包數據.
```
[3]如何達到reliable(可靠)           
```
他可靠性高UDP可靠性低.傳送東西速度快。
```
[4]Three-way handshaking機制 
```
 A =發出請求 > B

 A <回復+請求= B

 A  發出回復   B
```
6.簡述下列網路設備  主要功能 與 特色 及 運作在 OSI哪一層
(1) Hub vs Repeater
```
Hub

集線器 / 實體層 / 集線器上所有的連接埠都是共享一個頻寬 / 集線器的功能只是單純的把封包送到每一個連接埠上，並不會將封包過濾和導向

Repeater

增益器 / 實體層 / 一個可擴大訊號或重新建立訊號的機器 / 
```
(2)Switch vs Bridge
```
Switch 

資料層 / 每一個連接埠的頻寬都是獨立的 / L2交換機並不具備IP路由功能

Bridge

資料層 / 用來連接兩個相同協定網路的設備 / 主要功能在決定是否要讓資料通過橋接器，到另外一端的網路上，橋接器會檢查資料的起始位址與終止位址是否屬於同一個網路
```
(3)Router vs L3 Switch

Router

資料層 / 主要功能 適時選擇最佳的資料傳輸路徑 / 考慮頻寬、線路品質、使用人數等因素，選擇出最好的路徑

Switch

網路層 / L3 的交換器又稱為 IP Switch 或 Switch Router /
```
(4)Proxy

網路層 / 一種特殊的網路服務，允許一個客戶端通過這個服務與另一個網路伺服器進行非直接的連接
```
7.簡述下列 簡述下列 address(位址 )的意義 與定義 在 OSI Model哪一層
(1)PORT address

傳輸層 / 通常需要指定埠號 / 客戶機可以按照伺服器IP與埠號與相應的伺服器行程建立網路連接

(2)IP address

網路層 / 任務僅僅是根據源主機和目的主機的位址來傳送資料

(3)MAC address

資料層 / 提供定址及媒體存取的控制方式，使得不同裝置或網路上的節點可以在多點的網路上通訊，而不會互相衝突

```

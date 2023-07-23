面試職缺：DBA
面試人員：William
## 管道
linkedin 看到釋出招聘，原先限制是 HK 地區。透過裡面的朋友詢問， base 台灣也可以，請他幫忙內推。
但中間等了很久之後，某一天突然 HR 從 WtahsApp 上聯繫我，和我約面試時間。（當下就約明天的時間，說實在都沒時間準備複習ＱＱ）

## 2023/07/17 13:30~14:00 casual meeting
因為擔心自己英文不夠好，所以一開始有先和 HR 提過這塊。HR 很貼心的安排這場臨時的 call，主要是給我一些英文上的 tips，然後試著和我用英文對話測驗看看，並且幫我跟面試官那邊打個照會這樣。
還順便介紹了一些該 team 的管理模式和風格，我覺得蠻不錯的～

## 2023/07/17 18:30~20:00 面 - DBA teammate *2 + line manager *2
DBA 隸屬於 devops 底下，兩位 DBA 都是中國人，base 在深圳，不會英文。
line manager 兩位都是香港人，其中一位只會講英語但聽得懂中文，另一位不太會中文但還能說，所以他也是盡量用中文和我說。

首先要求自我介紹，中英文都可以，我其實準備了英文版，但當下還是怯場了，選擇用中文。
接著就開始技術面試
1. Btree 和 B+tree 的原理與差別
2. MySQL 聚簇索引和非聚簇索引的差別
3. MySQL MVCC 的原理
4. MySQL redo/undo 分別是做什麼用的
5. MySQL Innodb 四大特性有哪些
6. MySQL 四種隔離級別有哪些，分別解決哪些問題
7. MySQL GTID 的原理，mysiam/innodb 是否都支援 GTID
8. MySQL 主從同步有哪些？請分別詳述異步複製、半同步、增強半同步、全同步、組提交等所有同步方式與差異
9. mysiam 和 innodb 的差異
10. 關於 sql tuning，你們都怎麼做？
11. 有哪些情況下不會用到索引
12. 請詳述 raft 的原理
13. 請詳述 AWS Aurora 的架構
14. AWS Aurora 的 failover 是基於什麼樣的條件觸發，以及如何選擇要用哪個節點作為新的 master
15. AWS Aurora blue/green deployment 的原理是什麼
16. 針對 db 版本升級，如何做到 zero downtime
17. 你們都怎麼管理 DB，是否有 audit/review 的流程
18. 你們用 MySQL 哪些版本？會調整哪些參數？在規格調整時，AWS 都會自動根據算法調整一些連接參數，為何你們要手動去調整？原因是什麼
19. 對 cockroachdb 的理解

軟實力相關：（這邊基本都是 line manager 提問環節，都是英文）
1. 請問你認為 DBA 是什麼或者怎麼樣才是一個好的 DBA
2. 生涯中有沒有曾經犯下甚麼錯令你印象深刻或是什麼事蹟令你印象深刻
3. 你為什麼想離開 BN 和加入 crypto.com，你的 career path 是什麼情況？

我提問：
Q:過去兩年監管的不確定性讓這產業備受打擊，公司未來短中長期計畫有哪些?是否有雄心來拓展市占率
A:商業機密，無可奉告

Q:目前 dba 團隊有多少人？db 規模有多少，用了哪些種類資料庫？平常你們是怎麼樣管理這些資料庫的？
目前兩位 DBA，原先有三個，都掛在 devops 底下。DB 規模約 150個 pg 集群，其他像是 tidb, es, redis 等等。但每個 DBA 負責的業務項目不同，能碰到的 db 也不同。大部分是 Aurora pg
（其他細節記不太清楚了）

Q:對於新夥伴和整個 DBA team 的期望?以及組織未來的方向?
A:希望可以獨立自主作業，三個人平均分工，回到以前他們習慣的工作模式。（組織未來等因為用英文我聽不太明白）

Q:您會如何形容公司的文化和團隊的工作氛圍?以及考績怎麼打？
A:自由且會自我負責，然後不知道為何就開始講一些跟這題無關的敘述，主要就是一直問我在意哪一點，為何要離開 bn 等等


心得：
面試的當天工作很忙，加上前一天才約了這個時間，所以沒有充裕的複習。加上本來預期對方都是 pg，應該會問些非 MySQL 的題目，沒想到準備錯誤..QQ
整體來說技術面試這一環很慘，用膝蓋想也知道沒過了。至於英文本身也是講的2266，但好歹是撐過去了。之後可能要重新回憶下底層技術然後英文練好一些～
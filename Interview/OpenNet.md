# OpenNet
台灣的博弈公司，沒記錯以前是中資的，後來被英國 sporty 買下來，專做非洲市場。HR Freya 在 linkedin 上主動連繫我進行面試

## hackrank
面試前，會給予一份 DBA考題，使用 hackrank 作答。題目不算難，大概十多題。但給的時間不算特別充裕


## 第一面 面試時間 - (因為後來有加面，所以這算第一面)
```
Interview details-
Date: 2025. 9/1 (Mon)
Schedule: 14:00 - 16:00 (This will be adjusted by the interview situation.)
Interviewers: DBA Members, Lead, and HR (There will be 2-3 technical sessions.)
https://meet.google.com/rdn-nujf-jrm?authuser=0&hs=122

實際花了將近 2.5小時，分成三關
第一關是 member alan、tony
第二關是歐洲 team 的 Usman(德國人，這時候要用英文面試)
第三關是 Jack（就是 devops + dba leader，目前 dba 由他暫時帶領）
```

一樣先自我介紹，然後針對我的自介和履歷問問題，基本圍繞在技術實作交流，我只記得一部分，不太記得全部問了哪些
1. 對於 db 升級是怎麼做到 zero downtime
2. 對於 data archive 都怎麼設計和計畫
3. db password 的 ratate 是怎麼做的，如何結合 secret manager
4. 大表分庫分表怎麼做?有沒有再擴容的經驗?遇到那些困難?
5. 大表操作 ddl 怎麼做? ghost 和 ptosc 的差異是什麼，優缺點又是什麼
6. 對於 auto scaling 的設計和想法
7. 有沒有用過 rds proxy 或 proxysql


## 我問的問題包括：
### 技術層面
1. 這裡資料庫用了哪些? 規模如何?例如實例數量、QPS、TPS 有多高? DBA 團隊目前的狀態如何?有多少人，怎麼分工?你希望這位新來的 DBA 能為團隊帶來什麼幫助?
2. 你們是否有使用過 Docker 和 Kubernetes 管理資料庫?或是用雲還是地端?
3. 你們對於資料庫管理的自動化是怎麼做的?譬如創建 db、modify db、 sql deploy, 監控, 備份還原等

### 其他面向
1. 從 DBA 的角度來看，你認為 DBA 如何幫助公司達到更好的發展?
2. 你們選人的標準是怎麼樣的?
3. 與其他地方相比，在 opennet 工作有哪些優勢讓你想繼續在這裡工作? (這個我問的是 Usman)
4. 你們的團隊文化是什麼樣的?例如工作氛圍、團隊合作等
6. 博弈市場瞬息萬變，公司對於技術創新和市場變化的應對策略是什麼?公司接下來幾年的短期目標是什麼？長期目標是什麼?


## 第二面 面試時間 - (後來加面)
```
Interview details-
Date: 9/17 (Wed) 
Schedule: 15:00 - 15:40
Interviewer: Senior 
```
與 Director 比較像聊聊天，人感覺很 nice，專注在一些技術面上的架構經驗分享，還有對於 leadership 的討論。我也同步問了些問題
1. 你們目前在資料庫管理方面面臨的最大挑戰是什麼?未來有什麼計劃來解決這些挑戰?
2. 你對於 dba team 的期望是什麼?以及你覺得 DBA TEAM 的核心價值是什麼?
3. 你希望我加入之後能為團隊做出什麼樣的貢獻
4. 對你來說，現在技術團隊的整體目標或方向是什麼?
5. 能否分享你是如何當上 CTO 的歷程?
6. 博弈市場瞬息萬變，公司對於技術創新和市場變化的應對策略是什麼?公司接下來幾年的短期目標是什麼？長期目標是什麼?

## 總結
Hr 我覺得蠻專業，在來回溝通也很人性，不會死板的照紙上規則。團隊兩次加起來四關的面試也都挺愉快，沒有任何感受不尊重的情況(比大陸人好太多了)。
整體數據量在台灣應該算很大的，聽說整體到了 PB 級別，目前有十多位 DBA，但從側面消息聽說這個 team 很不團結，進去可能需要花很長時間整頓。


offer get, staff level, fully remote, 有機會可以當 leader，leader 的薪酬級距更高。目前 staff level 的月薪和我在 binance 現職基本持平，沒有漲幅，單看稅後的話領得更少些。
合約上保 13，每一季有季獎金(通常是0.5~1個月)，平均整包通常落在 17個月左右。 如果可以拿到5,6個月，那就不會輸 Binance 太多。
我是第一位談 fully remote 的，未來這個政策是否能繼續實施不曉得，有風險。

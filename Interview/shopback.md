面試人員：William
## 2021 shopback 第一階段前測 - 限期一週
#### 完成後對方回信說約 5-7days 會給回覆，實際上兩天後就收到回信約一面了
ShopBack DBA/SRE homework. 

MongoDB (https://www.mongodb.com/) is a well-known NoSQL database. As a DBA, you got a mission to deploy a new mongodb cluster in an AWS environment. Assume that mongodb cluster has 1 primary + 2 secondary nodes. Also we can assume the scale of data-size won’t be extremely huge. 

Please workout 
- (a) a deployment plan and deployment script 
- (b) a maintenance plan, including backup/restore script. 
- (c.a ) feel free to add anything you believe should have in plan if you are the DBA and this cluster needs to be long term maintenance by you. 

Notes: 
- (1) Your document, script, plan need to put in git and this homework result need to send via a git-bundle file (https://git-scm.com/docs/git-bundle) 
- (2) You can use tools (for example ansible, terraform)


## 2021/06/09 一面 - DBA teammate (週三) 上午10點 - 下午12:30 
Interview agenda: 
10:00-11:30  Tech interview: Thomas, Lisa
11:30-12:30  Manager interview: Lisa, Tao-sheng

首先要求自我介紹<br>

1. 你們 mysql 節點數量有多少、qps 多少、架構是什麼、備份還原怎麼做？
2. 對 AWS 熟悉嗎，是否使用過 RDS 或 DBsaas？
3. Redis 的備份原理
4. Redis RDB 與 AOF 的差異，該如何搭配使用或何時適合使用哪一種備份方式？
5. MongoDB 的 sharding 和 replica 差異
6. MongoDB sharding 的好處與潛在問題點有哪些？
7. 假設你要替一個連鎖圖書館 (如台北市立圖書館或高雄市立圖書館) 設計系統，以用來記錄圖書和讀者借閱資訊。請設計 db schema 和 ER model
8. 承上題，如果要擴展成全國各地的圖書分館，但為了讀者的方便和便於管理，因此大家都一起採用這個系統。那你會如何修改 schema
9. 承上題，如果我們預計使用者5000位，書籍數量500000本，請問基於你設計的 db schema，需要多少容量的硬碟

到這邊後技術問題差不多都結束了，Thomas 先離開，剩下主管 Lisa。<br>
接下來本來預計會換 vp 進來聊天，結果似乎人在開會，變成我和 Lisa 隨意聊天。<br>
兩邊互相交流的問題大概如下
1. 你們團隊都怎麼分工
2. 未來職涯規劃
3. 如果加入 shopback，你有什麼想做的事情嗎
4. 使用 aws rds 有遇到哪些問題
其他沒印象了

## 2021/6/18 二面 - engineering VP
針對團隊目前要做的事情 & SRE接下來的任務跟做一些討論跟分享~
並讓我提問
1. shopback 目前除了亞洲市場，有打算擴大到其他地方嗎？
2. 除了現金回饋，有沒有其他的獲利方式？
3. 您期望 DBA 帶來的價值是什麼？
4. 未來是否有可以調派國外的機會？
5. 對於 DB 技術架構的改善或調整，DBA 是否有權力主導？
6. 對於招募流程相對其他公司花費較長時間的原因是什麼？
其他的細節差不多都忘了，但有一句話我很深刻
VP 說這邊的薪水不會是業界最高的，但是進來的人基本上都不會後悔。
聽起來好像是工作氛圍與發展性不錯吧～

## 其他福利或特點
1. 每週四 wfh 
2. 可以在辦公室打桌球XD

## 整體心得
每一關面試都是視訊面試，要開鏡頭<br>
薪資確實不高，保障年薪 + signon bonus + 股票配額約 230萬，不過幾乎都綁1~3年不等的時間，個人不太喜歡被綁約的感覺。<br>
目前台灣沒有 DBA，我如果進去會是第一位，歸屬在 SRE Team，可以學到相關技能，其餘 DBA 散落在新加坡和日本。<br>
從接觸到前測，最後面試結束，拿到 offer。總共花了一個月的時間，整體面試時間拉得較長，如果有心想來的話，這點要有心理準備。中間過程都和 HR 用 line 溝通，包含談薪資也是，不會額外花時間 meeting。人很 nice，有問題或需求都可以透過 HR 得到解答。<br>
整體來說蠻不錯的，如果不是因為綁約而且想找 wfh 的職缺，可能我那時候就會去了。

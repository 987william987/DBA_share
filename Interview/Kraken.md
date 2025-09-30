# Kraken 海妖交易所
世界排名前十的交易所，是真外商，去年投過一次沒得到回覆，今年再投了一次拿到了面試機會<br>
Interview with Kraken - 2025-03-12 (週三) 下午5點 - 下午5:45 (GMT+8) <br>
面試會開鏡頭且錄影，所以不要做一些奇怪的事情

## Self Introduction
全英文面試，需要準備英文的自我介紹

## 面試官提問
基本上問題都不難，但因為全用英文很緊張，所以題目大部分都忘記了，只記得有這些
1. slow query 如何優化，explain 如何使用，執行計劃如何分辨好壞
2. 解釋 sync_binlog 和 innodb_flush_log_at_trx_commit 兩個參數的涵義和差別
3. 是否使用過 k8s or container 管理 db
4. 在申請職位時，會有一道題目，是關於如果P0 DB crash，每 downtime 一秒，公司就會損失很多錢，請問你會怎麼處理?  面試官會針對這個問題詢問面試者為什麼這麼做

最重要的是 kraken 很重視工作文化和 crypto 熱忱，他們的官網有一篇露露等的文章在講述這塊 https://www.kraken.com/zh-cn/culture <br>面試時也問到了這些相關問題，例如你對我們的文化哪裡有共鳴?哪裡不清楚?那裡跟你契合等等等

## I ask questions:
1. What is the scale of MySQL here, such as how many instances and how high the QPS is. What is the current status of the DBA team? and how many people are there? What kind of help do you hope this new DBA can bring to the team? 
2. Does DBA only focus on MySQL? Can we work with other databases?
3. What is your experience with managing databases with Docker and Kubernetes?
Based on my previous experience, the advantages of containers are fast deployment, update, and expansion. But using containers to manage MySQL is not very stable, and I remember that the support for statefulset is not very high.
4. From the dba side, how do you think that DBA help the company achieve better development?
5. What will the next interview process be like?
6. What are the advantages of working at Kraken compared to other places that make you want to continue working here?

## 結論
沒有通過蠻可惜的。面試官人很好，即使我有些東西聽不懂，他都會有耐心地重複或者打字給我看，單論技術問題而言，第一面題目都非常簡單，沒有任何答錯的可能性。但我覺得就差在英文能力不夠好，以及對於 crypto 的理念沒有和他們很契合吧。他們是熱衷於 crypto 的技術者，而我只是想賺錢而已哈。如果能進去的話應該很不錯，推薦大家去試試看

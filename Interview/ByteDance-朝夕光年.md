面試人員：William

## ByteDance 朝夕光年
字節跳動的遊戲部門公司，之前嚴重裁員過，新加坡 onsite，目前沒有專門的 DBA，只有 sre 代管，專注使用 mongodb

```
Interview Details:​
Position: Database Administrator - Game​
Interviewer: Kevin Xiao- SRE Team Lead​
Interview Duration: 45 mins​
Interview Date and Time: 2025-02-20 10:00, (GMT+08:00) China Standard Time - Beijing​
```

## 我問的問題
1. 這邊 mongodb, redis 的量級有多少，譬如多少實例，多大的 qps。目前是誰在負責數據庫，以前是否有專門的 dba
2. 組織架構是怎麼樣的。這個職位的工作是以新加坡為主 還是和大陸那邊的 dba team 合作? sre team, dba team 的概況，以及未來還會擴充人手嗎
3. 能否接觸其他 sre 的工作內容，例如 k8s, cicd 等等
4. 希望這個職位可以對團隊帶來什麼樣的幫助
5. 朝夕光年的未來發展，以前裁員很嚴重，現在有什麼優勢吸引人才


## 面試官提問
1. 請面試官先自我介紹
2. 你打遊戲嗎?玩什麼遊戲
3. 為什麼遊戲行業都用 mongodb
4. mongodb 跟 MYSQL 哪個快?或者什麼場景下哪個快?為什麼?
5. mongodb 和 mysql 的 b+ tree 各自怎麼實現的?兩者差異在哪裡
6. 詳細說明 mongodb 主從複製原理，線程還是進程，主跟從各自做什麼，oplog 扮演的角色
7. 情境題: mongodb 上線前做過壓測，性能沒問題。上線後兩三個月，業務反饋系統卡了，請問是什麼問題，具體排查思路為何?
8. 情境題: 業務反饋服務查詢 mongodb 一直超時，請問是什麼原因，具體排查思路為何?
9. 詳細說明 redis 主從複製的原理，主跟從怎麼做的複製，以及 cluster 的原理為何?
10. redis cluster 主要解決了什麼問題，cluster 規模限制嗎?有的話是多少
11. 你之前運維 mongodb, redis 有遇到什麼困難，怎麼解決的

## 結論:
大陸人面試實在不友善，總是想要打破砂鍋問到底，把你問到回答不出來就是他贏了這樣

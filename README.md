2014_nkfust_oose_3B_11
======================
|資管3B 組員:|分配工作|
|------------|--------------|
|0124044 李亞駿|使用案例圖、循序圖|
|0124068 林士瑋|活動圖、各事件合約|
|0124070 許程翔|架設Github、類別圖|
|0124082 張鈞復|個別使用案例的描述、使用案例英文名稱對應|



專題名稱:自動派車系統
======================
跟朋友一起出去玩時，走在路上想要去下個景點，可是當我們要叫計程車時，計程車說他們說要等30分鐘後車才會到，當下想說要等那麼久，那我們可不可以做一個可以聯絡最近的計程車的APP
  
自動派車系統基本需求描述
======================
自動派車需要使用到GOOLE MAP的距離計算，當公司接收到顧客經由APP所傳遞的客戶資訊（包括詳細候上車地點、姓名、電話等）時，須立即藉由Google Map得知該地點的路況，並由總公司直接發派最接近顧客候車地點的計程車司機，再將顧客的資訊通報給該計程車司機，由該司機聯絡本次使用APP系統叫車的顧客

利害關係人目標表
======================
|業務人員|
|------------|--------------|
|建立客戶基本資料|
|進行客戶位置的分析|
|處理車單的建立、修改與取消|
|管控所有計程車的現況|

|顧客|
|------------|--------------|
|使用APP系統叫車，並輸入系統要求的資訊|
|針對自己需求更改或取消叫車|
|短時間內計程車司機將會聯繫上，並送往目的地|

|計程車司機|	
|------------|--------------|
|與業務人員交互映照、使效率更佳|
|因應公司要求在最短時間內抵達顧客要求地點|

系統事件表
======================
|事件名稱|使用案例名稱|
|------------|--------------|
|1. 建立與修改客戶資料|1.客戶基本資料作業|
|2. 能夠進行客戶特性分析|2.客戶所在區域分析作業|
|3. 顧客叫車服務|3.叫車作業系統|
|4. 取消或修改叫車服務|4.取消或修改叫車系統|
	

使用案例之階段
======================
|第一階段:|
|------------|--------------|
|1.客戶基本資料作業|
|2.計程車輛資料管理作業|
|3.處理叫車記錄|

|第二階段:|
|------------|--------------|
|1.派車作業|
|2.取消叫車作業|

|第三階段：|
|------------|--------------|
|1.未派車車輛管理作業|

|第四階段：|
|------------|--------------|
|1.評估派車與車單處理作業|
|2.營運分析作業|

|第五階段：| 
|------------|--------------|
|1.客戶特性分析作業|
|2.取消派車與未派車車輛分析|

使用者案例圖
======================
![](http://i.imgur.com/40EMBT2.png)
個別使用案例的描述
======================
![](http://i.imgur.com/igsqPcf.png)
![](http://i.imgur.com/OZrnZvM.png)
![](http://i.imgur.com/hfIiDRh.png)
![](http://i.imgur.com/QjXlc3q.png)
活動圖-客戶基本資料作業
======================
1.客戶基本資料作業-活動圖
![](http://i.imgur.com/2dLGwxW.png)
2.客戶所在區域分析作業-活動圖
![](http://i.imgur.com/igfPOlT.png)
3.叫車作業系統-活動圖
![](http://i.imgur.com/vTYJmEc.png)
4.取消或修改叫車系統
![](http://i.imgur.com/FVtbhwV.png)
使用案例的名詞與概念類別列舉表
======================
|客戶基本資料作業類別列舉表|||
|------------|--------------|----------------|
|名詞|原因|結果(是否為概念類別)|
|業務人員|本系統需要建立客戶的基本資料|是|
|客戶|本系統需要由客人使用|是|
|客戶資料|本系統記錄客戶的基本資料|是|
|使用紀錄|客戶屬性|否|
|帳號|客戶資料屬性|否|
|密碼|客戶資料屬性|否|
|客戶名稱|客戶資料屬性|否|
|地址|客戶資料屬性|否|
|電話|客戶資料屬性|否|
|員工編號|業務人員屬性|否|
|姓名|業務人員屬性|否|

|客戶所在區域分析作業類別列舉表|||
|------------|--------------|----------------|
|名詞|原因|結果(是否為概念類別)|
|業務人員|本系統需要分析客戶使用分佈區域|是|
|客戶|本系統需要客人使用記錄|是|
|客戶資料|本系統需要客戶資料內的地址|是|
|使用紀錄|客戶屬性|否|
|帳號|客戶資料屬性|否|
|密碼|客戶資料屬性|否|
|客戶名稱|客戶資料屬性|否|
|地址|客戶資料屬性|否|
|電話|客戶資料屬性|否|
|員工編號|業務人員屬性|否|
|姓名|業務人員屬性|否|



|叫車作業系統類別列舉表|||
|------------|--------------|----------------|
|名詞|原因|結果(是否為概念類別)|
|客戶|本系統需要填入訂單內容|是|
|車單|本系統需要知道訂單內容|是|
|帳號|客戶資料屬性|否|
|密碼|客戶資料屬性|否|
|客戶名稱|客戶資料屬性|否|
|地址|客戶資料屬性|否|
|電話|客戶資料屬性|否|
|車單編號|訂單屬性|否|
|叫車日期|訂單屬性|否|
|叫車地點|訂單屬性|否|
|人數|訂單屬性|否|
|司機|本系統需要司機|否|

|取消或修改叫車系統類別列舉表|||
|------------|--------------|----------------|
|名詞|原因|結果(是否為概念類別)|
|業務人員|本系統需要業務人員批准取消|是|
|客戶|本系統需要取消訂單內容|是|
|車單|本系統需要取消訂單|是|
|帳號|客戶資料屬性|否|
|密碼|客戶資料屬性|否|
|客戶名稱|客戶資料屬性|否|
|地址|客戶資料屬性|否|
|電話|客戶資料屬性|否|
|車單編號|訂單屬性|否|
|叫車日期|訂單屬性|否|
|叫車地點|訂單屬性|否|
|人數|訂單屬性|否|
|員工編號|業務人員屬性|否|
|姓名|業務人員屬性|否|


客戶基本資料作業-初步類別圖

![](http://i.imgur.com/1uvLzgb.png)

客戶所在區域分析作業-初步類別圖

![](http://i.imgur.com/EMVOGsv.png)

叫車作業系統-初步類別圖

![](http://i.imgur.com/NorM84k.png)

取消或修改叫車系統-初步類別圖

![](http://i.imgur.com/dZCthCY.png)

系統初步類別圖

![](http://i.imgur.com/GND0gm7.png)

使用案例主要成功情節之英文名稱事件對應
======================
![](http://i.imgur.com/BPT6yTd.png)
![](http://i.imgur.com/ym2jcoU.png)
![](http://i.imgur.com/TPfAlVz.png)
![](http://i.imgur.com/Ycxi5gE.png)

各事件之合約
======================

|合約1：inputOrder()|
|------------|
|操作：inputOrder()|
|交互參照：客戶基本資料作業、客戶所在區域分析作業、叫車作業系統、取消或修改叫車系統|
|前置條件：存在類別Order之實例newOrder|
|後置條件：給定inputorder之屬性CustomerData最新顧客編號|
|　　　　　回傳CustomerData|

|合約2：getCustomer()|
|------------|
|操作：getCustomer(customerID,customerName,customerPhone,customerAdress)|
|交互參照：客戶基本資料作業、客戶所在區域分析作業、叫車作業系統、取消或修改叫車系統|
|前置條件：存在類別CustmerData之實例newCustmerData|
|後置條件：確認欄位customerName、customerPhone、customerAdress為空白|
|　        將customerName、customerPhone、customerAdress存入CustomerData|
|　　　　　回傳CustmerData|


|合約3：saveOrder()|
|------------|
|操作：saveOrder(orderRec)|
|交互參照：客戶基本資料作業、叫車作業系統、取消或修改叫車系統|
|前置條件：存在類別Order之實例newOrder|
|後置條件：將orderRec存入Order|
|　　　　　回傳Order|


|合約4：saveCustomerOrder()|
|------------|
|操作：saveCustomerOrder (customerRec)|
|交互參照：客戶基本資料作業|
|前置條件：存在類別CustmerData之實例newCustmerData|
|後置條件：將customerName、customerPhone、customerAdress存入CustomerData|
|　　　　  回傳CustmerData|


|合約5：modifyCustomer()|
|------------|
|操作：modifyCustomer(customerID,customerName)|
|交互參照：客戶基本資料作業|
|前置條件：存在類別CustmerData之實例newCustmerData|
|後置條件：確認customerID、customerName已存在資料|
|          將(customerID、customerName修改後存入CustomerData|
|　　　　　回傳CustmerData|


|合約6：checkItem()|
|------------|
|操作：checkItem(customerItem)|
|交互參照：客戶基本資料作業|
|前置條件：存在類別Order之實例newOrder|
|後置條件：確認檢查customerItem後存入Order|
|　　　　　回傳Order|


|合約7：deleteCustomer()|
|------------|
|操作：deleteCustomer(customerID,customerName)|
|交互參照：客戶基本資料作業|
|前置條件：存在類別Order之實例newOrder|
|後置條件：確認customerItem與已存在資料相符|
|　　　　　回傳Order|


|合約8：deliverNearestDrivers()|
|------------|
|操作：deliverNearestDrivers(customerID,customerAddress,customerPhone)|
|交互參照：客戶所在區域分析作業|
|前置條件：存在類別DNData之實例newDNData|
|後置條件：將customerID、customerAddress、customerPhone存入DNData|
|　　　　　回傳DNData|


|合約9：checkOrderItem()|
|------------|
|操作：checkOrderItem(orderItem)|
|交互參照：叫車作業系統|
|前置條件：存在類別Order之實例newOrder|
|後置條件：確認orderItem與已存載資料相符|
|　　　　　回傳Order|


|合約10：addCarPeper()|
|------------|
|操作：addCarPeper(customerAddress, customerTime)|
|交互參照：叫車作業系統|
|前置條件：存在類別Order之實例newOrder|
|後置條件：確認customerAddress、customerTime為空白|
|　　　　　將customerAddress、customerTime存入Order|
|　　　　  回傳Order|


|合約11：modifyOrder()|
|------------|
|操作：modifyOrder(orderID)|
|交互參照：叫車作業系統、取消或修改叫車系統|
|前置條件：存在類別Order之實例newOrder|
|後置條件：確認customerAddress、customerTime與已存載資料相符|
|　　　　　將customerAddress、customerTime修改後存入Order   |
|　　　　　回傳Order                                        |


|合約12：deleteOrder()|
|------------|
|操作：deleteOrder(orderID)|
|交互參照：取消或修改叫車系統|
|前置條件：存在類別Order之實例newOrder  |
|後置條件：確認orderID不為空白          |
|          將orderID、orderItem存入Order|
|　　　　　回傳Order                    |

循序圖
======================
![](http://i.imgur.com/wU9lQhF.png)


叫車作業系統循序圖
![](http://i.imgur.com/pIupMoL.png)


取消或修改叫車系統
![](http://i.imgur.com/Z2H72wl.png)

強韌圖
==============================================
![](https://fbcdn-sphotos-h-a.akamaihd.net/hphotos-ak-xpf1/v/t34.0-12/10743682_797953976929268_633728098_n.jpg?oh=8784d86821b7f8d937d9b7f464f3e83a&oe=54800922&__gda__=1417674431_e6e41a6f6aa0494792bbec8a2a208375)
![](https://fbcdn-sphotos-h-a.akamaihd.net/hphotos-ak-xpf1/v/t34.0-12/10816156_797953980262601_893969816_n.jpg?oh=b9f57265757c0a2bf8f0fb1e8267fdd7&oe=548023A4&__gda__=1417615609_9f2fb3c729fd341f408c5aafc27b9beb)
![](https://fbcdn-sphotos-h-a.akamaihd.net/hphotos-ak-xpa1/v/t34.0-12/10846772_797953983595934_77421984_n.jpg?oh=3b5820fb4861bdd809ed48552d341e6a&oe=547F30DE&__gda__=1417678853_b94c0be525d5548d2bdb3d5c21f2c9d6)
![](https://fbcdn-sphotos-h-a.akamaihd.net/hphotos-ak-xpf1/v/t34.0-12/10815936_797953986929267_102359807_n.jpg?oh=03c2a2f21a2e8301431dfed1c9cf278a&oe=5480279D&__gda__=1417608704_ff00350ace77f254f51be858c7165838)

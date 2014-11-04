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
![](https://fbcdn-sphotos-h-a.akamaihd.net/hphotos-ak-xpf1/v/t34.0-12/10301368_753050854772893_3585117902562920556_n.jpg?oh=5514f6baedcb510e1d25eb3cec94de84&oe=545998A2&__gda__=1415146909_29032f399dfeef9716c592058b93a5cc)
個別使用案例的描述
======================
![](https://fbcdn-sphotos-h-a.akamaihd.net/hphotos-ak-xpf1/v/t34.0-12/10744732_945384132196553_855379313_n.jpg?oh=6729eb59309b9c8390054a018935027e&oe=545B0FF6&__gda__=1415203947_cc0afc2acd9964f6cc9f454ca488a952)
![](https://fbcdn-sphotos-h-a.akamaihd.net/hphotos-ak-xpf1/v/t34.0-12/10744868_945384135529886_194626323_n.jpg?oh=aa88088d02bc31fb271f3c65de29c681&oe=545B0DA0&__gda__=1415272893_b839daaa55b6fe24504d56b14c376017)
![](https://fbcdn-sphotos-h-a.akamaihd.net/hphotos-ak-xpf1/v/t34.0-12/10751890_944647558936877_267258599_n.jpg?oh=00e34000f357ce5d87cb8e52e8ba5da8&oe=545774AF&__gda__=1415072050_1363fbcdeb9356abcb85632f515e45fa)
![](https://fbcdn-sphotos-h-a.akamaihd.net/hphotos-ak-xpf1/v/t34.0-12/10744782_945384125529887_227518688_n.jpg?oh=0d0f36f91391337ba8350f2ef05b5b8f&oe=54530765&__gda__=1414725048_22a889d73ced6da8ad9fb29fc0c56aec)
活動圖-客戶基本資料作業
======================
1.客戶基本資料作業-活動圖
![](https://fbcdn-sphotos-h-a.akamaihd.net/hphotos-ak-xpf1/v/t34.0-12/10744648_775852315806101_1077125425_n.jpg?oh=9c167c8913a99ccdba4ead7f78f98ecf&oe=5458BAD8&__gda__=1415089096_f5407e69b309591ab21865dccac9458f)
2.客戶所在區域分析作業-活動圖
![](https://fbcdn-sphotos-h-a.akamaihd.net/hphotos-ak-xpf1/v/t34.0-12/10735701_775852325806100_560374341_n.jpg?oh=49360182e3e2406b00e1134b2c239e81&oe=5458B6F1&__gda__=1415021740_6ddb47a93ac892978162a55e8c6fd8c1)
3.叫車作業系統-活動圖
![](https://fbcdn-sphotos-h-a.akamaihd.net/hphotos-ak-xpf1/v/t34.0-12/10733478_775852322472767_721811855_n.jpg?oh=88b2cb31cd16168f1a24f03bacab3174&oe=5458BA18&__gda__=1415021317_f9dbcba455e0c1d3c438b6eb2133d817)
4.取消或修改叫車系統
![](https://fbcdn-sphotos-h-a.akamaihd.net/hphotos-ak-xpf1/v/t34.0-12/10743684_775852319139434_285452377_n.jpg?oh=14fb17c57de3f5c8c677e1895a151a67&oe=545770C5&__gda__=1415021080_a5ccdf6bd1035c7593585ee78dd00fa6)
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
![](https://fbcdn-sphotos-h-a.akamaihd.net/hphotos-ak-xpf1/v/t34.0-12/10743782_947523538649279_590238526_n.jpg?oh=c3eb7501463a61aa34d621bef976cb17&oe=545A32A4&__gda__=1415194553_c478c2a837771a8668ec4e914792d472)

客戶所在區域分析作業-初步類別圖
![](https://fbcdn-sphotos-h-a.akamaihd.net/hphotos-ak-xpf1/v/t34.0-12/10751666_947523545315945_59556177_n.jpg?oh=d8a0f0a26cfa080e73693053d4fba321&oe=5458522A&__gda__=1415080247_43cdfc849d10ff3d02152b326a8aced2)

叫車作業系統-初步類別圖
![](https://fbcdn-sphotos-h-a.akamaihd.net/hphotos-ak-xpf1/v/t34.0-12/10799638_947523548649278_981782026_n.jpg?oh=2806b7969cb004276eed35a234434499&oe=54595292&__gda__=1415068623_ba84a72462418ad74a1159c492c02009)

取消或修改叫車系統-初步類別圖
![](https://fbcdn-sphotos-h-a.akamaihd.net/hphotos-ak-xpf1/v/t34.0-12/10745099_947523541982612_1767729186_n.jpg?oh=a815ceddbf25329916684f5ec7cc11d7&oe=5458566A&__gda__=1415145082_308461b9717f18f91d5a45e8182f98e4)

系統初步類別圖
![](https://fbcdn-sphotos-h-a.akamaihd.net/hphotos-ak-xpf1/v/t34.0-12/10751832_947523551982611_350220076_n.jpg?oh=c80e5a11c2a0911df706793892333c37&oe=54582FEB&__gda__=1415070006_f2e17903b5f9670c30d8b3e4e880d4b3)

使用案例主要成功情節之英文名稱事件對應
======================
![](https://fbcdn-sphotos-h-a.akamaihd.net/hphotos-ak-xpa1/v/t34.0-12/10735793_940207232714243_472548623_n.jpg?oh=22ee51e7bbd3aeb6baaf84c2585e203d&oe=545873E9&__gda__=1415080694_5fd79f8dad71a250b85ce9f8cd3c102a)
![](https://fbcdn-sphotos-h-a.akamaihd.net/hphotos-ak-xpf1/v/t34.0-12/10736084_940207226047577_906775896_n.jpg?oh=a3e1dee323c503da01fe3db564a89280&oe=54576E69&__gda__=1415087412_e7e3e9ff0eab9fcd13e110873ce6f25c)
![](https://fbcdn-sphotos-h-a.akamaihd.net/hphotos-ak-xpf1/v/t34.0-12/10745010_940207236047576_555328707_n.jpg?oh=52d53193f11027f8b34a2cd5408a749f&oe=54585823&__gda__=1415069054_93d86ffd560b228e0457841113a4a24a)
![](https://fbcdn-sphotos-h-a.akamaihd.net/hphotos-ak-xpf1/v/t34.0-12/10743516_940207229380910_810264670_n.jpg?oh=784727ebf86f1198acf49cbf93dced56&oe=545837F7&__gda__=1415022058_5878ec161fef5cd1a5feaa4e61b3ddcf)

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
![](https://fbcdn-sphotos-h-a.akamaihd.net/hphotos-ak-xpf1/v/t34.0-12/10744856_749815001763145_1794720695_n.jpg?oh=d4816a8e105688f459e0c19831a12f3e&oe=545880A7&__gda__=1415100215_6ed22159c84db680a87c1b8afe0bd7bb)
![](https://fbcdn-sphotos-h-a.akamaihd.net/hphotos-ak-xpf1/v/t34.0-12/10745064_753115778099734_1892053540_n.jpg?oh=ce32d644d6f527beadc3207ddb27db94&oe=545A48D4&__gda__=1415199748_df1093204bf09787d1fab3920187c70a)
叫車作業系統循序圖
![](https://fbcdn-sphotos-h-a.akamaihd.net/hphotos-ak-xpf1/v/t34.0-12/10576833_753285771416068_325757141_n.jpg?oh=4bea0ecb3d826f974c3ec922762ded97&oe=545A5388&__gda__=1415268693_d882f8480718cfaae5c5e3b35796e244)
取消或修改叫車系統![](https://fbcdn-sphotos-h-a.akamaihd.net/hphotos-ak-xpf1/v/t34.0-12/10576833_753297604748218_631600088_n.jpg?oh=e020be28219f0ba0f97d52a26eb16682&oe=545B2D2F&__gda__=1415274418_8e7a47bb2bf7ba84225e571172a2a600)

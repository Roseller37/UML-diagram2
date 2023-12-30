# 火車訂票管理系統
## 第一章問題定義
### 1.1課題背景及意義
隨著我國經濟的快速發展,我國的交通運輸能力不斷提高,越來越多的國民開始走出家門來到異地進行商或旅遊等活動。在這條件下,客流量不斷增大。火車售票的管理對於交通運輸的正常運行起著至關重要的作用,而著資訊量的逐步增加,繁雜的數據處理費時費力,單純以人力進行的火車售票已經不適合現狀了。

現今的社會發展迅速,火車成為了人們在交通方面不可缺少的交通工具,乘坐火出行的人越越多,所以火車的客運量也在迅速的增長著。為了帶給人們方便快速的交通環境,火車站系統採取提高列車的速度,增加火車站列車等措施來滿足大量的旅客的乘車需求。但是,現在人多車多的情況下,如果再像從前一樣,在一個單一的地點售票,必然滿足不了現在的情況。所以就需要售票能夠在不同的地點進行。在如此的情況下,售票系統自然是相當必要的售票系統的出現能夠在很大的程度上解決單一地點售票所帶來的種種不便,並能夠使想要出行的旅客方便的買到自己需要的車票。對於售票處的地點也從原來的單一地點(火車站)變成了多個地點,可以在市内的多個地點(賓馆、酒店、娛場所等等)這樣為將要出行的旅客帶來了更進一步的方便。使旅客無論是在金錢還是在時間方面都能夠得到充分的節省。為了方便旅客,火車售票系統不只售票,還能改,退票線上操作。也就是說系統的使用者應該不只是售票員,還應該有管理員。管理員能夠透過售票系統時的更新乘車資訊。這樣才能夠使乘客避免不必要的麻煩,真正的解決以前老式售票的種種不便,才能夠真正的成為現在網路社會的真正適應者。

現在的時代是資訊產業的時代,國家把資訊產業當作了成長國民經濟重要的一環。在這樣的環境下,以先進的資訊科技進行汽車售票的管理成為了時代發展的必然。綜上所述,開發這樣一個火車聯網售票系統是相當必要的。

## 1.2研究現狀
### 1.2.1國內研究現狀
我國火站很早就利用電腦管理系統加強管理、提升服水準。我國火站的展階段主要是以電腦系統的運用為標的,電話通訊系統其實也是程控交換技術出才獲得質得飛。著電腦的普電腦科技的不斷發展,同時也使火車站管理系統發展到了一個新的時期,趨於更加完善。火車站管理系統實現了火票預定、出行、退票流程的智慧化、自動化,節省了車站的人工成本,較少了乘客的等候時間,具有簡單、便捷、私密的特點。

#### 1.2.2國外研究現狀
國外的火車站發展較為國内早了好多年,同時在多年的發展探索中,火車站的能展更加全面和多様化。火車站由一開始的單一出行站點到現在的休閒商務旅遊多方面出行,朝著更複雜功能更齊全的方向發展。隨著這些火車站的全面發展,其對火車站的管理要求也隨著提高,為了更方便地訂票,在電腦迅速展的背景下,產生了火訂票系統軟體,在很大成程度上減少了人物力和財力,也同時使車站的經營更加規範化,提高了服務的標準。

## 第二章可行性研究
### 2.1可行性研究過程
技術性方面,採用前主流的Springboot框架進行系統主體框架的搭建,實現前台頁面的設计與美觀整,以上技術,均本人經過系統學習,並且都是在課程設計中實過的,可以使得開發更加便捷和系統。從技術角度看,這個系統是完全可以實現的。

實用性方面,本次設計的主要任務是在火訂票系統内火車票預定、次搜尋、票改、個人資料修改、票票等,符合當前潮流的發展。從使用者角度出發同時也考慮系統營運成本與人力資源,採網路上的便利方式,實現線上業務,使得業務流程更有系統,也更方便使用者的體驗,較實用。

### 2.2項目在經濟上的可行性
經濟性方面,由於本課題所設計的火定票系統的主要目的是為了能夠更方便快速的進行資訊的查管理及檢索服務,也是能夠直接投入使用的資訊化軟體。系統的主要成本主要是集中在對使用資料後期繼續維護及其管理更新這個操作但是一旦系統投入到實際的運作及使用之後就能夠很好的提高資訊查詢檢索的效率,同時也需要有效的保證查者的資訊方面的安全性,同時這個火訂票系統所帶來的實際應用方面的價值是遠遠的超過了實際系統進行開發與維方面的成本,因此,從經濟上來說開發這個軟體是可行的。

### 2.3項目在法律允許的可行性
本計畫是在大範圍内需求而產生的,針對的是大眾群體,使用對像是國家,而非個人,所以不會有侵權行為。因此,在法律範圍之内,無侵權行為。

## 第三章需求分析
### 3.1功能性需求
#### 3.1.1系統功能
登入模組:登入模組是進入系統的入口,所有使用者必須登入後才能存取系統。登入需要輸入使用者名稱和密碼,如果多次嘗試登入需要輸入驗證碼。登入時需要選擇使用者的角色,是一般使用者還是管理員登入等。登入成功後,會透過資料庫取得使用者的權限,並跳到使用者的主頁。

管理員使用者管理模組:管理員管理包括:管理員的添加,修改和刪除操作新增管理員,先判斷使用者新增的管理員是否為admin(超級管理員),如果不是則新增成功。修改時候,如果是超級管理員,可以修改所有管理員的訊息,如果是普通管理員,那麼只能修改自己的訊息。超級管理員可以刪除自己以外的所有其他管理員,一般管理員不能執行刪除管理員的操作。

留言版模組:留言板促進用戶之間的交流,發表個人意見、建議、看法等,在留言板可以查看已有的留言記錄,發布新留言,可以展示個人動態頭像,個人匿名稱等。

火車車次推薦模組:可分為火次推薦覽、火次薦檢索、火次推薦維護個模組,管理員對火車次推薦有維護的權限,發布新的火車車次推薦、更新已有的火車車次推薦等。

火車票管理模組:火車車次管理分為火車票添加修改和票預定,車票改,車票退票。火車票資訊由管理員進行修改、新增、刪除操作;火車票預訂, 改簽,退票由一般使用者來執行。

#### 3.1.2管理員功能
修改密碼:管理者可以隨時修改自己進入系統的登入密碼,以確保系統的安全性

管理普通管理員:對普通管理員進行管理。調動相關工作人員時可以新增或刪除普通管理員。

火車票資訊管理:對火車票資訊進行維護,新增、刪除、修改資訊。

預訂單資訊處理:辦理預訂單審等。

改簽管理:審核乘客的車票改簽資料。

退票管理:審核乘客的車票退票資訊。

使用者管理:可以查看註冊用戶的信息,並對其進行管理

#### 3.1.4旅客功能
前台用戶可分為未註冊用戶需求和以註冊用戶需求。

未註冊用戶的功能如下:

註冊帳號:用戶填寫個人資訊,並驗證手機號碼。

火車車次推薦資料:使用者可以瀏覽主頁面的車次推薦資料來了解系統的最新車次推薦資訊。

瀏覽車次:用戶可以根據車票類型瀏覽車次的信息,並選中某個次查看詳情,例如:班車、車型、價格、線路、出發間、車票價格、姓名、聯絡電話、出行日期、預人、是否支付等。

已註冊用戶的功能如下:
登入:根據帳號密碼進行登入操作。

維護個人資訊:使用者因個人資訊的變更可以隨時修改自己註冊資訊。

瀏覽評論資訊:選取某車次可查看其使用者的評論。

車票預訂:用戶根據自己的需求選取班次車票進行預訂操作。

個人車票改簽退票:用戶可以查看自己以往預訂數據,進行改簽或退票申請。

### 3.2性能需求
為了確保系統能夠長期、安全、穩定、可靠、有效的行,本系統應滿足以下的性能需求。

1.準確性和及時性

系統處理的準確性和及時性是系統的必要性能。系統應能及時且準確的根據使用者限及所輸入的資訊做出回應。由於本系統的查詢能對於整個系統的能和效能完成舉足輕重。作為系統的許多資料來源,而車票的數量和時間又影響使用者的決策活動,其準確性和及時性很大程度上決定了系統的成敗。

在系統開發過程中,必須採用一定的方法來確保系統的準確性和及時性。

2.易用性

本系統是直接面對使用者的,而使用者往往對電腦並不是很熟悉。這就要求系統能夠提供良好的使用者接口,易用的人機互動介面。要實現這一點,就要求系統應該盡量使用使用者熟悉的術語和中文資訊的介面,從而確保系統的易用性。

3.系統的標準性

系統在設計開發使用過程中都要涉及到許多電腦硬體、軟體。所有這些都要符合國家標準,各鐵道部統一。如規範的資料庫操作介面、作為業界標準的TCP/IP網路協定及IS09002標準所要求的品質規格等;同時,在自主開發本系統,要進行良好的設計工作,製訂行有效的軟體工程規範,保證程式碼的易讀性、可操作性和可移植性。

4.系統的反應速度

車票預訂系統在日常處理中的反應速度為級,達到即時要求,以及時回饋資訊。在進行統計分析時,根據所需資料量的不同而從秒級到分鐘級,原則是確保操作人員不會因為速度問題而影響工作效率。

### 3.3運行要求
#### 3.3.1伺服器子系統運作要求
系統環境:win10

資料庫:MySQL-架構:BS-原始碼類型:Web

編譯工具:Idea、Eclipse(選其一)

其他:jdk1.8、Tomcat8.5(內建)、Navicat

硬體需求:CPUi5,記憶體8G

#### 3.3.2客戶端子系統運作要求

系統環境:win10以上

資料庫管理系統:MySql

硬體需求:CPUi5記憶體8G

### 3.4需求模型
#### 3.4.1資料字典
1.數據需求分析

從前面可以分析到資料庫中最重要的是車票信息,預訂信息,評價信息。分析可以得到以下資料描述:

平台使用者:用於記録使用者的各種訊息,包括使用者名稱、密碼、姓名、性別、地址、郵箱、聯络資等資料項目。

管理員:記錄管理員的登入資訊。包括用戶名,密碼,權限等資料項目。

火車票:儲存各種火車票資訊。包括列車號、價格、時間、起始地點、終點站等據項。

火車票預定。儲存使用者的火票預訂資訊。包括火票預訂的車次、列車號碼、價格、行程時間、價格、姓名、聯絡電話、預定人、是否支付等資料項目。

留言:儲存用戶的留言。包括留言内容,留言的訊息,留言人,時間等資料項目。

2.資料庫概念設計

根據前面的資料流程圖,結合系統的功能模組設計,設計出符合系統的各資訊實體。

系統ER圖如下圖所示:
![image]()圖3-1 系統ER圖

3.資料庫表設計

火車訂票系统所擁有的資料表有以下使用者資訊表,評論資訊表,車票資訊表,車票預訂表,留言
表。

由於資料表較多,只展示系統主要資料表,如下表所示。

表3-1 registered_user表
| 名稱        | 類型   | 長度  | 不是null | 主鍵  | 注釋     |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| registered_user_id| int | 11 | 是 | 是 | 註冊用戶ID|
| user_number | varchar | 64 | 是 | 否 | 用戶編號 |
| examine_state | varchar | 16 | 是 | 否 | 審核狀態 |
| recommend | int | 11 | 是 | 否 | 智能推薦 |
| user_id | int | 11 | 是 | 否 | 用戶ID |
| create_time | datetime | 0 | 是 | 否 | 創鍵時間 |
| update_time | timestamp | 0 | 是 | 否 | 更新時間 |

<br></br>
| 名稱        | 類型   | 長度  | 不是null | 主鍵  | 注釋     |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| registered_user_id| int | 11 | 是 | 是 | 註冊用戶ID|
| user_number | varchar | 64 | 是 | 否 | 用戶編號 |
| examine_state | varchar | 16 | 是 | 否 | 審核狀態 |
| recommend | int | 11 | 是 | 否 | 智能推薦 |
| user_id | int | 11 | 是 | 否 | 用戶ID |
| create_time | datetime | 0 | 是 | 否 | 創鍵時間 |
| update_time | timestamp | 0 | 是 | 否 | 更新時間 |

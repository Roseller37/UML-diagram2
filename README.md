# 1第一章問題定義
## 1.1課題背景及意義
隨著我國經濟的快速發展,我國的交通運輸能力不斷提高,越來越多的國民開始走出家門來到異地進行商或旅遊等活動。在這條件下,客流量不斷增大。火車售票的管理對於交通運輸的正常運行起著至關重要的作用,而著資訊量的逐步增加,繁雜的數據處理費時費力,單純以人力進行的火車售票已經不適合現狀了。現  今的社會發展迅速,火車成為了人們在交通方面不可缺少的交通工具,乘坐火出行的人越越多,所以火車的客運量也在迅速的增長著。為了帶給人們方便快速的交通環境,火車站系統採取提高列車的速度,增加火車站列車等措施來滿足大量的旅客的乘車需求。但是,現在人多車多的情況下,如果再像從前一樣,在一個單一的地點售票,必然滿足不了現在的情況。所以就需要售票能夠在不同的地點進行。在如此的情況下,售票系統自然是相當必要的售票系統的出現能夠在很大的程度上解決單一地點售票所帶來的種種不便,並能夠使想要出行的旅客方便的買到自己需要的車票。對於售票處的地點也從原來的單一地點(火車站)變成了多個地點,可以在市内的多個地點(賓馆、酒店、娛場所等等)這樣為將要出行的旅客帶來了更進一步的方便。使旅客無論是在金錢還是在時間方面都能夠得到充分的節省。為了方便旅客,火車售票系統不只售票,還能改,退票線上操作。也就是說系統的使用者應該不只是售票員,還應該有管理員。管理員能夠透過售票系統時的更新乘車資訊。這樣才能夠使乘客避免不必要的麻煩,真正的解決以前老式售票的種種不便,才能夠真正的成為現在網路社會的真正適應者現在的時代是資訊產業的時代,國家把資訊產業當作了成長國民經濟重要的一環。在這樣的環境下,以先進的資訊科技進行汽車售票的管理成為了時代發展的必然。綜上所述,開發這樣一個火車聯網售票系統是相當必要的。
## 1.2研究現狀
### 1.2.1國內研究現狀
我國火站很早就利用電腦管理系統加強管理、提升服水準。我國火站的展階段主要是以電腦系統的運用為標的,電話通訊系統其實也是程控交換技術出才獲得質得飛。著電腦的普電腦科技的不斷發展,同時也使火車站管理系統發展到了一個新的時期,趨於更加完善。火車站管理系統實現了火票預定、出行、退票流程的智慧化、自動化,節省了車站的人工成本,較少了乘客的等候時間,具有簡單、便捷、私密的特點。
### 1.2.2國外研究現狀
國外的火車站發展較為國内早了好多年,同時在多年的發展探索中,火車站的能展更加全面和多様化。火車站由一開始的單一出行站點到現在的休閒商務旅遊多方面出行,朝著更複雜功能更齊全的方向發展。隨著這些火車站的全面發展,其對火車站的管理要求也隨著提高,為了更方便地訂票,在電腦迅速展的背景下,產生了火訂票系統軟體,在很大成程度上減少了人物力和財力,也同時使車站的經營更加規範化,提高了服務的標準。
# 第二章可行性研究
## 2.1可行性研究過程
技術性方面,採用前主流的Springboot框架進行系統主體框架的搭建,實現前台頁面的設计與美觀整,以上技術,均本人經過系統學習,並且都是在課程設計中實過的,可以使得開發更加便捷和系統。從技術角度看,這個系統是完全可以實現的。實用性方面,本次設計的主要任務是在火訂票系統内火車票預定、次搜尋、票改、個人資料修改、票票等,符合當前潮流的發展。從使用者角度出發同時也考慮系統營運成本與人力資源,採網路上的便利方式,實現線上業務,使得業務流程更有系統,也更方便使用者的體驗,較實用。
## 2.2項目在經濟上的可行性
經濟性方面,由於本課題所設計的火定票系統的主要目的是為了能夠更方便快速的進行資訊的查管理及檢索服務,也是能夠直接投入使用的資訊化軟體。系統的主要成本主要是集中在對使用資料後期繼續維護及其管理更新這個操作但是一旦系統投入到實際的運作及使用之後就能夠很好的提高資訊查詢檢索的效率,同時也需要有效的保證查者的資訊方面的安全性,同時這個火訂票系統所帶來的實際應用方面的價值是遠遠的超過了實際系統進行開發與維方面的成本,因此,從經濟上來說開發這個軟體是可行的。
## 2.3項目在法律允許的可行性
本計畫是在大範圍内需求而產生的,針對的是大眾群體,使用對像是國家,而非個人,所以不會有侵權行為。因此,在法律範圍之内,無侵權行為。
# 第三章需求分析
## 3.1功能性需求
### 3.1.1系統功能
登入模組:登入模組是進入系統的入口,所有使用者必須登入後才能存取系統。登入需要輸入使用者名稱和密碼,如果多次嘗試登入需要輸入驗證碼。登入時需要選擇使用者的角色,是一般使用者還是管理員登入等。登入成功後,會透過資料庫取得使用者的權限,並跳到使用者的主頁。管理員使用者管理模組:管理員管理包括:管理員的添加,修改和刪除操作新增管理員,先判斷使用者新增的管理員是否為admin(超級管理員),如果不是則新增成功。修改時候,如果是超級管理員,可以修改所有管理員的訊息,如果是普通管理員,那麼只能修改自己的訊息。超級管理員可以刪除自己以外的所有其他管理員,一般管理員不能執行刪除管理員的操作。留言版模組:留言板促進用戶之間的交流,發表個人意見、建議、看法等,在留言板可以查看已有的留言記錄,發布新留言,可以展示個人動態頭像,個人匿名稱等。火車車次推薦模組:可分為火次推薦覽、火次薦檢索、火次推薦維護個模組,管理員對火車次推薦有維護的權限,發布新的火車車次推薦、更新已有的火車車次推薦等。火車票管理模組:火車車次管理分為火車票添加修改和票預定,車票改,車票退票。火車票資訊由管理員進行修改、新增、刪除操作;火車票預訂, 改簽,退票由一般使用者來執行。

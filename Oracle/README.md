## Oracle Analytics 練習
Oracle Analytics 這部分老師並未授課教學使用，僅提供資料讓學員自行操作。這次拿到的資料是某間公司的員工資料，並無業績、考核...這類可做KPI的資訊，比較偏向員工個人基本資料，
所以這次製作的方向會是：提供給人資部門的員工基本資料分析。<br>
<br>
**仔細觀察資料原檔發現，該份資料裡也包含了已離職的員工，因此在製作所有圖表時，全部都有加入一個[% terminated:0]的篩選，以確保呈現的資料都是在職員工。<br>
每一份儀錶板在最上排都有放了一些篩選器，供人資部門依需求作查詢，其中location的欄位，裡面的設定是"是否為遠距"，顯現出這間公司有部分的人是採用遠距上班的。**
<br>
圖1
![image](https://github.com/hsiaotingg/data-visualization/blob/main/Oracle/basic.png)
圖1中可以觀察到：<br> 1. 該公司男女比例蠻平均<br> 2. Engineering部門人數最多，其次為Accounting，且設有Sales部門，推測可能是間提供財會資訊服務相關的公司<br> 3. 員工以白人為主，但也有其他不同族群的員工<br>
<br>
圖2
![image](https://github.com/hsiaotingg/data-visualization/blob/main/Oracle/operation-1.png)
*註:入職人數不需要去判別現在是否是在職員工，所以沒有加% terminated:0的篩選；而離職的部分就放% terminated:1<br>*
從入職人數的趨勢圖可以看出，該公司可能成立於2000年，每年持續招募1000-1200名左右的員工，男性員工稍微多於女性，且持續有未確認性別的員工，推測可能員工填寫入職資料時不願填寫或是遺漏而處理人員當下未發現也無追蹤。<br>
另外，從入職人數也可以看出該公司持續有用人需求，但是為什麼每年都招募這麼多人呢？是公司的人員流動大？還是公司規模擴大？這個問題我們就可以參考每年的離職人數。雖然每一年都有員工離開，但是每年離職人數都在160人以下，顯示每年員工總人數是成長的，如果是前者，應該離職人數會和入職人數差不多或更高，所以可以推測該公司應該是穩定擴編的。<br>
此外，離職人數在2021年達到高峰，且2021年無入職員工，可能是受新冠肺炎(covid-19)影響。由於資料沒有離職原因或是是否自願離職，確切原因不得而知。<br>
<br>
圖3
![image](https://github.com/hsiaotingg/data-visualization/blob/main/Oracle/operation-2.png)
圖3整理出員工的出生月份以及部門別，在圖2可以看出員工離職數是不高的，有可能公司的薪資福利是不錯的，或許會提供員工生日禮金或禮物，這部分應該也是由人資部門協助做處理，將每個月的人數提供給財會部門以利請款，或是相關單位的主管想了解每個月的禮金支出，透過這張圖即可一目瞭然。再者，因為部門、分公司眾多，所以有再製作一張部門別可以搭配篩選地點，方便人資管理及分配。<br>
<br>
圖4
![image](https://github.com/hsiaotingg/data-visualization/blob/main/Oracle/operation-3.png)
<br>
表1(僅擷取部分欄位)
![image](https://github.com/hsiaotingg/data-visualization/blob/main/Oracle/data.png)
圖4是根據在職年資製作，這部分主要可以了解每個年齡層的員工，工作年資大約落在哪。不過發現一件很神奇的事，20-24歲的員工，在職年資竟然落在10-12年間？
回頭查看資料(表1)發現~驚人的現象~25、26歲的員工怎麼會有20年的資歷呢？因此在年資及僱用日期的部分可能就需要人資部門去找尋原因，**可能有資料跑掉的問題**。
因為無法透過資料清洗的方式debug，故在年資的部分不再多做分析。<br>
<br>
圖5
![image](https://github.com/hsiaotingg/data-visualization/blob/main/Oracle/location-1.png)
圖6
![image](https://github.com/hsiaotingg/data-visualization/blob/main/Oracle/map.png)
透過圖6的地圖可以看出該公司服務據點主要分布在北美五大湖工業區附近7個州(伊利諾州、印第安納州、肯塔基州、密西根州、俄亥俄州、賓夕法尼亞州、威斯康辛州)，根據圖5可知俄亥俄州的員工人數是最多的，所以可能是總部或是主要服務重心。五大湖工業區是美國商業、金融與工業中心重鎮，更能印證該公司可能是提供財會相關的資訊服務。因為是經濟高度發展區，故人口的種族組成較多元，但仍是以白人為主，詳圖7。<br>
圖7
![image](https://github.com/hsiaotingg/data-visualization/blob/main/Oracle/location-2.png)

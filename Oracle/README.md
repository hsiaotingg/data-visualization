## Oracle Analytics 練習
Oracle Analytics 這部分老師並未授課教學使用，僅提供資料讓學員自行操作。這次拿到的資料是某間公司的員工資料，並無業績、考核...這類可做KPI的資訊，比較偏向員工個人基本資料，
所以這次製作的方向會是：提供給人資部門的員工基本資料分析。<br>
<br>
**仔細觀察資料原檔發現，該份資料裡也包含了已離職的員工，因此在製作所有圖表時，全部都有加入一個[% terminated:0]的篩選，以確保呈現的資料都是在職員工。<br>
每一份儀錶板在最上排都有放了一些篩選器，供人資部門依需求作查詢，其中location的欄位，裡面的設定是"是否為遠距"，顯現出這間公司有部分的人是採用遠距上班的。**
<br>
圖1
![image](https://github.com/hsiaotingg/data-visualization/blob/main/Oracle/basic.png)
圖1中可以觀察到：<br> 1. 該公司男女比例蠻平均<br> 2. Engineering部門人數最多，其次為Accounting，且設有Sales部門，推測可能是間做會計相關的資訊公司<br> 3. 員工以白人為主，但也有其他不同族群的員工<br>
<br>
圖2
![image](https://github.com/hsiaotingg/data-visualization/blob/main/Oracle/operation-1.png)
圖2是根據每年員工入職人數以及離職人數分別作出趨勢圖，


透過資料可以看出這間公司主要在美國，其分公司或是辦公室集中在ohio州

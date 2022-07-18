## 如何使用Oracle Analytics
### 1. 下載Oracle Analytics Desktop
進入官網並確認硬體設備(要求蠻高的，較低階文書機可能跑不動XD)，並點選download
[官網連結](https://www.oracle.com/tw/solutions/business-analytics/analytics-desktop/oracle-analytics-desktop.html)
### 2. 匯入資料
下載並安裝完畢後，開啟Oracle Analytic Desktop，點選[建立]，選擇[資料集]。<br>
Oracle Analytics除了自家的資料庫外也有支援各種資料庫連線，廣為人知的database就有MySQL、MongoDB。<br>
![image](https://github.com/hsiaotingg/data-visualization/blob/main/Oracle/pic_for_use/use1.png)
當然也有支援一般csv、excel文件。
### 3. 資料處理
Oracle Analytics會自動辨別欄位資料型態，使用者可視需求先檢視各個欄位並作調整，如果當下未能及時調整，也可在製圖中做設定。<br>
![image](https://github.com/hsiaotingg/data-visualization/blob/main/Oracle/pic_for_use/use2.png)
按下[新增]後會跳轉到以下畫面，會針對各欄位資料做一個簡易分析，也可點選上方按紅色框框按鈕，切換為列表呈現。<br>
![image](https://github.com/hsiaotingg/data-visualization/blob/main/Oracle/pic_for_use/use3.png)
右方有Oracle Analytics提供的資料處理建議，如果點選後不喜歡也可以按下[返回]按鈕<br>
![image](https://github.com/hsiaotingg/data-visualization/blob/main/Oracle/pic_for_use/use4.png)
在資料元素的欄位名稱按下右鍵，可以對欄位進行調整<br>
![image](https://github.com/hsiaotingg/data-visualization/blob/main/Oracle/pic_for_use/use12.png)
針對有日期的資料也可以做分割，非常的方便！<br>
![image](https://github.com/hsiaotingg/data-visualization/blob/main/Oracle/pic_for_use/use13.png)
新增自訂欄位當然也是沒問題
![image](https://github.com/hsiaotingg/data-visualization/blob/main/Oracle/pic_for_use/use14.png)
只要有調整資料，左方狀態會顯示做過的步驟，確認沒有問題後，要記得按下[套用命令檔]，資料設定才會更新哦！
![image](https://github.com/hsiaotingg/data-visualization/blob/main/Oracle/pic_for_use/use5.png)

### 4. 資料視覺化
按下[建立工作簿]後，就可以開始製作視覺化的圖表了。Oracle Analytics使用起來也是很直覺，將想要處理的欄位從左邊點選拖拉至右側，系統會自動產出圖表，想要更改圖表類型當然也沒問題。
![image](https://github.com/hsiaotingg/data-visualization/blob/main/Oracle/pic_for_use/use6.png)
![image](https://github.com/hsiaotingg/data-visualization/blob/main/Oracle/pic_for_use/use7.png)
圖表的配色可自訂，也可彈性選擇，在[色彩]的下拉選單選擇[管理指定項目]<br>
![image](https://github.com/hsiaotingg/data-visualization/blob/main/Oracle/pic_for_use/use8.png)
![image](https://github.com/hsiaotingg/data-visualization/blob/main/Oracle/pic_for_use/use9.png)
一個工作區可同時放多張圖表，在不選取任何已有的圖表時，從左側再次選擇要處理的欄位拖曳到下圖灰色區塊，就可以再新增圖表並可調整大小，讓多張圖片可同時呈現在一個工作區<br>
如果製圖中發現欄位資料需再調整，可以點選紅色框框[資料]再去設定(可參考3.資料處理)<br>
p.s Oracle Analytics使用中不時會當掉，建議每次做完圖表順手存檔！
![image](https://github.com/hsiaotingg/data-visualization/blob/main/Oracle/pic_for_use/use10.png)

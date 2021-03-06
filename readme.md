# Welcome To OA's Taipei Towns!
雙北市行政區域範圍座標，大家一起來維護劃分出雙北市甚至於全台灣的行政區域、鄉鎮區域的範圍座標吧！

---
## 聲明
本作品授權採用 姓名標示-非商業性 2.0 台灣 (CC BY-NC 2.0 TW) 授權，詳見 [http://creativecommons.org/licenses/by-nc/2.0/tw/](http://creativecommons.org/licenses/by-nc/2.0/tw/)


<br/>
## 簡介
* 取得雙北市行政區域範圍座標。
* 因為 Google maps js API 找不到可以取得行政區的範圍座標，故才自己畫完雙北市的範圍座標。
* 藉此分享出來給大家使用，各位大大也可以新增完後，發個 Pull Request 讓我合併，大家一起維護並且分享！


<br/>
## 步驟
* 各鄉鎮行政區域的檔案放置在 `towns/` 下，分別依照不同縣市資料夾分類，每個檔案接用區域名稱命名。
![行政區域範圍座標](img/towns-compressor.png)

* 開啟網頁後 [http://comdan66.github.io/TaipeiTowns/](http://comdan66.github.io/TaipeiTowns/)，於左上角選擇要編輯的區域。
![行政區域範圍座標](img/select-compressor.png)

* 利用滑鼠右鍵，會有 新增、插入、刪除 節點的功能，可以對所選的區域做編輯。
![行政區域範圍座標](img/menu-compressor.png)

* 編輯完後，點擊右上方 **匯出經緯度** 的按鈕後，即可下載行政區的 `.json` 檔案。
![行政區域範圍座標](img/export-compressor.png)
![行政區域範圍座標](img/download-compressor.png)

* 將該 `.json` 檔案放置 `towns/` 下所對應的行政區，即可修正原本的範圍座標。
![行政區域範圍座標](img/replace-compressor.png)

* 修改完 commit 後，對 [TaipeiTowns](https://github.com/comdan66/TaipeiTowns/pulls) 發 **Pull Requests**，待 [OA](https://github.com/comdan66) 確認後即會 merge。


<br/>
## 關於
* 作者名稱 - [OA Wu](http://www.ioa.tw/)

* E-mail - <comdan66@gmail.com>

* 作品名稱 - OA's Taipei Towns

* 最新版本 - 1.0

* GitHub - [OA's Taipei Towns](https://github.com/comdan66/TaipeiTowns)

* 更新日期 - 2015/12/10
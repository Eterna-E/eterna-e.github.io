# 作品集 - 總集

個人整合的開發程式範例與過去工作作品介紹，若有幫助歡迎取用。

TAMI 專案，因涉及到機敏性資料僅包含專案項目。

## 目錄

<table>
       <tr>
            <th>Side Project</th>
            <th>Work Sample</th>
        </tr>
        <tr>
            <td valign="top" width="450">
                <ul>
<!--                     <li>Tunffli-智慧家居系統 -->
<!--                     </li> -->
                    <li>Python
                        <ul>
                            <li>Youtube影片下載程式</li>
                            <li>ScrabbleWordFinder</li>
                            <li>AnimationDownloader</li>
                            <li>PySparkPracticeQuestions</li>
                        </ul>
                    </li>
                </ul>
            </td>
            <td valign="top" width="450">
                <ul>
<!--                     <li>WiNet-無線環境監控系統
                    </li> -->
                    <li>Python
                        <ul>
<!--                             <li>DjangoPuYuanApi</li> -->
                            <li>TAMI 專案(金融科技與產業行動AR應用平台)後端伺服器API開發</li>
                        </ul>
                    </li>
                </ul>
            </td>
        </tr>
</table>

## Side Project

### Youtube影片下載程式

![](https://i.imgur.com/kdo8J2b.png)

視窗圖形化介面的 Youtube 影片下載程式，可選擇影片畫質和影片檔案下載路徑，並列出下載清單與下載進度。
* [視窗圖形介面的Youtube影片下載程式](https://tw.coderbridge.com/series/c471d97bb201460ab137c5e4955987df)
* CoderBridge - https://tw.coderbridge.com/@Eterna-E

### ScrabbleWordFinder

![](https://i.imgur.com/jpy4tyP.png)

Scrabble Word Finder 找出英文字母排列的可能性(有意義的)，假設隨機輸入了幾個字母(字母數大約5~12個左右，超過太多，搜尋時間會很久)之後，到底能夠找出多少個有意義的單詞，再用 python 爬蟲程式到劍橋詞典搜尋這些單詞的意思，輸出到命令提示字元(cmd)顯示。

* GitHub - https://github.com/Eterna-E/ScrabbleWordFinder

### AnimationDownloader

Myself 動畫網站影片下載簡易工具

* GitHub - https://github.com/Eterna-E/MyselfAnimationDownloader

### PySparkPracticeQuestions

PySpark 的程式設計練習，Spark 題目是參考使用這兩篇：【Spark】Spark基础练习题（一）、【Spark】Spark基础练习题（二），但是因為這兩篇教學文章的題目解答，都是用 JAVA 語言寫的，沒有找到 PySpark 版本的練習，所以我自己用 Python 程式語言在寫一了遍，邊寫邊對答案。

* GitHub - https://github.com/Eterna-E/PySparkPracticeQuestions

## Work Sample

### 工業技術研究院 TAMI 專案(金融科技與產業行動AR應用平台)

<!-- ![](https://i.imgur.com/YmOJKN6.png=600x600) -->
 <img src="https://i.imgur.com/YmOJKN6.png" width = "200" height = "200" alt="图片名称" align=center />
 
參與項目：
工業技術研究院 - 資料分析平台建置與程式開發(金融科技與產業行動AR應用平台之研製)
擔任角色：
系統開發及部署維運人員
應用技術：
Elasticsearch
Spark
PySpark
Python Flask
PostgreSQL 資料庫
說明：
負責使用分散式資料處理引擎(Spark) 進行資料前處理及資料分析，並將資料處理結果存入 Elasticsearch 全文搜尋引擎做資料搜尋，以及Python Flask 網頁伺服器後端 API開發，用以提供網頁伺服器 Python Flask Server 經由 Elasticsearch 搜尋大量數據至網頁前台做資料顯示。
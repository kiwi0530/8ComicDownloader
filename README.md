8ComicDownloader
================

一個簡單從8Comic網站下載漫畫的程式

使用方式
================
1. 從 http://www.8comic.com/ 找到想要下載的漫畫
2. 隨意選擇集數，並將網址貼到8ComicDownloader的Url欄位中
3. Url欄位下可以選擇分析最後N集漫畫網址，或目前所有集數的網址
4. 按下[分析漫畫網址]按鈕，產生漫畫圖片連結，與對應目錄
5. 重複步驟1~4產生所有想下載漫畫的圖片網址
6. 按下[開始下載]按鈕，即可將漫畫下載到電腦中，路徑與主程式存放目錄相同

進階功能
================
- 分析過的漫畫會儲存起來，在[分析漫畫網址]按鈕旁邊的下拉選單可以直接選用
- 儲存的漫畫會存在comic_list.txt中，可以自行修改
- 漫畫檔案已存在的話預設不下載，希望強制下載的話可以取消勾選[檔案已存在就不下載]
- 程式最下方有[下載後路徑]選項，可設定預設漫畫的下載路徑

注意事項
================
- 必須安裝[.Net Framework 4]才可執行 http://www.microsoft.com/zh-tw/download/details.aspx?id=17718
- 本程式僅供網路測試，請勿做為商業或任何不法用途

版本紀錄
================
v1.2 - 2014/08/26
- [介面]抓最後N集原本最大值為100，現在為Decimal.MaxValue(總之非常非常大)
- [功能]新增下載路徑設定，畫面最下方可以設定調整預設的下載路徑

v1.1 - 2014/08/19
- [介面]調整介面，由GridView取代原來的Text顯示漫畫下載資訊

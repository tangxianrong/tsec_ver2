# tsec_ver2
引自於 https://github.com/Asoul/tsec
將附檔crawl_new.py 用於取代原網址提供的crawl.py
與crawl.py功能基本一致，並加入新的功能 python crawl_new.py -renewall(或寫成python crawl_new.py -r)
原來網站所提供的程式的back或check功能並無法偵測前一次抓取資料是何時，會浪費時間重複不必要的動作
這裡使用台灣50作為基準，偵測台灣50本機端的最新資料日期，並從日期的下一天開始抓取至程式執行當日
此檔案放置於與原網址crawl.py相同的路徑

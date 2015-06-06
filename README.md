# 14119157's bootstrap notes
## bootstrap installation
1. 至Sites新增資料夾後，拉至Sublime
2. 在Sublime新增檔案(index.html)
3. 輸入html後按Tab鍵
4. ``<html lang="utf-8">``
5. 在``<title>``下行輸入link後按Tab鍵
6. 下載bootstrap，將css、fonts、js資料夾拉剛新增的資料夾
7. 至link那行後面打"css/bootstrap.css"
8. ``<body></body>``間打``<h1>``、``<p>``、``<h2>``、``<p>``、``<button>``、``<button>``、``<h3>``、``<p>``
9. 開始輸入文字
10. 在下面``</body>``上行打``<script src="js/bootstrap.js">``
11. 至css bootstra
    >Getting strat >右邊Basic template
12. 複製``<!-- jQuery (necessary for Bootstrap's JavaScript plugins) -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.2/jquery.min.js">``
13. 在上面的``<body>``下面打``<div>``
14. 把後面的``</div>``拉至內容的結尾
15. 上面的``<div>``內打class="container"(置中)
    * ``<div class="container-fluid">``(佔滿頁面)
16. ``<div class="col-md-6">``(分欄位)加至`<h1>`上行
    * xs>768px以下、sm>768~992px、md>992~1200px、lg>1200px以上 (size)
17. `<img src="圖片網址" style="width:100%">`
    * style="width:100%"(圖片大小)
    * ``<div class="row">``(增加可讀性，可加可不加)
    
    **加間隔**	
    * 在分欄位後打col-md-offset-1(左右各縮1)     
    * 視窗拉大後跑位的調整>後面再加最前面的size，然後 - 0，
      拉大後就可正常     
      EX:``<div class='col-sm-4 col-xs-10 col-xs-offset-1 col-sm-offset-0'>``       

18. 先另開一個在css 新增檔案，輸入main.css ，然後存檔	
19. 之後打`body{
    　              font-family: "字體";    
                  }` (改字體－網頁：font-family)	
20. 回至index.html 在分欄位那行裡打features(名稱以對應檔案)
21. 在想強調內文前輸入`<p class="lead">` (突顯字)
22. 至components bootstrap選擇圖示後，在至index.html在任一想放的位置打`<i class="~~~~"></i>`
23. 複製`<title>`下面那行，把後面的bootstrap改main
24. 在main.css打`.features .glyphicon{    
                     font-size:32px;    
                     color:res;    
                    }`  (改圖示大小、顏色)
25. 在頁面最下做頁角 > 在內文下輸入`<footer class="container-fluid>`
26. 再至main.css打`footer{     
                        background-color:顏色
                        }`    
27. 後回至index.html將頁角劃分欄位和置中 > 輸入`<div class="col-md-4">`
					`<div class="container">`
28. 輸入標題`<h4>link</h4>`      
    * `<ul class="list-unstyle">`(消除點)
29. `<li><a href="網址">Home</a></li>`(連結網址)	  
    `<li>~~~~~~~</li>`       
    `<li>~~~~~~~</li>`     
    `</ul>`		
    `</div>`    
30. `<buttton type="button" class="btn-lg btn-顏色">分享</button>`(按鈕設定)	
    * default(白)、primary(藍)、success(綠)、info(淺藍)、warnig(黃)、danger(紅)	
    * xs、sm、lg (大小)
31. `<div class="row well">`(well > 內文會有框框)	
    * 在後面繼續輸入well-xs、sm、lg 可調整大小)

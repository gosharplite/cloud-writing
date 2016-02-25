#羅勃·派克 - 雲端歷史的源頭
作者：徐德平，上海卓易科技台北研究院，2016年2月
<hr>
這幾年智慧手機的普及，造成網路服務需求的大量增加。為了滿足大眾的需求，科技業端出各種創新的技術來回應。加上開源項目的興起，許多科技公司都不停的釋出新的開源技術，試圖在未知的世界中佔住一席之地。「雲端」被拿來形容這個現象，來和舊技術做區別。當有人問雲端歷史是從什麼時候開始，我會回答2012年3月。也就是Go語言1.0版發布的時間。Go是一個新世代電腦語言，已經迅速的成為開發雲端技術的首選。羅勃·派克這位長年在美國工作的加拿大軟體工程師，就是Go語言的靈魂人物。
<br><br>
雲端技術使用大量的容器架構，來應付網路上千軍萬馬的使用者。目前處於領導地位的公司有三家，Docker、CoreOS、Google。他們開源出來的雲端項目，都不約而同的使用Go語言。從技術的角度來看，Go語言有許多特色。如精簡的語義表達、內建的多併發模式、明確的語法建構，等等。這些特色讓它特別適合用來開發雲端技術的後台功能。透過觀察羅勃·派克，我們可以從不同的角度來認識雲端技術。
<br><br>
從1980到2002年，羅勃·派克在貝爾實驗室的電腦研究中心開發Unix、Plan9、Inferno等作業系統。這個期間他讓Unix能用滑鼠（Blit），並且幫助網路世界使用不同的語言（UTF-8）。離開貝爾實驗室後他加入Google至今，研究分散式架構、數據挖掘、程式語言、協助工具。最近幾年則專注於領導Go語言的成長。參考<sup>[1][2][3][4]</sup>。
<br><br>
對於他在貝爾實驗室的主要工作「作業系統研發」，羅勃·派克在2000年2月寫了一篇抒發悲觀情緒的文章
<sup>[5]</sup>。當時Linux系統靠著開源的成長模式，得到市場的喜愛。這對許多系統研究人員無疑的是很大的打擊，因為創新的系統架構無人問津，大眾頑固的繼續選擇Linux。作業系統研發變得了無新意，經費也漸漸撤離。在那樣時空背景下，或許導致兩年後他離開工作了22年的貝爾實驗室。參考<sup>[6]</sup>。
<br><br>
羅勃·派克有個特殊的經驗。在1990年5月他站在搞笑藝人後面演一位呆頭呆腦的技師，登上了大衛·賴特曼的「深夜」節目<sup>[7]</sup>。這個節目是美國家喻戶曉的電視秀。從藝人興奮的口氣叫出「從貝爾實驗室來的羅勃·派克在這兒！」，很容易感受到美國人對貝爾實驗室天才們的崇拜。看著他搖頭晃腦的配合演出，不禁想到戲如人生。懷疑這位天才當時的生活，是否跟這個角色相似。
<br><br>
在2010年的開源大會，羅勃·派克用12分鐘攻擊了流行的電腦語言，並給予Go語言清楚的定位<sup>[8]</sup>。電腦語言大致分為兩類，編譯語言（C++，Java）和解釋語言（Python，Ruby，JavaScript）。編譯語言經過長期的發展，語義和語法已過於複雜難懂，編譯時間也太長。解釋語言的語義和語法比較清楚，但即時執行的程序速度太慢。Go語言的定位就是要成為一個語義和語法簡潔的編譯語言，並支援可擴充的分散式架構。他當時呈現萬眾皆醉我獨醒的氣勢，被不少人看成狂犬吠日。畢竟太多新語言最後都默默無聞或無疾而終。
<br><br>
Go語言從2007年末開始構思，到2012年3月釋出1.0板，花了四年多的時間。羅勃·派克在2012年底把一篇演講稿詳細的轉變成介紹文<sup>[9]</sup>，寫出背後的動機和歷史。Google面對前所未見的挑戰，多核電腦、網路系統、分散集群、上百萬行並且頻繁變動的程序碼，都是C++、Java、Python在語言設計之初沒有考慮的需求。加上動輒數小時的程序編譯時間，讓工程師疲於奔命、痛苦不堪。Go語言在這個環境中應運而生，不談理論而注重有效率的解決真實的問題。了解這個背景，就不會驚訝許多大家慣用的電腦語言理論都被Go語言踢除。基本上任何會讓語義複雜，物件相依，編譯延長的語法都被取消。Go語言不是用來實現理論，而是要有效率的解決雲端系統的挑戰。
<br><br>
「我不習慣成功，這是個奇怪的感覺<sup>[10]</sup>。」Go語言爆發性的使用者成長，讓羅勃·派克的知名度與日俱增。這句話道出了內在的蛻變，從一個默默無聞跑龍套的角色，轉變成主導雲端未來語言的開創者。不遭人忌是庸才，就有過去的同行叫他「世界級蠢材」<sup>[11]</sup>。能批評他並且造成話題的人也不是省油的燈，對於作業系統和電腦語言有著深厚的功力<sup>[12]</sup>。批評的內容讓羅勃·派克在演講時特別從技術面解釋了一番<sup>[13]</sup>。面對情緒，技術的對錯事小，他們有相同的藝術連結事大。也許是這個潛意識，羅勃·派克在Twitter的自我介紹為「世界級蠢材的研究！羅勃」<sup>[14]</sup>。對長期在作業系統研究上默默耕耘並承受孤獨的同行們，表達出深刻的敬意。
<br><br>
Go語言和圍棋在英文是同一個字「Go」，這不完全是巧合<sup>[15]</sup>。羅勃·派克在演講中，流露出相當好的圍棋棋力。他仿照圍棋棋諺，把Go語言的重要觀念集結成「Go諺」<sup>[16]</sup>，讓工程師寫程序時能直覺的寫出好的結構。難怪在Go語言規格和標準程序庫中，處處可以看到不同層次的觀點、交換、取捨。若比較他2010年和2015年的演講，似乎少了憤世忌俗，多了柔和與自信。
<br><br>

###Renée French的藝術
##參考文獻
1. [wiki - Rob Pike](https://en.wikipedia.org/wiki/Rob_Pike)
2. [herpolhode.com - Rob Pike](http://herpolhode.com/rob/)
3. [usesthis.com - Rob Pike](https://usesthis.com/interviews/rob.pike/)
4. [Research at Google - Rob Pike](http://research.google.com/pubs/r.html)
5. [Systems Software Research is Irrelevant](http://herpolhode.com/rob/utah2000.pdf)
6. [Systems software research is still irrelevant](https://news.ycombinator.com/item?id=8651125)
7. [Late Night with David Letterman - Rob Pike](https://www.youtube.com/watch?v=z4iVAcYyWN0#t=3m5s)
8. [OSCON 2010: Rob Pike, "Public Static Void"](https://www.youtube.com/watch?v=5kj5ApnhPAE)
9. [Go at Google: Language Design in the Service of Software Engineering](http://talks.golang.org/2012/splash.article)
10. [GopherCon 2014 Opening Keynote by Rob Pike](https://www.youtube.com/watch?v=VoS7DsT1rdM#t=36s)
11. [World-class jackass](http://dtrace.org/blogs/wesolows/2014/12/29/fin/)
12. [Fin – Keith Wesolowski retires](https://news.ycombinator.com/item?id=8816055)
13. [GopherFest 2015: Rob Pike on the move from C to Go in the toolchain](https://www.youtube.com/watch?v=cF1zJYkBW4A#t=25m20s)
14. [Twitter - Rob Pike](https://twitter.com/rob_pike)
15. [Go Proverbs - Rob Pike - Gopherfest - November 18, 2015](https://www.youtube.com/watch?v=PAAkCSZUG1c#t=31s)
16. [Simple, Poetic, Pithy](https://go-proverbs.github.io/)

x. [GopherFest 2015: Rob Pike on the move from C to Go in the toolchain](https://www.youtube.com/watch?v=cF1zJYkBW4A#t=25m20s)

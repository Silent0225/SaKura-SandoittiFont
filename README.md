# SaKura-SandoittiFont (佐倉サンドイッチフォント)

　這個字體的最新版本是源自於0.34.1版、unhinted版的sarasa-mono-j-semibold ([Sarasa-Gothic](https://github.com/be5invis/Sarasa-Gothic))的派生字體。

![](https://i.imgur.com/85PFY55.png)
　
　
　
## 和Sarasa-Gothic之間的差異？

　我喜歡日本新字体和拡張新字体的漢字寫法、其簡化類推。

　而且，我過去曾經找到了一些字體。這些字體能夠把舊字體以略字來顯示。此外，我還找到了max32002製作的一些字體。這些字體能把繁體字以簡體字來顯示。或者，把部分簡體字以繁體字來顯示。（譬如說，[獅尾繁腿黑體](https://github.com/max32002/swei-fan-leg)）

　根據以上字體的「強制把某些字以某些字來顯示」這樣的想法，我以Sarasa-Gothic為基底改作出了一個字體。這個字體能把繁體字和簡體字給盡量地以日本新字体和拡張新字体來顯示。其實，就是使用fontforge的腳本功能執行代碼，把字圖存在著的日本新字体和拡張新字体的字圖給複製並貼到繁體字和簡體字的字圖上。

　所以，和Sarasa-Gothic之間的差異如下。

　Sarasa-Gothic是正常顯示繁體字和簡體字的字體。SaKura-SandoittiFont是以Sarasa-Gothic為基底改作的。把很多繁體字和簡體字都盡量以日本新字体和拡張新字体給顯示的字體。
　
　
　
## 有哪些字被更換了字圖？

　常用漢字表和人名用漢字之中出現的漢字所對應到的繁體字和簡體字是主要被更換字圖的字。還有，如果在中文之中比較常用的字在拡張新字体之中有相對應的字的話，這些中文字也會被更換字圖。

　此外，在常用漢字表之中被規定的某些字的寫法是沿用舊字體的，但如果在拡張新字体之中有相對應的字圖的話，且是符合漢字検定中的「許容字体（是不是許容字体參考了[這網站](https://kanji.jitenon.jp/)）」、能被接受的寫法的話，，我會比較傾向於用拡張新字体來顯示（因為我更喜歡類推簡化的寫法）。

（譬如說，在常用漢字表之中「塡」字應該寫成「塡」，但因為在拡張新字体的字圖之中有「填」字存在，且是符合漢字検定中能被接受的寫法，所以我會把「填」字字圖貼到「塡」的字圖上。用拡張新字体來顯示。所以，可以這樣說。此字體不是完全依照常用漢字和人名用漢字表中的標準漢字寫法來顯示文字）

　除此之外，還有根據自己的喜好而被更換字圖的字。
　
　
　
## 有哪些字沒有被更換字圖？

　在日本新字体和簡體字之中，有多種原來的字簡化成一種簡化方式這樣的情況時，就有可能不會把這些繁體字和簡體字更換成日本新字体、拡張新字体的字圖。

　通常來說，我會調查繁體字和簡體字在更換成日本新字体、拡張新字体的字圖之後，有沒有可能會發生混亂的情況。如果這個情況很嚴重的話，就不會把這個字的字圖更換。

（譬如說，辨、瓣、辯的新字体都是弁。因為預防使用混亂所以沒有把辨、瓣、辯的字圖給更換成弁。譬如說，發、髮的簡體字都是发。因為預防使用混亂所以沒有把发的字圖給更換成発。但是，有把發的字圖給更換成発。因為發和発是一對一的簡化方式）

　另外，在中文之中比較少被使用的字可能就不會被更換字圖。
　
　
　
## 下載字體

　點擊右側邊的「Releases」按鈕，選擇最新版下載。
　
　
　
## 題外話

　這個字體只是出於個人的興趣而改作出來的。因為我經常使用的字體粗細只有一種，所以就只有改作出了一種粗細的字體。

　此外，有些字的字圖在其他人的眼中應該要被更換。有些字的字圖在其他人的眼中不應該被更換。上述的這些事情有可能會發生。實際上，我已經對中文之中常用的字進行了很多次的調查。有哪些字的字圖應該被更換這件事基本上已經是確認完成了。

　因為是由我自己去判斷是不是要被更換的所以主觀性很高。這也是上述的事情為什麼可能會發生的理由吧。

　無論如何，有哪個字的字圖不應該被更換這樣的問題如果有的話，還是可以提出來。我通常可以給一個解釋。或者，可能是我把某個字的字圖給不小心更換了這樣的錯誤發生了也說不定。
　
　
　
## 授權

　和[Sarasa-Gothic](https://github.com/be5invis/Sarasa-Gothic)一樣的授權，基於SIL Open Font License, Version 1.1而發布的字體。
　

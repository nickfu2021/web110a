# html5 教程

* 區塊元素: 整個寬度
         h1~h6, div, p, ul, ol, li
* 行內元素: 依據文字寬度
        a, img, span, sup, sub, b, i, big, small, strong,
        del, u, mark, em, s, ins
* h1~h6標籤盡可能避免重複使用
* 請合理使用html標籤，讓網頁增加瀏覽器可讀性
* 合理使用a標籤，可以讓使用者停留在當前網站
* 使用visual studio code emmet可快速生成html
* 選取要複製的html標籤，按下鍵盤 alt + shift + ↓ 可以進行複製
* div標籤透過F12查看元素，是沒有預設樣式的，所以適合用來排版。(li, span)
* a標籤可以加上 target 屬性(\_blank, \_self)來設定開啟連結的方式

## emmet 使用

~~~emmet
h${標題$}*6

輸出:
        <h1>標題1</h1>
        <h2>標題2</h2>
        <h3>標題3</h3>
        <h4>標題4</h4>
        <h5>標題5</h5>
        <h6>標題6</h6>
~~~

## 產生假文字(英文)

~~~emmet
<p>lorem</p> 預設30個字

<p>lorem40</p> 指定文字數量*40
~~~

## 產生假文字(簡體中文)

> 請安裝套件clorem

## 產生假文字(繁體中文)

> 請安裝套件Chinese Lorem _by_ Kevin Yang

~~~emmet
使用方法:
<p>ctlorem</p> 預設128個字
<p>ctlorem40</p> 指定文字數量*40
~~~

## 快速產生清單項目(emmet)

~~~emmet
ul>li{item-$}*5

輸出:
<ul>
    <li>item-1</li>
    <li>item-2</li>
    <li>item-3</li>
    <li>item-4</li>
    <li>item-5</li>
</ul>
~~~

## 變更 ul li 圖形

~~~html
type = disc/circle/square 
<ul type="square">
    <li>item-1</li>
    <li>item-2</li>
    <li>item-3</li>
    <li>item-4</li>
    <li>item-5</li>
</ul>
~~~

## 有序清單列表(ol)

~~~html
type = 1/A/a/I/i
<ol type="1" start="3">
    <li>item-1</li>
    <li>item-2</li>
    <li>item-3</li>
    <li>item-4</li>
    <li>item-5</li>
</ol>
~~~

## 上標字下標字

~~~html
2 <sup> 4</sup>

\\ <!-- 輸出：二的四次方 -->

H <sub> 2 </sub> o

\\ <!-- 輸出：化學式 水 -->
~~~

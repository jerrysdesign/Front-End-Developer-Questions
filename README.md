#前端開發面試題目 （題目列表頁）


## <a name='list'>目錄</a>

  1. [HTML部分](#html)
  1. [CSS部分](#css)
  1. [JavaScript部分](#js)
  1. [其他問題](#other)


## <a name='preface'>前言</a>

前端工作包羅萬象，尤其在近幾年不斷提高學習曲線，
雖然 CSS 並不是一種很複雜的技術，但就算是一個使用 CSS 多年的高手，仍然會有很多CSS用法/屬性/屬性值你從來沒使用過，甚至從來沒聽說過。

以下問題可能包山包海，請盡可能的作答，甚至多數都可以 search 到答案，也可以就本次經驗順便腦補一下。

而實作的題目可能就要自己動點腦筋，發會想像力了。


## <a name='html'>HTML</a>

 1. Doctype 作用？standards mode 與 quirks mode 如何區分？它們有何意義?

    A:
    ```
    ```

 2.  inline 元素有哪些？block 元素有哪些？

    A:
    ```
    ```

 3.  html5有哪些新特性、移除了那些元素？如何處理HTML5新標簽的瀏覽器兼容問題？如何區分 HTML 和 HTML5？

    A:
    ```
    ```
 4.  HTML 語義化的理解？ (寫)描述一段語義的 html 代碼吧。

    A:
    ```
    ```

 5.  HTML5的離線儲存？

    A:
    ```
    ```

 6.  瀏覽器是怎麼對HTML5的離線儲存資源進行管理和加載的呢？

    A:
    ```
    ```

 7.  請描述一下 cookies，sessionStorage 和 localStorage 的區別？

    A:
    ```
    ```

 8.  Label 的作用是什麼？是怎麼用的？

    A:
    ```
    ```

 9.  如何實現瀏覽器內多個標簽頁之間的通信?

    A:
    ```
    ```

 10.  webSocket 如何相容低瀏覽器？

    A:
    ```
    ```

 11.  Page Visibility API 可以有哪些範例？

    A:
    ```
    ```

 12.  你如何解決瀏覽器的相容的問題？常見的 Moderniz 外有更好的作法嗎？

    A:
    ```
    ```

## <a name='css'>CSS</a>

1. 說明 CSS 的盒子模型？

    A:
    ```
    ```

1. CSS 選擇器有哪些？哪些屬性可以繼承？優先級算法如何計算？ CSS3 新增偽類有那些？

    A:
    ```
    ```

1. 列出 display 的值，說明他們的作用。position 的值， relative 和 absolute 定位原點是？

    A:
    ```
    ```

1. 為什麼要初始化CSS樣式。

    A:
    ```
    ```

1. 請解釋一下 CSS3 的 Flexbox? 已經適用場景？

    A:
    ```
    ```

1. li 與 li 之間有看不見的空白間隔是什麼原因引起的？有什麼解決辦法？

    A:
    ```
    ```

1. display: inline-block 會顯示間隙怎麼辦？

    A:
    ```
    ```

1. absolute 的 containing block 計算方式跟 fixed positioning 有什麼不同？

    A:
    ```
    ```

1. CSS 定義的權重？

    A:
    ```
    ```

1. 解釋下 float 和它的工作原理？清除 float 的技巧

    A:
    ```
    ```

1. 怎麼讓 Chrome 支持小於12px 的文字？

    A:
    ```
    ```

1. 讓頁面裡的字體變清晰，變細用 CSS 怎麼做？

    A:
    ```
    ```

1. 元素橫向的百分比設定是相對於容器的寬度嗎？

    A:
    ```
    ```

1. 你使用 CSS 預處理器嗎？喜歡那個？

    A:
    ```
    ```

1. 你用什麼方式優化 CSS 、提高性能的方法有哪些？

    A:
    ```
    ```

1. 什麼是響應式設計？為什麼要做響應式設計？響應式設計的基本原理是什麼？如何兼容低版本的 IE？

    A:
    ```
    ```

1. 你用過 @media queries ，針對 mobile 的排版嗎？

    A:
    ```
    ```

1. 用純 CSS 創建一個三角形

    A:
    ```
    ```

1. 針對下述 line-height 是如何理解的？

    A:
    ```
	body {
		font-size: 16px;
		font-size: 2rem;
		line-height: 32px;
	}
	.imgod {
		font-size: 3rem;
		line-height: 5;
	}
	/* .imgod 的line-height 是幾px */

    ```

1. 請實作三欄區塊，且可隨內容增加維持彼此等高

    ![等高](https://github.com/jerrysdesign/Front-End-Developer-Questions/blob/master/images/_3-col-auto-height.pngg)

    A:
    ```
    可使用 codepen or jsfiddle or jsbin，並附上連結
    ```

1. 請實作一個全螢幕下的九宮格？條件不可使用 height

    ![九宮格](https://github.com/jerrysdesign/Front-End-Developer-Questions/blob/master/images/_9-block.png)

    A:
    ```
    可使用 codepen or jsfiddle or jsbin，並附上連結
    ```
1. 請使用 yeoman generator-lb 構一個環境，並使用 bower install 'animateCSS'，並發佈於 github

    A:
    ```
    可使用 codepen or jsfiddle or jsbin，並附上連結
    ```


## <a name='js'>JavaScript</a>

-  用原生JavaScript的實現過什麼功能嗎？

-  介紹JavaScript的基本數據類型。

-  說幾條寫JavaScript的基本規範？

-  JavaScript原型(prototype)? 每個JS對像都有原型屬性嗎？

-  JavaScript有幾種類型值？（堆：原始值和 棧：引用值），你能畫一下他們的內存圖嗎？

-  Javascript如何實現繼承？

-  如何創建一個對像? （畫出此對像的內存圖）

-  談談This對像的理解。

-  eval是做什麼的？

-  什麼是window對像? 什麼是document對像?

-  null，undefined的區別？

-  寫一個通用的事件偵聽器函數。

-  ["1", "2", "3"].map(parseInt) 答案是多少？

-  事件、IE與火狐的事件機制有什麼區別？ 如何阻止冒泡？

-  什麼是閉包（closure），為什麼要用它？

-  "use strict";是什麼意思 ? 使用它的有什麼好處或壞處？

-  如何判斷一個對像是否屬於某個類？

-  new 操作符具體干了什麼呢?

-  Javascript中，有一個函數，執行時對像查找時，永遠不會去查找原型，這個函數是？

-  對JSON的了解？

-  `[].forEach.call($$("*"),function(a){
  a.style.outline="1px solid #"+(~~(Math.random()*(1<<24))).toString(16)
})` 能解釋一下這段代碼的意思嗎？

-  js延遲加載的方式有哪些？

-  ajax是什麼?

-  同步和異步的區別?

-  如何解決跨域問題?

-  模塊化開發怎麼做？

-  requireJS 的核心原理是什麼？（如何動態加載的？如何避免多次加載的？如何緩存的？）

-  知道 ECMAScript 6 裡怎麼寫 class 嗎?

-  AMD（Modules/Asynchronous-Definition）、CMD（Common Module Definition）規範區別？

-  非同步加載加載的方式有哪些？

-  .call() 和 .apply() 的區別？

-  JavaScript 中的作用域與變數量宣告提升？

-  如何編寫高性能的 Javascript？

-  那些操作會造成內存泄漏

-  jQuery

    -  JQuery 的源碼看過嗎？能不能簡單說一下它的實現原理？

    -  jQuery.fn 的 init 方法返回的 this 指的是什麼對像？為什麼要返回 this？

    -  jquery 中如何將數組轉化為json字符串，然後再轉化回來？

    -  jQuery 的屬性拷貝(extend)的實現原理是什麼，如何實現深拷貝？

    -  jquery.extend 與 jquery.fn.extend的區別？

    -  jQuery 的隊列是如何實現的？隊列可以用在哪些地方？

    -  談一下 Jquery 中的 bind(),live(),delegate(),on()的區別？

    -  JQuery 一個對像可以同時綁定多個事件，這是如何實現的？

    -  jQuery 是通過哪個方法和 Sizzle 選擇器結合的？（jQuery.fn.find()進入Sizzle）

    -  針對 jQuery 性能的優化方法？

    -  Jquery 與 jQuery UI 有啥區別？

    -  jQuery 和 Zepto的區別？各自的使用場景？

    -  Zepto的點透問題如何解決？

    -  jQueryUI 如何自定義組件?

-  寫一個無刷新的網站，並且能在瀏覽器前進、後退時正確響應怎麼實現？

-  如何判斷當前腳本運行在瀏覽器還是 node 環境中？

-  Mobile side 最小觸控區域是多少？

-  jQuery 的 slideUp 動畫 ，如果目標元素是被外部事件驅動, 當鼠標快速地連續觸發外部元素事件, 動畫會滯後的反復執行，該如何處理呢?
-  把 Script 標簽 放在頁面的最底部的body封閉之前 和封閉之後有什麼區別？瀏覽器會如何解析它們？

-  移動端的點擊事件的有延遲，時間是多久，為什麼會有？ 怎麼解決這個延時？（click 有 300ms 延遲,為了實現safari的雙擊事件的設計，瀏覽器要知道你是不是要雙擊操作。）

-  知道各種JS框架(Angular, Backbone, Ember, React, Meteor, Knockout...)麼? 能講出他們各自的優點和缺點麼?
-  Underscore 對哪些 JS 原生對像進行了擴展以及提供了哪些好用的函數方法？

-  Node.js的適用場景？

-  (如果會用node)知道route, middleware, cluster, nodemon, pm2, server-side rendering麼?
-  解釋一下 Backbone 的 MVC 實現方式？

-  什麼是“front end router”? 什麼時候適合使用“front end router”?  “front end router”有哪些優點和缺點?

-  知道什麼是 webkit 嗎? 知道怎麼用瀏覽器的各種工具來和 debug 麼?

- 如何測試前端代碼麼?


## <a name='other'>其他問題</a>

- 現公司工作流程是怎麼樣的，如何與其他人協作的？

- 你遇到比較難的技術問題是？你是如何解決的？

- 設計模式 知道什麼是 singleton, factory, strategy, decrator麼?

- 常使用的 library 有哪些？常用的前端開發工具？開發過什麼應用或組件？

- 頁面重構怎麼操作？

- 列舉 IE 與其他瀏覽器不一樣的特性？

- 什麼叫優雅降級和漸進增強？

- WEB app 從 server 主動推送 Data 到客戶端有那些方式？

- 對 Node 的優點和缺點提出了自己的看法？

- 你有用過哪些前端性能優化的方法？

- http 狀態碼有那些？分別代表是什麼意思？

- 一個頁面從輸入 URL 到頁面加載顯示完成，這個過程中發生了些什麼？（流程說的越詳細越好）

- 除了前端以外還了解什麼其它專長嗎？你最最厲害的技能是什麼？

- 你順手熟練的編輯器 & 開發環境是什麼樣子？

- 對前端界面工程師這個職位是怎麼樣理解的？它的前景會怎麼樣？

- 對加班的看法？

- 平時如何管理你的專案資料？

- Git 知道 branch, diff, merge麼?

- 當團隊人手不足，把功能代碼寫完已經需要加班的情況下，你會做前端 souce code 的 testing 嗎？

- 說說最近最流行的一些東西吧？平時常去哪些網站？

- 你在現在的團隊處於什麼樣的角色，最明顯的作用是？

- 你認為怎樣才是全端工程師（Full Stack developer）？

- 介紹一個你最得意的作品吧？

- 你有自己的技術 blog 嗎，常去那些技術 blog？

- 對前端安全有什麼看法？

- 最近在學什麼？能談談你未來3，5年給自己的規劃嗎？


## 有趣的問題


- .A、B兩人分別在兩座島上。B生病了，A有B所需要的藥。C有一艘小船和一個可以上鎖的箱子。C願意在A和B之間運東西，但東西只能放在箱子裡。只要箱子沒被上鎖，C都會偷走箱子裡的東西，不管箱子裡有什麼。如果A和B各自有一把鎖和只能開自己那把鎖的鑰匙，A應該如何把東西安全遞交給B？


	    答案：A把藥放進箱子，用自己的鎖把箱子鎖上。B拿到箱子後，再在箱子上加一把自己的鎖。
	    箱子運回A後，A取下自己的鎖。箱子再運到B手中時，B取下自己的鎖，獲得藥物。



#實作測驗 （題目列表頁）


## CSS 排版

  1. [清除浮動](#clear)
  1. [文字換行](#wordwrap)
  1. [多元素水平居中](#aligncenter)
  1. [畫一個三角形](#triangle)
  1. [多欄自適應排版](#boxflex)
  1. [css3文字分欄](#column)
  1. [flex 排版](#flexbox)
  1. [未知高度多行文本垂直居中](#js)
  1. [修復側邊欄](#fix)
  1. [超過一定長度，以'...'顯示](#fix)


## <a name='clear'>清除浮動</a>

 1. 當容器內容中有浮動（float為left或right）的元素，在這種情況下，容器的高度不能自動伸長以適應內容的高度，使得內容溢出到容器外面而影響（甚至破壞）佈局的現象。這個現象叫浮動溢出，為了防止這個現象的出現而進行的CSS處理，就叫CSS清除浮動。分別使用兩種不同的解法讓 '.container' 可以正常顯示

    [CODEPEN](http://codepen.io/djjd/pen/KdzLqr)
    
    HTML:
    ```
    <div class="container">
      <div class="left-float"></div>
      <div class="right-float"></div>
    </div>
    ```
    
    CSS:
    ```
    .container {
      border: 3px dotted #000;
      padding: 20px;
    }

    .left-float {
      float: left;
      width: 50px;
      height: 50px;
      background: #ccc;
    }

    .right-float {
      float: left;
      width: 100px;
      height: 100px;
      background: pink;
    }

    ```

    A:
    ```
    ```

## <a name='clear'>畫一個朝右的三角形</a>

 1. 用 CSS3 畫一個朝右的三角形

    A:
    ```
    ```




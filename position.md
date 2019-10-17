# Position

Position屬性元素有以下幾種

* static 
* relative
* absolute
* fixed
* inherit

### static

預設值，沒有定位，也就是一般配置。只會照著瀏覽器預設的配置自動排版在頁面上，無法用top、bottom、left、right 、z-index來做定位。

```css
.static {
      width: 30px;
      height: 100px;
      background-color: rgb(231, 13, 133);
      color: #ffffff;
      text-align: center;
      line-height: 25px;
      position: static;
    }
```

![](.gitbook/assets/static.jpg)

![](.gitbook/assets/image%20%286%29.png)

### relative 相對定位

定位表現起始會和static 一樣，但可以給與其他額外屬性設定，top、left、right、bottom，不會影響其他元素原本所在的位置。



```css
  .relative {
      width: 30px;
      height: 100px;
      background-color: rgb(231, 13, 133);
      color: #ffffff;
      text-align: center;
      line-height: 25px;
      position: relative;
      left: 150px;
      top: 100px;
    }
```

![](.gitbook/assets/image%20%281%29.png)

### absolute 絕對定位

absolute會相對於它的父元素進行定位元素定位，如果沒有父元素則會以網頁最外層也就是&lt;body&gt;，左上角的絕對位置來定位。

```css
.absolute {
      width: 30px;
      height: 100px;
      background-color: rgb(231, 13, 133);
      color: #ffffff;
      text-align: center;
      line-height: 25px;
      position: absolute;
      right: 50px;
      top: 100px;
    }
```

![](.gitbook/assets/image%20%2812%29.png)

![](.gitbook/assets/image%20%2845%29.png)

![](.gitbook/assets/image%20%2810%29.png)

最外框父元素設定相對定位 `position: relative;` 它的子元素\(也就是今日公告\)套用絕對定位 `position: absolute;` 就會以父元素來做定位的標準。

如果父元素使用 `position: static;`，子元素會忽略它，並以網頁&lt;body&gt;來做定位標準。

### fixed 固定定位

它會以相對於瀏覽器視窗來定位，即使頁面捲動，它會固定在設定的位置。

```css
 .fixed {
      width: 30px;
      height: 100px;
      background-color: rgb(231, 13, 133);
      color: #ffffff;
      text-align: center;
      line-height: 25px;
      position: fixed;
      right: 0;
      top: 100px;
    }
```

![](.gitbook/assets/image%20%285%29.png)




# Position運用在網頁上

Position 在網頁拼板上，很常運用到。

### 建立網頁最外部框架

會看到右邊預覽只有一條紅線，因為外框裡面沒有塞東西進去，版面還沒有撐起來。

![](.gitbook/assets/image%20%286%29.png)

建立ul選單

![](.gitbook/assets/image%20%283%29.png)

一開始&lt;body&gt;都有預設**8像素的空隙**，這會導致網頁都會無法貼其瀏覽器，所以要將瀏覽器默認的設定重置，所以要在body上面下重置語法。

```css
 body{ 
 margin: 0; 
 padding: 0; 
 }
```

![](.gitbook/assets/image.png)

瀏覽器在很多元素上面都有默認的屬性，例如: li 、 input 、 table 、 ol...等，做網頁開始，會有習慣全部重置，網路上已經有人寫好CSS reset ，我們只要引入或是外部連結進網頁就可以了。

[https://meyerweb.com/eric/tools/css/reset/](https://meyerweb.com/eric/tools/css/reset/)

將nav加入背景色比較容易識別，並讓選單靠上靠左貼其瀏覽器。

![](.gitbook/assets/image%20%2836%29.png)


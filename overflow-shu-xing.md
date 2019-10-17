# overflow 屬性

### **`overflow: hidden`**

很常運用在隱藏多餘文字上。

![](.gitbook/assets/image%20%2831%29.png)

![](.gitbook/assets/image%20%2826%29.png)

### `overflow: auto`

預設就是會自動產生捲軸效果，但要請先設定寬或是高。

![](.gitbook/assets/image%20%2825%29.png)

![](.gitbook/assets/image%20%2832%29.png)

### `overflow: visible`

超出的範圍的文字並不會隱藏，會直接顯示出來

```css
.Text3 {
      height: 75px;
      overflow-x: hidden;
      overflow-y: auto;
    }
```

![](.gitbook/assets/image%20%2845%29.png)

### `overflow: scroll`

無論文字內容放得下放不下，都加入上捲軸功能直接以捲軸呈現。

```css
 .Text3 {
      height: 75px;
      overflow: scroll;
    }
```

![](.gitbook/assets/image%20%2848%29.png)

指定卷軸會自動產生水平捲軸，如果不想讓水平卷軸出現，也可以這樣寫

```css
overflow-x: hidden;
overflow-y: auto;
```

![](.gitbook/assets/image%20%2816%29.png)


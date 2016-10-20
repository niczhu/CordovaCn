如果单纯的使用
```html
<input type="search">
```
在移动端的弹出键盘是不显示成search类型的。我们需要套一个form在外面，并且必须指定一个action属性
```html
<form action="">
  <input type="search">
</form>
```

(作者@Ryouaki)

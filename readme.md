
使用说明

```javascript
$("#search-button").popup({
	top: '56px',
	right: '65px',
	overlay: 0.1,
	focus: '#s',
	close: '.hidewindow'
});
```

> 参数:
top:    弹窗顶端边距(默认垂直居中,居顶参数优先)
bottom: 弹窗底部边距(默认垂直居中)
left:   弹窗左侧边距(默认水平居中,居左参数优先)
right:  弹窗右侧边距(默认水平居中)
overlay:覆盖层透明度(默认0.1,越小颜色越浅)
focus:  窗口弹出后焦点元素选择器(默认无)
close:  关闭按钮选择器(默认无)

CSS文件
```css
#popup_overlay{position:fixed;top:0;left:0;z-index:10004;display:none;width:100%;height:100%;background:#000}
```
# 文本溢出显示省略号

## 单行文本溢出显示省略号

```css
width:50px;/*兼容部分浏览器*/
overflow: hidden;
text-overflow:ellipsis;
white-space: nowrap;
```



## 多行文本溢出显示省略号

```css
display: -webkit-box;/*将对象作为弹性伸缩盒子模型显示*/
-webkit-box-orient: vertical;/*设置或检索伸缩盒对象的子元素的排列方式*/
-webkit-line-clamp: 3;/*限制在一个块元素显示的文本的行数*/
overflow: hidden;
```

# 瀑布流

使用columns多列布局

使用flex布局

使用isopojs插件

使用masonryjs插件


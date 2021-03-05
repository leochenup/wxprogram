## swiper
## scroll-view
    enable-flex="true" 
    scroll-x="true"
## 阿里 iconfont
## 单行、多行文字超出范围显示 ...
```css
/*单行*/
selector {
    display: block;
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
}

/*多行*/
selector {
    overflow: hidden;
    text-overflow: ellipsis;
    display: -webkit-box;
    -webkit-box-orient: vertical; /*设置对齐模式*/
    -webkit-line-clamp: 2;/*设置显示两行*/
}

```
### form表单元素的样式初始化

在开发过程中往往会遇到表单相关元素样式重置，下面是我的一些处理策略：

```css
.form-ele-reset{
    margin: 0;
    padding:0;
    line-height:inherit;
    vertical-align: middle;
    font: inherit;
    color:inherit;
    background-color: transparent;
    box-shadow: none;
    appearance: none;
    -webkit-appearance: none;
    -moz-appearance: none;
    border:0;
    outline:0;
    border-radius:0;/*IOS*/
    resize: none;
}
```


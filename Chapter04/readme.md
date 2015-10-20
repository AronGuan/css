1. css-button:  
用css实现按钮    
2. css-rollover:
改变背景，text-indext是首行缩进，针对字体，如果用padding的话，会影响到背景颜色，不一定行  
3. css-tooltips:  
通过css来实现超链接提示，关键在于absolut和relative想配合

4. external-links:  
实现在超链接上加上提示图标  
    
    a[href^="http:"] {
        background: url(images/externalLink.gif) no-repeat right top;
        padding-right: 10px;}

5. pixy-rollover:  
通过背景图片的转移来实现背景的转变  
 `background: #94B8E9 url(images/pixy-rollover.gif) no-repeat left top;`  
 `background-position: right top;`  
6. visited-links:  
对列表自己义样式，关键是`list-style-type:none;`去掉原有样式
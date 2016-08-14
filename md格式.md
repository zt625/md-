#md格式
1. 123
2. 456
##二级标题
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Document</title>
    <style>
        .box{ 
        position:relative; 
        width:200px; 
        height:200px; 
        border:1px solid #666; 
        z-index:0;
    }

.box .bg{ 
    background:red; 
    position:absolute; 
    z-index:-1; 
    opacity:0.5; 
    filter:alpha(opacity=50); 
    width:100%; 
    height:100%;
}
    </style>
</head>
<body>
<div class="box">
    <!-- 背景 -->
    <div class="bg"></div>
    <!-- 内容 -->
    <div class="text">
        <p>呵呵，我不受透明度影响！</p>
    </div>
</div>
</body>
</html>
```
```javascript

```
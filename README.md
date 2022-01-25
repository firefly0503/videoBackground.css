# 视频背景.css
一个纯 CSS3 方法，将视频媒体作为背景属性元素。

### 1. 如何使用？

#### 1.1 插入 HTML

在 `<body>` 主体中插入多种格式的背景视频：

```html
<video autoplay loop poster="images/moon.jpg" id="moon">
	<source src="images/moon.webm" type="video/webm">
	<source src="images/moon.mp4" type="video/mp4">
</video>
```

#### 1.2 添加 CSS

使用如下 CSS 样式：

```css
@media screen and (max-width: 500px) {
	div{width:70%;}
}

@media all and (max-device-width: 800px) {
	body {
    background: url("images/moon.jpg") #000 no-repeat center center fixed; 		
    background-size: cover;
  }
	#bgvid, #polina button { display: none; }
	div{width:70%;}
}
```

### 2. 一个演示

一个演示页面：[点击这里](https://github.nousbuild.com/demo/video-background/index.html)

![Moon](assets/videobackground.jpg)

### 3. 许可

[MIT License](https://github.com/windmill0503/videoBackground/blob/master/LICENSE)
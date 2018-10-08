# Video Background
Making video as a page background

## Installation
### HTML
Insert into `<body>:`

```html
<video autoplay loop poster="images/moon.jpg" id="moon">
<source src="images/moon.webm" type="video/webm">
<source src="images/moon.mp4" type="video/mp4">
</video>
```

### CSS
Add a short css into`<body>:`

```html
<style>
@media screen and (max-width: 500px) {
div{width:70%;}
}
@media all and (max-device-width: 800px) {
body { background: url("images/moon.jpg") #000 no-repeat center center fixed; background-size: cover; }
#bgvid, #polina button { display: none; }
div{width:70%;}
}
</style>
```

Then link a `css/videobg.css` file to make full-screen processing.

## Demo
[Demo Page](http://www.nousbuild.org/demo/background-video-cover/index.html)</br>
![Moon](http://img.nousbuild.top/github/videobackground.jpg)

## Legal
Copyright (c) 2016： [windmill0503](https://github.com/windmill0503)
Show it on Code Studio [this article](http://www.nousbuild.org/codeu/background-video/)
# videoBackground.css
Making video as a page background

## Installation
### HTML
Insert into `<body>:`</br>
`<video autoplay loop poster="images/moon.jpg" id="bgvid">`</br>
`<source src="images/moon.webm" type="video/webm">`</br>
`<source src="images/moon.mp4" type="video/mp4">`</br>
`</video> `

### CSS
Add a short css into`<body>:`</br>
`<style>`</br>
`@media screen and (max-width: 500px) {`</br>
`  div{width:70%;} `</br>
`}`</br>
`@media all and (max-device-width: 800px) {`</br>
`  body { background: url("images/moon.jpg") #000 no-repeat center center fixed; background-size: cover; }`</br>
`  #bgvid, #polina button { display: none; }`</br>
`  div{width:70%;}`</br>
`}`</br>
`</style>`</br>

Then link a `css/videobg.css` file to make full-screen processing.

## Demo
[Demo Page](http://www.nousbuild.org/demo/background-video-cover/index.html)</br>
![Moon](http://www.nousbuild.org/demo/githubimages/videobackground.jpg)

## Legal
copyright (c) 2016： [firefly0503](https://github.com/firefly0503)
Show it on Code Studio [this article](http://www.nousbuild.org/codeu/background-video/)

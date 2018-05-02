# VerificationCode
## 效果图   
![效果图](result.jpg)
## Demo
演示地址：[demo](https://redjupid.github.io/VerificationCode/demo.html)
## Quick Start
### 1.Get some image with size of 300*200
### 2.import RedJu.js and RedJu.css
```html
<link rel="stylesheet" type="text/css" href="RedJu.css">
<script type="text/javascript" src="RedJu.js"></script>
```
### 3.Add html and you must create elements like this
```html
<div id="slideVerify">
    <div class="image">
        <div class="chip2"></div>
        <div class="chip"></div>
    </div>
  <div class="drag">
        <div class="bg"></div>
        <div class="text" onselectstart="return false;">请拖动滑块解锁</div>
        <div class="btn">&gt;&gt;</div>
    </div>
</div>
```
### 4.Finally new Object to import the plugin
```javascript
<script type="text/javascript">
  var slideVerify = new SlideVerify("img/",9);
</script>
```
`SlideVerify()`'s first arguments represent the path of your image and the second arguments represent your number of image.You must name your image like `0.jpg`,`1.jpg`...

# VerificationCode
##效果图
![Alt text](result.jpg)
##How To Use
###Get some image with size of 300*200
###import RedJu.js and RedJu.css
'<link rel="stylesheet" type="text/css" href="RedJu.css">
<script type="text/javascript" src="RedJu.js"></script>'
###Add HTML and you must create elements like this
'<div id="slideVerify">
		<div class="image">
        	<div class="chip2"></div>
        	<div class="chip"></div>
    	</div>
		<div class="drag">
        	<div class="bg"></div>
        	<div class="text" onselectstart="return false;">请拖动滑块解锁</div>
        	<div class="btn">&gt;&gt;</div>
    	</div>
	</div>'
  ###finally new Object to import the plugin
  '<script type="text/javascript">
		var slideVerify = new SlideVerify("img/",9);
	</script>'

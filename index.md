<link href="assets/css/style.scss" rel="stylesheet">

## Welcome to Cornea Project Website.

### Slice Visualization

<script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/jquery/2.1.4/jquery.min.js"></script>
<script> 
	function createIframe(){
		var i = document.createElement("iframe");
		i.src = "https://valentina-s.github.io/volumeJS/index.html";
		i.frameborder = "0";
		i.width = "800px";
		i.height = "600px";
		allowfullscreen="allowfullscreen";
		document.getElementById('contentframeindex').appendChild(i);
	};
	
		if (window.addEventListener)
		window.addEventListener("load", createIframe, false);
		else if (window.attachEvent)
		window.attachEvent("onload", createIframe);
		else window.onload = createIframe;		
</script>

<style> 
	#contentframeindex{
	position: relative; 
	top: 160px; 
	left: 50px;
	}
</style>

<div id="contentframeindex"></div>

### Volume Visualization

<script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/jquery/2.1.4/jquery.min.js"></script>
<script> 
	function createIframe(){
		var i = document.createElement("iframe");
		i.src = "https://valentina-s.github.io/WebGLVolumeRendering/Index_eye.html";
		i.frameborder = "0";
		i.width = "800px";
		i.height = "600px";
		allowfullscreen="allowfullscreen";
		document.getElementById('contentframe').appendChild(i);
	};
	
		if (window.addEventListener)
		window.addEventListener("load", createIframe, false);
		else if (window.attachEvent)
		window.attachEvent("onload", createIframe);
		else window.onload = createIframe;
</script>

<style> 
	#contentframe{ 
		position: relative; 
		top: 500px; 
		left: 50px; 
		bottom: 100px;
	}
</style>

<div id="contentframe"></div>

<br/>


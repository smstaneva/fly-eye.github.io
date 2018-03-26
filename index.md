<link href="assets/css/style.scss" rel="stylesheet">

<h2> Welcome to Cornea Project Website.</h2>

<h3>Slice Visualization</h3>

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
	}
</style>



<div id="contentframeindex"></div>

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
	.volume{
	position: relative;
	top:200px;
	left:50px;}

	#contentframe{ 
		position: relative; 
	}
	
</style> 

<h3 class="volume";> Volume Visualization </h3>

<div id="contentframe"></div>

<br/>


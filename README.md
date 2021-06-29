<p>вставлять - Insert - დაამატეთ<span style="color: #e03e2d;"><b>main.tpl-ში </b></span></p>
<p><span style="color: #e03e2d;"><b><span style="color: #000000;">&lt;/head&gt;</span></b></span></p>
<pre class="language-markup"><code>&lt;link rel="stylesheet" type="text/css" href="{THEME}/css/jquery.fancybox.min.css"&gt;</code></pre>
<p><span style="color: #e03e2d;"><b><span style="color: #000000;">&lt;/body&gt;</span></b></span></p>
<pre class="language-javascript"><code>&lt;script src="{THEME}/js/jquery.fancybox.min.js"&gt;&lt;/script&gt;
	   &lt;script&gt;
        $('[data-fancybox]').fancybox({
    loop: true,
            buttons: [ 
   "zoom",
   "share",
   "slideShow",
   "fullScreen",
   "download",
   "thumbs",
   "close"
],
    autoFocus: false
});
    &lt;/script&gt;</code></pre>

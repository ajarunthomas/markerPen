# markerPen
Include a marker pen for your webpage
<br>
Developed by Arun Thomas
<br>
www.ajarunthomas.com
<br>
<br>
<a href="http://www.ajarunthomas.com/jquery/markerPen/demo/" target="_blank" style="text-decoration:none">Demo</a>
<a download href="http://www.ajarunthomas.com/jquery/markerPen/js/markerPen.js" target="_blank" style="text-decoration:none">Download</a>
<br><br>
<a href="http://www.ajarunthomas.com/jquery/markerPen/" target="_blank" style="text-decoration:none">Website</a>
##USAGE
###Step 1 : Include JS Files
```
<script src="https://code.jquery.com/jquery-1.12.0.min.js"></script>
<script type="text/javascript" src="js/markerPen.js"></script>
```
###Step 2 : Initialize Plugin
```
$(document).ready(function() {
    $.markerPen();
});
```
###More Options
You have three options to specify while initializing the plugin. You can change the color, stroke width and the transparency of the markings. If you don't specify them then the default color is yellow, stroke width is 10 and the opacity is 0.7 .
```
$(document).ready(function() {
    $.markerPen({
        "color":"red",
        "stroke":20,
        "opacity":".5"
    });
});
```

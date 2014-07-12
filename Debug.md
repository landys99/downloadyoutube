Debug
=============

<p>The latest version of the script added support for debugging using the web console. If the script doesn't work, the button disappears or you find other issues, use the instructions below to send some helpful when reporting bugs.</p>

<p><b>Firefox</b></p>

<p>1. open a YouTube video page where you see the bugs. Example: <a href="http://www.youtube.com/watch?v=PK8dsAeMmPk">http://www.youtube.com/watch?v=PK8dsAeMmPk</a></p>

<p>2. open Firefox's web console - Ctrl+Shift+K or use these instructions: <a href="https://developer.mozilla.org/en-US/docs/Tools/Web_Console#Opening_the_Web_Console">https://developer.mozilla.org/en-US/docs/Tools/...</a></p>

<p>3. copy the following code and paste it to the huge box at the bottom of the window using Ctrl+V (Step 3 in the screenshot below):
<br><code>
<br>document.getElementById('download-youtube-video-debug-info').innerHTML+"***"+document.cookie.match(/VISITOR_INFO1_LIVE=([\w\-]*)/g)
<br></code></p>

<p>4. type dyvam in the "Filter" box next to the "clear" button (Step 4 in the screenshot)</p>

<p>5. right-click the long text that starts with "DYVAM - Info" from the console and select "copy".</p>

<p>6. paste the result in a message to <a href="mailto:deadline.support@gmail.com">deadline.support@gmail.com</a> with other information about your issues.</p>

<p><img src="http://i.imgur.com/uKryRkh.png"></p><div></div><b>Chrome and Opera 15+</b><p></p>

<p>- open a YouTube video page that illustrates the bugs. Example: <a href="http://www.youtube.com/watch?v=PK8dsAeMmPk">http://www.youtube.com/watch?v=PK8dsAeMmPk</a>
<br>- open Chrome's Javascript console - Ctrl+Shift+J or use these instructions: <a href="https://developers.google.com/chrome-developer-tools/docs/shortcuts">https://developers.google.com/chrome-developer-...</a>
<br>- copy the following code and paste it to the console using Ctrl+V:
<br><code>
<br>document.getElementById('download-youtube-video-debug-info').innerHTML+"***"+document.cookie.match(/VISITOR_INFO1_LIVE=([\w\-]*)/g)
<br></code>
<br>- select the messages that start with "DYVAM", right-click and then "copy".
<br>- paste the result in a message to <a href="mailto:deadline.support@gmail.com">deadline.support@gmail.com</a> with other information about your issues.</p>

<p><img src="http://i.imgur.com/oUjTg.png"></p><div></div><b>Opera 12</b><p></p>

<p>- open a YouTube video page that illustrates the bugs. Example: <a href="http://www.youtube.com/watch?v=PK8dsAeMmPk">http://www.youtube.com/watch?v=PK8dsAeMmPk</a>
<br>- open Opera Dragonfly - Ctrl+Shift+I, then select "console" - <a href="http://www.opera.com/dragonfly/documentation/">http://www.opera.com/dragonfly/documentation/</a>
<br>- copy the following code and paste it to the console using Ctrl+V:
<br><code>
<br>document.getElementById('download-youtube-video-debug-info').innerHTML+"***"+document.cookie.match(/VISITOR_INFO1_LIVE=([\w\-]*)/g)
<br></code>
<br>- select the result and press Ctrl+C.
<br>- paste the result in a message to <a href="mailto:deadline.support@gmail.com">deadline.support@gmail.com</a> with other information about your issues.</p>

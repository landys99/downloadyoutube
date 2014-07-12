Known issues
================

<p>1. 480p and 1080p are no longer available. YouTube doesn't provide the download links. There's no workaround at the moment.</p>

<p>2. If you don't see the download button for some long videos (&gt;20 minutes), there's an explanation for that.</p>

<p>The extension doesn't show the download button because no download URL is available for that specific video, YouTube doesn't include them. That's pretty rare, but it happens for videos that are delivered using protected streams (rtmpe - <a href="http://en.wikipedia.org/wiki/Real_Time_Messaging_Protocol">http://en.wikipedia.org/wiki/Real_Time_Messagin...</a>). Especially for long videos from premium channels.</p>

<p>As you can read from Wikipedia - <a href="http://en.wikipedia.org/wiki/Protected_Streaming">http://en.wikipedia.org/wiki/Protected_Streaming</a> "Protected Streaming is a DRM technology by Adobe. The aim of the technology is to protect digital content (video or audio) from unauthorized use." </p>

<p>To check if YouTube actually uses encrypted streams, right-click the page, select "view page source" or a similar option and search for <b>rtmpe</b> inside the page (Ctrl+F). If you find some matches for this keyword, then YouTube uses DRM to stream the video. Some examples: <a href="http://www.youtube.com/watch?v=-x6-MXJaPxc">http://www.youtube.com/watch?v=-x6-MXJaPxc</a>, <a href="http://www.youtube.com/watch?v=4mbQPvztAP8">http://www.youtube.com/watch?v=4mbQPvztAP8</a>.</p>

<p>There are some applications that let you save to disk rtmp streams - <a href="http://en.wikipedia.org/wiki/Real_Time_Messaging_Protocol#Client_software">http://en.wikipedia.org/wiki/Real_Time_Messagin...</a> . Most of the them use rtmpdump - <a href="http://rtmpdump.mplayerhq.hu/">http://rtmpdump.mplayerhq.hu/</a>, which can't download Youtube's rtmpe videos because Google uses Handshake 10 Encryption, a feature that's not implemented in rtmpdump yet.</p>

<p>3. If all the downloaded videos are saved with the filename "videoplayback", clear the cookies for youtube.com. Here are the instructions for Firefox: <a href="http://support.mozilla.org/en-US/kb/delete-cookies-remove-info-websites-stored#w_delete-cookies-for-a-single-site">http://support.mozilla.org/en-US/kb/delete-cook...</a> and for Chrome: <a href="https://support.google.com/chrome/answer/95647?hl=en">https://support.google.com/chrome/answer/95647?...</a>. Search for youtube.com and remove all the cookies.</p>

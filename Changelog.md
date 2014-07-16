## Download YouTube Videos as MP4: Changelog


##### 1.7.22
* bug fix for signature detection (thanks, jfurg26)

##### 1.7.21
* support for YouTube's latest UI experiment (thanks, David Book)

##### 1.7.19
* bug fix for signature detection

##### 1.7.18
* Korean translation (thanks, daunmore - <a href="http://userscripts.org/topics/147092">http://userscripts.org/topics/147092</a>)
* improved URL matching
* better file size detection
* Dash improvements:
 * setting for enabling Dash formats (if you use Scriptish in Firefox or the standalone Firefox extension, go to about:config, search for download-youtube-dash-enabled and change the value to 1. To disable Dash items, change the value to 0.)
 * 256kbps Dash audio is back (thanks, Lunboks - <a href="http://userscripts.org/topics/135892">http://userscripts.org/topics/135892</a>)
 * added support for 1440p Dash videos
 * replaced 4K labeling with 2160p

##### 1.7.17
* AJAX support for channels
* dropped file size styling

##### 1.7.15
* added file size next to each download option
* bug fixes

##### 1.7.14
* removed 480p FLV, 1080p MP4, 4K MP4. They're no longer available.

##### 1.7.13
* signature bug fix

##### 1.7.12
* brings back support for 480p FLV, 1080p MP4, 4K MP4. 
Thanks, Xytras, Morten79, toejam119, ReadALot, Denisk, Tupring, milkywaif, funkinlesson and FlashGot devs.

##### 1.7.10
* fixes for the AJAX interface in Chrome

##### 1.7.9
* added low-quality FLV fallback - the 240p FLV option is added if no other FLV download URL is available
* the script now works when cookies are disabled (thanks, soft475u - <a href="http://userscripts.org/users/529340">http://userscripts.org/users/529340</a>)

##### 1.7.8
* dropped Feather support
* fix for the "share buttons" experiment - <a href="https://plus.google.com/111166827982420581810/posts/DYdHZouXbAP">https://plus.google.com/111166827982420581810/p...</a>

##### 1.7.7
* using the GreaseMonkey API to store signature data (thanks, Eric - <a href="http://userscripts.org/topics/129461">http://userscripts.org/topics/129461</a>)
* inline signature update
* Indonesian translation (thanks, <a href="http://userscripts.org/users/bayuah">http://userscripts.org/users/bayuah</a>)

##### 1.7.6
* updated Ajax support

##### 1.7.3, 1.7.5
* restored some features from 1.7

##### 1.7.2
* back to 1.6.3
* fixed signature obfuscation

##### 1.7
* fixed signature obfuscation (Firefox/Chrome)
* better support for the AJAX experiment

##### 1.6.3
* added support for Hindi (thanks, Arpit Kumar)
* fixed signature obfuscation

##### 1.6
* supports the new experimental Ajax interface
<a href="http://googlesystem.blogspot.com/2013/05/youtube-search-experiments.html">http://googlesystem.blogspot.com/2013/05/youtub...</a>
* workaround for Chrome's unsafeWindow bug fix

##### 1.5.18
* fixed the same old signature obfuscation

##### 1.5.17
* removed the Chrome workaround for unsafeWindow (thanks, ngyikp - <a href="http://userscripts.org/topics/127453">http://userscripts.org/topics/127453</a>)

##### 1.5.16
* added Turkish translation (thanks, fader ed - <a href="http://userscripts.org/users/240701">http://userscripts.org/users/240701</a>)
* cosmetic fixes for non-English interfaces
* more bug fixes

##### 1.5.10-15
* keeping up with YouTube's experiments for the signature parameter

##### 1.5.9
* Chinese and Japanese translations (thanks, SiwyPL and JayXon - <a href="http://userscripts.org/users/420869">http://userscripts.org/users/420869</a>)
* bug fix for encrypted signatures

##### 1.5.7.2
* fix for obtaining video information

##### 1.5.7.1
* keeping up with YouTube's experiments for the signature parameter

##### 1.5.7
* Polish translation (thanks, SiwyPL)
* keeping up with YouTube's experiments for the signature parameter

##### 1.5.4-1.5.6
* more bug fixes for the blank download page (YouTube experiments with new signature formats)

##### 1.5.3
* bug fix for blank download page (thanks, Caroline)

##### 1.5.1
* Feather support - <a href="http://www.youtube.com/feather_beta">http://www.youtube.com/feather_beta</a> (thanks, Joe)
* removed FLV 240p

##### 1.5
* faster video info detection
* Czech translation (thanks, Baegus - <a href="http://userscripts.org/users/495526">http://userscripts.org/users/495526</a>)
* fixed unsafewindow hack in Chrome

##### 1.4.15
* removed black border around the download button

##### 1.4.14
* new debugging mode - <a href="http://userscripts.org/topics/120920">http://userscripts.org/topics/120920</a>

##### 1.4.12
* fixed download button placement for non-English interfaces
* added support for debugging - <a href="http://userscripts.org/topics/120920">http://userscripts.org/topics/120920</a>
* dropped support for the old YouTube interface

##### 1.4.10
* new interface tweaks (YouTube constantly tests new versions of the "watch7" UI)

##### 1.4.9
* fixed button position in the experimental YouTube interface (VISITOR_INFO1_LIVE=vSPn-CmshUU)

##### 1.4.8
* fixed button position in the experimental YouTube interface (VISITOR_INFO1_LIVE=wyVhs9Df-0E)

##### 1.4.7
* fixed code for the HTML5 player

##### 1.4.6
* fixed bug that showed a blank page when downloading videos (thanks, hnch - <a href="http://userscripts.org/topics/115665">http://userscripts.org/topics/115665</a>)
* language translation: Brazilian Portuguese (thanks, Paulo)

##### 1.4.5
* added Italian and Russian translation (thanks, Pietrodn and iHastr - <a href="http://userscripts.org/topics/102662">http://userscripts.org/topics/102662</a>)
* fixed parameter validation

##### 1.4.4
* bug fixes

##### 1.4.3
* initial support for the new YouTube interface that's <a href="http://googlesystem.blogspot.com/2012/06/youtube-tests-new-interface-for-video.html">currently tested</a>. It's not clear if placing the button next to the like/unlike buttons is the right way, but it removes an extra click.

##### 1.4.2
* new video version: WebM 1080p (disabled by default, can be enabled by editing the code and replacing 'webm':'none' with 'webm':'all' ). Thanks, liadb - <a href="http://userscripts.org/topics/113027">http://userscripts.org/topics/113027</a> .

##### 1.4.1
* fixed UI bug (misplaced arrow)

##### 1.4
* messages are translated in French, German, Spanish, Arabic and Romanian (thanks, Ibrahim - <a href="http://userscripts.org/topics/102662">http://userscripts.org/topics/102662</a>)

##### 1.3.9
* simplified code for obtaining video title (thanks, Lunboks)

##### 1.3.8
* updated CSS code (thanks, Fanel89 and TLUL <a href="http://userscripts.org/topics/97909">http://userscripts.org/topics/97909</a>)

##### 1.3.6
* removed Cosmic Panda support
* better validation for video URLs (thanks, Lunboks)

##### 1.3.5
* Cosmic Panda bug fix for videos with transcripts

##### 1.3.4
* bug fix for videos that can't be downloaded because YouTube uses encrypted streams (thanks, pooprscooper)

##### 1.3.3
* auto-update and update checking support for <a href="https://addons.mozilla.org/en-US/firefox/addon/scriptish/">Scriptish</a>
* update checking support for Greasemonkey 0.9.12+ (see <a href="http://www.greasespot.net/2011/09/greasemonkey-0912-release.html">the blog post</a>)
* bug fix for video titles

##### 1.3.2
* more flexible code for selecting formats (now you can easily edit the code, change a setting and add WebM videos or remove FLV videos)
* bug fixes

##### 1.3.1
* visual tweaks for the download button

##### 1.3
* bug fixes, faster code

##### 1.2.5
* fixed code (thanks, TLUL - <a href="http://userscripts.org/scripts/show/109103">http://userscripts.org/scripts/show/109103</a> )

##### 1.2.3
* support for Cosmic Panda (<a href="http://www.youtube.com/cosmicpanda">http://www.youtube.com/cosmicpanda</a>)

##### 1.2.2
* fixed video title

##### 1.2.1
* updated workarounds for YouTube's international versions

##### 1.2
* fixed two important bugs
* better performance for both the Flash player and the HTML5 player

##### 1.1.9
* fixed broken download URLs (YouTube changed the code and started to use Unicode values for ampersands)

##### 1.1.7
* using data URI for script icon, which is now smaller

##### 1.1.6
* simplified code (removed support for Ajax pages, missing FMT18 URLs)
* script icon (requires Greasemonkey 0.9+ or Scriptish)

##### 1.1.3
* tooltip adjustment

##### 1.1.2
* tweaks for YouTube's latest UI changes

##### 1.1.1
* support for <a href="https://www.youtube.com/">https://www.youtube.com</a> (partially secure YouTube pages)

##### 1.1
* HTML5 player support in Google Chrome

##### 1.0.9
* UI tweaks (YouTube changed the interface)

##### 1.0.8
* adjustments for localized interfaces

##### 1.0.6
* added support for the HTML5 player:
 * only works in Opera 10.6+, Firefox 4 beta (unfortunately, Greasemonkey doesn't support Firefox 4, but you might try <a href="http://siliconchaos.blogspot.com/2010/08/firefox-4-beta-extensions-firebug.html">this unofficial version</a>)
 * links to WebM videos aren't included (in Firefox, you can right-click on the video and download the WebM file)

##### 1.0.5
* fixed MP4 360p links (the proper filename is displayed when you right-click and select "save link as")

##### 1.0.4
* fixed MP4 360p

##### 1.0.3
* removed MP4 360p (YouTube returns error 404)
* better support for non-English interfaces

##### 1.0.1
* support for YouTube's AJAX watch pages (only in Firefox and Opera)

##### 1.0
* important parts of the script have been rewritten for the Firefox extension: <a href="https://addons.mozilla.org/en-US/firefox/addon/11869/">https://addons.mozilla.org/en-US/firefox/addon/...</a>

##### 0.9973
* added support for 4K videos: <a href="http://youtube-global.blogspot.com/2010/07/whats-bigger-than-1080p-4k-video-comes.html">http://youtube-global.blogspot.com/2010/07/what...</a>

##### 0.9972
* menu items are now links (that means you can right-click and select "save target as" to change the filename before saving the file). This feature doesn't work in Internet Explorer/IE7Pro.

##### 0.9971
* fix for a small layout change

##### 0.9962
* fix for adding the download button even if there's no flagging button

##### 0.9961
* encode a few characters in the title

##### 0.996
* filenames can now include quotes
* detect broken standard MP4 URLs (only if you use Firefox/Greasemonkey or Chrome)

##### 0.9951
* replace the standard function for simulating a click with a script injection because it doesn't work in Chrome

##### 0.995
* obtain the final redirect URL for standard MP4s, so you'll no longer see video.mp4 in the filename (only if you use Greasemonkey)
* add a standard function for simulating clicks

##### 0.9945
* removed "YouTube -" from filenames
* add the highest-quality FLV file to the download list

##### 0.9944
* add the download button even if there's no flagging button

##### 0.9943
* faster parameter detection

##### 0.9942
* removing more characters from the filename

##### 0.9941
* workaround for FlashBlock

##### 0.994
* simplified code

##### 0.993
* add fake click for the download button to fix a bug

##### 0.992
* included HQ FLV format

##### 0.991
* fix code for adding the download button

##### 0.99
* new code for YouTube's updated interface (April 2010)

##### 0.98
* updated code for Chrome compatibility

##### 0.97
* fallback algorithm for detecting parameters

##### 0.95
* better HD detection

##### 0.9
* fix for YouTube code changes

##### 0.8
* a better way to get parameters

##### 0.7
* HD detection

##### 0.6
* message rewording

##### 0.5
* initial version

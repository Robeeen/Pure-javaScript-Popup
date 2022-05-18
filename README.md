# Pure-javaScript-Popup
A JavaScript Popup with Video, Video playback will stop on click close Button.

I have added a source of Video webm inside a <video></video> HTML Tag. Also have added an ID called "test".
This ID "test" will called by a variable video:

 var video = document.getElementById("test");
            function stopVideo() {
                video.pause();
                video.currentTime = 0;
            }
            
 A function stopVideo() will work to pause video when it called by onlick button ID "Close".
 
 span.onclick = function () {
            modal.style.display = "none";
             stopVideo();
        }
        
This way we can stop the Video when closing a Video Modal or Video Pop-up.

Best Regards.
Shams.

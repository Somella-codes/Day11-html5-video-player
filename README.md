# Day11-html5-video-player
 
Native HTML5 video player built with freeCodeCamp's Responsive Web Design curriculum.

### What I Built
A simple video player using only HTML5. No JavaScript, no frameworks.

**Key feature:** Multiple `<source>` tags for format fallbacks.  
The browser tries MP4 first, then falls back to MOV if needed.

### Screenshot 
![freeCodeCamp Completion 1](Screenshot_2026061620171541_Samsung%20Intenet.jpg)
![freeCodeCamp Completion 2](Screenshot_20260621_134256_Samsung%20Internet.jpg)
*freeCodeCamp "Congratulations" screen after completing the HTML Video Player workshop*

### Code
```html
<video controls width="100%">
  <source src="video.mp4" type="video/mp4">
  <source src="video.mov" type="video/quicktime">
  Your browser does not support the video tag.
</video>

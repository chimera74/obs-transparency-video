Simple script for showning and hiding video on a page.  
Shows video by fading in, plays it, fades out, waits some time and repeats.  
Created by chimera (chimera.alv@gmail.com).  

Requres CLR Browser Plugin to use with OBS.  
Uses jQuery, so requires internet connection to start.  

Setup:  
1. Prepare your video as descriibed on this page http://www.sciencelifeny.com/transparency/transparency.html  
	"Directions", Steps 1-5.  
	TL;DR:  
	You need to make one video with double of original height where top part is the original video and lower part is black-and-white alpha channel.  
2. Save this code as ".html" file.  
3. Specify path to your video in the "<source>" tag.  
4. Set HIDDEN_TIME variable to the time in milliseconds you want video to remain hidden.  
5. After that add new browser source in OBS, specify this html as local file  
	and make sure to set up width and length to fit your video.  
6. Done! The video will be replaying over and over.  
NOTE: If you want to change settings like HIDDEN_TIME varible or video path you have to delete and add browser source again after you save changes.

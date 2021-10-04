---
tutorial:
date: 2021-10-03
tags:Field work and ethical data collection
---

# what I was trying to do

Continue recording gravestones from findagrave.com, create 3d model of an object and try out webmapping

## how it might connect to other research I'm doing

_continuation of last week with the addition of 3d models and webmapping

## what I did
**Recording Gravestones**
+ Continued to enter info into our recording framework
	+ As I am recording the info from the images I have, I am aware that trying to force my "real life" stones into a fixed (non expandable) framework designed for the UK is not ideal. 
		+ Fonts dont always match what is available to record
		+ Hard to determine materials without just "googling" and assuming that what I am seeing on the stone is the same as what my search results yielded
		+ The shape of stones or text boxes often resemble none, some, or many options and I am forced to use my own discretion in entering the information
		+ The exact Denomination is rarely/never available from the stone. I decided to leave this blank, but it would be more accurate to have a "unknown only" field 
		+ using images from the internet means I record the condition of the stone as it is depicted in the image. since the internet, and more specifically findagrave.com has been around for quite sometime, many of the graves I am recording could likely have weathered more since the date my reference image was taken.
			+ this could skew data later if my classmates are using up to date photos of graves from the same period as my own, but theirs may appear to be more weathered than mine. 

		+ I am assuming the date of creation for all stones but I dont have a way to verify this information
		+ The decisions I make in recording my data are likely different than the decision of my classmates. When we compile all this data together, how will these differences be represented?
+ recorded a grave of a 6 year old girl. Will comment more in reflection, but I had to take a break emotionally from logging more graves. I will try and add a few more in week 4 if I can.

**Photogrammetry**
+ Located an object, my acoustic guitar, to turn into a 3D model
	+ Used my DSLR to take lots of photos (Used my DSLR for metadata)
	+ took 35 pictures, hopefully that isnt too much
+ Transferred photos to my google drive
+ Followed each cell of instructions, all ran successfully until the end when I got this error
 ![[Pasted image 20211003221945.png]]
 + navigated to files on the left and attempted to manually download my model
	 + got the texturedMesh.mtl file
	 + Wont prompt me to save texture_0.png or texturedMesh.obj file
	 + Realized google was blocking my download in the top right, so I allowed downloads
	 + That fixed it! I can download manually, will try running the zip cell again
	 + Got the same error for the Zip cell, but at least I have the files. 

+ Zip my files manually
+ signedp for sketchfab 
+ Voila!
 <div class="sketchfab-embed-wrapper"> <iframe title="My Guitar.... Hopefully" frameborder="0" allowfullscreen mozallowfullscreen="true" webkitallowfullscreen="true" allow="autoplay; fullscreen; xr-spatial-tracking" xr-spatial-tracking execution-while-out-of-viewport execution-while-not-rendered web-share src="https://sketchfab.com/models/13094e1686e34e15a888a56ff99da72f/embed"> </iframe> <p style="font-size: 13px; font-weight: normal; margin: 5px; color: #4A4A4A;"> <a href="https://sketchfab.com/3d-models/my-guitar-hopefully-13094e1686e34e15a888a56ff99da72f?utm_medium=embed&utm_campaign=share-popup&utm_content=13094e1686e34e15a888a56ff99da72f" target="_blank" style="font-weight: bold; color: #1CAAD9;"> My Guitar.... Hopefully </a> by <a href="https://sketchfab.com/Saltypasta?utm_medium=embed&utm_campaign=share-popup&utm_content=13094e1686e34e15a888a56ff99da72f" target="_blank" style="font-weight: bold; color: #1CAAD9;"> Saltypasta </a> on <a href="https://sketchfab.com?utm_medium=embed&utm_campaign=share-popup&utm_content=13094e1686e34e15a888a56ff99da72f" target="_blank" style="font-weight: bold; color: #1CAAD9;">Sketchfab</a></p></div>
 
 
+ It looks absolutely atrocious but I made it!

**Webmapping**
+ I got stuck in the 3D modeling section, so ill press pause here. In week 4 I may go further and add Webmapping

```NameError Traceback (most recent call last)

[<ipython-input-6-611ef82e37f5>](https://localhost:8080/#) in <module>()  1 # zip and download the results!  2 get_ipython().system('zip -r meshobject.zip ./object_out') ----> 3 files.download('meshobject.zip') 

NameError: name 'files' is not defined```

## challenges 

_error messages, unclear instructions, gaps in my knowledge, links to relevant asks for help on discord, stackoverflow posts, websites I went to for help_

## thoughts on where to go next

_what can I do? who can I talk to? links to posts in discord, helpf fora, etc. links to other research projects etc_

**copy this file to your github repository and rename it there ``notes-file-for-week-xxxx.md`**

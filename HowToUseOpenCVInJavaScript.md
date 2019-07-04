How to use OpenCV in JavaScript
=====
# Download OpenCV.js

 1. Click on this link: https://docs.opencv.org/3.4/opencv.js.
 2. Right click and select "Save As" from the drop down menu, this should open up the file explorer.
 3. Save the file as "opencv.js" wherever you desire.  In this markdown, we are going to call this folder "js".
 **Note that some computers or browsers may not have the "Save As" option appear in the dropdown menu when you right click.  If this is the case, you may have to take the brute force approach and copy the text into your own JavaScript file.*
# Create your html file
 4. Create a new html file called index.html in a folder of your choice  In this markdown, we will call this folder "Folder A".
 5. Import the "js" folder with the "opencv.js" file into "Folder A".
 6. To help you visualize, this is what the inside "Folder A" looks like in visual studio code.
 ![us](https://lh3.googleusercontent.com/dJN1mQGyCoKFjvQaelPaY9JUgYePZmzlXqNK5bm_-jgQFCRPVqFkzPBCYpBoN4R-CLeBwiiZDei-)
 7. Copy or type in the following code in index.html:
        
        <!DOCTYPE html>
        <html lang="en">   
        <head>  
	        <title>OPENCV_JSTEST</title>  
	        <meta name="viewport" content="width=device-width, initial-scale=1.0">  
	        <link rel="stylesheet" type="text/css" media="screen" href="main.css"> 
	        //  load file asynchronously.
	         <script async src="js/opencv.js"></script> 
         </head> 
         <body>
	        // the following details how to load an image
	        <img id="input_image">  
	        <input type="file" id="file_input"> 
	        // creating a canvas will allow the image to be displayed
	        <canvas id='output'></canvas>
	     </body>  
	     // It is inside the scipt where you will write your JavaScript code.
	     <script>  
		     // First, you want to update the image whenever you upload a new file.
		     let img_input = document.getElementById('input_image');  
		     let file_input = document.getElementById('file_input');
	
		     // Whenever there is a change in the input, we need to update the loaded image
		     file_input.addEventListener('change',(e)=> {  
			     // Change the source to the new file
			     img_input.src = URL.createObjectURL(e.target.files[0])
		     },false);
		     
		     //now we start the opencv commands
		     img_input.onload = function(){  
			     let mat = cv.imread(img_input);
			     // This morphs you input image into a grey scale image
			     cv.cvtColor(mat,mat,cv.COLOR_RGB2GRAY);
			     // We are changing the size of the grey scale image to make it easier to see next to large images
			     let dsize = new cv.Size(300, 300);  
			     cv.resize(mat, mat, dsize, 0, 0, cv.INTER_AREA);
			     // Now we display the image
			     cv.imshow('output', mat);  
			     mat.delete(); 
		     }  
		 </script>
         </html>
## Run your File
 1. Each IDE has different ways of opening a live server.  Once running, your browser of choice should look like the following: 
 
 ![show](https://lh3.googleusercontent.com/bb2w8NEjbPY_5uavP4G1eTsE9sI_mLGAbdDTwpARRCvCYp1W5ZjxX6qOTBGu9t4YVHJR8e3dh0qc)
 
 2. Click the "Browse" button.  This will open up the File Explorer. 
 ![browsw](https://lh3.googleusercontent.com/pBvfKvhyjpk2oh8g8C-TuQ-tKVWZvSVx1iZv19x_wg3nmsMBxWHKpAmep9uxaNi0EBkarpOb-65e)
 
 3. Select the image file of your choice and then click the "Open" button on the bottom right.  In this example, I am selecting RGB.png.
 
 4. The image you selected and the grey scale version of it should appear side by side in your browser. Remember that the grey scale image will be smaller since it is resized in the code. 
 ![side](https://lh3.googleusercontent.com/lFe8YYf1HXKe7QZxENAEEnZnUyaBUFjaMNVGL2JEOJap7CBtsxljFTvwnijoxm1GDWF0PGJm-RFh)
 
**If you want to make the grey scale image the same size as your original image, go back to the code and delete the following two lines:*

		    let dsize = new cv.Size(300, 300);  
		    cv.resize(mat, mat, dsize, 0, 0, cv.INTER_AREA);
   


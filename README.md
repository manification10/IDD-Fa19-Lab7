# Video Doorbell, Lab 7


### In This Report


## Part A. HelloYou from the Raspberry Pi

**a. Link to a video of your HelloYou sketch running.**
[Sketch Video](https://youtu.be/ZrvkE4vA_Ks)

## Part B. Web Camera

**a. Compare `helloYou/server.js` and `IDD-Fa18-Lab7/pictureServer.js`. What elements had to be added or changed to enable the web camera? (Hint: It might be good to know that there is a UNIX command called `diff` that compares files.)**
<br>
There is an additional 'takePicture' function for user to take a picture. The npm package NodeWebcam in the function takes the picture which takes the picture. 
The HTML has new line of code to display the captured image.

**b. Include a video of your working video doorbell**
[Doorbell Video](https://youtu.be/1yZirggg0nU)

## Part C. Make it your own

**a. Find, install, and try out a node-based library and try to incorporate into your lab. Document your successes and failures (totally okay!) for your writeup. This will help others in class figure out cool new tools and capabilities.**

I used [Jimp](https://www.npmjs.com/package/jimp) nodejs library to edit my image captured. 
It was difficult to use the library initially to edit it immediately after capture. 
So I created a different button, added necessary code in index.html and client.js to call function 'editPicture' which inverts the picture and makes it grayscale. 

Find the code [here](https://github.com/manification10/IDD-Fa19-Lab7/).
<br>
**b. Upload a video of your working modified project**

[Edited Image Video](https://youtu.be/bWXYvE6iVUM)

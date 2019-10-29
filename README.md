# Video Doorbell, Lab 7

*A lab report by Meera Nanda*

### In This Report

1. Upload a video of your version of the camera lab to your lab Github repository
1. As usual, update your class Hub repository to add your [forked IDD-Fa18-Lab7](/FAR-Lab/IDD-Fa18-Lab7) repository.
1. Answer the questions in-line below on your README.md.

## Part A. HelloYou from the Raspberry Pi

**a. Link to a video of your HelloYou sketch running.**

[Hello You Video](https://youtu.be/LCotdgU7tfs)

## Part B. Web Camera

**a. Compare `helloYou/server.js` and `IDD-Fa18-Lab7/pictureServer.js`. What elements had to be added or changed to enable the web camera? (Hint: It might be good to know that there is a UNIX command called `diff` that compares files.)**\

The main difference between the two files is that the pictureServer.js includes a Node Webcam variable to control the external webcam, and includes a snippet of code to set this up. There is also an additional function in pictureServer.js to take the picture, which is not in the helloYou/server.js since that one is simply to show that the button click is being registered. 

**b. Include a video of your working video doorbell**

[Video Doorbell](https://youtu.be/jxCw9uKRnK8)

## Part C. Make it your own

**a. Find, install, and try out a node-based library and try to incorporate into your lab. Document your successes and failures (totally okay!) for your writeup. This will help others in class figure out cool new tools and capabilities.**\

I started out by testing the paackages provided in the lab for ideas. The first idea I had was to take a burst of photos with the webcame when the button was clicked and then loop them together in a gif to display on the html page. I was unable to get this working correctly, so I finally settled on adding sound effects to the client.js file for when the doorbell button was clicked. 

**b. Upload a video of your working modified project**

[Audio/Video Doorbell](https://youtu.be/FJy-uJv9hOE)

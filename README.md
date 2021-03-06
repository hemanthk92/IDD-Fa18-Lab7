# Video Doorbell, Lab 7

*A lab report by Hemanth Kondapalli*

### In This Report

1. Upload a video of your version of the camera lab to your lab Github repository
1. As usual, update your class Hub repository to add your [forked IDD-Fa18-Lab7](/FAR-Lab/IDD-Fa18-Lab7) repository.
1. Answer the questions in-line below on your README.md.

## Part A. HelloYou from the Raspberry Pi

**a. Link to a video of your HelloYou sketch running.**
[link to video](https://youtu.be/tCPrmyYGiVo)
## Part B. Web Camera

**a. Compare `helloYou/server.js` and `IDD-Fa18-Lab7/pictureServer.js`. What elements had to be added or changed to enable the web camera? (Hint: It might be good to know that there is a UNIX command called `diff` that compares files.)** <br>
We import the module NodeWebCam. We define a set of options for the camera to operate such camera height, width, quality, etc this is saved in a object called opts. We also define a case when the user selects "Take a picture". And in here
the line NodeWebCam.capture to take the picture and we display the picture in the main UI, with the ui.emit function. <br>

**b. Include a video of your working video doorbell**
[link to video](https://youtu.be/T_2jkQRigRc)

## Part C. Make it your own

**a. Find, install, and try out a node-based library and try to incorporate into your lab. Document your successes and failures (totally okay!) for your writeup. This will help others in class figure out cool new tools and capabilities.**
I used the node library jimp which allows for easy modification of images. I really wanted to build a meme generator which would overlay text onto the image. But i had issues loading fonts. I find Javascript coding tough since its asynchronous which makes it hard to debug code, etc. I ended up just building a website that converts image to night vision colors.

**b. Upload a video of your working modified project**
[link to video](https://youtu.be/Sc62OYj4dCw)

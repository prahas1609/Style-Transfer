# Style-Transfer
## Project Overview
The project is based on neural style transfer using pretrained vgg19 model.Neural style transfer (NST) refers to a class of software algorithms that manipulate digital images, or videos, in order to adopt the appearance or visual style of another image. NST algorithms are characterized by their use of deep neural networks for the sake of image transformation.

## Setup Required
Required these to run the code\
1)Python\
2)Juypiter, Anaconda or any software that can have jupyiter environment.\

## How to use the code
First download the image in the repo in your system.\
Then replace style_pic and content_pic with the path of the images on your system. If error occurs please try to use r in front (example -- r"C:\Users\Hp\Desktop\Aries Style transfer\style\Oscar Florianus Bluemner - Old Canal Port.jpg")
Now run the code in the last there is the function for interactive user experience so that all the functions need not to be executed all the times (only once)\
It takes input as path of content and style image respectively.(dont forget r if error happens)\
The output will be privew of the two images you selected and the the final image with the loss obtained after every 50 steps.\

## Libraries that you need to install are (Dependencies:)
1)Pytorch\
2)Pillow\
3)Matplotlib\
4)Torchvision (if not installed by pytorch)\

# A note
I HAVE DEPLOYED THE CODE ON STEAMLIT BUT DUE TO SOME PROBLEMS BY STEAMLIT THE APP IS NOT WORKING PROPERLY\
IF YOU WANT TO HAVE LOOK THE WEBSITE IS MENTIONED BELOW\
https://style-transfer-mby5dcagzymkgmac3nnc83.streamlit.app/

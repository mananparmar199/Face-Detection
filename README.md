Face-Detection using Haarcascade Classifiers!
To understand the concept of face detection, we have to understand the following:

Understand the Viola-Jones algorithm.
Understand the OpenCV built-in function to detect a face on the image.

Face detection using Haar cascades is a machine learning based approach where a cascade function is trained with a set of input data.
OpenCV already contains many pre-trained classifiers for face, eyes, smiles, etc.. we will be using the face classifier.
The classifier is trained using lots of positive and negative images.

*First we need to load the required XML classifiers. Then load our input image (or video) in grayscale mode.
*Now we find the faces in the image. If faces are found, it returns the positions of detected faces as Rect(x,y,w,h).
*Similarly, we can detect faces in videos. As you know videos are basically made up of frames,
which are still images. So we perform the face detection for each frame in a video.

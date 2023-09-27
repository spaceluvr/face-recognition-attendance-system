# face-recognition-attendance-system

How to use the code:
1. Mount your Google Drive
2. Create 3 folders inside the folder where you're storing all of your work
   2.1 Training folder:
     -> This folder contains sub folders with names corresponding to the person who's images are inside the folder
     -> These images will be used to generate encodings for face detection
   2.2 Output folder:
     -> This is the folder that will store all of the encodings in a file called 'encodings.pkl'
   2.3 Validation folder:
     -> To make sure that the model is working properly, we need images that the model hasn't trained on before. This folder will contain           those images
     -> In this code the images are taken from the webcam so this folder isn't used much, but was incredibly important during training
3. Give the path locations to the corresponding variables
4. Run


Link to the CoLab notebook: https://colab.research.google.com/drive/1m5J5agTnX1CSci6yhldxaWqnwG0vPH1l?usp=sharing
     

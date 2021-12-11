# Facial-landmark-localization-68-Facial-landmark-Detection-in-Python

######## Use Google Colab if you dont have "dlib" installed  ########### (Try "pip install Dlib") (use in Colab )

""""""" Note: You will get errors if you run this code on jupyter Notebook and don't have "dlib" installed."""""""
#### Download : "Create shape_predictor_68_face_landmarks.dat" from my repository and keep it in the same folder of your code. ####

Facial landmark localization seeks to detect a set of predefined key points on a human face. 68-point landmark detectors: This pre-trained landmark detector identifies 68 points ((x,y) coordinates) in a human face. These points localize the region around the eyes, eyebrows, nose, mouth, chin and jaw.

Use any Facial Database to detect 68 landmark position.

The only thing you need to do after downloading this code is to change the directory names based on where your images are, Thats it!!
These are some changes you need to do..

IMAGES_DIR = '/content/drive/MyDrive/ckplus'  # original image directory
sadness_DIR = os.path.join(IMAGES_DIR, 'sadness') 
surprise_DIR = os.path.join(IMAGES_DIR, 'surprise')
disgust_DIR = os.path.join(IMAGES_DIR, 'disgust')
anger_DIR = os.path.join(IMAGES_DIR, 'anger')
happiness_DIR = os.path.join(IMAGES_DIR, 'happiness')
fear_DIR = os.path.join(IMAGES_DIR, 'fear')

Now You Are All Set, All The Best!!

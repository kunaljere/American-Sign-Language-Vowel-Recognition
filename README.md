# American-Sign-Language-Vowel-Recognition
Uses a binary threshold model to recognize vowels in American Sign Language

Training dataset taken from: https://www.kaggle.com/datasets/grassknoted/asl-alphabet

Test vowel dataset can be found here: https://drive.google.com/drive/folders/1lD1YYXXTdR1GgKbk4pfKmIuntS-gwXso?usp=sharing

Vowel training model can be found here: https://drive.google.com/drive/folders/15d6j06dpZO5bWbTJb_dRY2JtvfkXH4B5?usp=sharing

asl_recognition_training.py - creates a model to recognize ASL vowel images using the training dataset and a neural network.

vowel_static_images_test.py - tests the model created by taking 28 random images from the vowel_test_images folder and making predictions based on the vowel signed in the image.

live_asl_recognition.py - uses a live camera feed to predict the vowel signed within the green box displayed.

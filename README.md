# ASL-Detection
The objective of this project is to detect and recognize American Sign Language (ASL) signs in real-time using a webcam. This is accomplished using computer vision and machine learning techniques, with the help libraries such as cv2, TensorFlow, and OpenCV.

The object training process is carried out using the Teachable Machine image model maker, which is a web-based tool for creating custom machine learning models. The model is trained to identify ASL signs by using a dataset of images representing the signs A, B, and C.

During runtime, the webcam is used to capture live video data, which is processed by the OpenCV library. OpenCV provides the necessary tools to preprocess and analyze the video data, enabling the detection and recognition of ASL signs in real-time. Once a sign is detected, the corresponding letter is output to the screen.

It is worth noting that the current version of the project only recognizes the ASL signs A, B, and C, but other signs can be easily added to the model to improve its versatility.

## *IMPORTANT NOTE:*
Instructions for Setting Up Image Data and Running the Code:

To prepare the image data for this project, you need to create a folder named "imageData" exactly as written and then create three subfolders inside it named "A", "B", and "C" (all capitalized).

To make the code function properly, you must run the "dataCollection" file and press the 'S' key to capture images of your hand performing the correct sign while the variable "folder" is set to the corresponding folder (A, B, or C). Repeat this process for every letter you want to recognize.

Next, you should paste the collected images into the "Teachable Machine" website and train the model to recognize the hand signs. After training, export the model in the TensorFlow format (not .js or lite) and save it in a subfolder named "Model" (exactly as written) within the project folder.

To run the code, you must first download and install the necessary libraries: TensorFlow, NumPy, cvzone, and OpenCV. Once the libraries are installed, you can run the code to detect and recognize the hand signs in real-time using the webcam.
![image](https://user-images.githubusercontent.com/123900134/230507559-0efb4f36-e3a5-4b38-bf17-5f2953953076.png)

## *Final Product:*
![image](https://user-images.githubusercontent.com/123900134/230506101-9b3e91fa-0112-4a94-9cc9-82b85a6848ae.png)
![image](https://user-images.githubusercontent.com/123900134/230506175-33c6e8e1-9a89-4238-85b6-ee3ebb25186f.png)
![image](https://user-images.githubusercontent.com/123900134/230506268-3d945d18-7986-437e-8239-6ea9e681a347.png)

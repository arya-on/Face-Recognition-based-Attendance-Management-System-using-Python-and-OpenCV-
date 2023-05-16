# Face-Recognition-based-Attendance-Management-System-using-Python-and-OpenCV-

I. INTRODUCTION
Attendance plays an important role in any organisation whether it be educational institutions or companies. So it is very important 
to keep record of the attendance. The problem arises when one has to manually take the attendance which is not only time 
consuming but exhausting as well. 
So an automatic attendance system can solve such problem.
The conventional attendance system consists of registers marked by teachers which leads to human error and a lot of maintenance. 
Time consumption is an important point of concern in this system. We have thought of revolutionize it using available digital tools 
in the modern era i.e. FACE RECOGNITION. This project will ensure more precision and negligible manual work. The project is 
revolutionized in order to overcome the problems of conventional system. Face recognition and then marking the attendance is our 
project all about. The database of all the students in the class is stored in a folder and when the face of the individual student 
matches with one of the faces stored image, attendance is marked else the face is ignored and attendance not marked. In our project, 
face recognition (Machine Learning) technology is used .Inside this Histogram of Oriented Gradient for face detection and SVM 
Classifier for name recognition is used. The model has an accuracy of 99.38% on the Labelled Faces in the Wild benchmark.[2]. 
Keywords- Face Detection, Face Recognition, OpenCV, etc

II. Steps to Build a Face Recognition System

# Step 1: Install libraries
We need to install 3 libraries in order to implement face recognition.

1) dlib: Dlib is a modern C++ toolkit containing machine learning algorithms and tools for creating complex software in C++ to solve real-world problems.
installing dlib-
pip install dlib

2)face recognition: The face_recognition library, created and maintained by Adam Geitgey, wraps around dlib facial recognition functionality.
installing face recognition-
pip install face recognition

3)Opencv for some image pre-processing.
installing opencv-
pip install opencv


# Step 2: Import libraries

# Step 3: Load images
After importing libraries you need to load an image.
face_recognition library loads images in the form of BGR, in order to
print the image you should convert it into RGB using OpenCV.

# Step 4: Find the face location and draw bounding boxes
You need to draw a bounding box around the faces in order to show if the human face has been detected or not.

# Step 5: Train an image for face recognition
This library is made in such a way that it automatically finds the face and works on only faces, so you don’t need to crop the face out of pictures.
Training:
At this stage, we convert the train image into some encodings and store the encodings with the given name of the person for that image.
Testing:
For testing, we load an image and convert it into encodings, and now match encodings with the stored encodings during training. This matching is based on finding maximum similarity. When you find the encoding matching the test image, you get the name associated with train encodings.

![image](https://github.com/arya-on/Face-Recognition-based-Attendance-Management-System-using-Python-and-OpenCV-/assets/133690875/31c938c4-99ef-4a97-9a2f-95bff98821fd)
![image](https://github.com/arya-on/Face-Recognition-based-Attendance-Management-System-using-Python-and-OpenCV-/assets/133690875/2dca99a4-302f-4273-a146-2c890226c3ec)
![image](https://github.com/arya-on/Face-Recognition-based-Attendance-Management-System-using-Python-and-OpenCV-/assets/133690875/688c6b3c-0cf2-495f-8dbe-a31399a98cd2)

# OUTCOME & FUTURE SCOPE
The facial recognition feature embedded in the attendance monitoring system can not only ensure attendance to be taken accurately and also eliminated the flaws in the previous system. By using technology to conquer the defects cannot merely save resources but also reduces human intervention in the whole process by handling all the complicated task to the machine. The only cost to this solution is to have sufficient space in to store all the faces into the database storage. Fortunately, there is such existence of micro SD that can compensate with the volume of the data. In this project, the face database is successfully built. Apart from that, the face recognizing system is also working well.







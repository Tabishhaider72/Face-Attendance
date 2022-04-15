# Face-Attendance
In this project I'm going to Show how to perform Facial recognition with high accuracy. I will first briefly go through the basic implementation. Then I will created an Attendance project that will use webcam to detect faces and record the attendance live in an excel sheet.
![FR-Facial-Recognition-Web-Responsive-Banner-30-may-2020_1-1320x500-1](https://user-images.githubusercontent.com/93794214/163526087-9f309351-bfed-4de0-a858-1861b3b8bdb4.jpg)

> Installations:
> 
The installation process for this project is a bit more than usual. First we have to download a C++ compiler. We can do this by installing Visual Studios. You can download the community version for free from their website. Once the intaller we will run it and select the ‘Desktop development with C++’. The download and installation will take some time as it is a few Gbs.

>After completing and restarting the computer, now we will head on to our Pycharm project. Here we will install the required packages. Below is the list.
cmake
dlib
face_recognition
numpy
opencv-python

##Understanding the problem

>Although many face recognition algorithms have been developed over the years, their speed and accuracy balance has not been quiet optimal . But some recent advancements have shown promise. A good example is Facebook, where they are able to tag you and your friends with just a few images of training and with accuracy as high as 98%. So how does this work . Today we will try to replicate similar results using a face recognition library developed by Adam Geitgey. Lets look at the 4 problems he explained in his article.

Face recognition is a series of several problems:
![giphy](https://user-images.githubusercontent.com/93794214/163526265-de8b02be-288f-4f15-b9df-ca4325531ff9.gif)

- [x] First, look at a picture and find all the faces in it.
- [x] Second, focus on each face and be able to understand that even if a face is turned in a weird direction or in bad lighting, it is still the same person.
- [x] Third, be able to pick out unique features of the face that you can use to tell it apart from other people— like how big the eyes are, how long the face is, etc.
- [x]  Finally, compare the unique features of that face to all the people you already know to determine the person’s name.
## [Project DemoClip]
https://user-images.githubusercontent.com/93794214/163526543-6105c66c-ee58-4bb3-bff6-71b47324bcf6.mp4

# Car Detection App as used in Full Self Driving (FSD) cars.



This app uses Computer Vision technology as used in self driving cars i.e Tesla for vehicle detection as well as pedestrian detection. This is better than Lidar Technology. Lidar is a method of measuring distance by shooting lasers and detecting how much time they take to return. The idea is similar to Radar but instead of radio waves, we use lasers. The technology is extremely accurate at detecting objects even up to millimeters. However tends to be expensive

On the other hand,Computer Vision is a field of Artificial Intelligence that trains computers to understand the visual world. This is basically reverse engineering human vision.

## Technologies Used
* OpenCV 


## Methodology
In this project, I am using IBM's trained dataset of cars, where the A.I. has been trained to recognize cars. This is the xml file in the attachment. From the code, I have rescaled the video to frames which are grey and white for the A.I. to be able to recognize the cars.

The A.I. is better able to process the Haar-like features.
To further know more about Haar-like features you may wish to refer to :
https://en.wikipedia.org/wiki/Haar-like_feature#:~:text=Haar-like%20features%20are%20digital%20image%20features%20used%20in,were%20used%20in%20the%20first%20real-time%20face%20detector.


## Output

![Screenshot 2021-07-21 at 7 03 28 PM](https://user-images.githubusercontent.com/77420780/126480987-4b6aa70c-e46a-4378-9fa1-f0612b614aed.png)



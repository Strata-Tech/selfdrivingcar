# Car Detection App as used in Full Self Driving (FSD) cars.

![14718404807_be38c5f2b2](https://user-images.githubusercontent.com/77420780/126481426-616f8f2d-0dc3-41f5-9442-3c6f473b2d20.jpg)

This app uses Computer Vision technology as used in self driving cars i.e Tesla for vehicle detection as well as pedestrian detection. This is better than Lidar Technology. Lidar is a method of measuring distance by shooting lasers and detecting how much time they take to return. The idea is similar to Radar but instead of radio waves, lasers are used. The technology is extremely accurate at detecting objects even up to millimeters. However tends to be expensive and not without flaws.

On the other hand,Computer Vision is a field of Artificial Intelligence that trains computers to understand the visual world. This is basically reverse engineering human vision.

![maxresdefault](https://user-images.githubusercontent.com/77420780/126481784-e15ae5cb-2a45-40db-815a-c0c619e167e6.jpg)


## Technologies Used
* OpenCV 


## Methodology
In this project, I am using IBM's trained dataset of cars, where the A.I. has been trained to recognize cars. This is the xml file in the attachment. From the code, I have rescaled the video to frames which are grey and white allow the A.I. to better recognize the cars.

The A.I. is better able to process the Haar-like features.
To further know more about Haar-like features you may wish to refer to [here](https://data.gov.sg/dataset/realtime-weather-readings?resource_id=8bd37e06-cdd7-4ca4-9ad8-5754eb70a33d)


## Output

![Screenshot 2021-07-21 at 7 03 28 PM](https://user-images.githubusercontent.com/77420780/126480987-4b6aa70c-e46a-4378-9fa1-f0612b614aed.png)



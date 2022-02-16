# vehicle-identification-and-alerting-using-deep-learning

## _**Introduction:**_

With the exponential increase in road traffic all over the world, traffic monitoring and control has become more and more important. Intelligent transportation systems (ITS) have attracted a lot of attention in the last decades. Vehicle detection, classification, counting and tracking from input from highways and other roadways and extracting essential parameters related to vehicular traffic can help better management of traffic on busy roads. With the installation of traffic surveillance cameras, a vast database of traffic video footage has been obtained for analysis.

## _**Objectives of our project:**_

_A. Implementing a vehicle detection and counting system_

For vehicle detection: YOLOv5 training with custom data.
Collect data/images. Data is split into training and validation data
Assign labels to each image in the dataset using makesense.ai / labelimg
We have the following labels/classes: Car, Motorcycle, Scooter, Auto, Truck, Bus, Bicycle
Use YOLOv5 for object detection and classification using the custom dataset. 

For counting: count the number of vehicles of each class passing through the specified reference line.

_B. Implementing traffic rule violation and alerting system_

Traffic rule violations can include overspeeding or traffic signal breaking.
Upon any such violation, the number plate of the violating vehicle is to be obtained and an alert is to be sent to the authorities who can then take necessary action. A database can be created to record all these violations and the offenders.



https://user-images.githubusercontent.com/58129107/154209278-98275489-c766-485f-ae3f-2ed3c5a33322.mp4


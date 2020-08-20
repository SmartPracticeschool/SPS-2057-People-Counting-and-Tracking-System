# SPS-2057-People-Counting-and-Tracking-System
Project Idea :

Real-time people flow estimation can be very useful to gain insights for many commercial and non-commercial applications. Counting people on streets or at entrances of places is indeed beneficial for security, tracking, and marketing purposes. People counters can be used to monitor occupancy of entire buildings, individual rooms or anything some of the application where you can implement people counters are Retail stores and supermarkets, Higher education, Corporate workplaces,Restaurants, hospitality leisure facilities and Washrooms


Project Solution:
The objective of this project is to develop a people counter device to count the number of pedestrians walking through a door or corridor through a video or camera. Most of the time, this system is used at the entrance of a
building so that the total number of visitors can be recorded. Live stream of visitors flow is streamed on to a web application 


Project Flow :


This project has two phases, phase 1 is to implement  detection of person and the second phase is to implement tracking of a person

Phase1: Person Detection

*Get the camera / Video Feed

*Detect people in the frame using the cafe pre-trained model

*Localize the pedestrians in the frame

*use the detected person bounding box coordinates to track them

Phase 2:  Tracking Phase:
*create an object tracker for each detected object to track the object as it moves around the frame
*continue tracking until  the N-th frame is reached  and then re-run our object detector
*The entire process repeats

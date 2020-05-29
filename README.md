# Traffic-Sign-Recognition-using-Morphological-Segmentation-and-Template-Matching
- Automatic detection and recognition of traffic signs for assisting driver to ensure a safe travel.

- The proposed method detects the location of the traffic sign in the captured image, based on its geometrical characteristics and using color information by implementing morphological operations. 

- Such signs are then recognized using pattern matching with the normalized keys of pre-computed cluster-centroids in the dictionary. 

- Experimental result yielded a recognition rate of 93.75% with an average recognition time of 0.5725s.

Note: We have considered direction signs only.


To run this project on Ubuntu terminal:
- Download the Dataset and TrafficSignRecognition.py files in the same folder.
- Install the necessary modules: cv2, numpy, imutils
- On terminal, run the code as: python3 TrafficSignRecognition.py


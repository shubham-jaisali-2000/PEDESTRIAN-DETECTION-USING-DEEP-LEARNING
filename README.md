# PEDESTRIAN-DETECTION-USING-DEEP-LEARNING
This repo includes source code, sample images and videos, report, research paper, pre-trained model for the project entitles "PEDESTRIAN-DETECTION-USING-DEEP-LEARNING"

REAL TIME HUMAN DETECTION & COUNTING
- A tensorflow based `Faster RCNN inception v2` python model to detect and count humans in real time images, videos & camera.
- Used pre-trained `frozen_inference_graph.pb` frozen graph to handle the detection.
- Visualize the data using `Enumeration Plot` and `Avg. Accuracy Plot`.

REQUIREMENTS : 
- python 3
- tkinter
- messagebox
- PIL
- cv2
- argparse
- matplotlib.pyplot
- numpy
- time
- os
- tensorflow
- fpdf

Instructions :

Install all above mentioned liberaries(using pip)
for example to install PIL, open Command Prompt and type command "pip install pillow" (before this make sure your environment variable path is set)

Open main.py with any IDE(ex.VS Code).Debugging and Run the code, user will directed to the GUI of the project.


How this Script works :
- User just need to download the file and run the main.py on their local system.
- On the starting window of the application, user will be able to see START and EXIT option, using which user can start the application or exit from the application.
- When user starts the application using START button, a new window will open, which allows user with options like, DETECT FROM IMAGE, DETECT FROM VIDEO or DETECT FROM CAMERA.
- When user selects any of the first two option, he/she needs to select the respective files using SELECT button.
- User can preview the selected file using PREVIEW button, and detect and count the humans using DETECT button.
- And when user selects, the last option of detecting through camera, user need to open the Camera, using OPEN CAMERA button, As soon as camera opens, detection process will start.
- After detection process gets completed or user manually completes it, two graph get plotted, 
	- 1.) Enumeration Plot(Human Count Vs. time) and 
	- 2.) Avg. Accuracy Plot(Avg. Accuracy Vs. time).
- Along with this two plots, an option to generate crowd report also appears, On clicking on it, a crowd report in form of PDF is generated ans saved autmatically at the project file location.
- In the crowd report genrated, there will be information like, What is Max Human Count, Max Accuracy, Max Avg. Accuracy, and also a two line status about crowd.

Purpose :
- This scripts helps user to easily get the count of human through real time image, video or camera, and thereafter also analysis of crowd through crowd report.

Compilation Steps :
- Install all the required libraries.
- After that download the code file, and run main.py on local system.
- Then the script will start running and user can explore it by detecting the human and also getting the count of it.



 

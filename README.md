# Face-Detection-System

1. Training Phase: train.py 
Purpose: Build a dataset and train a facial recognition model.

Steps:
1) Capture 50 images per person from multiple angles to ensure the model learns robust facial 
   features for each individual.
2) Store the captured images in a structured format, creating the training dataset.
3) Train the recognition model using these images. The trained model learns unique facial 
   characteristics for each employee, preparing it for detection tasks.

2. Detection Phase: detect.py
Purpose: Perform real-time face detection using the trained dataset.

Steps:
1) Load the trained dataset into the detection script.
2) Utilize the YOLO library for real-time, efficient face detection. YOLO is a deep learning 
   framework known for its speed and accuracy in object detection tasks.
3) Process video streams or images to detect faces and match them with the trained dataset to 
   identify individuals.

3. Monitoring and Output Phase: monitore.py
Purpose: Provide the final output of the project, including real-time face monitoring and reporting.

Steps:
1) Capture live video feed using a webcam.
2) Use the previously trained model and YOLO to detect faces in real-time.
3) Match detected faces with the trained dataset to identify employees.
4) Determine the employees' working status (whether they are active or not).

Generate a detailed report:
1) List of detected employees.
2) Their working status (working or not working).
3) Save the data into an Excel file for documentation and further analysis.


## 🔍 Quality-Inspection
The project is developed to conduct a quality inspection of Dengue Kits using custom object detection to ensure the design of the kit is correct.

### 🚀 Objective
The manufacturing industry has a lot of its manpower allotted towards building and quality inspection. Ensuring the accurate design of the product is a crucial step before sending it over to the market to be made available to the customers. To be able to cut down the manual crunch required for the examination of the design, we designed a system to be able to automate the process. 
For this project, we have taken an example of a dengue kit.

### ⚙️ Process 
The project involves the design of the entire system which includes a conveyor belt, and its components, cameras, and other types of equipment that would be required in an industrial setting. The product (dengue kit) would be passed on the conveyor belt and the images will be captured once it passes through a small chamber including cameras. The image is then passed through the computer vision model to classify whether or not it is perfectly designed. The faulty ones are then discarded.

>**The computer vision model is developed by training a custom object detection model using Yolov4.**

### 📍 Main aspects of the project
1. Designing of the multiple components of the conveyor belt using Fusion 360. 
2. Assembling of all the components to showcase the entire system.
3. Training the model using Yolov4 to carry out custom object detection
4. Creating a streamlit webapp to show the output on the screen.
5. Rendering all this into one main video to show how the entire project would look on an industrial level.

### 🗜️ Demo of the working
#### Streamlit Working
https://github.com/ashita03/Quality-Inspection/assets/66629830/5b36acc5-3624-4399-92de-1fef46d2dd2e

### 🔳 Training result 
Attached below is the result of the dengue kit
![DengueKitTraining](https://user-images.githubusercontent.com/66629830/183103562-d8f2ca41-2e12-44e3-8d2a-16ae3e31a008.png)

### 🖇️ Link to the Research Paper

https://www.ijraset.com/best-journal/quality-inspection-of-dengue-kits-using-yolov4-architecture



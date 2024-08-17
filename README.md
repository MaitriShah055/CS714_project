# CS714_project
## Lane Detection in Autonomous Driving
### Autonomous driving represents a significant technological advancement, promising to revolutionize the transportation industry. By leveraging advancements in sensors, machine learning algorithms, and real-time data processing, autonomous vehicles (AVs) can navigate and operate with minimal human intervention. Lane detection is a fundamental component of AV technology, enabling vehicles to stay within their designated lanes and maintain safe navigation. The autonomous vehicles are made of a lot of sensors and different systems.
### Autonomous driving technology has rapidly evolved over the past decade, promising safer roads and more efficient transportation. A core component of any autonomous driving system is its ability to perceive the environment accurately, with lane detection being a critical task. Lane markings serve as guiding paths for vehicles, enabling them to stay within designated lanes, make safe turns, and avoid collisions.
## Problem Statement
### The main challenge in lane detection lies in accurately identifying lane boundaries under diverse and unpredictable driving conditions. This project aims to address these challenges by developing a lane detection system based on FCNs, which can generalize well across different environments and adapt to the varying appearances of lane markings. As current lane detection systems often struggle with inconsistencies across different lighting, weather, and traffic conditions
## Dataset
### The dataset “Berkely Deep Drive” also known as ‘BDD100K’ is obtained from Berkeley Artificial Intelligence Research lab. The Berkeley Deep Drive (BDD) dataset is one of the largest and most diverse video datasets for autonomous vehicles and heterogeneous multitask learning.The BDD100K dataset contains 100,000 video clips collected from more than 50,000 rides covering New York, San Francisco Bay Area, and other regions. The dataset contains diverse scene types such as city streets, residential areas, and highways. Furthermore, the videos were recorded in diverse weather conditions at different times of the day. It can be download from https://www.bdd100k.com/. This project uses masks from Lane lables and 100k train, val and test folder from the BDD100K site. 
## Software and tools
### This project uses AWS cloud service for storing the dataset and training the model
### 1. To store the dataset: Login to the AWS services and create a S3 bucket. Unzip the folders obtained from the BDD100k dataset and upload the folders in the S3 bucket.
### 2. To create and train the model we have used AWS Sage Maker: Create a Sage maker domain for any zone and region in US or Canada. Create a notbook instance in the sage maker and upload the notbook provided here.
### 3. Run the Python notebook after ensuring if the paths for files are correct.

### 4. Visualize the results

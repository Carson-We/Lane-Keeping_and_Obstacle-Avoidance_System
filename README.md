# Lane-Keeping and Obstacle-Avoidance System

# Project Goals

The goal of this project is to enhance the reliability and accuracy of the Autopilot system, specifically focusing on the lane-keeping and obstacle-avoidance capabilities. Our aim is to improve the performance of the Autopilot system, making it more robust and precise in navigating through lanes and avoiding obstacles.

# Installation Guide

To install the Lane-Keeping and Obstacle-Avoidance System, follow these steps:

1. Clone the project repository from GitHub:
git clone https://github.com/Carson-We/Lane-Keeping_and_Obstacle-Avoidance_System.git

2. Install the necessary dependencies by running the following command:
   pip install -r requirements.txt

3. Set up the required hardware components and configure the environment as specified in the project documentation.

# Usage Instructions

To use the enhanced Autopilot system, follow these instructions:

1. Import the Autopilot module into your project:
   from autopilot import Autopilot

2. Initialize the Autopilot object:
   autopilot = Autopilot()
  
3. Connect the vehicle's sensors and controllers to the Autopilot system.

4. Call the Autopilot's control function to activate the automated navigation:
   autopilot.control()
 
   This function will continuously monitor sensor inputs, process the data, and generate control commands for maintaining lane position and avoiding obstacles.

5. Monitor the vehicle's behavior and performance while the Autopilot is engaged. Ensure that the algorithm operates reliably and accurately.

# Datasets

To access our trained dataset, you can easily download it from our GitHub repository. Please visit the following link to download the dataset:

- [Dataset Download](https://github.com/Carson-We/Lane-Keeping_and_Obstacle-Avoidance_System\dataset)

The dataset contains labeled samples for training and evaluating the Lane-Keeping and Obstacle-Avoidance System.

# Demo

We have included a comprehensive demo in the `demo/` directory to showcase the enhanced capabilities of the Autopilot system. To run the demo, follow these steps:

1. Navigate to the `demo/` directory:
   cd demo

2. Execute the demo script:
   python autopilot_demo.py


   The demo script will simulate real-world scenarios, demonstrating the improved reliability and accuracy of the Autopilot system in lane-keeping and obstacle-avoidance tasks.

# Contribution Guidelines

We welcome contributions to the Lane-Keeping and Obstacle-Avoidance System project. If you would like to contribute, please adhere to the following guidelines:

1. Fork the project repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with descriptive messages.
4. Push your changes to your forked repository.
5. Submit a pull request, providing a clear explanation of your contribution and its purpose.

# Author and Contact Information

Authors: Carson and Mr. Jonathan Tse

For any inquiries or feedback regarding the project, feel free to contact us:

- Carson
  - Email: carsonw1125@icloud.com

- Mr. Jonathan Tse
  - Email: 

We appreciate your interest and support in enhancing the Autopilot system to achieve greater reliability and accuracy in lane-keeping and obstacle-avoidance tasks.

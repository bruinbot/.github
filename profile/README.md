![BruinBot](https://jacobsayono.github.io/assets/misc/bruinbot.png)

# Winter 2024 Timeline
For the next 2 months (8 weeks), we'll structure the project timeline with deliverables for each week, breaking down tasks based on the roles and objectives I've outlined last week. We have a successful simulation with robust localization and navigation algorithms. The goal is to ensure a smooth transition from a simulated to a real-world autonomous delivery system, along with developing supporting platforms for data collection, machine learning model development, and user interaction, all compatible within the ROS2 framework. We will balance hardware development, data platform creation, algorithm development, and user interface design, aligning with the project's long-term goals of offering a comprehensive package to companies interested in autonomous delivery solutions.
## Weeks 1-2: Initial Setup and Testing
### Jacob & Matthew:
Week 1: Dual boot a fresh MacBook with Ubuntu and ensure the simulated repository is clonable and fully functional on another machine. Begin assembling the first prototype of the hardware robot based on the simulated design. Test basic functionality with ROS2.

Week 2: Finalize hardware assembly and integrate Raspberry Pi as the robot's brain. Perform initial tests to ensure hardware and software compatibility, focusing on basic movement and sensor integration within the ROS2 environment.
### Pierce & Joe:
Week 1: Set up a data collection framework that captures and formats perception data and manual teleoperation inputs from the simulated robot. Ensure data can be stored efficiently on a local server or cloud storage.

Week 2: Begin developing a simple algorithm for data transformation and storage optimization. Establish a basic version of the imitation learning algorithm framework, without full implementation.
### Gavin Wong:
Week 1: Draft initial designs for the user interface that will allow tracking and controlling the robot(s). This includes basic functions such as start, stop, and monitor status.

Week 2: Develop a prototype of the user interface, ensuring compatibility with ROS2 and the ability to communicate with the simulated robot system.
## Weeks 3-4: Integration and Initial Data Collection
### Jacob & Matthew:
Week 3-4: Begin integration of the real hardware with the ROS2 system, ensuring all sensors and actuators are properly interfaced with ROSSerial. Start basic movement tests and sensor data collection to replicate simulated environment behaviors.
### Pierce & Joe:
Week 3: Implement data collection from the real robot, ensuring smooth capturing and storage of perception and teleoperation data.

Week 4: Refine the data transformation algorithms and storage system based on initial real-world data collection. Enhance the framework for imitation learning algorithm development.
### Gavin:
Week 3-4: Integrate the user interface with real-time data from the hardware robot. Implement basic control features and live status updates, ensuring system stability and responsiveness.
## Weeks 5-6: Refinement and Advanced Testing
### Jacob & Matthew:
Week 5-6: Conduct extensive testing of the hardware robot in various conditions to identify and rectify potential issues. Optimize performance for stability and reliability. Begin preliminary work on modular hardware design concepts for future scalability.
### Pierce & Joe:
Week 5: Enhance the data collection and transformation algorithms based on feedback from initial tests. Start developing more complex features of the imitation learning algorithm.

Week 6: Conduct tests of the imitation learning algorithm with collected data, making necessary adjustments. Begin planning for reinforcement learning components.
### Gavin:
Week 5-6: Refine the user interface based on test feedback, focusing on usability, robustness, and integration with the multi-robot system. Implement advanced tracking and control features.
## Weeks 7-8: Finalization and Documentation (Transition to Spring)
### Jacob & Matthew:
Week 7-8: Finalize the hardware prototype, ensuring all systems are fully functional and ready for demonstration. Document the hardware setup, including modular design aspects and scalability features. Prepare for future expansion to multiple robots.
### Pierce & Joe:
Week 7: Finalize the data collection platform and imitation learning algorithm, ensuring robustness and scalability. Document the data platform and algorithm setup for potential clients.

Week 8: Prepare a demonstration of the data collection and learning algorithm, showcasing the potential for autonomous operation and continuous learning.
### Gavin:
Week 7-8: Complete the user interface platform, ensuring full compatibility with the ROS2 system and multi-robot control. Document the interface design and functionalities, preparing for a comprehensive demonstration.

## Footnotes
Let's continue our regular team meetings Wednedays at 6 pm (Bomb Shelter) to ensure cross-functional alignment and address any questions/challenges or adjustments to the plan. We will continue our momentum and move fast in our developments, treating this project like a varsity sport. I've scheduled a time for us (2-4 PM every Thu, Fri, and Sat) for workdays in the Makerspace.

In Week 2, I've discussed with ASME leads, and we will begin collaborating with them starting 4th week of Winter 2024. We are finalizing our plans for collaboration. Blake Dee will be ASME's representative who connects me with the other ASME leads.

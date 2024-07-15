The following is a programming task description. 
Please finish it by yourself, and use of chatgpt is highly not recommand.
(After finishing this project, merge this project to master branch!!!)
-----------------------------------------------------------------------------------------------
Project Overview

Create a simple ROS node that publishes and subscribes to a custom message type. 
The project should include the definition of the message type, the implementation of the nodes,
and the configuration of the CMakeLists.txt file. 
The entire project structure should contain all necessary files and directories to 
ensure it can be compiled and run successfully.

Task Requirements
Project Structure:

Create a new ROS package named simple_ros_project in this folder directory.
Include the following directories and files:
msg/CustomMessage.msg
src/publisher_node.cpp
src/subscriber_node.cpp
CMakeLists.txt
package.xml

Custom Message Type:

Define a custom message type CustomMessage with the following fields:
string message
int32 number
Publisher Node (publisher_node.cpp):

Create a publisher node that publishes CustomMessage type messages to the /custom_topic topic.
The published message should contain a fixed string and an incrementing integer.

--------------------------------------------------------------------------------------------------------------
Subscriber Node (subscriber_node.cpp):

Create a subscriber node that subscribes to the /custom_topic topic and prints the received message content.
CMakeLists.txt File:

Configure the CMakeLists.txt file to include the generation of the custom message and to compile the publisher and subscriber nodes.
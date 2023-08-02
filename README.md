# Advanced_toolbox

README for GitHub Repository
Advanced_toolbox
This repository contains a Python program named "Advanced_toolbox" that serves as a command-line interface (CLI) for various tasks related to Hadoop configuration, web server setup, Docker management, AWS (Amazon Web Services) operations, basic Linux commands, face cropping, measuring distance from a face, and pose detection.
Following is a glimpse of program:
- 1.Configure Hadoop Namenode
- 2.Configure Hadoop Datanode
- 3.Configure Webserver
- 4.Configure Docker
- 5.Amazon Web Service
- 6.Hadoop services
- 7.Basic Linux commands
- 8.cropping face
- 9.measure distance from face
- 10.pose detection
- 11.Web based CLI
- 12.Exit program
Features
Hadoop Configuration: The program allows you to configure Hadoop Namenode and Datanode services by providing necessary inputs such as IP, folder name, and port number.

Webserver Setup: The program installs and starts the Apache HTTP web server.

Docker Management: The program sets up Docker on the system, allowing you to manage Docker services, pull operating system images, and launch containers.

Amazon Web Services (AWS): The program provides functionalities for creating a key pair, security group, launching an EC2 instance, creating a volume, attaching a volume, and creating an S3 bucket using the AWS CLI.

Hadoop Services Management: The program allows you to start and stop Hadoop Namenode and Datanode services, view the Hadoop DFS admin report, and check running processes.

Basic Linux Commands: The program offers basic Linux commands such as displaying the date, calendar, IP address, RAM usage, memory, current user, current directory, and viewing the contents of a directory.

Face Cropping: The program utilizes the "face_crop" module to crop faces from images.

Face Distance Measurement: The program uses the "face_dist" module to measure the distance between two faces in an image.

Pose Detection: The program utilizes the "pose_detect" module to detect poses in images.

Web-based CLI: The program launches a web-based command-line interface using ShellInABox.

How to Use
Clone the repository to your local machine.
Ensure you have Python and the necessary dependencies installed.
Run the "menu.py" script to start the My Menu Program.
The program will prompt for a password, and the default password is "redhat".
Once inside the main menu, choose from the available options to perform various tasks.
Dependencies
The program has the following dependencies:

Python
getpass
face_crop
face_dist
pose_detect
Third-Party Information
Please note that this program uses third-party modules for face cropping, face distance measurement, and pose detection. These modules might have their own dependencies and licenses, which you can find in their respective repositories or documentation. Make sure to comply with the licensing terms of these third-party modules.

Disclaimer: This program is intended for educational and demonstration purposes only. The user is responsible for any consequences that may arise from using the program or its functionalities.

Author
The program was created by [vishvratna shegaonkar].

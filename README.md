# Python-Port-Scanning-Lab

## Objective

The objective of this project is to develop a multi-threaded Python port scanner that efficiently scans a target IP address or domain for open TCP ports within a user-specified range. The script allows users to check the status of ports, identifies open ports, and attempts to determine the services running on those ports. The project aims to provide a lightweight tool for network security assessment by identifying potential vulnerabilities in accessible ports.

### Skills Learned

- Python programming (sockets, threading, queues)
- Multi-threading for efficient task execution
- Network socket programming (TCP port scanning)
- Queue management for thread-safe operations
- Basic network security and port identification
- Input handling and user interaction in Python
- Service identification for open ports
- Project organization and file management in Python

### Tools Used

- Visual Studio: Integrated development environment (IDE) for writing and testing Python code
- Python: Primary programming language used for the port scanner
- Socket Library: Python library for network communication
- Threading Library: Python module to manage multi-threaded execution
- Queue Library: Python module for thread-safe queue management

## Steps
- Set Up Visual Studio:
- Download and install Visual Studio
Configure Python environment within Visual Studio
Write the Python Port Scanner:
- Import required libraries: socket, threading, queue
Implement the scan_port function to scan individual ports
Create a thread-safe queue to manage port scanning tasks
Write a worker function to handle multi-threaded port scanning
Take user input for target IP and port range
Start multiple threads to scan the ports concurrently
Test the Script:
- Run the script in Visual Studio or the terminal
Input a target IP (e.g., 8.8.8.8) and port range to scan
Verify the script outputs open/closed port statuses


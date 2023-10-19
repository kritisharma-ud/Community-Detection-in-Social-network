# Community-Detection-in-Social-network
Implementing BIG CLAM(Cluster Affiliation Model for Big Networks), an overlapping community detection method for social networking graph.
This method used distributed and parallel programming for the implementation.
Below are the details and instructions for the same:

Files
Code: Community_detection_cps534.ipynb Community_detection_cps534.py
Input Files: sample_1.txt 

Requirements:
The code can be run in any environment with the respective installations.
Python, spark, Apache spark. If you are trying locally, you must be Apache spark installed and configured.
The provided code is created on Google collab. Each cell needs to be executed one by one to download the packages and created the instant runtime.

Input :
The input provided is one in the zip file. Th file is large so it may take a while to upload. The way to read the input can vary according to the OS or the file used.

Program:
Running the cells one by one and execute the code in one manner.

Output:
Since it is parallel programming, it takes time to run. Number of triangles and triangle nodes is printed as output. Also, some of the functions give output as we use flatmap/ map / groupby key or union function and collect it while running the code.

# Coding Assessment

This coding assessment comprises a series of programming challenges ranging from easy to hard. Each challenge is designed to evaluate your coding skills, problem-solving abilities, and, in some cases, your proficiency with specific tools or libraries.

## General Rules

### Honesty
Candidates are expected to complete the test independently. Any form of plagiarism, cheating, or seeking external help is strictly prohibited.

### Time Limit
You are required to complete the questions within 1 week of the release.

### Programming Languages
You have the flexibility to choose your programming language for most questions. However, some questions specify the use of a particular language.

### Environment and Tools
For the ROS (Robot Operating System) question, you need to have Ubuntu 20.04 and ROS Noetic installed on your system.

### Submission Format
You will need to fork this repository and submit your solutions via pull requests.

The name of forked repo should be <your full name_horizon>
If a person name is Rahul Kumar , repo name will be rahulkumar_horizon


### Documentation
We strongly encourage you to provide clear and concise documentation alongside your code. This documentation should include comments, explanations, and instructions on how to run your programs or simulations.

---

## Easy: Calculate Average (Any Programming Language)

### Question
Write a program that continuously accepts numbers as input and displays the average of all the inserted numbers. However, the program should not accept the same number more than once.

### Sample Input & Output
**Input**: 4
**Output**: 4

**Input**: 5
**Output**: 4.5

**Input**: 5
**Output**: 4.5

### Rules and Instructions
- You can use any programming language for this question.
- The program should keep reading numbers until the user decides to exit.
- If a number is repeated, it should not be included in the calculation of the average.
- Ensure that the code is well-documented and easy to understand.

---

## Medium: Calculate Particle Position (C++)

### Question
The current position of a particle is (0,0) units. You will be provided with (velocity, direction, time interval) in unit/s, in degrees, and in seconds as an array. Write a C++ program to calculate the final position in (x, y) coordinates.

### Sample Input & Output
**Input**: ((5, 0, 2), (1, 45, 3), (2, -45, 1))
**Output**: (10.707, 0.707)

### Rules and Instructions
- Write a C++ program to calculate the final position based on the given inputs.
- Assume that the particle starts at (0,0) and moves according to the provided parameters.
- Make sure the code is well-structured and includes comments to explain the logic.

---

## Hard: ROS Subscriber-Publisher System (C++)

### Question
Install ROS Noetic on your system (Ubuntu 20.04) and implement a subscriber-publisher system in C++.

### Rules and Instructions
- You need to install ROS Noetic, which requires Ubuntu 20.04. Make sure you have the necessary system requirements before attempting this question.
- Implement a subscriber-publisher system in C++ using ROS. You can choose the topic and message type.
- Provide documentation for setting up ROS and running your code.
- The code should be well-commented and easy to understand.
- Include a brief explanation of what your subscriber-publisher system does.

---

## Bonus Question: Servo Motor Control (Tinkercad & Arduino)

### Question
Write C code in Tinkercad for Arduino to control a servo motor using a potentiometer. The servo should not go beyond 68 degrees and should turn on an LED if it exceeds 68 degrees. You need to submit a video of this circuit simulated in Tinkercad and the source code.

### Rules and Instructions
- Use Tinkercad to simulate the circuit.
- Provide a video demonstrating the simulation.
- Write C code for Arduino to control a servo motor using a potentiometer. The servo should not exceed 68 degrees, and if it does, it should turn on an LED.
- Share the source code along with any necessary instructions for setting up and running the simulation.
- Ensure that the source code is well-commented and easy to understand.

---

Good luck with your coding assessment! If you have any questions or need clarifications, please don't hesitate to ask.

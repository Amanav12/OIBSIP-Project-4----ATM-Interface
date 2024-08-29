# OIBSIP-Project-4----Online Exam System
Project Overview: Online Exam System in Java
Project Name: Online Exam System

Description:
This project is a Java-based desktop application that simulates an online exam system. It includes a login interface and a timed quiz functionality. The application allows users to log in using a username and password and then take a multiple-choice exam within a specified time limit. The system tracks the user's progress, allows them to save questions for later review, and displays the final score at the end.

Key Features:

Login Interface:

Users must log in with a username and password.
Validates user credentials before allowing access to the exam.
Timed Exam:

A countdown timer is implemented using Timer and TimerTask.
The exam consists of multiple-choice questions, and users must answer them within the time limit.
Question Navigation:

Users can move to the next question or save a question for later review.
A "Save for later" option allows users to revisit questions before submitting the final exam.
Scoring:

The system tracks the number of correct answers and calculates the final score.
The final score is displayed in a dialog box once the exam is completed.
Question Bank:

The application includes a set of predefined questions with multiple-choice answers.
Questions cover basic Java programming concepts.
Technology Used:

Java Swing: For building the GUI components like login form, buttons, labels, and radio buttons.
Java AWT: For basic window and layout management.
JButton, JRadioButton, JLabel, JTextField: Core components used to create the user interface.
Timer and TimerTask: For implementing the countdown timer during the exam.

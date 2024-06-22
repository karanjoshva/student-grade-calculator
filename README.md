# student-grade-calculator
java program for student grade calculator
## Grade Calculator: A Java Program

This program is a simple grade calculator written in Java. It calculates the total marks, average percentage, and grade for a student based on their marks in five subjects.

### Getting Started

1. **Prerequisites:** You will need Java installed on your system. You can check if you have Java by running `java -version` in your terminal. If you don't have it, download and install it from the official Java website: [https://www.oracle.com/java/technologies/downloads/](https://www.oracle.com/java/technologies/downloads/)
2. **Running the Program:** 
    * Save the provided code as `gradecalculator.java`.
    * Compile and run the program using the following commands in your terminal:
        ```
        javac gradecalculator.java
        java gradecalculator
        ```

### How to Use the Calculator

The program will prompt you to enter the following information:

* Your Name (String)
* Roll Number (Integer)
* Marks for each subject (Maths, French, English, Science, Social) - Integers between 0 and 100

Once you enter all the information, the program will calculate and display the following:

* Total Marks out of 500
* Average Percentage
* Grade based on the following scale:
    * O: 95% and above
    * A: 90% to 94%
    * B: 80% to 89%
    * C: 70% to 79%
    * D: 60% to 69%
    * E: 50% to 59%
    * Fail: Below 50%

### Additional Notes

* This is a basic grade calculator and assumes all subjects have equal weightage.
* You can modify the program to accommodate different grading scales or subject weightages. 

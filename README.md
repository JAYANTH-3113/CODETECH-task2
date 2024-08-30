## *NAME*:ADIGARLA JAYANTH KUMAR
## *COMPANY*:CODETECH IT SOLUCTIONS
## *ID*:CT08DS7293
## *DOMAIN*:JAVA PROGRAMMING
## *DURATION*:AUGUST 20th TO SEPTEMBER 20th, 2024
## *MENTOR*:neela santhosh kumar


# *Project Overview*

## *Project: Exploratory Java Programming On STUDENT GRADE TRACKER*
## Overview of Student Grade Manager

## **Purpose**
The Student Grade Manager is a Java application designed to help students and educators track and manage grades for various subjects or assignments. The system allows users to input grades, calculate averages, and display detailed information about individual subjects and overall performance.

## **Features**
1. **Subject Management**:
   - Add new subjects or assignments.
   - Maintain a record of grades for each subject.

2. **Grade Management**:
   - Input grades for specific subjects.
   - Calculate and display the average grade for each subject.
   - Determine and display the letter grade for each subject based on average scores.

3. **Overall Performance Tracking**:
   - Calculate and display the average grade across all subjects.
   - Determine and display an overall letter grade based on the average of all subjects.

4. **User Interface**:
   - A command-line interface (CLI) for user interaction.
   - Options to add subjects, input grades, view subject information, and display overall grades.

## **Components**

1. **`Subject` Class**:
   - **Attributes**:
     - `name`: The name of the subject.
     - `grades`: A list of grades for the subject.
   - **Methods**:
     - `addGrade(double grade)`: Adds a grade to the subject.
     - `calculateAverage()`: Calculates the average of all grades for the subject.
     - `getLetterGrade()`: Determines the letter grade based on the average grade.
     - `toString()`: Provides a string representation of the subject’s information.

2. **`GradeManager` Class**:
   - **Attributes**:
     - `subjects`: A map storing subjects with their names as keys.
   - **Methods**:
     - `addSubject(String subjectName)`: Adds a new subject.
     - `addGrade(String subjectName, double grade)`: Adds a grade to a specific subject.
     - `displaySubjectInfo(String subjectName)`: Displays information for a specific subject.
     - `displayOverallGrades()`: Calculates and displays average grades and letter grades for all subjects.
     - `getOverallLetterGrade(double average)`: Determines the overall letter grade based on the average of all subjects.

3. **`StudentGradeManager` Class (Main Application)**:
   - **Purpose**: Provides a command-line interface for users to interact with the `GradeManager`.
   - **User Options**:
     - Add new subjects.
     - Input grades for existing subjects.
     - View detailed information about specific subjects.
     - Display overall performance across all subjects.
     - Exit the application.

## **How It Works**

1. **Adding Subjects**:
   - Users can add new subjects to the system, which initializes with an empty list of grades.

2. **Adding Grades**:
   - Users can input grades for each subject. Grades are appended to the respective subject’s list of grades.

3. **Displaying Subject Information**:
   - For each subject, the system calculates and displays the average grade and the corresponding letter grade.

4. **Overall Performance**:
   - The system calculates and displays the average grade across all subjects and provides an overall letter grade based on this average.

5. **Command-Line Interface**:
   - The CLI allows users to select options for managing grades and viewing information. The system prompts users for input and displays results in a text-based format.

## **Benefits**

- **Comprehensive Tracking**: Allows tracking of grades for multiple subjects with detailed average and letter grade calculations.
- **Easy Management**: Simplifies the process of adding subjects and grades, and provides clear information about performance.
- **User-Friendly**: Provides a straightforward CLI for managing and viewing grade-related data.

This project serves as a foundational tool for grade management and can be expanded with features such as data persistence (e.g., saving to files or databases), more advanced statistical analysis, or a graphical user interface (GUI) for improved user experience.

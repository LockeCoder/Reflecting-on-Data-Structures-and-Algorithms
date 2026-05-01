# CS-300 Data Structures and Algorithms Portfolio

CS-300 portfolio repository for my ABCU advising assistance program. This project demonstrates data structure analysis, algorithm selection, C++ implementation, file parsing, input validation, and reflection on writing maintainable software.

## Project Overview

The main problem I addressed was creating an advising assistance program for ABCU academic advisors. The program needed to load course data from a CSV file, display all available courses in alphanumeric order, and allow users to retrieve information for a specific course, including prerequisites.

This required building a data management system that could organize course records, support quick lookups, validate input, and present course information clearly to the user.

## Repository Contents

- `ProjectTwo.cpp`: Final C++ advising assistance program
- `CS 300 ABCU_Advising_Program_Input.csv`: Course input data
- `Project One.docx`: Data structure analysis and pseudocode
- `2-3 Assignment Vector Sorting.docx`: Vector sorting assignment
- `4-2 Assignment Hash Tables.docx`: Hash table assignment
- `5-2 Assignment Binary Search Tree.docx`: Binary search tree assignment
- `Case 1 and 2.png`: Program testing screenshot
- `Case 2 and 3.png`: Program testing screenshot
- `Case 3 and 4.png`: Program testing screenshot
- `Case 4 and 5.png`: Program testing screenshot
- `Input and Output Test with Case 9.png`: Exit/input-output test screenshot
- `README.md`: Repository documentation

## Data Structure Approach

For the final advising program, I used a hash table because it supports efficient course lookup by course number. This was appropriate for the project because academic advisors need to search for course information quickly and retrieve prerequisite details without scanning the entire dataset manually.

The project also included analysis of other data structures, including vectors and binary search trees. Comparing these structures helped show how data organization affects runtime efficiency, lookup speed, sorting behavior, and maintainability.

## Program Features

- Loads course data from a CSV file
- Parses course number, course title, and prerequisites
- Stores course records in a hash table
- Displays all loaded courses
- Prints courses in alphanumeric order
- Looks up a specific course by course number
- Displays prerequisite information for a selected course
- Validates menu input
- Handles missing files and malformed course data
- Provides a menu-driven console interface

## Build and Run

### Requirements

- C++17 or newer
- Visual Studio, g++, or another C++ compiler

### Example Run

Compile and run `ProjectTwo.cpp`, then enter the path to the CSV file when prompted.

Example input file:

```text
CS 300 ABCU_Advising_Program_Input.csv
```

The program menu allows the user to:

1. Load course data
2. Display all courses
3. Display course information
4. Display a sorted list of courses
5. Print a course and prerequisites
9. Exit

## Skills Demonstrated

- C++ programming
- Data structure analysis
- Hash table implementation using `unordered_map`
- CSV file parsing
- Input validation
- Error handling
- Alphanumeric sorting
- Menu-driven console application design
- Requirements-based implementation
- Algorithmic thinking
- Technical reflection and documentation

## Portfolio Reflection

### What Was the Problem You Were Solving in the Projects for This Course?

The main problem I addressed was creating an advising assistance program for ABCU academic advisors. The program needed to load course data efficiently, display all available courses in alphanumeric order, and allow users to retrieve information on specific courses, including prerequisites.

This required building a robust data management system to handle course data and support quick lookups.

### How Did You Approach the Problem? Why Are Data Structures Important to Understand?

I approached the problem by focusing on data organization and retrieval efficiency. Based on my analysis from Project One, I decided to use a hash table for this task because it supports fast data access, which is ideal for applications requiring frequent searches.

Understanding data structures is essential in software development because they directly impact a program's efficiency, speed, and scalability. By selecting a hash table, I could ensure that course lookups and data manipulation operations were optimized for the user's needs.

### How Did You Overcome Any Roadblocks You Encountered?

I encountered roadblocks such as managing user input validation and file errors. To overcome these, I implemented error handling for file operations and designed a user input validation function to support smooth interaction with the menu.

Testing was also crucial in identifying and fixing unexpected behaviors, such as handling empty files or malformed data entries, which improved the program’s reliability.

### How Has Your Work on This Project Expanded Your Approach to Designing Software and Developing Programs?

This project reinforced the importance of planning and analyzing the problem before coding. By developing pseudocode and analyzing various data structures, I understood the optimal solution and could code with a purpose.

This approach helped me focus on building a scalable and efficient program while keeping the user experience in mind, which is essential in real-world applications.

### How Has Your Work on This Project Evolved Regarding How You Write Maintainable, Readable, and Adaptable Programs?

Working on this project highlighted the need for clear code structure and documentation. To enhance readability, I used inline comments, meaningful variable names, and modular functions.

Additionally, I focused on keeping the code adaptable for potential future requirements, such as adding new features. The experience improved my approach to writing maintainable code so that others and my future self can understand and expand upon my work.

## Project Value

This project shows my ability to analyze a problem, compare data structure options, select an appropriate implementation strategy, and build a functional C++ console application. It is strongest for demonstrating foundational software engineering skills, algorithmic thinking, data handling, input validation, and maintainable program design.

## Future Improvements

- Reformat `ProjectTwo.cpp` for improved GitHub readability
- Add a `.gitignore` file for C++ and Visual Studio artifacts
- Add screenshots directly to the README
- Add clearer compile/run commands for Visual Studio and g++
- Organize documents and screenshots into `docs/` and `media/` folders

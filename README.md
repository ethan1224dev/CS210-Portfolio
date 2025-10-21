Summarize the project and what problem it was solving.
This project focused on creating an item-tracking program for a grocery store. The goal was to analyze daily sales records by reading a text file containing all purchased items, then count how many times each item appeared. The program helps the store understand customer purchasing patterns so they can optimize their product layout. It features a menu system that allows the user to search for an item, display all item frequencies, print a histogram for visualization, and automatically generate a backup file called frequency.dat for data preservation.

What did you do particularly well?
I designed the program using a clear class structure (GroceryTracker) that keeps data and functionality organized. The use of a map to store item frequencies made the logic efficient and straightforward. I also made sure the file handling process worked smoothly so the program could automatically back up data without any user input. The final result was stable, readable, and user-friendly.

Where could you enhance your code? How would these improvements make your code more efficient, secure, and so on?
I could add input validation to prevent invalid user entries and handle cases where the input file might be missing or empty. Adding exception handling and checking for edge cases would make the program more robust and secure. I could also refactor some parts to use functions for menu handling and output formatting to make the program more modular and easier to expand in the future.

Which pieces of the code did you find most challenging to write, and how did you overcome this? What tools or resources are you adding to your support network?
The most challenging part was getting the program to correctly locate and read the input file. Visual Studio can be very picky about where files are stored, so the program initially couldn’t find grocerylist.txt. I fixed this by reconfiguring the project so that the working directory matched the source files, ensuring the executable could access the text file. I used Visual Studio documentation and testing through trial and error to understand how file paths work within a C++ project environment.

What skills from this project will be particularly transferable to other projects or course work?
This project helped strengthened my understanding of file input and output in C++, as well as how to use maps and classes effectively. The skills I gained in data organization, code structure, and debugging are easily transferable to future programming courses and software development projects. It also gave me practical experience with version control through GitHub, which is important in real-world development.

How did you make this program maintainable, readable, and adaptable?
I made the program maintainable by separating logic into a class and keeping variable and function names clear and descriptive. Inline comments were used to explain key parts of the code, making it easier for others to understand. The menu-driven design makes it simple to add new features later, such as sorting items alphabetically or exporting reports in different formats. The code follows consistent formatting and naming conventions, which supports long-term adaptability and readability.

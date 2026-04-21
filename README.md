# CS210-project
Airgead Banking investment calculator for CS-210 Project Two. Console app displaying year-by-year compound interest growth with and without monthly deposits, featuring input validation and OOP design in C++.

Module Eight Journal Reflection

Summarize the project and what problem it was solving.

This project was an investment calculator for Airgead Banking that shows how money grows over time with compound interest. It compares growth with and without monthly deposits so users can see the difference and make better financial decisions.

What did you do particularly well?

I did well with input validation. The program catches bad input like negative numbers or invalid entries and prompts the user to try again without crashing. I also separated the calculation logic into its own class instead of putting everything in main, which made it easier to work with.

Where could you enhance your code? How would these improvements make your code more efficient, secure, and so on?

I could add better output formatting to align dollar amounts in columns so the tables look cleaner. I could also add error handling for edge cases like overflow errors from extremely large inputs. Adding file output would let users save their results instead of just viewing them in the console.

Which pieces of the code did you find most challenging to write, and how did you overcome this? What tools or resources are you adding to your support network?

The input validation loops were the hardest because I had to handle multiple failure cases and clear the input buffer or the program would get stuck. I used cplusplus.com and Stack Overflow to figure out how cin.clear and cin.ignore work together, and those are now part of my regular toolkit.

What skills from this project will be particularly transferable to other projects or course work?

Input validation is transferable to any program that takes user input, especially the kind of tools and applications I want to build as I move toward cloud development and software engineering. The OOP structure and class separation makes code reusable and maintainable. Working with loops, conditionals, and formatted output are foundational skills I'll use in every project.

How did you make this program maintainable, readable, and adaptable?

I separated the calculation logic into its own class with header and implementation files, which keeps main.cpp focused on user interaction. I used descriptive variable names and added comments explaining what each file does. If I need to change how interest is calculated, I only have to edit the InvestmentCalculator class without touching main.

# Module 8 Journal

- Summarize the project and what problem it was solving.

This program enables a store owner or analyst to easily analyze item sales data.
Instead manually counting items in a list, the user can
spin up the program, display the aggregated data, and write interactive queries.

- What did you do particularly well?

I believe I did an good job of keeping each method and function concise and readable.
I made an effort to use insightful variable names and reduce lines of code when possible.

- Where could you enhance your code? How would these improvements make your code more efficient, secure, and so on?

One thing I would like to change is the that the code currently has file names hardcoded in the main function.
It would be better to have them either passed in via user input or as CLI arguments. This would make the program
more adaptable and useful.

- Which pieces of the code did you find most challenging to write, and how did you overcome this? What tools or resources are you adding to your support network?

The most challenging part for me was the output/display logic. I am unfamiliar with the C++ style of output
formatting using `setw`, `left` ect... I defintely used various sources of online C++ documentation like
cpprefernce.com as well as Stack Overflow to help me with that part of the project.

- What skills from this project will be particularly transferable to other projects or course work?

In future course work I'm sure there will be tasks that require reading and writing files using code.
This project was an excellent way to become more familiar with that process.

- How did you make this program maintainable, readable, and adaptable?

I separated my code into three different modules. Main, DB, and IO. This promotes modularity and
makes it easier to reason with the program. I also used descriptive variable and method names
to make it clear what my code is doing. Finally, I implemented inline comments and Google standard
documentation to my classes and methods so that anyone reading my code will have a better idea
of what the code is doing.

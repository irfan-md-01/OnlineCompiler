🖥️ Django Online Compiler
An online compiler built with Django that supports Python, C++, and Java code execution with input handling, persistent code storage, and a user-friendly editor using CodeMirror.

🚀 Features
✔️ Supports Python, C++, and Java Compilation & Execution
✔️ Code Editor with Syntax Highlighting (CodeMirror)
✔️ User Input Support
✔️ Persistent Code (Retains code on revisits)
✔️ Handles Infinite Loops & Time Limit Exceeded (TLE) errors
✔️ Separate execution pages for each language

📝 Usage
Select a programming language: Python, C++, or Java.
Write your code in the syntax-highlighted editor.
Provide custom input (if needed).
Click Run Code to execute.
The output appears below the editor.

🔧 Tech Stack
Backend: Django
Frontend: HTML, CSS, JavaScript (CodeMirror)
Compiler Execution: Python subprocess

🛠️ How It Works
Python execution: Runs using the system’s python3 interpreter.
C++ execution: Uses g++ to compile and execute code.
Java execution: Uses javac to compile and java to execute code.
Time Limit Exceeded (TLE) Handling: Uses subprocess timeout to prevent infinite loops.

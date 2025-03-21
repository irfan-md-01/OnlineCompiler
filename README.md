🖥️ Django Online Compiler

An online compiler built with Django that supports Python, C++, and Java code execution with input handling, persistent code storage, and a user-friendly editor using CodeMirror.

🚀 Features

✅ Supports Python, C++, and Java Compilation & Execution
✅ Code Editor with Syntax Highlighting (CodeMirror)
✅ User Input Support
✅ Persistent Code (Retains code on revisits)
✅ Handles Infinite Loops & Time Limit Exceeded (TLE) errors
✅ Separate Execution Pages for each language

📝 Usage

1. Select a programming language: Python, C++, or Java.
2. Write your code in the syntax-highlighted editor.
3. Provide custom input (if needed).
4. Click Run Code to execute.
5. The output appears below the editor.

🔧 Tech Stack

● Backend: Django
● Frontend: HTML, CSS, JavaScript (CodeMirror)
● Compiler Execution: Python subprocess

🛠️ How It Works

● Python Execution: Runs using the system’s python3 interpreter.
● C++ Execution: Uses g++ to compile and execute code.
● Java Execution: Uses javac to compile and java to execute code.
● Time Limit Exceeded (TLE) Handling: Uses subprocess timeout to prevent infinite loops.

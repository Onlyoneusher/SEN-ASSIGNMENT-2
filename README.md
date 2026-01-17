# SEN-ASSIGNMENT-2
Dominion Borngreat 24/13566 Computer Science
Planning:
Define the project scope: Create a basic CLI app for managing todos. Target audience: Beginners or anyone needing a quick task tracker.
Identify requirements: Users should add, view, complete, and delete tasks. Keep it console-based, no GUI or persistence beyond runtime.
Resources: Python (standard library only, no external packages). Time estimate: 1-2 hours for development.
Risks: Minimal – edge cases like invalid inputs.

Requirements Analysis:
Gather detailed functional requirements:
Add task: Input a string description.
View tasks: Display numbered list with status (pending/completed).
Mark as completed: Select by number.
Delete task: Select by number.
Exit app.

Non-functional: Simple, user-friendly prompts; handle invalid inputs gracefully.
Stakeholders: End-user (you or anyone running the script).

Design:
High-level design: Use a list of dictionaries to store tasks (e.g., [{'task': 'Buy groceries', 'completed': False}]).
Architecture: Main loop for menu options; functions for each action (add_task, view_tasks, etc.).
UI: Text-based menu with numbered choices.
Data flow: User inputs → Process → Update list → Display.

Implementation:
Write the code in Python.
Break into functions for modularity.
(This is where the actual coding happens – see the implementation below.)

Testing:
Unit testing: Test each function (e.g., add_task adds to list correctly).
Integration testing: Run the full app; simulate user inputs.
Edge cases: Empty list, invalid menu choices, marking non-existent tasks.
For this simple project, manual testing in the terminal suffices.

Deployment:
Package as a single .py file.
Run via python todo_app.py.
For sharing: Upload to GitHub (steps provided below).

Maintenance:
Fix bugs if reported (e.g., add error handling for large inputs).
Enhancements: Add file persistence (save to JSON), due dates, or priorities.
Monitor usage: If popular, iterate based on feedback.


This SDLC ensures the project is built systematically, reducing errors and making it scalable if needed.
Project Implementation

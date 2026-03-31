What I'm building:
A web-based grade calculator that helps students estimate their course grade in real time.

Who it's for / Why:
This tool is for students who want to track their performance and plan study time by seeing how assignment/test scores affect their final grade; it solves uncertainty around grade projection and goal-setting.

Core features:
1. Input fields for assignment, quiz, exam categories with weights and earned points.
2. Dynamically compute current grade based on entered scores and weights.
3. "What-if" mode to preview how future grades would impact the final course grade.
4. Validation and user feedback for missing or invalid input (e.g., percentages > 100).
5. Save/load configuration to local storage so students can revisit their grade plan.

What I don't know yet:
- How to manage state updates and re-calculate grade efficiently when multiple fields change.
- How to implement robust form validation and error messaging in vanilla JavaScript.
- How to structure JavaScript code for maintainability (modules, functions, DOM updates).
- How to persist data in localStorage and recover it safely (JSON parsing, edge cases).
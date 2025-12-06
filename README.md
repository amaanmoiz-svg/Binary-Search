# Algorithm name - Binary Search

# Demo Screenshots (are in the screenshots folder)

- Random list generation  
  ![Random List](Screenshots/Random Generated List.png)

- Successful search  
  ![Success](Screenshots/Target_found.png)

- Failed search  
  ![Failed](Screenshots/Target_not_found.png)



#Problem Breakdown & Computational Thinking
1. Decomposition
Breaking the problem into smaller, manageable steps:
-Generate a sorted list of numbers.
-Take a target value as input from the user.
-Compare the middle element of the current list segment with the target.
-If the middle element equals the target → stop (found).
-If the middle element is greater → search the left half.
-If the middle element is smaller → search the right half.
-Repeat until the target is found or the list segment is empty.

2. Pattern Recognition
Identifying repeated behaviors or similarities in the algorithm:
The algorithm always checks the middle element of the current list segment.
Each step reduces the search space by half.
Decisions follow a consistent pattern: move left or right based on comparison.

3. Abstraction
Hiding unnecessary details and focusing on what matters for the user:
User only sees the list and step-by-step results.
Internal variables like low, high, and mid are hidden from the user.
Only essential information (current segment, middle value, comparison result) is displayed.

4. Algorithm Design
Describing input, process, and output:
Input:
A sorted list of numbers
A target number

Process:
Perform binary search using divide-and-conquer: compare middle element → decide left or right → repeat

Output:
Step-by-step explanation of the search
Whether the target was found or not


#Steps to run
1.	Install Python 3
-Ensure that Python 3 is installed on your computer. You can verify by running python --version or python3 --version in your terminal.
2. Install Required Libraries
The app uses Gradio for the interactive interface. Install it using pip. 

pip install gradio

3) Run the App
Navigate to the project folder where app.py is located and run:
python app.py
This will start the app and display a local URL in the terminal.

4)Open the App in Your Browser
Copy the local URL (e.g., http://127.0.0.1:7860) into your browser to interact with the app.

5)Use the App

Enter a target number to search.

Observe the step-by-step visualization of the binary search.

Try different numbers to test both successful and unsuccessful searches

Author & Acknowledgment

Author: Amaan Mohammed
Course: CISC-121

Acknowledgments:
Gradio documentation for UI guidance
Course lectures and examples for algorithm visualization and testing

This project was developed with guidance from course lectures, Gradio documentation, and the assistance of ChatGPT for documentation and debugging suggestions.

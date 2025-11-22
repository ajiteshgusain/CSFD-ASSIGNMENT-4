# Project Deep Dive and Development Log

## 1. Project Overview

This mini-project is a **Console-Based Calculator** developed in Python (or your chosen language). [cite_start]The primary goal was to create a fully functional, reliable application capable of performing the four basic arithmetic operations: addition, subtraction, multiplication, and division. The project serves as a practical demonstration of several core concepts:

* **Fundamental Programming:** Use of functions, loops, and conditional logic.
* **Development Tools:** Efficient use of Visual Studio Code (VS Code) for development[cite: 32].
* **Version Control:** Maintenance and tracking of project history using a Git repository[cite: 33].
* **Documentation:** Creating clear, professional documentation in Markdown format[cite: 63].

---

## 2. Development Process (How I Built It)

The project followed a structured development workflow, ensuring proper use of version control and creating a history of changes (at least 5 meaningful commits ).

1.  **Repository Setup:** The project folder was initialized as a Git repository (`git init`) and created within VS Code.
2.  **Core Functions:** I started by defining four separate functions: `add(x, y)`, `subtract(x, y)`, `multiply(x, y)`, and `divide(x, y)`. This modular approach makes the code readable and easy to test.
3.  **Error Handling (Division):** A critical step was implementing error checking within the `divide` function. This prevents the program from crashing by checking if the divisor (`y`) is zero and returning an error message instead of executing the division.
4.  **Main Loop and User Interface:** I built the main program loop, which continually prompts the user to select an operation and enter two numbers. This loop also handles exiting the application and validating input.
5.  **Final Documentation:** The project was finalized by creating the required files: the `.gitignore` file , the `README.md` file and this documentation file within the dedicated `docs/` folder.

---

## 3. Future Improvements

To expand this project beyond the assignment requirements, the following features could be implemented in future development:

* **Advanced Operations:** Introduce support for more complex mathematical functions, such as exponents (`**`), square roots, or trigonometric functions.
* **Graphical User Interface (GUI):** Move the calculator from the command line to a graphical interface using a Python library (like Tkinter) for a modern, more user-friendly experience.
* **Continuous Calculation:** Implement logic that allows the user to chain operations, using the result of the previous calculation as the first input for the next one.
* **Better Input Validation:** Add more robust checks to ensure the user only enters numbers when required, providing helpful feedback for incorrect inputs.

---

##  Final Steps to Complete the Assignment

1.  **Save the File:** Save this content in your `docs/project_details.md` file in VS Code.
2.  **Final Commit and Push (GitHub Desktop):**
    * Go to **GitHub Desktop**.
    * On the **Changes** tab, you will see the new `docs/` folder listed.
    * **Commit:** Enter a **Summary** (e.g., "Added all final documentation and repository structure") and click **Commit to main**.
    * **Push:** Click the **Push origin** button to upload all final documentation to GitHub.

Once that final push is complete, you will have submitted the fully documented project.
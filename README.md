# Assignment 0: Tool Setup & Workflow Test

**Due Date:** ส่งภายในเวลาเรียน

---

### **Objective (วัตถุประสงค์)**

This assignment is a mandatory "warm-up" exercise. Its goal is to ensure that you have all the necessary development tools installed on your local machine and that you understand the basic Git workflow we will be using for all submissions in this course.

**This assignment will be graded based on completion.**

---

### **Part A: Tool Installation Checklist**

Before starting the task, please ensure you have the following tools installed and working on your local machine.

- **[ ] 1. Git:** The core version control system.
  - [Download here](https://git-scm.com/downloads/)

- **[ ] 2. Visual Studio Code (VS Code):** Our primary code editor.
  - [Download here](https://code.visualstudio.com/)

- **[ ] 3. VS Code Extensions:** Open VS Code, go to the Extensions tab (Ctrl+Shift+X), and install the following:
  - **[ ] GitLens:** To supercharge Git capabilities within VS Code. (Search for `eamodio.gitlens`)
  - **[ ] PlantUML:** To create and preview UML diagrams directly in the editor. (Search for `jebbs.plantuml`)

---

### **Part B: Your Task**

Your task is to modify this repository to prove that your tools are set up correctly.

**1. Edit This README File:**
   - Open this `README.md` file in VS Code.
   - Fill in your personal information below:
     - **Name:** [Your Name]
     - **Student ID:** [Your Student ID]

**2. Answer a Simple Question:**
   - In the section below, please answer the following question:
     - **What are you most excited to learn in this Software Design course?**
       > My Answer: [Your answer here...]

**3. Create a Simple UML Diagram:**
   - Inside this project folder on your local machine, create a **new file** named `diagram.puml`.
   - Open this new file and paste the following PlantUML code into it. This will create a very simple Use Case diagram.
     ```plantuml
     @startuml
     actor Student
     rectangle "My First System" {
       usecase "Submit Assignment" as UC1
     }
     Student -- UC1
     @enduml
     ```
   - You can preview the diagram directly in VS Code by pressing `Alt+D` (on Windows) or `Option+D` (on Mac). If you see a diagram, your PlantUML extension is working correctly!

---

### **Part C: Submission Workflow (How to Submit)**

This is the most important part. Follow these steps precisely to submit your work.

1.  **Clone the Repository:** After accepting the assignment on GitHub Classroom, clone your personal repository to your local machine using the `git clone <repository-name>` command.

2.  **Complete the Tasks:** Perform all tasks listed in Part B.

3.  **Commit and Push Your Changes:** Open a Terminal or Git Bash inside your project folder and run the following three commands in order.

    **Step 1: Stage your changes (Add files to the box)**
    ```bash
    git add .
    ```
    *(This command adds all modified files, including your updated `README.md` and the new `diagram.puml`, to the staging area.)*

    **Step 2: Commit your changes (Seal the box and label it)**
    ```bash
    git commit -m "Complete Assignment 0: Tool setup test"
    ```
    *(This command saves your changes permanently to your local Git history with a descriptive message.)*

    **Step 3: Push your changes to GitHub (Send the box to the post office)**
    ```bash
    git push
    ```
    *(This command uploads all your saved commits to your GitHub repository, completing the submission.)*

4.  **Verify Your Submission:**
    - Go back to your assignment repository on the GitHub website.
    - You should see your updated `README.md` file with your name and answers.
    - You should see the new `diagram.puml` file in the file list.
    - If you see your changes, you have successfully submitted the assignment! The autograding test should now show a passing score.

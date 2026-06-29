# Windows Commands 
# Windows Command Prompt (CMD) Essentials

The Command Prompt (CMD) is a text-based Interface (CLI) used to interact with the Operating System. For developers, mastering CMD is essential for automation, running scripts, and managing system files efficiently without a graphical interface.

---

## Part 1: File and Directory Navigation

These commands are used to move around directories (folders) and manage files inside the system:

### 1. `cd` (Change Directory)
* **What it does:** Moves you from your current folder to another folder.
* **Example:** `cd Desktop\CmdStudio` moves you straight into your project folder.
* **Tip:** `cd ..` moves you back one folder level.

### 2. `dir` (Directory Listing)
* **What it does:** Displays a list of all files and subfolders inside your current directory.
* **Benefit:** It helps you verify if a specific file (like a script) exists before trying to run it.

### 3. `mkdir` (Make Directory)
* **What it does:** Creates a brand new, empty folder.
* **Example:** `mkdir PythonProjects` creates a folder with that name instantly.

### 4. `echo` and `type` (File Creation & Reading)
* **What it does:** * `echo hello > note.txt` creates a file named `note.txt` and writes "hello" inside it.
  * `type note.txt` displays the contents of that text file directly inside the CMD screen.

---

## Part 2: Networking and System Status

These commands are used to diagnose connection issues and check the system network:

### 1. `ipconfig` (IP Configuration)
* **What it does:** Shows all network adapter details, including your local IP address and Default Gateway.
* **Benefit for Programmers:** Crucial when setting up local servers or connecting mobile apps to a local backend API during development.

### 2. `ping` (Network Connectivity Test)
* **What it does:** Sends small packets of data to a specific IP or server to check if it is reachable and measures the speed of the connection.
* **Example:** `ping google.com` checks if your internet is working properly.

## Part 3: Git Version Control Commands

Git is a command-line tool used for Version Control. It helps developers track changes in their code, save project history, and upload files to GitHub.

Here are the essential Git commands used to manage a project:

### 1. `git init`
* **What it does:** Initializes a brand new, empty local Git repository inside your project folder. It starts tracking your files.

### 2. `git status`
* **What it does:** Shows the current state of your repository. It lets you see which files have been modified, which are new, and which ones are not being tracked yet.

### 3. `git add .`
* **What it does:** Prepares all new or modified files in the folder to be saved (Stages the changes). The dot `.` means "add everything".

### 4. `git commit -m "your message"`
* **What it does:** Saves your changes permanently in the local history of your PC with a descriptive note (like a snapshot of your project). 
* *Example:* `git commit -m "Add study bootcamp notes"` saves the files with that specific description.

### 5. `git branch`
* **What it does:** Lists all the branches in your repository and shows you which branch you are currently working on (usually `main` or `master`).

### 6. `git log --oneline`
* **What it does:** Displays a clean, short history of all your past commits. Each commit is shown in just a single line, making it very easy to read.

### 7. `git remote add origin <URL>`
* **What it does:** Links your local folder on the PC to the remote repository online on GitHub. 
* *Note:* If you need to change or fix the link later, you use: `git remote set-url origin <URL>`.

### 8. `git push -u origin main`
* **What it does:** Uploads all your local saved commits safely from your computer straight to the `main` branch online on GitHub.

---

## 💡 Summary for Programmers: Why use Git?
* **Time Machine:** If you write a bug that breaks your code, you can easily roll back to a previous working version.
* **Collaboration:** It allows multiple programmers to work on the exact same project and files simultaneously without overwriting each other's work.

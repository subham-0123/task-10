. Initialize Git in Your Project Folder
cd /path/to/your/project
git init

2. Add All Your Files
git add .


Or for better commit history, stage them task-by-task (see below in Commit section).

3. Create .gitignore File (Optional but Recommended)

Example:

__pycache__/
*.log
.env
node_modules/


Save and commit:

git add .gitignore
git commit -m "Add .gitignore to exclude unnecessary files"

4. Write a README.md File (Documentation)

Create a README.md with an overview of your tasks/project.

Example Content:

# Task Collection

This repository contains solutions to previous tasks completed as part of [your course/project/personal practice].

## Structure

- Task 1 - Data Cleaning
- Task 2 - Web Scraping
- Task 3 - Flask API
- Task 4 - Machine Learning Model

## Usage

Clone the repository:

```bash
git clone https://github.com/yourusername/your-repo-name.git


Add & commit it:
```bash
git add README.md
git commit -m "Add README.md with project overview"

5. Make Commits Per Task

Break your work into meaningful commits.

git add task1/
git commit -m "Add Task 1: Data Cleaning Script"

git add task2/
git commit -m "Add Task 2: Web Scraping with BeautifulSoup"

git add task3/
git commit -m "Add Task 3: Flask API Endpoint Implementation"

git add task4/
git commit -m "Add Task 4: ML Model Training Script"

6. Link to GitHub Repo

Create a repository on GitHub, then:

git remote add origin https://github.com/yourusername/your-repo-name.git
git branch -M main

7. Push to GitHub
git push -u origin main

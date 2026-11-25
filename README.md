# SmartBudget_Manager
A project for managing Budget
SmartBudgetManager

Author: Your Name | Group: Your Group | ESI-SBA, 2nd year CP, 2026/2027

A small project for managing a personal budget. It keeps budget records (date, amount and ID) in simple files, tracks every change with Git, and is hosted on GitHub so it can be shared and developed with others.

What it does
Stores budget entries, for example January 1: Budget 1500£, ID 2026001.
Keeps a spreadsheet (SmartBudgetManager.xlsx) to view and calculate budget figures.
Records the full history of changes through commits, so any earlier version can be recovered.
Requirements
A free GitHub account.
Git installed (check with git --version).
Microsoft Excel, LibreOffice or Google Sheets to open the .xlsx file.
Any text editor (VS Code, Notepad, etc.) to edit .txt and .md files.
Getting started
Clone the repository
bash
git clone https://github.com/YOUR-USERNAME/SmartBudgetManager.git
cd SmartBudgetManager
Open the files: read this README.md first, then open SmartBudgetManager.xlsx in a spreadsheet program.
Add or change data: edit a file, then save your work:
bash
git add .
git commit -m "Describe your change"
git push
Check the history
bash
git log --oneline
Project structure
File	Purpose
README.md	Project description and instructions
SmartBudgetManager.xlsx	Budget spreadsheet
budget.txt	Budget entries as plain text (created, then deleted during the TP exercise)
Contributing

Do not commit directly to main. Create a branch for your task, push it, and open a pull request so a teammate can review it before merging.

Contact

Your Name, your.email@esi-sba.dz

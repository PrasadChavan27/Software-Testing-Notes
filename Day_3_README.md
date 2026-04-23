 Day 3: Git, GitHub & Test Documentation (Hands-on Guide)
🔧 1. Setup Git Environment (Do this first)
✅ Install Git
Download from: Git
Install with default settings
✅ Configure Git (VERY IMPORTANT)
Run in terminal:
git config --global user.name "Your Name"
git config --global user.email "your-email@gmail.com"
Check:
git config --list

✅ Create GitHub Account
Go to: GitHub
Create account

✅ (Optional) Install GUI
Install GitHub Desktop if you don’t like CLI

📁 2. Create Your First QA Test Repository
Step 1: Create Repo on GitHub
Name: qa-test-project
Step 2: Clone Repo
git clone https://github.com/your-username/qa-test-project.git
cd qa-test-project

📂 3. Create QA Project Structure (Important for interviews)
Create this folder structure:
qa-test-project/
│
├── test-cases/
│   ├── functional/
│   ├── integration/
│   ├── regression/
│
├── test-data/
├── bug-reports/
├── test-plans/
├── screenshots/
└── README.md

🧠 4. Git Basics for Testers (Practice Commands)
🔹 Initialize (if needed)
git init
🔹 Add files
git add .
🔹 Commit (write meaningful message)
git commit -m "Added initial test project structure"
🔹 Push to GitHub
git push origin main

🔄 Pull Latest Changes
git pull origin main

🚫 .gitignore for QA
Create .gitignore file:
*.log
*.tmp
node_modules/
.env
screenshots/*.png

✍️ 5. Commit Message Best Practice (VERY IMPORTANT)
Bad ❌
update file
Good ✅
Added login test cases for valid and invalid scenarios
Fixed bug report formatting issue
Updated test data for edge cases
👉 Use format:
[Action] + [What] + [Why]

🌿 6. Branching Strategy for Testing
Create branch:
git checkout -b feature/test-login
Examples:
feature/test-login
bugfix/login-validation
test/regression-suite

🔁 Merge Process
git checkout main
git pull origin main
git merge feature/test-login

📄 7. Add Test Cases (Real Work)
Create file:
test-cases/functional/login-test-cases.xlsx
Add:
Valid login
Invalid password
Empty fields
SQL injection case
Boundary inputs
👉 Then commit:
git add .
git commit -m "Added login functional test cases"
git push

🐞 8. Bug Reports Folder
Create:
bug-reports/login-bug-001.docx
Include:
Bug ID
Steps
Expected result
Actual result
Screenshot

🤝 9. Collaboration Workflow (Real Industry Flow)
Step 1: Create Branch
git checkout -b feature/test-signup
Step 2: Work + Commit
Step 3: Push
git push origin feature/test-signup
Step 4: Create Pull Request on GitHub
Step 5: Review → Merge

📘 10. Write README.md (MUST for interviews)
Add this:
# QA Test Project

## Test Approach
Manual + Functional Testing

## Project Structure
Explain folders

## How to Run Tests
Open test cases and execute manually

## Test Environment
Browser: Chrome
OS: Windows

## Test Data
Located in /test-data

## Bug Reporting
Check /bug-reports folder


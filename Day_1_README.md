Feature
SDLC
STLC
Meaning
Software Development Life Cycle
Software Testing Life Cycle
Scope
Entire development process
Only testing process
Objective
Build software
Test software
Activities
Dev + Test + Deploy
Only testing activities
Starts
From requirement phase
After requirements are analyzed
Ends
After maintenance
After test closure

🔷 SDLC (Software Development Life Cycle)
SDLC is the complete process of developing software from start to end.
📌 Phases:
Requirement Analysis – Gather client requirements
Planning – Timeline, resources, cost
Design – System architecture, UI design
Development – Coding starts
Testing – Verify product quality
Deployment – Release to users
Maintenance – Bug fixes, updates
👉 Goal: Build the software product

🔷 STLC (Software Testing Life Cycle)
STLC is a subset of SDLC, focused only on testing activities.
📌 Phases:
Requirement Analysis – Understand testable requirements
Test Planning – Strategy, tools, effort estimation
Test Case Development – Write test cases
Test Environment Setup – Prepare testing setup
Test Execution – Run test cases, find bugs
Test Closure – Reports, metrics, lessons learned
👉 Goal: Ensure software quality
SDLC is the complete process of software development including planning, design, coding, testing, and deployment.
 STLC is a part of SDLC that focuses only on testing activities like test planning, test case writing, execution, and reporting to ensure quality.
🔷 What is Software Testing?
Software Testing is the process of checking whether a software application is working correctly and meets requirements.
👉 Goal: Find bugs + ensure quality

🔶 Why Software Testing is Important?
Detects bugs early
Improves software quality
Ensures customer satisfaction
Prevents failures in production
👉 Example: Payment failure in an e-commerce app = loss of money 💸

🔷 Basic Terminologies (Very Important)
✅ Bug / Defect
Error in the application
 👉 Example: Login button not working
✅ Test Case
Step-by-step process to test a feature
✅ Test Scenario
High-level idea of what to test
 👉 Example: “Check login functionality”
✅ Test Suite
Collection of test cases

🔶 Types of Testing
1. Functional Testing
Checks what the system does
Examples:
Login
Signup
Payment

2. Non-Functional Testing
Checks how the system performs
Examples:
Performance (speed)
Security
Usability

🔷 Testing Levels
Unit Testing – Done by developers
Integration Testing – Check module interaction
System Testing – Test complete system
Acceptance Testing – Done by client/user

🔶 Testing Methods
🟢 Manual Testing
Testing done by humans
No automation tools
🔵 Automation Testing
Using tools like Selenium WebDriver
Faster & repeatable

🔷 SDLC vs STLC (Quick Recall)
SDLC → Develop software
STLC → Test software

🔶 Important Testing Concepts
🔹 Verification vs Validation
Verification → “Are we building the product right?”
Validation → “Are we building the right product?”

🔹 Severity vs Priority
Severity
Priority
Impact of bug
Urgency to fix
High → App crash
High → Fix immediately


🔹 Smoke vs Regression Testing
Smoke → Basic functionality check
Regression → Check after changes

🔥 Real Example (Easy to Remember)
👉 Login Page Testing:
Enter valid data → Should login
Enter wrong password → Show error
Leave fields empty → Show validation
🔷 What are Types of Testing?
Types of Testing = Different ways to check software based on purpose, level, and approach
👉 Simple: What exactly are we testing and how?

🔶 1. Functional Testing (MOST IMPORTANT)
👉 Checks features are working correctly
📌 Examples:
Login works or not
Payment success or fail
Add to cart
🔑 Common Types:
Unit Testing
Integration Testing
System Testing
Acceptance Testing

🔶 2. Non-Functional Testing
👉 Checks performance & behavior
📌 Examples:
Website speed 🚀
Security 🔐
UI/UX experience
🔑 Types:
Performance Testing
Load Testing
Stress Testing
Security Testing
Usability Testing

🔶 3. Manual Testing
👉 Testing done without tools
Human executes test cases
Used in early stages

🔶 4. Automation Testing
👉 Testing using tools like Selenium WebDriver
Faster
Reusable scripts
Used for regression

🔶 5. Smoke Testing
👉 Basic check of build stability
📌 Example:
App opens
Login works
👉 Done before detailed testing

🔶 6. Sanity Testing
👉 Check specific functionality after changes
📌 Example:
Only payment module tested after bug fix

🔶 7. Regression Testing
👉 Ensure old features still work after update
📌 Example:
After adding new feature, check login again

🔶 8. Retesting
👉 Test fixed bug again
📌 Example:
Bug: Login failed
Fix applied → Test login again

🔶 9. Exploratory Testing
👉 Tester explores app without test cases
Find unexpected bugs
Based on experience

🔶 10. Ad-hoc Testing
👉 Random testing without planning
No documentation
Quick bug finding

🔶 11. Alpha Testing
👉 Done by internal team
Before releasing to users

🔶 12. Beta Testing
👉 Done by real users
Feedback collected

🔥 Easy Real-Time Example (E-commerce)
Testing Type
Example
Functional
Login, Add to cart
Performance
Website load time
Smoke
App launch check
Regression
Old features after update
Security
Payment safety


🧠 Smart Trick to Remember
👉 Functional = What system does
 👉 Non-functional = How system performs

💬 Interview Answer (Best Short)
There are mainly two types of testing: functional and non-functional. Functional testing checks whether features like login or payment are working correctly, while non-functional testing checks performance, security, and usability. Additionally, we have testing types like smoke, regression, and sanity testing based on scenarios.
🔷 1. Waterfall Model
👉 A linear, step-by-step approach
📌 Flow:
Requirement → Design → Development → Testing → Deployment
👉 Each phase must be completed before moving to next
✅ Advantages:
Easy to understand
Clear structure
Good for small projects
❌ Disadvantages:
No flexibility
Changes are difficult
Testing comes late
💡 Example:
Banking system where requirements are fixed

🔷 2. Agile Methodology
👉 A flexible, iterative approach
Work is divided into small cycles (iterations)
Continuous feedback from client
📌 Key Features:
Frequent releases
Customer involvement
Quick changes possible
✅ Advantages:
Flexible
Faster delivery
Better quality
❌ Disadvantages:
Requires experienced team
Less documentation
💡 Example:
E-commerce apps (features updated frequently)

🔷 3. Scrum Framework (Agile Type)
👉 Scrum is a framework inside Agile
📌 Key Roles:
Product Owner → Defines requirements
Scrum Master → Manages process
Development Team → Builds product
📌 Key Concepts:
Sprint (2–4 weeks work cycle)
Daily Stand-up meeting
Sprint Planning
Sprint Review
🔁 Flow:
Plan → Develop → Test → Review → Repeat
💡 Example:
Developing login, cart, payment in different sprints

🔷 4. DevOps Approach
👉 Combines Development + Operations
📌 Goal:
Faster delivery
Continuous integration & deployment
🔑 Concepts:
CI/CD (Continuous Integration / Continuous Deployment)
Automation
Monitoring
✅ Advantages:
Fast releases
Automation reduces errors
Better collaboration
❌ Disadvantages:
Complex setup
Requires tools knowledge
💡 Example:
Apps like Netflix where updates happen frequently

🔥 Quick Comparison (Interview Gold)
Model
Type
Flexibility
Testing
Waterfall
Sequential
❌ Low
Late
Agile
Iterative
✅ High
Continuous
Scrum
Agile framework
✅ High
Every sprint
DevOps
Culture/process
✅ Very High
Continuous + automated


🧠 Easy Trick to Remember
Waterfall → Step by step 💧
Agile → Flexible 🔄
Scrum → Agile + Sprints 🏃
DevOps → Automation + Speed ⚡

💬 Interview Answer (Best Short)
Waterfall is a linear model where each phase is completed before the next begins. Agile is an iterative approach with continuous feedback. Scrum is a framework within Agile that works in sprints with defined roles. DevOps focuses on continuous integration and deployment with automation for faster delivery.
🔷 What is STLC?
STLC (Software Testing Life Cycle) is a step-by-step process followed by testers to ensure software quality.
👉 Goal: Deliver bug-free, high-quality software

🔶 STLC Phases (Step-by-Step)

1️⃣ Requirement Analysis
👉 Understand what needs to be tested
🔍 Activities:
Study SRS (requirement document)
Identify testable requirements
Clarify doubts with BA/Client
📌 Output:
Requirement understanding
RTM (Requirement Traceability Matrix)
💡 Example:
Login feature → username, password validation

2️⃣ Test Planning
👉 Decide how testing will be done
🔍 Activities:
Define test strategy
Select tools (manual / automation)
Estimate time & resources
📌 Output:
Test Plan document
💡 Example:
Decide to use Selenium WebDriver for regression

3️⃣ Test Case Development
👉 Write test cases & scenarios
🔍 Activities:
Create test cases
Prepare test data
Review test cases
📌 Output:
Test cases
Test scenarios
💡 Example:
Enter valid login → success
Invalid password → error message

4️⃣ Test Environment Setup
👉 Prepare testing setup
🔍 Activities:
Setup server / browser
Install tools
Prepare test data
📌 Output:
Ready test environment
💡 Example:
Chrome browser + test URL ready

5️⃣ Test Execution
👉 Execute test cases & find bugs
🔍 Activities:
Run test cases
Log defects in tool like JIRA
Retest & regression testing
📌 Output:
Test execution report
Defect reports
💡 Example:
Login fails → Bug reported

6️⃣ Test Closure
👉 Final stage of testing
🔍 Activities:
Check if all testing completed
Prepare test summary report
Analyze defects
📌 Output:
Test closure report
Lessons learned

🔥 STLC Flow (Easy to Remember)
👉 Requirement → Plan → Write → Setup → Execute → Close

🧠 Real-Time Example (Login Module)
Phase
Example
Requirement Analysis
Understand login feature
Test Planning
Decide testing approach
Test Case Dev
Write login test cases
Environment Setup
Open browser, setup URL
Execution
Test login with data
Closure
Report bugs & results


💬 Interview Answer (Best Short)
STLC is the Software Testing Life Cycle which includes phases like requirement analysis, test planning, test case development, test environment setup, test execution, and test closure. It ensures systematic testing and delivery of quality software.
🔷 1. Functional Testing (Verifies Features)
👉 Checks what the system does (features)
📌 Focus:
Business requirements
Expected functionality
🧪 Examples:
Login with valid credentials → Success
Add to cart → Product added
Payment → Transaction successful
✅ Key Point:
✔ “Does the feature work correctly?”

🔷 2. Non-Functional Testing (Verifies Performance & Behavior)
👉 Checks how the system performs
📌 Types:
Performance Testing → Speed
Load Testing → Multiple users
Security Testing → Data protection
Usability Testing → User experience
🧪 Examples:
Website loads within 2 seconds
System handles 1000 users at once
User data is secure
✅ Key Point:
✔ “How well does the system work?”

🔷 3. Maintenance Testing
👉 Done after deployment or updates
📌 Types:
🔹 Regression Testing
Ensure old features still work after changes
👉 Example:
 After adding a new payment method → check login & cart again

🔹 Sanity Testing
Check specific functionality after minor changes
👉 Example:
 Only test payment module after bug fix

✅ Key Point:
✔ “Did new changes break anything?”

🔷 4. Change-Related Testing
👉 Focus on recent changes or bug fixes
📌 Types:
🔹 Re-testing
Test the same bug again after fix
👉 Example:
 Login bug fixed → test login again

🔹 Regression Testing (again)
Ensure entire system is still working
👉 Example:
 After fixing login → test all modules

✅ Key Point:
✔ “Is the fix working & system stable?”

🔥 Quick Summary Table
Testing Type
Purpose
Example
Functional
Check features
Login, Payment
Non-functional
Check performance
Speed, Security
Maintenance
After changes
Regression, Sanity
Change-related
After bug fix
Re-testing, Regression


🧠 Easy Trick to Remember
Functional → What system does
Non-functional → How system performs
Maintenance → After release changes
Change-related → After bug fix

💬 Interview Answer (Best Short)
Functional testing verifies that features like login and payment work correctly. Non-functional testing checks performance, security, and usability. Maintenance testing includes regression and sanity testing after changes, while change-related testing focuses on re-testing and regression to ensure bug fixes and system stability.
🔷 What are Testing Levels?
👉 Testing levels define at which stage testing is performed in the software development process.
👉 Simple: From small parts → to full system → to user validation

🔶 1. Unit Testing (Component Level)
👉 Testing individual components or code units
👨‍💻 Done by:
Developers
📌 Focus:
Smallest part of application (function/method)
🧪 Example:
Test login function:
Check if password validation works
✅ Key Point:
✔ Tests single piece of code

🔶 2. Integration Testing (Combined Components)
👉 Testing interaction between modules
👨‍💻 Done by:
Developers / Testers
📌 Focus:
Data flow between modules
🧪 Example:
Login module + Database
Check if user data is fetched correctly
✅ Key Point:
✔ Tests module connections

🔶 3. System Testing (Complete System)
👉 Testing entire application as a whole
👨‍💻 Done by:
Testers
📌 Focus:
End-to-end functionality
🧪 Example:
Login → Add to cart → Payment → Logout
✅ Key Point:
✔ Tests complete system behavior

🔶 4. Acceptance Testing (User Perspective)
👉 Testing from end-user/business point of view
👨‍💼 Done by:
Client / End Users
📌 Types:
UAT (User Acceptance Testing)
Alpha & Beta testing
🧪 Example:
Client checks if website meets requirements
✅ Key Point:
✔ “Is the product ready for release?”

🔥 Easy Flow (Important)
👉 Unit → Integration → System → Acceptance
👉 Small → Medium → Large → User Level

🧠 Real-Time Example (E-commerce)
Level
Example
Unit
Test login function
Integration
Login + database
System
Full shopping flow
Acceptance
Client verifies app


💬 Interview Answer (Best Short)
Testing levels include unit testing, where individual components are tested; integration testing, where interactions between modules are verified; system testing, where the complete application is tested; and acceptance testing, where the client validates the system against requirements.
🔷 1. Testing Shows Presence of Defects
👉 Testing can show bugs exist, but cannot prove no bugs exist
💡 Example:
You test login → works fine
Still, some hidden bugs may exist
✔ Meaning: Testing reduces risk, not guarantees perfection

🔷 2. Exhaustive Testing is Impossible
👉 You cannot test everything
💡 Example:
Infinite input combinations (username, password)
Testing all = impossible
✔ Solution: Use risk-based testing

🔷 3. Early Testing (Shift Left)
👉 Start testing as early as possible
💡 Example:
Find requirement mistake early → saves time & cost
✔ Benefit:
Less cost
Fewer defects later

🔷 4. Defect Clustering
👉 Most bugs are found in few modules
💡 Example:
Payment module has maximum bugs
✔ Based on Pareto Principle (80/20 rule)
 👉 80% bugs in 20% areas

🔷 5. Pesticide Paradox
👉 Running same test cases again → no new bugs found
💡 Example:
Repeating same login test → no new defects
✔ Solution:
Update test cases regularly

🔷 6. Testing is Context Dependent
👉 Testing approach depends on project type
💡 Example:
Banking app → High security testing
Gaming app → Performance testing
✔ No one-size-fits-all

🔷 7. Absence of Errors Fallacy
👉 No bugs ≠ Correct product
💡 Example:
App has no bugs but doesn’t meet user needs
✔ Meaning:
Software must be useful + correct

🔥 Easy Trick to Remember
👉 Presence → Impossible → Early → Cluster → Pesticide → Context → Absence

💬 Interview Answer (Best Short)
The 7 principles of testing include that testing shows the presence of defects, exhaustive testing is impossible, early testing saves cost, defects are clustered in specific areas, repeated tests may not find new bugs (pesticide paradox), testing depends on context, and absence of errors does not mean the product is correct.
🔷 1. Identify Testing Types for Scenarios
Here are real scenarios + correct testing types:
🧪 Scenario-Based Mapping
Scenario
Testing Type
Check login functionality
Functional Testing
Website loads slowly
Performance Testing
App crashes with 1000 users
Load/Stress Testing
After bug fix, test same bug
Re-testing
After new feature, test old features
Regression Testing
Quick check after new build
Smoke Testing
Test specific module after change
Sanity Testing
Check data security (password encryption)
Security Testing
UI is user-friendly or not
Usability Testing

👉 Interview Tip: Always explain why you chose that type

🔷 2. Map STLC to SDLC Phases
👉 This is a very important interview question
SDLC Phase
STLC Phase
Requirement Analysis
Requirement Analysis
Planning
Test Planning
Design
Test Case Development
Development
Test Environment Setup
Testing
Test Execution
Deployment/Maintenance
Test Closure

🧠 Easy Understanding:
👉 STLC runs parallel to SDLC
Example:
Dev writes code → Tester prepares test cases
Dev completes feature → Tester executes tests

🔷 3. Create Testing Glossary (Important Terms)
Here’s a mini glossary (must know):
📘 Basic Terms
Bug/Defect → Error in software
Test Case → Step-by-step testing procedure
Test Scenario → High-level testing idea
Test Suite → Collection of test cases
Test Data → Input values for testing

📘 Advanced Terms
Severity → Impact of bug
Priority → Urgency to fix
RTM → Requirement Traceability Matrix
Build → Version of software
Release → Delivered to users

📘 Execution Terms
Smoke Testing → Basic check
Regression Testing → Check old features
Re-testing → Test fixed bug

🔷 4. Analyze Sample Application (Real Example)
🛒 Example: E-commerce Website
🔍 Modules:
Login
Product Search
Cart
Payment

🧪 Testing Approach:
🔹 Functional Testing
Login with valid/invalid data
Add/remove product
🔹 Non-Functional Testing
Page load speed
Payment security

🐞 Sample Bugs:
Login button not working
Cart not updating quantity
Payment failed but money deducted

📄 Sample Test Case:
Test Case: Login Functionality
Step 1: Enter valid username
Step 2: Enter password
Step 3: Click login
👉 Expected: User should login successfully

🔥 How to Answer in Interview
For different scenarios, I identify testing types based on functionality, performance, or changes. I map STLC phases parallel to SDLC phases to ensure testing is aligned with development. I also use a testing glossary to communicate clearly. While analyzing applications like e-commerce systems, I design test cases, identify bugs, and apply both functional and non-functional testing.

📄 1. SDLC vs STLC Comparison Document
Writing
SDLC vs STLC Comparison
🔷 SDLC (Software Development Life Cycle)
SDLC is the complete process of developing software from requirement gathering to maintenance.
Phases:
Requirement Analysis
Planning
Design
Development
Testing
Deployment
Maintenance

🔷 STLC (Software Testing Life Cycle)
STLC is a subset of SDLC that focuses only on testing activities.
Phases:
Requirement Analysis
Test Planning
Test Case Development
Test Environment Setup
Test Execution
Test Closure

🔥 Key Differences
Feature
SDLC
STLC
Scope
Full development process
Only testing process
Objective
Build software
Ensure quality
Phases
7 phases
6 phases
Focus
Development + Testing
Testing only
Start
Project start
After requirement analysis
End
Maintenance
Test closure


🧠 Conclusion
STLC runs parallel to SDLC and ensures quality at every stage of development.
What is this?

📄 2. Testing Types Classification Document
Writing
Testing Types Classification
🔷 1. Functional Testing
Verifies application features
Example: Login, Signup, Payment
🔷 2. Non-Functional Testing
Verifies performance and behavior
Types: Performance, Load, Security, Usability

🔷 3. Maintenance Testing
Done after changes or updates
Types:
Regression Testing → Check old features
Sanity Testing → Check specific changes

🔷 4. Change-Related Testing
Types:
Re-testing → Test fixed defects
Regression Testing → Ensure system stability

🔷 5. Other Important Types
Smoke Testing → Basic build check
Exploratory Testing → No predefined test cases
Ad-hoc Testing → Random testing

🧠 Conclusion
Testing types are selected based on project needs, functionality, and changes in the system.
What is this?

📄 3. 7 Principles of Testing (With Examples)
Writing
7 Principles of Software Testing (With Examples)
Testing shows presence of defects
 Example: Login works but hidden bugs may still exist
Exhaustive testing is impossible
 Example: Cannot test all input combinations
Early testing
 Example: Finding requirement errors early saves cost
Defect clustering
 Example: Most bugs found in payment module
Pesticide paradox
 Example: Same test cases → no new bugs
Testing is context dependent
 Example: Banking app needs security testing
Absence of errors fallacy
 Example: Bug-free app but not user-friendly

🧠 Conclusion
Testing improves quality but cannot guarantee a completely defect-free product.
What is this?

📄 4. Testing Glossary Document
Writing
Software Testing Glossary
🔷 Basic Terms
Bug/Defect → Error in software
Test Case → Step-by-step testing procedure
Test Scenario → High-level testing idea
Test Suite → Collection of test cases
Test Data → Input values

🔷 Important Terms
Severity → Impact of defect
Priority → Urgency to fix
RTM → Requirement Traceability Matrix
Build → Version of software
Release → Delivered product

🔷 Execution Terms
Smoke Testing → Basic functionality check
Regression Testing → Check old features
Re-testing → Test fixed bugs

🧠 Conclusion
Understanding these terms helps in clear communication during testing and interviews.
 


👉 “What is white box testing?”
Answer:
White box testing is a testing technique where we verify internal code logic, structure, and flow. It includes validating conditions, loops, and paths, and measuring coverage like statement and branch coverage.
✅ 1. What is White Box Testing?
White box testing = testing internal code logic.
Instead of just checking output (like black box), you:
Read the code
Understand logic
Write tests to cover all paths
👉 Example:
if (age >= 18) {
   return "Eligible";
} else {
   return "Not Eligible";
}
You don’t just test output—you test:
condition true
condition false
. Statement Coverage
📌 Definition:
Execute every line of code at least once
📌 Formula:
Coverage % = (Executed Statements / Total Statements) × 100

🔹 Example:
if (x > 10)
   print("A");
print("B");
Test Case:
x = 15
Execution:
print("A") ✅
print("B") ✅
👉 Statement Coverage = 100%

⚠️ Problem:
if (x > 10)
   print("A");
else
   print("C");
Test:
x = 15
➡ "else" not executed ❌
👉 Statement coverage < 100%
 Branch Coverage (VERY IMPORTANT)
📌 Definition:
Test all decision outcomes (true + false)

🔹 Example:
if (x > 10)
   print("A");
else
   print("B");
Test Cases:
x = 15 → TRUE branch
x = 5 → FALSE branch
👉 Branch Coverage = 100%

💡 Key Point:
Branch coverage is better than statement coverage
Because:
Statement may execute without testing logic properly
Branch ensures decision testing
 Path Coverage (Advanced)
📌 Definition:
Test all possible execution paths

🔹 Example:
if (x > 10) {
   if (y > 5)
       print("A");
}
Possible Paths:
x > 10, y > 5
x > 10, y <= 5
x <= 10
👉 Total paths = 3

⚠️ Problem:
With many conditions → paths explode (impractical
✅ 1. What is Code Coverage?
Code coverage = how much of the application code is tested by your test cases
👉 It answers:
Did we test all lines?
Did we test all conditions?
Did we miss anything?

✅ 2. Why Testers Should Care
Even if you don’t write code:
You identify missing test scenarios
You ask developers for coverage reports
You improve test quality
💡 In real projects:
Developers generate coverage reports, testers analyze gaps.

✅ 3. Types of Code Coverage (Must Know)

🔹 1. Statement Coverage
📌 Checks: Did every line run?
🧠 Formula:
 Coverage %=Executed StatementsTotal Statements×100\text{Coverage \%} = \frac{\text{Executed Statements}}{\text{Total Statements}} \times 100Coverage %=Total StatementsExecuted Statements​×100
👉 Example:
if (x > 10)
   print("A");
print("B");
Test:
x = 20
✔ Both lines executed → 100%

🔹 2. Branch Coverage (VERY IMPORTANT)
📌 Checks: Did you test all outcomes?
TRUE branch
FALSE branch
👉 Example:
if (x > 10)
   print("A");
else
   print("B");
✔ Test cases:
x = 20 → TRUE
x = 5 → FALSE
👉 100% branch coverage

🔹 3. Path Coverage (Advanced)
📌 Checks: All possible execution paths
👉 Example:
if (x > 10) {
   if (y > 5)
       print("A");
}
Paths:
x > 10, y > 5
x > 10, y ≤ 5
x ≤ 10
⚠️ Not always practical (too many combinations)

✅ 4. Real Example (Tester Thinking)
🔹 Code:
String login(String user, String pass) {
   if (user.isEmpty() || pass.isEmpty())
       return "Empty";

   if (user.equals("admin") && pass.equals("1234"))
       return "Success";

   return "Fail";
}

✅ 5. Tester’s Test Cases
Test Case
Input
Output
TC1
"", ""
Empty
TC2
"admin", ""
Empty
TC3
"admin", "1234"
Success
TC4
"admin", "wrong"
Fail


✅ 6. Coverage Thinking (This is what interviewers want)
Ask yourself:
Did I test empty inputs? ✅
Did I test valid login? ✅
Did I test invalid login? ✅
👉 That means:
Statement coverage → 100%
Branch coverage → 100%

❌ 7. Common Mistake (Test Gap)
If you only test:
admin / 1234
👉 Coverage becomes LOW:
Empty condition not tested ❌
Fail case not tested ❌
👉 This is called a test gap

✅ 8. How to Read Coverage Report
Example:
Statements: 80%
Branches: 50%
👉 Meaning:
Some lines never executed
Some conditions not fully tested

✅ 9. Tools You Should Know (Important)
🔹 Java
JaCoCo
🔹 JavaScript
Istanbul (nyc)
🔹 Python
Coverage.py

✅ 10. What Testers Actually Do in Projects
You usually:
Write test cases (UI/API)
Ask developer:
 👉 “Can you share coverage report?”
Analyze:
Which code not covered?
Add missing test cases

✅ 11. Interview Answers (Ready to Speak)
❓ What is code coverage?
👉
Code coverage measures how much of the code is executed during testing. It helps identify untested parts of the application.

❓ Why is branch coverage important?
👉
Because it ensures all decision outcomes (true/false) are tested, improving test quality.

❓ Can 100% coverage guarantee no bugs?
👉
No. It only ensures code execution, not correctness.
🔍 1. If Statements (Decision Making)
📌 What it does:
Controls logic based on a condition
🔹 Example:
if (x > 10) {
   print("A");
} else {
   print("B");
}
✅ Tester Thinking:
Condition: x > 10
Branches:
TRUE → A
FALSE → B
🎯 Test Cases:
x = 15 → A
x = 5 → B
👉 You must test both paths

🔁 2. For / While Loops
📌 What it does:
Repeats code multiple times

🔹 Example (for loop):
for (int i = 0; i < 3; i++) {
   print(i);
}
✅ Tester Thinking:
Test loop behavior:
Loop runs 0 times
Loop runs 1 time
Loop runs multiple times

🔹 Example (while loop):
while (x > 0) {
   x--;
}
🎯 Test Cases:
x = 0 → loop not executed
x = 1 → runs once
x = 5 → runs multiple times
👉 This is very important for coverage

🧩 3. Functions and Methods
📌 What it does:
Reusable block of code

🔹 Example:
int add(int a, int b) {
   return a + b;
}
✅ Tester Thinking:
Check:
Inputs
Outputs
Edge cases
🎯 Test Cases:
add(2, 3) → 5
add(0, 0) → 0
add(-1, 5) → 4

🔄 4. Understand Flow (Execution Flow)
📌 What it means:
How code executes step-by-step

🔹 Example:
if (x > 10) {
   print("A");
}
print("B");
🔍 Flow:
Check condition
If true → print A
Always → print B

🎯 Flow Diagram:
Start
↓
Check x > 10
↓ yes → A
↓
B
↓
End
👉 Flow helps you:
Understand execution
Design better test cases

🌿 5. Identify Branches (Very Important)
📌 What is a branch?
A decision point in code

🔹 Example:
if (x > 10) {
   print("A");
} else {
   print("B");
}
👉 Branches:
TRUE branch
FALSE branch

🔹 More Complex Example:
if (x > 10 && y > 5) {
   print("A");
}
👉 Branches:
x > 10 → T/F
y > 5 → T/F
👉 Possible combinations:
T, T
T, F
F

🎯 Tester Goal:
Cover all branches

🔥 Final Tester Mindset (Very Important)
Whenever you see code, ask:
What are the conditions?
How many branches?
Are loops tested for 0, 1, many?
What are edge cases?
Is any path untested?

If asked:
👉 “How do you read code in white box testing?”
Say:
I identify conditions, loops, and functions, then analyze execution flow and branches. I create test cases to cover all possible paths including edge cases to ensure complete code coverage.


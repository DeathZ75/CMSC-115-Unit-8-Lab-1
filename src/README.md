# Lab Reflection: Git Version Control + Debugging (BuggyProgram)

## Student Name
Stephen Epperly

## GitHub Repository URL
https://github.com/DeathZ75/cmsc115-unit8lab1

---

# Commit 1: Initial Commit

## What did you include in this commit?
- Nothing, baseline commit.

## What was the purpose of this commit?
- To create a baseline of initial code that will be altered.

---

# Commit 2: Task 1 (getGrade)

## Which tests in Task1Test were failing before your fix?
- The first four tests. (95, 90, 85, 80)

## What was the issue in the code?
- The strings for the first two ranges have swapped return strings.
- 90 and 80 are not included in their intended ranges. 

## What change did you make to fix it?
- Add an '=' operator to the if statements to include the missing numbers to the ranges.
- Swapped the return strings to match the intended ranges.

## How did the tests help guide your fix?
- Allowed me to identify what logical errors would occur and make corrections. 

---

# Commit 3: Task 2 (sumEvenNumbers)

## Which tests in Task2Test were failing before your fix?
- All tests fail due to the way the code is set up.

## What was the issue in the code?
- The sum variable starts at 1 instead of 0 causing it to skip the initial value of each array at index[0].
- Plus with sum assigned with 1 makes it return 1 for the second test when it should have 0 since all values are odd.
- The loop goes to the length of the array which exceeds the number of indexes contained in the array.
- Lastly, the last test has no values in the array causing an error since no index 1 is present.

## What change did you make to fix it?
- Assigned sum with value 0 instead of 1.
- Remove the = sign from the for loop.

## How did the tests help guide your fix?
- They demonstrated what errors were present in the codes logic and hinted to what syntax changes were needed.

---

# Commit 4: Task 3 (sumRange)

## Which tests in Task3Test were failing before your fix?
- The reverse order test fails since it can't lower the i value in the event that start has a higher value then end.

## What was the issue in the code?
- It is designed for if end has a higher value then the start value. not vice versa.

## What change did you make to fix it?
- I coded it to detect which value was higher between start and end. Based on that, the loop would increase the value of i or decrease.

## How did the tests help guide your fix?
- Showed a programmer error for not considering the user might put a higher start number.

---

# Overall Reflection

## Which task was the easiest to fix? Why?
- Task 3
- By this point I was able to tell how to use the tests provided and 
- just needed to add conditional statements for which variable was higher.
- Then I just used the already provided code and only altered the loop statement.

## Which task was the most difficult? Why?
- Task 1
- First time using Github, so struggled to understand how it worked properly and that I had to manually 
- add branches so I didn't override the initial commit and show clear difference with each task.
- Additionally, The test values that I am supposed to reference were only provided in the virtual desktop.
- I didn't know where to locate them at first and struggled to understand how they functioned at first without
- just using the automatic grader provided in zybooks.

## How did Git help you track your progress through the debugging process?
- If this was a bigger program I can see how it would make a lot of help with being able to revert to different stages.
- However, with this being simple fixes, it makes relying on github kind of extra for debugging.

## Why is it important to make small, frequent commits when debugging code?
- So that you can determine where the bug that needs fixing is located and can revert to specific points
- without having to redo large amounts of work. Or notice that you can make more efficient code as your
- programing knowledge grows.

## What did you learn about using JUnit tests to guide debugging?
- Seeing what is the intended output based on input can make focusing on specific issues easier.
- Though I think the zybooks should show what the tests are instead of just saying containers found, 
- and how many passed or failed.

---

# Commit 5: Final Reflection

## What did you complete or update before making this final commit?
- I made corrections to all 3 methods as instructed. To include small alterations to assigned values, operators,
- and conditional statements.

## Why is it useful to document your work after completing a programming task?
- To have a clear and concise understanding of what changed between each commit and the reason behind the change.
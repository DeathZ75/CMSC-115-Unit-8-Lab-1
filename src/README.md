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
-

## What was the issue in the code?
-

## What change did you make to fix it?
-

## How did the tests help guide your fix?
-

---

# Overall Reflection

## Which task was the easiest to fix? Why?
-

## Which task was the most difficult? Why?
-

## How did Git help you track your progress through the debugging process?
-

## Why is it important to make small, frequent commits when debugging code?
-

## What did you learn about using JUnit tests to guide debugging?
-

---

# Commit 5: Final Reflection

## What did you complete or update before making this final commit?
-

## Why is it useful to document your work after completing a programming task?
-
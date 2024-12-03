# MongoDB Aggregation Pipeline Bug
This repository demonstrates a common yet subtle error in MongoDB aggregation pipelines that can lead to inaccurate results. The bug involves an incorrect field reference within the \$group stage, causing unintended summation behavior.

## Bug Description
The provided JavaScript code snippet showcases an aggregation pipeline designed to calculate the sum of a field for each unique value of another field.  However, due to a minor error in field specification, the sum calculation is flawed.

## Solution
The solution corrects the field reference in the \$group stage, ensuring that the sum is calculated correctly.  The corrected code snippet is also included.

## How to Reproduce
1. Clone this repository.
2. Ensure you have a MongoDB instance running.
3. Execute the `bug.js` script to see the incorrect summation. 
4. Execute the `bugSolution.js` script to see the correct summation. 

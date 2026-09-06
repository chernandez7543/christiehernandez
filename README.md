# christiehernandez
Assignment 01: 2Sum and Complexity

# 2Sum - C++
# About this Project
This Project is for my C++ 2Sum problem. For the initial required test, we were provided an array of integers nums and an integer target. The goal was to determine if two numbers in the array add up to the target value. Return indices, and values of two  numbers that add up to the target. Check if its valid. We were asked to provide two different approaches to compare their efficiency: Brute-force and Hash method.

What I learned from doing this assignment is how the same problem can be solved using two different approaches. For example, in test case 4 the target was 8 and there were two 3s and one 5 listed in the array. The indices results showed different positions for value number 3 due to that duplicate 3. The Brute-force method starts with the first 3 (index 0) and checks it with each value that comes after it. Once it finds the 3 + 5, it stops looking and results the indices and values. Brute-force tries each possible combination pair until one works. While the hash method resulted the second value 3 (index 1) in its return. The hash method goes through the array while also keeping track of the values and their indices.  It first stores the value 3 with index 0. When it reaches the second 3 at index 1, the stored index for 3 is then updated from 0 to 1. When it reaches 5, it determines that it needs a 3 to reach the target of 8. The hash table shows that the most recent stored number 3 is at index 1, which then returns indices 1 and 4. The hash method recalls what it has seen and looks for the number it needs.


Resources:
Youtbube- https://youtu.be/wEpviAgbDtk?si=tdQDpWak0N7nIcK8 for guidance on how brute force and hash methods work.
Youtube- https://www.youtube.com/watch?v=yFZSxPK2E7Y&t=73s for explanation of why optimized method improves on the brute-force method
Leet code website- Two Sum Description and solution examples
ChatGpt: Troubleshoot parts of my code, logic behind 2Sum assignment, differences between the two methods used, time and space complexity of each methods, and interpretation of the test case results

echo "# christiehernandez" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/chernandez7543/christiehernandez.git
git push -u origin main



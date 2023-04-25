# ES6-Exercises

Create a JavaScript program that takes an array of objects containing student data as input and returns a new array of objects containing only the name and average score of each student. Use ES6+ features such as arrow functions, destructuring, and template literals, and include exception handling to handle cases where the input is invalid.


# Instructions
1. Define an arrow function that takes an array of student objects as input.
2. Use exception handling to check that the input is valid (i.e. an array of objects where each object has a “name” property and a “scores” property that is an array).
3. If the input is invalid, throw a custom error message using the “throw” keyword.
4. Use the “map” method to transform each student object into a new object containing only the name and average score properties.
5. Inside the map function, use destructuring to extract the name and scores properties from each student object.
6. Use exception handling to check that the scores array is not empty.
7. If the scores array is empty, throw a custom error message using the “throw” keyword.
8. Use the “reduce” method to calculate the average score for each student’s scores array.
9. Return a new object containing the name and average score using template literals.
10. Return the final array of transformed objects.
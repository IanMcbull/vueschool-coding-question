# Exercise

Create a function that generates a tree of matryoshka dolls.

## Instructions

1. Open a new text editor or your preferred Integrated Development Environment (IDE) that supports JavaScript.

2. Create a new JavaScript file and save it with a name of your choice.

3. Define a function with the name **parentMatroshyka** that will return another function.

4. Inside the **parentMatroshyka** function, create a variable called `parent` and set its value to 🪆. Log the value of `parent` in the console.

5. Inside **parentMatroshyka**, define another function called **childMatroshyka** and return it as a return value to the **parentMatroshyka** function.

6. Inside the **childMatroshyka** function, define a variable called **child**  and set its value to `parent + 🪆`.
Log the value of `child` in the console.

7. Inside **childMatroshyka**, define another function called **grandChildMatroshyka** and return it as a return value to the **childMatroshyka** function.

8. Inside the **grandChildMatroshyka** function, define a variable called **grandChild**  and set its value to `child + 🪆`.
Log the value of `grandChild` in the console.

9. Save your code and test your function by calling it and invoking the inner functions.

Expected Output
```js
parentMatroyshka()()()
// output 
🪆
🪆🪆
🪆🪆🪆
```

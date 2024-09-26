# JavaScript Output-Based Interview Questions Repository

Welcome to the **JavaScript Output-Based Questions Repository**! 🎯

The goal of this repository is to provide a collection of advanced JavaScript questions that focus on predicting the output of various code snippets. This will help you sharpen your problem-solving skills and prepare for technical interviews.

## Purpose of this Repository

- 🚀 **Hands-on Practice**: Engage with real-world JavaScript challenges to enhance your coding skills.
- 🧠 **Deepen Understanding**: Tackle questions covering advanced concepts such as closures, asynchronous programming, hoisting, scope, event loops, and more.
- 💡 **Interview Prep**: Build confidence for technical interviews by practicing tricky output-based questions often asked by companies.

## Topics Covered

This repository covers a wide range of JavaScript topics, including but not limited to:

- **Arrays**: Working with array methods like `map()`, `filter()`, `reduce()`, and understanding the impact of mutations.
- **Strings**: Manipulating and comparing strings, using methods like `split()`, `replace()`, `includes()`, and template literals.
- **Closures**: Understanding how functions retain access to variables from their outer scopes and their role in JavaScript patterns.
- **Promises**: Handling asynchronous code, understanding `Promise` chaining, `Promise.all()`, `Promise.race()`, and async/await syntax.
- **Asynchronous JavaScript**: The event loop, microtasks, macrotasks, and how JavaScript handles asynchronous operations.
- **Hoisting**: How JavaScript hoists variable and function declarations and how it affects code execution.
- **Scope**: Lexical scope, block scope, and function scope, along with practical examples.
- **Prototypes & Inheritance**: JavaScript’s prototype chain, `Object.create()`, `class` syntax, inheritance models.
- **Event Loop**: Deep dive into how JavaScript handles asynchronous behavior, callbacks, and event queue.
- **Function Expressions & Declarations**: Understanding the difference between function expressions and function declarations, IIFEs, and arrow functions.
- **Type Coercion & Comparisons**: Understanding how JavaScript coerces types and handles equality comparisons (`==` vs `===`).
- **Error Handling**: Working with `try...catch` blocks, custom error classes, and error propagation.
- **Destructuring & Spread/Rest Operators**: Using destructuring for arrays and objects, and the powerful applications of spread/rest operators.
- **This Keyword**: Understanding the context of `this`, how it behaves differently in different scenarios like methods, constructors, and arrow functions.

## How to Use

1. **Clone or download the repository**:
    ```bash
    git clone https://github.com/your-username/js-output-questions.git
    ```
   
2. **Explore the questions**: Each folder contains questions grouped by topics. Try predicting the output of each code snippet before looking at the explanation.

3. **Learn from explanations**: Each question comes with detailed explanations so you can understand why the code behaves the way it does.

4. **Contribute**: Have a cool JavaScript question to share? Feel free to contribute by opening a pull request!

## Sample Question

Here’s a sample question you’ll find in this repository:

```javascript
let a = 10;
(function() {
   console.log(a); // ???
   let a = 20;
})();

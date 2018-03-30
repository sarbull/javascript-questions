# javascript
## questions
1. What is Javascript?
2. What is Javascript Hoisting?
3. What is Javascript Closure? Give an example and explain what you can achieve by writing closures.
4. Is Javascript multi-thread? Please explain.
5. What are Web Workers? Give an example on how they can be used.
6. What is a Websocket? Give an example for a problem that it can solve.
7. Is Javascript a typed language?
8. What is the Javascript Prototype mechanism? Give an example on how it can be used.
9. What is the difference between '==' and '===' in javascript?
10. Implement an `add` function using closure(e.g. `add(1)(2)`).
11. What is an arrow function, what is the most specific thing to say about it?
12. What default data types does the plain Javascript have?
13. Name two programming paradigms important for JavaScript?
14. What is a pure function?
15. What are the pros and cons of functional programming vs object-oriented programming?
16. What does “favor object composition over class inheritance” mean?
17. What are the pros and cons of monolithic vs microservice architectures?
18. What is asynchronous programming, and why is it important in JavaScript?
19. What is a Promise in Javascript?
20. What is a lambda function in Javascript?

## exercises
1. What is being console.logged in the console?
```js
b();
a();

function b() {
  console.log('b();');
}

var a = function() {
  console.log('a();');
}
```
2. What is being console.logged in the console?
```js
setTimeout(function() {
  console.log('setTimeout(500);');
}, 500);

console.log('console.log("after 500");');

setTimeout(function() {
  console.log('setTimeout(0);');
}, 0);

console.log('console.log("after 0");');

setTimeout(function() {
  console.log('setTimeout(2000);');
}, 2000);

console.log('console.log("after 2000");');
```

# typescript
## questions
1. What is Typescript?
2. Is Typescript a typed language?
3. What is an Interface in TypeScript?
4. Can a Typescript class implement multiple interfaces?
5. Does Typescript have annotaions?

## excercises
1. Create a `Person` class with getters and setters for the following parameters: `name`, `age`, `email`.

# html
## questions
1. What is HTML5?
2. What new tag elements were added in HTML5?
3. How can you tell what HTML versions is beind used in a webpage?
4. What do you understand by normalized HTML?
5. What is the difference between a `<div>Lorem ipsum dolor.</div>`, a `<p>Lorem ipsum dolor.</p>` and a `<span>Lorem ipsum dolor.</span>`.

## exercises
1. Write a paragraph tag with 'Lorem ipsum dolor.'.
2. Is the following HTML valid?
```html
<h1>
  <div>Hello world</div>
</h1>
```
3. What is the default structure of a HTML page?

# css
## questions
1. What is CSS?
2. What are the known selectors usually used by CSS?
3. What is SASS/LESS? What would be the purpose of using SASS/LESS?

## exercises
1. Select all `div` elements having the `.default` class and make the background colored with `#cccccc`;

# HTTP
# questions
1. What is HTTP?
2. Define `Request` and `Response` and what data they contain.
3. What are the differences between GET and POST requests?
4. What is the REST convention?
5. Can you upload files via a GET request?




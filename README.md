# javascript
## questions
1. What is JavaScript?
2. What is JavaScript Hoisting?
3. What is JavaScript Closure? Give an example and explain what you can achieve by writing closures.
4. Is JavaScript multi-thread? Please explain.
5. What are Web Workers? Give an example on how they can be used.
6. What is a Websocket? Give an example for a problem that it can solve.
7. Is JavaScript a typed language?
8. What is the JavaScript Prototype mechanism? Give an example on how it can be used.
9. What is the difference between '==' and '===' in JavaScript?
10. What is an arrow function, what is the most specific thing to say about it?
11. What default data types does the plain JavaScript have?
12. Name two programming paradigms important for JavaScript?
13. What is a pure function?
14. What are the pros and cons of functional programming vs object-oriented programming?
15. What does “favor object composition over class inheritance” mean?
16. What are the pros and cons of monolithic vs microservice architectures?
17. What is asynchronous programming, and why is it important in JavaScript?
18. What is a Promise in JavaScript?
19. What is a lambda function in JavaScript?
20. How can you create modules in JavaScript?

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
3. Implement an `add` function using closure(e.g. `add(1)(2)`).
4. Select a `div` element with an `id="myDiv"` using plain JavaScript.
5. What is being console.logged in the console?
```js
function isTrue (data) {
  if (data == { value: true }) {
    console.log('true');
  } else {
    console.log('false');
  }
}
isTrue({ data: true })
```
6. What is being console.logged in the console?
```js
for (var i = 0; i < 4; i++) {
  setTimeout(() => console.log(i), 0);
}
```
7. What is being console.logged in the console?
```js
let moduleA = {
  moduleName: 'Module A',
  init() {
    console.log('init ' + this.moduleName);
  }
}

let initModuleA = moduleA.init;

moduleA.init();
initModuleA();
```

# typescript
## questions
1. What is Typescript?
2. Is TypeScript a typed language?
3. What is an Interface in TypeScript?
4. Can a TypeScript class implement multiple interfaces?
5. Does TypeScript have annotaions?

## excercises
1. Create a `Person` class with getters and setters for the following parameters: `name`, `age`, `email`.

# html
## questions
1. What is HTML5?
2. What new tag elements were added in HTML5?
3. How can you tell what HTML version is beind used in a webpage?
4. What do you understand by normalized HTML?
5. What is the difference between a `<div>Lorem ipsum dolor.</div>`, a `<p>Lorem ipsum dolor.</p>` and a `<span>Lorem ipsum dolor.</span>`.
6. What do you know about the DOM structure?
7. What is the difference between the initial HTML code and the DOM.

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
4. How can you add CSS in a HTML page?
5. What is the difference between `padding` and `margin`?
6. Explain the `overflow` property in a CSS selector and how it can be used.

## exercises
1. Select all `div` elements having the `.default` class and make the background colored with `#cccccc`;
2. Change the font in a HTML page.

# HTTP
# questions
1. What is HTTP?
2. Define `Request` and `Response` and what data they contain.
3. What are the differences between GET and POST requests?
4. What is the REST convention?
5. Can you upload files via a GET request?

# Let & Const

Let is block level scope local variable and Const is same as let but read-only single assignment variable.


## Let

<a href="http://goo.gl/UaqMoj" target="_blank">Demo</a>

````
var obj = {
	name: 'Gokul',
	age: 21,
	car: 'Swift'
};

//let is block level variable here

for (let i in obj) {
	console.log(i); //print name age car
}

console.log(i); //i is not defined

````

````

if (true) {
	let foo = 10;

	let foo = 11; //Duplicate declaration "foo"
}

console.log(foo); //foo is not defined

````


## Const

<a href="http://goo.gl/DdQ10l" target="_blank">Demo</a>

````
const bar = 'Hello';

console.log(bar); //print Hello

bar = 'World'; //"bar" is read-only

````

**[⬆ back to top](#table-of-contents)**


## Reference

- <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/let" target="_blank">let</a>
- <a href="http://babeljs.io/docs/learn-es2015/#let-const" target="_blank">let const</a>
## Interview

[Master the js interview](https://medium.com/javascript-scene/master-the-javascript-interview-what-s-the-difference-between-class-prototypal-inheritance-e4cd0a7562e9)

[toptal questions](https://www.toptal.com/javascript/interview-questions)

### Interviewer
+ How many steps? how long does it generally take?
+ How big is your engineering team?
+ Which team would I be Interviwing for?
+ What is the culture like?
+ Who are your competitors?
+ What sort of projects would I work on?
### code questions
+ Difference between const, let, and var ==> var global to the declaring scope, let brackets scope, and const you cant point a const to a different pointer.
+ prototypical inheritance
	+ **class taxonomies are not an automatic side-effect of prototypal OO**: _a critical distinction._
	+ three different kinds of prototypal OO
		+ Concatenative. copying source objects props (mixins) Object.assign()
		+ Prototype. prototype delegation. new | Object.create()
		+ Functional. factory function
	+ this. Is the current scope you are in which can be changed (apply||call) or fixed (bind) and if there is no scope on web context it defaults to the window object.
	+ structure of DOM. Tree
	+ what is a stack. LIFO data structure. an array push & pop
	+ 	what is a queue. LIFO data structure. an array push & shift
	+ How can you tell if an image has been loaded. listening to onload events.
	+ event delegation. handle events at the top element event bubling
	+ worker. a background process (different thread)
	+ Clousure
	+ Pure function
	+ Funxction composition
	+ Functional programming
	+ Promise

### Code test
+ make your code as readeble as posible
	+ Comment code
	+ Make it simple
+ Don`t import too many libraries
+ Add unit tests
+ Ask questions
+ Make the problem as straightforward as possible
+ Be honest with the time
+ Have a code review checklist

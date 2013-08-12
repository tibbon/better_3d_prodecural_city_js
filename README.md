Better 3d Prodecural City in JavaScript
============================

[MrDoob](http://www.mrdoob.com/) released a [3d City Generator](http://www.mrdoob.com/lab/javascript/webgl/city/01/) in Javascript [on Twitter](https://twitter.com/mrdoob/status/350730133319073792). 

Jerome Etienne did a [nice blog post](http://learningthreejs.com/blog/2013/08/02/how-to-do-a-procedural-city-in-100lines/) describing what it does, and how it works. 

But, when I looked at the code I realized that a few things could be refactored and made better. I couldn't find the city in a Github repo, so I cut/pasted the code over here. I do hope that no one minds me refactoring it.

A few things I wanted to change: 

- More efficient `for` loops
- Single `var` pattern inside functions
- More functions
- Jasmine tests
- Positioning all local variables in functions at the top of the functions to help with hoisting bugs
- Storing everything inside of a protected namespace
- Use of closures when needed to create private variables
- Better commenting
- Use of `use strict` to enforce more stringent programming patterns in JavaScript

None of this is a nitpick of the code. Rather its just me getting better at refactoring other people's JavaScript and thinking more about different patterns and how things can be made better. 

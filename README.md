# -Javascript30
Daily challenge exercise
Goal spend some time practicing vanilla js.

Day 1:
Javascript Drum Kit

Learned about: Key events, playing audio, listening to transition and end events.

Day 2:
Playing with CSS Variables and JS

CSS variables work on a certain element set to. Variables are defined and set to such as: blur, color, filter, padding and background. JS used for event listing to update CSS trigger changes.

Day 3: 
Update CSS Variables with JS

When using a CSS variable you can update the variable in any element and any selectors that are inside of the
element that ref the variable will be using it.  Scoping the div itself can make changes to the lower scope. 
Using data attribute "data-____" to create an object. Select the entire document (root) and set a property of the 
objects of names used (variables) document.documentElement.style.setProperty('--${this.name}', this.value + suffix);

CSS:
```
<style>
:root {
--base: #ffc600; //yellow
--spacing: 10px;
--blur: 10px;
}

</style>

const inputs = document.querySelectorAll('.controls input'); //nodelist
function handleUpdate() {
const suffix = this.dataset.sizing || '';  //sizing variable being changed or nothing.
}
	inputs.forEach(input => input.addEventListener ('change', handleUpdate));
	inputs.forEach(input => input.addEventListener ('mousemove', handleUpdate));
```
	
Day 4: Javascript Array Cardio Practice

Fundamental of JS with array methods:

```
Array.protortpe.filter //filter return results after bringing things in and base on criteria displays (can be more or less)
Array.prototype.map //retuns a new array of the same length and also the same amount of items given
Array.prototype.sort // sort between two items (a,b)
Array.prototype.reduce // allow to build and return from previous entry
```
Day 5: Flexbox + JavaScript Image Gallery

Flexbox is a CSS layout model method. Default items will be from left to right.
Flexbox nested to create layout page.

```
CSS:
.panel {
display: flex; // goes side-by-side
flex: 1; // length of space, each will evenly distribute by 1
flex-direction: column; // vert center middle
flex: 5; // 5x the amount of room compared to the reg size
}
```
Day 6: Ajax Type Ahead with fetch()


Day 7: .some(), .every(), .find() and [...SPREADS] — Array Cardio Day 2 

Day 8: Let's build something fun with HTML5 Canvas
Exercise learning about canvas, learning about events, flag with true or false to test.
Using event info to draw and remain idle when user has not clicked and trigger event.

Day 9: Must Know Chrome Dev Tools Tricks

Using chrome browser and inspect tool: Break on...> attribute modification
Will enable debugger mode and pause and show line of code causing.
```
console.log(``)
console.log(1%c I am some great text`, `font-size:50px;`) allows styling
console.warn(`oh no`); warning shown in console
console.error(`stop`); error shown in console
console.info(`facts: I am happy`);
console.assert(1 === 1, `that is wrong!`); will only fire if wrong, test if false will throw error in console if correct nothing happens.
console.clear(); clear console
console.log(p); viewing DOM elements
console.dir(p); shows the directory on the element
console.Collapsed`${}`);
console.groupEnd`${}`);
console.count(``); will count how many counted
console.time(``) will enable logging of time is taking 
console.timeEnd(``);
console.log(data); 
console.table(); take a array of objects and display it into a table
```

Day 10: JS Checkbox Challenge!
Day 11: Custom HTML5 Video Player
Day 12: JavaScript KONAMI CODE! 
 




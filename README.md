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
`<style>
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
	inputs.forEach(input => input.addEventListener ('mousemove', handleUpdate));`



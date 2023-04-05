// get the btn element by ID
const btn = document.getElementById('btn');

// add click event listener to the btn element
btn.addEventListener('click', function () {



// generate random color value
const randomColor = Math.floor(Math.random() \* 16777215).toString(16);

// get the body element
const body = document.body;

// change the background color of the body
body.style.backgroundColor = '#' + randomColor;
});

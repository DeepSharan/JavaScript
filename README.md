# JavaScript
Beginning


<p id = "demo">
JavaScript can change HTML content.
</p>
<button onclick = 'document.getElementById("demo").innerHTML = "Ta-da ! It's JavaScript" '> Click me </button>
<!-- this will find the element with id ="demo" nd change it with the "innerHTML". -->

<!-- JS can also CHANGE ATTRIBUTE VALUES -->
<button onclick = "document.getElementById('Image').src = 'bulbon.gif' "> Turn On Light </button>
<img id = "Image" src = "bulboff.gif" style = "width:100px"> 
<button onclick = "document.getElementById('Image').src = 'bulboff.gif' "> Turn off Light </button>

<!-- JS can also CHANGE STYLE OF HTML ELEMENT -->
<p id="demo">JavaScript can change the style of an HTML element.</p>
<button type="button" onclick="document.getElementById('demo').style.fontSize='35px'"> Click Me! </button>

<!-- JS can also HIDE HTML ELEMENTS -->
<p id="demo">JavaScript can hide HTML elements.</p>
<button type="button" onclick="document.getElementById('demo').style.display='none'">Click Me!</button>


<!-- JS can SHOW HIDDEN HTML ELEMENTS -->
<p id="demo" style="display:none">Hello JavaScript!</p>
<button type="button" onclick="document.getElementById('demo').style.display='block'">Click Me!</button>



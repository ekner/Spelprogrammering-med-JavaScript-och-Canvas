Spelprogrammering med JavaScript och Canvas - Game development with JavaScript and Canvas
=========================================================================================

Added function "textSize"; to calculate the width and height of text created with the "text" function. This can be useful when you for example want to position the text in the middle of the screen, or make a border around it. Usage: textSize(size, text). This will return an object with the properties "width" and "height". Example:

    text(50, 50, 20, "Programming", "black");
    var width = textSize(20, "Programming").width;
    alert("The width of the text is: " + width);

Spelprogrammering med JavaScript och Canvas - Game development with JavaScript and Canvas
=========================================================================================

Added function "textWidth"; to calculate the width of text created with the "text" function. This can be useful when you for example want to position the text in the middle of the screen, or make a border around it. Usage: textWidth(size, text). This will simply return a number; the width.

    text(50, 50, 20, "Programming", "black");
    var width = textSize(20, "Programming");
    alert("The width of the text is: " + width);

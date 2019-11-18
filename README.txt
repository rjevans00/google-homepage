From The Odin Project's [curriculum](http://www.theodinproject.com/courses/web-development-101/lessons/html-css)

Assignment
Easy Version: Build the Google.com homepage
(the simple one with just a search box).

Tips:
DON’T BE A PERFECTIONIST! You’re just trying to make it look like google.com, not actually function like it and it doesn’t have to be spaced exactly the same way to the pixel. Any dropdown menus or form submissions or hover-highlighting should be ignored.

USE GOOGLE! You’ll probably run into roadblocks where you can’t figure out how to do something so do what all good devs do… Google it!
If you’re frustrated with trying to get buttons or inputs to style the way you want (for instance, they seem to just not respond to any styles), look into the css property -webkit-appearance: none; or -moz-appearance if you’re using Firefox.
Start with just putting the main elements on the page (the logo image and search form), then get them placed horizontally. You can either download the Google logo or link directly to its URL on the web in your <img> tag.

Next do the navbar across the top, first building the content and then trying to position it. Check out how to build a horizontal CSS navbar if you’re lost.

Finally, put in the footer, which should be very similar to the top navbar.
In general, do as much on your own as you can before relying on the developer tools (or viewing the page’s source code) to help you along.
Push your project to Github using the instructions above!


###################################

Notes:

Google search bar

<div align="center"><form method="get"action="https://www.google.com/search"></div>
<input type="text" name="q" size="31" value="">

input name must be "q" and not "g" for search results to show.

Icons need seperate Div for align="center" to work.

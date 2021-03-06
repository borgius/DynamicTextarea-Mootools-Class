DynamicTextarea
===========
Purpose: Provides a lightweight plugin for the textarea tag that dynamically resizes based on its content that has no UI glitches or quirks.

MooTools 1.3 only!

[Demo](http://jsfiddle.net/amadeus/Shd8G/ "Demo")

![Screenshot 1](http://dl.dropbox.com/u/18782/dynamicTextarea.jpg)


How to use
----------
DynamicTextarea is a reusable class that can by applied to any textarea tag on a page (with any sort of CSS styling attached to it) that allows it to dynamically resize based on the content it contains.

Constructor:

	new DynamicTextarea(el,options);
	//el: A dom node or id string.
	//options: an object containing key:value pairs for configuring the class. Check the source for more details on available options
	
In Context:

	new DynamicTextarea('myInput',{
		minRows:2
	});

This will ensure the textarea is always at least 2 rows tall.


Notes
----------
Opera fails with certain CSS styles, so please test Opera and disable if necessary.
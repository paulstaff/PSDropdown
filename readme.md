PSDropdown - v0.9.1
==========

PSDropdown provides an alternative to standard HTML select elements. It converts all select elements with the class `PSDropdown` to custom `PSDropdown` elements that consist of a readonly text element and a list of options. To use this javascript plugin, simply include the `PSDropdown.js` and `PSDropdown.css` files and add the `PSDropdown` class to all select elements.


Installation
------------


### Prerequisites

- jQuery 2.0+ is required to run all PSToolkit plugins

### Instructions

1. Download [PSDropdown.zip](http://paulstaff.com/random/PSToolkit/PSDropdown/PSDropdown.zip).
2. Unzip the contents and include the `PSDropdown.js` and `PSDropdown.css` files in the plugins folder for your project.
3. Include the following two lines in the `<head>` section of your HTML file (be sure to change file path):

	```HTML
	<script src="path/to/plugins/folder/PSDropdown.js"></script>
	<link rel="stylesheet" href="path/to/plugins/folder/PSDropdown.css">
	```

4. Add the class `dropdown` to all select elements that you would like to convert: 

	```HTML
	<select class="dropdown">
		<option value="1">This is an Option</option>
        <option value="2">Another Option</option>
        <option value="3">Option the Third</option>
    </select>           
	```

5. Optionally, you can call `PSDropdown.convert()` at any point to re-render all select inputs on the page as dropdown inputs (use this after inserting a new select element in the DOM).  This does not affect select inputs already rendered as dropdowns.


Developed By
------------

[Paul Staff](http://paulstaff.com)
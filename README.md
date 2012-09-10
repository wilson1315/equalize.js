# equalize.js
The jQuery plugin for equalizing the height or width of elements

## How to Use
Call the plugin on the parent of the elements to equalize their height.
<pre>$('#height-example').equalize();</pre>

Equalize will accept any of the [jQuery Dimension](http://api.jquery.com/category/dimensions/) methods: height, outerHeight, innerHeight, width, outerWidth, innerWidth.

# See it in action
[Demo page](http://tsvensen.github.com/equalize.js)

# Examples
<pre>$('.parent').equalize('height'); // default, same as above
$('.parent').equalize('outerHeight');
$('.parent').equalize('innerHeight');
$('.parent').equalize('width');
$('.parent').equalize('outerWidth');
$('.parent').equalize('innerWidth');</pre>

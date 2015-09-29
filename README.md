# carousel
The carousel tool of javascript

It depends on jQeury.

Usage:
	
	Link the file 'carousel.js' and 'carousel.css'

	Create the element in dom like this:
		<div class="example1" id="carousel">
			<div class="slide-button left">
			<ul class="carousel-list">
				<li class="pic-item"><img></img></li>
				........(The pictures you want to show)
			</ul>
		</div>

	And in javascript, create an instance of Object Carousel:
	var carousel = new(height, width, id, speed);
	parameters:
		height : The height of the pictrues
		width  : The width of the pictures
		id     : The id of the dom element you create, in the example the id is 'example1' 
		speed  : The value can be 'fast', 'slow' or the number(the time of the animation)
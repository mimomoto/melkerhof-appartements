---
layout: en
---

<!-- Slideshow -->

<script language='javascript'>
	$(document).ready(
		function (){
			$("#impressionen").PikaChoose({
				IESafe:true,
				showCaption:false,
				animationSpeed:0,
				startOn: 5,
				autoPlay:false,
				thumbOpacity:1,
				thumbChangeEvent:'mouseover.pikachoose',
				autoPlay:false
			});
		});

	function preload(arrayOfImages) {
	    $(arrayOfImages).each(function(){
	        $('<img />')[0].src = this;
	        // Alternatively you could use:
	        // (new Image()).src = this;
	    });
	}

	// Usage:

	preload([
	    'images/photos/impressionen/1.jpg',
	    'images/photos/impressionen/2.jpg',
	    'images/photos/impressionen/3.jpg',
	    'images/photos/impressionen/4.jpg',
	    'images/photos/impressionen/5.jpg',
	    'images/photos/impressionen/6.jpg',
	    'images/photos/impressionen/7.jpg',
	    'images/photos/impressionen/8.jpg',
	    'images/photos/impressionen/9.jpg',
	    'images/photos/impressionen/10.jpg'
	]);
</script>

<figure id="c_impressionen">
<ul id="impressionen">
	<li><img src="images/photos/impressionen/1.jpg" alt="Melkerhof Apartments in Vienna 1 - Stay in the best location." /></li>
	<li><img src="images/photos/impressionen/2.jpg" alt="Melkerhof Apartments in Vienna 1 - Stay in the best location." /></li>
	<li><img src="images/photos/impressionen/3.jpg" alt="Melkerhof Apartments in Vienna 1 - Stay in the best location." /></li>
	<li><img src="images/photos/impressionen/4.jpg" alt="Melkerhof Apartments in Vienna 1 - Stay in the best location." /></li>
	<li><img src="images/photos/impressionen/5.jpg" alt="Melkerhof Apartments in Vienna 1 - Stay in the best location." /></li>
	<li><img src="images/photos/impressionen/6.jpg" alt="Melkerhof Apartments in Vienna 1 - Stay in the best location." /></li>
	<li><img src="images/photos/impressionen/7.jpg" alt="Melkerhof Apartments in Vienna 1 - Stay in the best location." /></li>
	<li><img src="images/photos/impressionen/8.jpg" alt="Melkerhof Apartments in Vienna 1 - Stay in the best location." /></li>
	<li><img src="images/photos/impressionen/9.jpg" alt="Melkerhof Apartments in Vienna 1 - Stay in the best location." /></li>
	<li><img src="images/photos/impressionen/10.jpg" alt="Melkerhof Apartments in Vienna 1 - Stay in the best location." /></li>
</ul>
</figure>

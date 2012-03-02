	Usage:
	
	<div id="slider">
			<div><img src="image1.jpg" /></div>
			<div><img src="image2.jpg" /></div>
			<div><img src="image3.jpg" /></div>
	</div><!-- /slider -->
	
	$(document).ready(function() {
				$('#slider').fwslider({
					auto:			true,  //auto start
					speed: 		800,   //transition speed
					pause:		2000,  //pause duration
					panels: 	3,		 //number of image panels
					width:  	960,
					height:  	490,
					nav: 			true 	 //show navigation
			});
		});
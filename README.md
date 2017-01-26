# Simple Parallax
Simple Parallax Scrolling Demo
https://razaniroula.github.io/simple-parallax/

# jQuery
	jQuery(document).ready(function(){
		jQuery(window).bind('scroll',function(e){
			simpleScroll();
		});   	
		function simpleScroll(){
			var scrolledY = jQuery(window).scrollTop();
			jQuery('.parallax-section').css('background-position','center -'+((scrolledY*0.2))+'px');
			//*(scrolledY*0.2) Background Position*//
		}   	
	});

Comet
=====

Facebox
-------

Grab a copy of defunkt's [facebox](http://github.com/defunkt/facebox) and make sure you include it in your app.

Script
------

Make sure you have this in your `<head>`:

	<link rel="stylesheet" href="facebox/facebox.css" type="text/css" />
	<script src="facebox/facebox.js"></script>
	<script src="jQueryProfiler.js"></script>
	
	<!-- This part's optional -->
	<script type="text/javascript">
		<!--
			$(document).keypress(function(e){
					if (!e)
						e = window.event;
					var code = e.keyCode || e.charCode || e.which || 0;
					var character = String.fromCharCode(code);
					if(character == 'p') {
						jQuery.displayProfile();
					}
			});	
	// -->
	</script>
	
This just assigns the profiler overlay to a hotkey, in this case `p` is assigned to open the profiler. If you don't want to include it, then you can always open up Firebug and call `jQuery.displayProfile();` via the console.

Copyright
---------

Facebox is &copy;[defunkt](http://www.github.com/defunkt) &amp; jQueryProfiler is &copy;[jeresig](http://www.github.com/jeresig)
Comet brought to you in part by [me](http://www.github.com/marksands)
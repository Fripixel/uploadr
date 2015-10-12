#UPLOADER

##simplifying the upload proccess

This plugins will accelerate your upload process.

it's simple to use, and its very useful.

Just add the styles 

```html
	<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/materialize/0.97.1/css/materialize.min.css" />	
	<link rel="stylesheet" href="//maxcdn.bootstrapcdn.com/font-awesome/4.3.0/css/font-awesome.min.css">	
	<link rel="stylesheet" href="dist/css/uploadr.css" /> 	
```

...and the necessary libraries...

```html
	<script src="//cdnjs.cloudflare.com/ajax/libs/jquery/2.1.3/jquery.min.js"></script>		
	<script src="https://cdnjs.cloudflare.com/ajax/libs/materialize/0.97.1/js/materialize.min.js"></script>
	<script src="dist/js/uploadr.min.js"></script>			
```

...create the basic HTML structure...

```html
	<!-- uploadr -->
	<div class="input-field col s12 margin-reset margin-bottom-default">
		<!-- basic structure -->
		<div class="uploadr">
			<a href="javascript:;" id="addfile" class="btn btn-block blue lighten-1"><i class="fa fa-picture-o"></i> images</a>	
			<ul id="preview"></ul>
		</div>
		<!--// basic structure -->
		<hr />
	</div>
	<!--// uploadr -->
```

...and initialize the plugin like this:

```javascript
$(function(){
	$(".uploadr").uploadr({
          'buttonID': '#addfile', //id of the uploadr
          'inputName': 'images[]', //field name 
          'accept': "image/x-png, image/gif, image/jpeg", //filter extensions
          'multiple': null //multiple files
	});
});
```

Done! Enjoy it!

Developed by: http://www.fripixel.com.br
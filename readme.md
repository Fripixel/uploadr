#UPLOADER

##simplifying the upload proccess

This plugins will accelerate your upload process.

it's simple to use, and its very useful.

just initialize the plugin like the example:

```
$(function(){
	$(".uploadr").uploadr({
          'buttonID': '#addfile', //id of the uploadr
          'inputName': 'images[]', //field name 
          'accept': "image/x-png, image/gif, image/jpeg", //filter extensions
          'multiple': null //multiple files
	});
});
```


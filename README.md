# string-slug.js
Converts a string to a "URL-safe" slug.
Allows for some customization with two optional parameters:
@param {string} Delimiter used. If not specified, defaults to a dash "-"
@param {array} Adds to the list of non-alphanumeric characters which
will be converted to the delimiter. The default list includes:
['–', '—', '―', '~', '\\', '/', '|', '+', '\'', '‘', '’', ' ']
Source code get from https://gist.github.com/demoive/4249710

## Using as nodejs module
npm install git@github.com:vdmitriy/string-slug.git

## Using with amd loaders (requirejs)
<script type="text/javascript">
	require(["string-slug"],function(stringSlug){
		var slug = stringSlug("some text");
	});
</script>

## Using in browser
<script type="text/javascript" src="string-slug.js"></script>
<script type="text/javascript">
	var slug = stringSlug("some text");
</script>

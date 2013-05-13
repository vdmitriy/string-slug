Converts a string to a "URL-safe" slug.
Allows for some customization with two optional parameters:
@param {string} Delimiter used. If not specified, defaults to a dash "-"
@param {array} Adds to the list of non-alphanumeric characters which
will be converted to the delimiter. The default list includes:
['–', '—', '―', '~', '\\', '/', '|', '+', '\'', '‘', '’', ' ']
Source code get from https://gist.github.com/demoive/4249710

#futurama-quotes

This is a polymer element that gives you a random polymer element.

##basic usage
To use the element, include these two items in your `<head>` tags, this works like
any other polymer element.

```
<script src="bower_components/platform/platform.js"></script>
<link rel="import" href="elements/futurama-quotes.html">
```

The quote element has a width set of 100%, this way it will fit to the width of
whatever container you put the `<futurama-quote>` element in.


###Setting it up
1. use bower to download and update polymer, and polymer's platform.js
2. include the files listed above in your `<head>`
3. put `<futurama-quotes></futurama-quotes>` in your HTML.
4. look at your futurama quotes on your site!

Note that viewing these on your local machine will require a server running as
for security reasons, polymer element will not be loaded on `file://` paths. I
recommend `python -m SimpleHTTPServer` for the easiest way to test.

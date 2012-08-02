== Development ==
minified version created with:
* npm install uglify-js
* uglifyjs -o jquery.oembed.min.js jquery.oembed.js

== jquery-oembed ChangeLog ==

== 1.2.0-woodwardjd ==
* change default oembed provider to embedly since oohembed got absorbed by them
* add oembed endpoint 404 handling (calls onError callback)
* add ability for beforeEmbed callback to cancel execution of onEmbed and afterEmbed callbacks (allows for constraining on types of embeds)
* add ability to set embedly key

== 1.1.0 RC ==
* Slideshare native oembed API support (patch by jaipandya)
* Photobucket native oembed API support
* Blip.tv native oembed API support
* Removed providers that are not working (myspace, screenr, qik, revision3)
* Use regex to detect URLs using the regular expressions provided by http://oohembed.com/static/endpoints.json
* Added callback function when specific provider is not found
* Added beforeEmbed and afterEmbed functions
* Support to embed.ly generic oembed provider.
* Support to jquery up to version 1.5
* Added features examples
* Added supported providers tests
* Allow user to specify ajax options (patch by corneliu...@gmail.com)
* Added onError callback
* BugFix: Incorrect use of $.extend (recommended by rformato)

Special thanks to Sam Cole, Jai Pandy, Steve and Sean for their patches.

== 1.0.5 ==
* BugFix: Fixed slideshare & revision3 providers
* BugFix: Problem with the "auto" insert method.

== 1.0.4 ==
* Added support for screenr.com videos
* Added support for vids.myspace.com videos
* Fixed a little bug with providers that already have query string parameters

== 1.0.3 ==
* Bugfixes

== 1.0.2 ==
* Added alt attribute to flickr images with image title and author
* New default behavior when executing plug-in. Now it replaces the original element with the oembed code.
* Added three new behaviors for inserting code

== 1.0.1 ==
* Bugfixes

== 1.0.0 ==
* Initial release

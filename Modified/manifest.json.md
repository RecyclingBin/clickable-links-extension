Why this file is here:  I'm using this extension to learn to develop my own extension which means I need comments
comments defined like this : //

{
   "content_scripts": [ {
      "css": [ "style.css" ],
      "exclude_globs": [ "*://*.google.*/*", "*://*.bing.*/*", "http://*.acidtests.org/*", "*://*twitter.com/*" ],
      "js": [ "jquery.min.js", "jquery.ba-replacetext.js", "clickable_links.js" ],
      "matches": [ "\u003Call_urls>" ]///all urls it's able to (has permission to modify) it does modify
   } ],
   "description": "Turns unclickable urls & email addresses into clickable ones.",
   "icons": {
      "128": "icon128.png",
      "16": "icon16.png",
      "32": "icon32.png",
      "48": "icon48.png"
   },
   "key": "MIGfMA0GCSqGSIb3DQEBAQUAA4GNADCBiQKBgQCuIl4vlMbCOfyZPRPvu8aDpT3meLaA6jaYx1Gtk/TC4gYFp+e36v8dRAm6wgKcs7tt0TSBn6grQiF03QAcwJwUURvadqV2tSjIhRz3xVIueHXfIFzHhnpjo3SaqCKCswel5uGpkxU53v0HGc7odn0Ne4RcGSuDt9ozJYmrTsr0nQIDAQAB",
   "manifest_version": 2,
   "name": "Clickable Links",
   "options_page": "options.html",
   "update_url": "http://clients2.google.com/service/update2/crx",
   "version": "2.3"
}

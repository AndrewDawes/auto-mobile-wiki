# auto-mobile-wiki
A Chrome plugin to automatically switch you to the mobile version of Wikipedia.

### Why?
Because the desktop version is so wide, especially on big screens. It's far easier to read articles on the mobile version.

### How?
The plugin works by using the chrome.declarativeNetRequest API. 
By using this API, no Javascript is required and therefore the plugin is very performant. 
Requests to the desktop version of Wikipedia are "redirected" to requests for the mobile site before they are even sent!
Regular Expressions are used behind the scenes to match the requests.
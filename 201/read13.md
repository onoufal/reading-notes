# Read 13: Local Storage:

### Local storage have many advatages over web storage.

## Local Storage before HTML5:
* Internet Expolorer
* Flash Cookies
* Dojo Toolkit
* Google fears

## HTML5 Storage (Web Storage):
> It’s a way for web pages to store named key/value pairs locally, within the client web browser.

* check wh ether the broswer support localStorage
* Access HTML5 Storage from JavaScript through localStorage object.

> HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats. However, the data is actually stored as a string. If you are storing and retrieving anything other than strings, you will need to use functions like parseInt() or parseFloat() to coerce your retrieved data into the expected JavaScript datatype.

## TRACKING CHANGES TO THE HTML5 STORAGE:

 Trap the storage event, the storage event is fired on the window object whenever setItem(), removeItem(), or clear() is called and actually changes something.

 ## LIMITATIONS:

 * 5 megabytes is how much storage space each origin gets by default.

 * “QUOTA_EXCEEDED_ERR” is the exception that will get thrown if you exceed your storage quota of 5 megabytes.

 * Can't ask the user for more storage space.


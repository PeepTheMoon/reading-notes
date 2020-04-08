# “The Past, Present, and Future of Local Storage for Web Applications”
Native applications allow for you to store and retrieve data beyond key/value pairs.  You can embed your own database, invent your own file formtat, and a number of other solutions.  

Web applications historically didn't allow for this, and cookies were invented.  These come with downsides:
1. Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over
2. Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)
3. Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful

What we need:
1. a lot of storage space
2. on the client
3. that persists beyond a page refresh
4. and isn’t transmitted to the server

HTML5 set out to solve: to provide a standardized API, implemented natively and consistently in multiple browsers, without having to rely on third-party plugins.

HTML5 Storage is a way for web pages to store named key/value pairs locally, within the client web browser. Like cookies, this data persists even after you navigate away from the web site, close your browser tab, exit your browser, or what have you. Unlike cookies, this data is never transmitted to the remote web server (unless you go out of your way to send it manually). Unlike all previous attempts at providing persistent local storage, it is implemented natively in web browsers, so it is available even when third-party browser plugins are not.

From JavaScript code, you’ll access HTML5 Storage through the localStorage object on the global window object.

HTML5 Storage is based on key/value pairs and stores data on a named key in a string.  The data can be any type, but will always be stored as a string.  use parseInt() or parseFloat() to coerce reteived data into the expected JavaScript data type.

setItem() will silently overwrite the previous value. 

There are methods for removing values and clearing the entire storage area:
    interface STorage {
        deleter void removeItem(in DOMString key);
        void clear();
    };

The property to get the total number of values in the storage area, and to iterate through all of the keys by index (to get the name of each key):

 interface Storage {
  readonly attribute unsigned long length;
  getter DOMString key(in unsigned long index);
};

If you call key() with an index that is not between 0–(length-1), the function will return null.

The storge event keeps track of changes in the storage area

5 megabytes is the default storage space, consistent across browsers.  You will get a OUTAH_EXCEEDED_ERR if you go over.


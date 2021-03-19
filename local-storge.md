# INTRODUCING HTML5 STORAGE
What I will refer to as “HTML5 Storage” is a specification named Web Storage,
 which was at one time part of the HTML5 specification proper, but was split
 out into its own specification for uninteresting political reasons. Certain 
browser vendors also refer to it as “Local Storage” or “DOM Storage.”
 The naming situation is made even more complicated by some related, 
similarly-named, emerging standards that I’ll discuss later in this chapter.

## USING HTML5 STORAGE
HTML5 Storage is based on named key/value pairs. You store data based on
a named key, then you can retrieve that data with the same key. 
The named key is a string. The data can be any type supported by JavaScript, 
including strings, Booleans, integers, or floats. However, the data is actually
 stored as a string. If you are storing and retrieving anything other than 
strings, you will need to use functions like parseInt() or parseFloat() 
to coerce your retrieved data into the expected JavaScript datatype.
## TRACKING CHANGES TO THE HTML5 STORAGE AREA
If you want to keep track programmatically of when the storage area changes,
 you can trap the storage event. The storage event is fired on the window 
object whenever setItem(), removeItem(), or clear() is called and actually 
changes something. For example, if you set an item to its existing value
or call clear() when there are no named keys, the storage event will not fire,
because nothing actually changed in the storage area.

### Why Store Data on the Client?
The main reason is practicality. JavaScript code running on the browser
 does not necessarily need to send all information to the server. 
There are several use cases:

1. You want to increase performance. You can cache data client-side so it can
 be retrieved without additional server requests.
2. You have a significant quantity of client-side-only data, e.g. 
HTML strings or widget configuration settings.
3. You want you make your application work off-line.

The simplest choice is JavaScript variables. It may be practical to create a single global variable to store application data, e.g.

// global application storage
var appDataStore = {};

// set values
appDataStore.hello = "Hello World!";
appDataStore.info = { a:1, b:2, c:3 };

// retrieve values
console.log(appDataStore.hello);
console.log(appDataStore.info.b);

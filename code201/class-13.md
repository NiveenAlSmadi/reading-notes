# Local Storage:-
#### After I read “The Past, Present, and Future of Local Storage for Web Applications” i came with this: 
- The article discusses the history of storing data in web browsers so it can be reused after refreshing the page, closing the browser, or sometimes after restarting the device.

- Local storage start working correctly from Html5.

- What we really want is a lot of storage space on the client that persists beyond a page refresh and isn’t transmitted to the server.


- HTML5 storage it’s a way for web pages to store named key/value pairs locally, within the client web browser.

- Unlike cookies, Local storage data is never transmitted to the remote web server (unless you go out of your way to send it manually).

- The latest version of pretty much every browser supports HTML5 Storage… even Internet Explorer!

- The storage event is fired on the window object whenever setItem(), removeItem(), or clear() is called and actually changes something.

- Web SQL Database (formerly known as “WebDB”) provides a thin wrapper around a SQL database.

 ##### How to Check for HTML5 Storage ?
 ``` function supports_html5_storage() {
  try {
    return 'localStorage' in window && window['localStorage'] !== null;
  } catch (e) {
    return false;
  }
} 
```
##### or using Modernizer:
``` if (Modernizr.localstorage) {
  // window.localStorage is available!
} else {
  // no native support for HTML5 storage :(
  // maybe try dojox.storage or a third-party solution
} 


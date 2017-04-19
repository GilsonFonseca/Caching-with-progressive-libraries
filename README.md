# Caching-with-progressive-libraries

  In this codelab, is taught how to use sw-precache and sw-toolbox, two progressive web app libraries built by google to make service
  worker implementation faster and easier. [Here](https://codelabs.developers.google.com/codelabs/using-caching/index.html?index=..%2F..%2F#0)
  you can see how to do it.</br>

## What you'll need in order to make it work
  In order to run it properly you'll need to download the [Web Server for Chrome app](https://chrome.google.com/webstore/detail/web-server-for-chrome/ofhbbkphhbklhfoeikjpcbhemlocgigb),
  because this codelab was designed to work well with it, but you're free to use your own web server.</br>
  After that you need to configurate it by selecting the app folder of the project in the  "choose folder" button,
  you'll need to check the box next to "Automatically show index.html" too,
  and lastly stop and restart the server by sliding the toggle labeled "Web Server: STARTED",
  now the web server is setted for you to work on the codelab.</br>
  In order to you test this code after setting up the server, you'll need to open it, visit some reddit sites, than in devtools you go to 
  network and click in the offline button, after that you should see that in addition to the sw-toolbox message you've already seen,
  a network error for the same URL. The sw-toolbox library responds to this by falling back to the cache.

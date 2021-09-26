# No-Time<sup>`BETA`</sup>
<kbd><a href='https://github.com/Parking-Master/No-Time'>No-TimeJS</a></kbd> <kbd><a href='https://github.com/Parking-Master/No-Time'>No-TimeJS<sup>BETA</sup></a></kbd><hr>
Before reading, listen to this: _this library can load up to 10 JS libraries at once at about 40ms._
###### Continue...
## What's the purpose?
Embed this library from CDN:<br>
`<script src="//cdn.jsdelivr.net/gh/Parking-Master/No-Time@latest/no-time.js" async></script>`<br>
Try loading at least 10 JS libraries or 10 CSS libraries at once. Then, test the loading speed.
<br>
Basically, It takes the slow-loading speed of a page, then minifies it by half (or less).
## How to use it
There is no downloader. You can easily get it with CDN:<br>
`<script type="text/javascript" src="//cdn.jsdelivr.net/gh/Parking-Master/No-Time@latest/no-time.js" async defer></script>`<br>
And make sure to put it right before the closing body tag
## How it works
It checks if the load speed _(ms)_ is higher than the loading speed -1000 or if the document is ready but the window is still loading.<br>
But, it can also redefine the window even when it is still loading. If there is an error loading the document, **No-Time** can reload the page and cache.

### Other repos:
##### <kbd><a href='https://github.com/Parking-Master/No-Time'>No-TimeJS</a></kbd> <kbd><a href='https://github.com/Parking-Master/Security.js'>SecurityJS</a></kbd>

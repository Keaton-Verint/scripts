# scripts
Scripts used to update VOF

After a commit, it takes a while for the cache to clear. To get around this go to the purge URL of the resource and do a hard refresh of the page with Ctrl+f5.

Example URL for resource tab:

https://cdn.jsdelivr.net/gh/GDS-Verint/scripts@latest/style-4.css

https://cdn.jsdelivr.net/gh/GDS-Verint/scripts@latest/style-4.js

https://cdn.jsdelivr.net/gh/GDS-Verint/scripts@latest/map.js


Purge URL to clear cache: https://purge.jsdelivr.net/gh/GDS-Verint/scripts@latest/style-4.css

Purge URL to clear cache: https://purge.jsdelivr.net/gh/GDS-Verint/scripts@latest/style-4.js

Purge URL to clear cache: https://purge.jsdelivr.net/gh/GDS-Verint/scripts@latest/map.js

To bypass the insecure origin stopping geolocation - go to chrome://flags/#unsafely-treat-insecure-origin-as-secure - enable it and add http://win-vfa56rd7v6n:9081 in the text area

Why are we using jsdelivr.net rather than using the raw?
Because the raw view has a MIME of (text/plain) which prevents the scripts from being used

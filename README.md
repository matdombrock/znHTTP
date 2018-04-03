# znHTTP
## A (very) minimal HTTP web server using Node
![screenshot](https://github.com/matdombrock/zserver/blob/master/web/screenshot.png?raw=true)
### Usage
 
```node znHTTP.js```
 
**NOTE:** Binds to port 80 by default which probably means you need root.
 
The webroot is in ```/web/``` this is where you should place your html, images ect. 

Not all MIME types are currently supported. See the supported MIME types in ```/local_modules/mtypes.js```
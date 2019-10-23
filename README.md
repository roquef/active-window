# active-window
> Get active window title in Node.js.

Compatible with Linux, Windows 7+, and OSX;

## Usage

```javascript
var monitor = require('active-window');

callback = function(window){
  try {
    console.log("App: " + window.app);
    console.log("Title: " + window.title);
  }catch(err) {
      console.log(err);
  } 
}

monitor.getActiveWindow(callback);

```
## Tested on
- Windows
 - Windows 10
 - Windows 7
- Linux 
  - Raspbian [lxdm]
  - Debian 8 [cinnamon]
- OSX
  - Yosemite 10.10.1

## TODO

- Test on more operating systems.
- Use native APIs. 

## License

MIT

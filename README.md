# active-window
> Get active window title in Node.js.

Compatible with Linux, Windows 7+, and OSX;

## Usage

```javascript
const monitor = require('active-window');

monitor.getActiveWindow((window) => {
  console.log("App: " + window.app);
  console.log("Title: " + window.title);
});

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

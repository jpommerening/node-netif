# netif

Node library which uses native calls to locate the mac address for
a given interface name.

Currently works on OSX, Solaris and Linux, working on support windows at the moment.

-[![Build Status](https://secure.travis-ci.org/wolfeidau/node-netif.png)](http://travis-ci.org/wolfeidau/node-netif)

## Getting Started
Install the module with: `npm install netif`

```javascript
var netif = require('netif');
netif.getMacAddress('eth0'); // '00:0C:00:00:00:00'
```

## Contributing
In lieu of a formal styleguide, take care to maintain the existing coding style. Add unit tests for any new or changed functionality. Lint and test your code using [grunt](https://github.com/gruntjs/grunt).

## Release History
_(Nothing yet)_

## License
Copyright (c) 2012 Mark Wolfe  
Licensed under the MIT license.

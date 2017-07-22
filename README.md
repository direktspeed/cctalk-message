# cctalk-command

[![Greenkeeper badge](https://badges.greenkeeper.io/direktspeed/cctalk-message.svg)](https://greenkeeper.io/)

Example
```
cmd = require('cctalk-message')
setAcceptanceMask = cmd(src, dest, command, [data], crc).toBuffer -> <Buffer .. .. .. >
```

p2pool-node-status
==================

This is a more modern looking p2pool node dashboard, which aims at 
p2pool nodes with multiple miners.

This version displays local, pool and network hashrates, expected time
to block or share, the pool minimum share difficulty etc. It includes auto-
update for graph, miners and blocks.

For each miner the individual share difficulty plus expected time to share is
displayed (this feature needs a patch to p2pool, currently included in the
p2pool-vtc version, see https://github.com/donSchoe/p2pool-vtc/pull/7 ).

Besides new features this version contains a bunch of bugfixes to the original
script. Hope you like it.

Claus Herwig <c.herwig@checon.de>
VTC: Ve5qPpuqrmXdZ3Z2MrE4Ki65Hu6rzc7pfY


original readme follows
=======================

An alternative clean p2pool node dashboard. It uses Bootstrap, jQuery and Highcharts.

## Installation

On your p2pool node in web-static directory do:

```
git clone https://github.com/johndoe75/p2pool-node-status.git
```

If you want your miner address highlighted, adjust `myself` variable accordingly. E. g.

``` JavaScript
var myself= [
  '1MzFr1eKzLEC1tuoZ7URMB7WWBMgHKimKe'
];
```

…

## Credits & License

Alexander Zschach <alex@zschach.net>

### Donate

If you like this tool, find it useful or if you just find it useful, that people out there writing free software for everybody to use or contribute, please donate some coins:

Bitcoins 1MzFr1eKzLEC1tuoZ7URMB7WWBMgHKimKe   
Litecoins LSRfZJf75MtwzrbAUfQgqzdK4hHpY4oMW3   
Terracoins 1MsuC6knLeZKHCyQ39Xcw1qcgScS1ZK5R   
Feathercoins 6tfEE48qk8Kgs9ancC82Y2iQBSX3VGYXfL

### License

The MIT License (MIT)

Copyright (c) 2013 Alexander Zschach alex@zschach.net

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

--------------------------

:wq!


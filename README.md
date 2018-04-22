!deprecated use https://github.com/joshyOcuk/equihashverify-192_7


nodejs native binding to check for kindof valid Equihash solutions

##usage:
````javascript
var ev = require('bindings')('equihashverify.node');

var header = new Buffer(..., 'hex');
var solution = new Buffer(..., 'hex'); //do not include byte size preamble "fd4005"

ev.verify(header, solution);
//returns boolean
````

##help
https://zclassic.herokuapp.com


<!--#echo json="package.json" key="name" underline="=" -->
inspectobj-pmb
==============
<!--/#echo -->

<!--#echo json="package.json" key="description" -->
Another flavor of string representations of objects in node and browsers,
similar to Node&#39;s util.inspect.
<!--/#echo -->

Forked from @substack's object-inspect@1.2.1


Usage
-----
see [doc/demo/usage.js](doc/demo/usage.js)
:TODO:

<!--!#include file="test/usage.js" start="  //#u" stop="  //#r"
  outdent="  " code="javascript" -->
```javascript
var inspectobj-pmb = require('inspectobj-pmb');
D.result  = inspectobj-pmb(null);
D.expect('===',           null);
```
<!--/include-->

```bash
$ inspectobj-pmb foo
bar
```


<!--#toc stop="scan" -->



Known issues
------------

* needs more/better tests and docs




License
-------
<!--#echo json="package.json" key=".license" -->
MIT
<!--/#echo -->

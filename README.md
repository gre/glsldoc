glsldoc
=======

**glsldoc** is a JSON-formatted documentation of all WebGL GLSL predefined functions, constants, types, types, qualifiers,...
are documented respectively to the [GLSL ES Specification](http://www.khronos.org/registry/gles/specs/2.0/GLSL_ES_Specification_1.0.17.pdf).


GLSL documentation is maintained in [this Google Spreadsheet](https://docs.google.com/spreadsheets/d/15AiAFxPq--59v0RFufYWkV8wnYjEtOOUwr-EgMXUZIE) and exported to JSON using [this script](http://blog.pamelafox.org/2013/06/exporting-google-spreadsheet-as-json.html).

Use case
--------

It can be used to add contextual documentation to your GLSL editor.

Usage
-----


```sh
npm install glsldoc
```

then you can:

```javascript
var Documentation = require("glsldoc");
console.log(Documentation);
```

Example
-------

(used in GLSL.io – link to the code to come)

node-tcc
========

TCC bindings for node.js. You can compile C code and run it on demand.

SYNOPSIS
--------

    var TCC = require('tcc'),
    var tcc = new TCC();
    tcc.compile_string('int main() { return 4649; }');
    var ret = tcc.run();
    # => 4649

TODO
----

Following methods are not supported yet.

    // TODO add_symbol

FUTURE PLAN
------------

You may use a symbol from TCC by ffi.


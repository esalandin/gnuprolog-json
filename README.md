This is a fork of https://github.com/emacstheviking/gnuprolog-json to support handling of arrays.
Original version does not support decoding of arrays as objects; for example the following valid json is not parsed correctly:  
``[ 1, 2 ]
``

Note that this is parsed correctly:  
``{ "array_value": [ 1, 2 ] }``

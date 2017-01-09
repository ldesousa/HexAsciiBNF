BNF grammar for ASCII Hexagonal grids
=====================================


Copyright
--------------------------------------------------------------------------------------

Copyright 2016-2017 Luís Moreira de Sousa. All rights reserved. 
Any use of these documents constitutes full acceptance of all terms of the 
documents licence.


Description
--------------------------------------------------------------------------------------

Defines a grammar to encode hexagonal raster in ASCII text files.

Please consult the BNF file for the exact meaning of each parameter.

Example
-------

```
ncols	3
nrows	3
xll		2.5
yll		-2.5
side	1.5
no_data	9999
23 24 23.2
24 24.2 23.7
24.1 23.8 23.3
```

Tools using this grammar
------------------------

. [**Hex-Utils**](https://github.com/ldesousa/hex-utils) - a Python package for the manipulation of hexagonal grids.

. [**CADDIES**](http://www.eawag.ch/en/department/sww/projects/caddies/) - a cellular automata development framework, presently applied to urban flood modelling.


Licence
--------------------------------------------------------------------------------------

This grammar is released under the EUPL 1.1 licence. For further details please 
consult the LICENCE file.

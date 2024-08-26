# Mega Man Battle Network 1 Symbols
This .sym file contains almost all the original function names, as found in the Nintendo Switch release of Mega Man Battle Network Legacy Collection.
This file is intended to assist in debugging with no$gba.

Contains 2 sym files:
+ `MEGAMAN_BN_AREE00.sym` - Functions are prefixed by the file they were found in.
	+ e.g. The function `_AgbMain` in `main.cpp` is labeled `main_AgbMain`
+ `MEGAMAN_BN_AREE00_min_prefix.sym` - Functions that are in CamelCase are not prefixed by the file they were found in. Functions without prefix match the original function names.
	+ e.g. The function `_AgbMain` in `main.cpp` is labeled `_AgbMain`


![](dabugr.png)
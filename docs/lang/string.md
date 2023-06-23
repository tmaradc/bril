String
======

Types
-----

The string extension adds one new base type:

    "string"

Strings are a sequence of [chars](./char.md).


Operations
----------

- `strlen`: One argument: a variable of type `string`. Returns a `int`, that is the length of the string.

- `strchar`: Two arguments: a `string` and a `int`. Returns the char at the integer position.

- `strcat`: Two arguments of type `string`. Returns a new string with the concatenation of both.


Conversion operators:

- `str2ptr`: One argument: a variable of type `string`. Returns a char pointer with the chars of the string.

- `ptr2str`: Two arguments: a `ptr` of type `char` and a `int`. Returns a string with n chars of the pointer, being n the `int` provided.


Printing
--------

The [core `print` operation](./core.md#miscellaneous) prints `string` values.

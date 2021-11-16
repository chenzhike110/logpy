kanren
=====

[![](https://travis-ci.org/logpy/logpy.png)](https://travis-ci.org/logpy/logpy)

Logic Programming in Python 

Changes
------------
add delete facts api to the relation


Dependencies
------------

``kanren`` supports 3.5+.
It is pure Python and requires no dependencies beyond the standard
library, [`toolz`](http://github.com/pytoolz/toolz/),
[`multipledispatch`](http://github.com/mrocklin/multipledispatch/), and
[`unification`](http://github.com/mrocklin/unification/).

It is, in short, a light weight dependency.

Author
------

[Matthew Rocklin](http://matthewrocklin.com)

License
-------

New BSD license. See LICENSE.txt

Motivation
----------

Logic programming is a general programming paradigm.  This implementation however came about specifically to serve as an algorithmic core for Computer Algebra Systems in Python and for the automated generation and optimization of numeric software.  Domain specific languages, code generation, and compilers have recently been a hot topic in the Scientific Python community.  kanren aims to be a low-level core for these projects.

References
----------

*   [Logic Programming on wikipedia](http://en.wikipedia.org/wiki/Logic_programming)
*   [miniKanren](http://minikanren.org/), a Scheme library for relational programming on which this library is based.  More information can be found in the
[thesis of William
Byrd](https://scholarworks.iu.edu/dspace/bitstream/handle/2022/8777/Byrd_indiana_0093A_10344.pdf).
*   [core.logic](https://github.com/clojure/core.logic) a popular implementation of miniKanren in Clojure.

NAME
====

Raku port of Perl's Tie::StdHash module

SYNOPSIS
========

    use Tie::StdHash;

DESCRIPTION
===========

This module tries to mimic the behaviour of Perl's `Tie::StdHash` module as closely as possible in the Raku Programming Language.

Tie::StdHash is a module intended to be subclassed by classes using the [P5tie](tie()) interface. It uses the standard `Hash` implementation as its "backend".

SEE ALSO
========

[P5tie](P5tie), [Tie::StdHash](Tie::StdHash)

AUTHOR
======

Elizabeth Mattijsen <liz@wenzperl.nl>

Source can be located at: https://github.com/lizmat/Tie-StdHash . Comments and Pull Requests are welcome.

COPYRIGHT AND LICENSE
=====================

Copyright 2018-2019 Elizabeth Mattijsen

Re-imagined from Perl as part of the CPAN Butterfly Plan.

This library is free software; you can redistribute it and/or modify it under the Artistic License 2.0.


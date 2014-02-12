Prolog-Utility-FromPerl version 1.0.2

This module was written to fill a need to create prolog terms from perl data structures. This is useful when you need to generate all of your prolog facts ahead of time in a file that will be consulted.

INSTALLATION

To install this module, run the following commands:

	perl Makefile.PL
	make
	make test
	make install

Alternatively, to install with Module::Build, you can use the following commands:

	perl Build.PL
	./Build
	./Build test
	./Build install


DEPENDENCIES

Regex::Common
Test::More
version


COPYRIGHT AND LICENCE

Copyright (C) 2013, Tyson Maly

This library is free software; you can redistribute it and/or modify
it under the same terms as Perl itself.

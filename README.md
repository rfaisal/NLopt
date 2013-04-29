#NLopt

This repository is forked from NLopt-2.3 and then modified. You can learn more about the original library from http://ab-initio.mit.edu/wiki/index.php/NLopt and http://ab-initio.mit.edu/wiki/index.php/NLopt_Introduction .


## Installation

It is compiled and installed with the standard GNU autoconf/automake commands:
`$ ./configure`
`$ make`
`$ make install`
(See `$ ./configure --help` or the INSTALL file for other options.)


## Usage

Once it is installed, #include <nlopt.h> in your C/C++ programs and link it with -lnlopt -lm. You may need to use the C++ compiler to link in order to include the C++ libraries (which are used internally by NLopt, even though it has a C API).

The minimization function, nlopt_minimize, is described in the man page (api/nlopt_minimize.3, which is installed by `make install`.

Interfaces for other languages may be added in the future.


## License

It is released under MIT license.

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

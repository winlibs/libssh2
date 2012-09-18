# libssh2

libssh2 is a client-side C library implementing the SSH2 protocol.

# Building for PHP

libssh2 depends on openssl and zlib. To build follow these steps:

* create a directory named "deps" inside the root of libssh2 source tree and put the dependencies there
* use win32/libssh2.vcproj to build the libssh2 with VS2008
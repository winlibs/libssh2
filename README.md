# libssh2

libssh2 is a client-side C library implementing the SSH2 protocol.

# Building for PHP

libssh2 depends on openssl and zlib. To build follow these steps:

* create a directory named "deps" at the level of the libssh2 source dir and put the dependencies there
* build libssh2
 * use win32/libssh2.vcproj to build with VS2008
 * use win32/libssh2.vc11.sln to build with VS2012
 * use win32/libssh2.vc14.sln to build with VS2015
 * use win32/libssh2.vc15.sln to build with VS2017

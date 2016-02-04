# jNotify

fork from http://jnotify.sourceforge.net/

JNotify is a java library to listen filesystem events, such as created, deleted, midified and renamed. 

Mechniasm
------
JNotify is a jni library, with the underline native implementations
* Linux: inotify
* Max OS X: fsevent
* Win32: api ReadDirectoryChangesW

Enhancements
-------
* maven friendly. 
* recompile linux native library with lower version GLIBC_2.2.5. 
* package native library to jar. 

Tested in platforms
-------
* Mac OS X 10.11
* CentOS amd64 5.7




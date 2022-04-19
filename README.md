# Example using etr/libhttpserver

This example features using the [etr/libhttpserver](https://github.com/etr/libhttpserver) with [tipi.build](https://tipi.build) to run a simple http server.

Simply run : 

```
tipi . -t linux
```
Alternatively you can use *macos* or *vs-16-2019-win64-cxx17* as target platform.

Then : 

```
tipi run build/linux/bin/hello_world
```

And point your browser to http://localhost:8080/hello to test it.


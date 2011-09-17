Introduction
============

This project provides allows the use of PicoContainer-managed instances as Jersey resources.

The Jersey project provides bindings for springframework and google-guice, but I wanted to see what
it required to use [PicoContainer](http://www.picocontainer.org/) as an IoC container within Jersey.

Dependencies
------------

* jersey APIs - see https://jersey.dev.java.net
* picocontainer.jar - see http://www.picocontainer.org

Examples
--------

Please take a look at `src/test/webapp/WEB-INF/web.xml` for examples of how to configure the PicoServlet.

All the example code is located in the `com.sun.jersey.spi.pico.container.servlet.example` package in `src/test/java`.

You can build and run the examples using `ant` and the provided `build.xml` file.

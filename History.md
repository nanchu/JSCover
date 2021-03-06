0.0.12 / 2012-11-13
==================
  * Fix error message re: destination as sub-directory of source https://github.com/tntim96/JSCover/issues/18
  * Fix detection of destination as sub-directory of source https://github.com/tntim96/JSCover/issues/16

0.0.11 / 2012-11-07
==================
  * Use platform default encoding. Add documentation on -Dfile.encoding JVM property usage in manual.

0.0.10 / 2012-11-07
==================
  * Flawed and download. Replaced with 0.0.11

0.0.9 / 2012-11-05
==================
  * Fix https://github.com/tntim96/JSCover/issues/8, https://bugzilla.mozilla.org/show_bug.cgi?id=800616

0.0.8 / 2012-10-25
==================
  * Add simple non-instrumenting web-server used in the manual's examples
  * Improve manual to a usable state independent of JSCoverage's documentation
  * Fix bug where destination folder can be in the source folder

0.0.7 / 2012-10-23
==================
  * Add '--include-unloaded-js', only for non-proxy web-server, to scan beneath www-root for unloaded/untested JS files
  * Leading slash in --no-instrument and --exclude are ignored for consistent internal handling.
  * Double forward slashes in URLs replaced with single forward slashes
  * Internal - Replace URL based proxy with sockets. All headers now forwarded as received.

0.0.6 / 2012-10-17
==================
  * Fixed basic non-SSL proxy support
  * Add POST, cookie and redirect support for proxy mode

0.0.5 / 2012-10-16
==================
  * Add proxy support (flawed and download has been replaced with 0.0.6)
  * Message 'Report stored at' changed to 'Coverage data stored at' (important for HtmlUnit/Selenium)
  * Internal - Swap from NanoHTTPD to JSCover's own web-server - index.htm(l) no longer served automatically

0.0.4 / 2012-10-12
==================
  * Include JSCover-all.jar, containing all JAR dependencies, in distribution
  * Fix https://github.com/tntim96/JSCover/issues/2, https://bugzilla.mozilla.org/show_bug.cgi?id=800616
  * Internal - More tests, remove Apache commons JARs, upgrade Mockito, Inverted mode test

0.0.3 / 2012-10-09
==================
  * Add server handling of JavaScript-programmatic triggering of report storage
  * Add more tests

0.0.2 / 2012-10-03
==================
  * Addition of command line file instrumentation
  * Working example of QUnit test suite

0.0.1 / 2012-10-01
==================
  * Initial release comprising of web-server

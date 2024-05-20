Byte Buddy
==========

<a href="https://bytebuddy.net">
<img src="https://raw.githubusercontent.com/raphw/byte-buddy/gh-pages/images/logo-bg.png" alt="Byte Buddy logo" height="180px" align="right" />
</a>

runtime code generation for the Java virtual machine

[![Actions Status](https://github.com/raphw/byte-buddy/workflows/CI/badge.svg)](https://github.com/raphw/byte-buddy/actions)
[![Security Score](https://snyk-widget.herokuapp.com/badge/mvn/net.bytebuddy/byte-buddy/badge.svg)](https://snyk.io/test/github/raphw/byte-buddy)
[![Coverage Status](https://img.shields.io/coveralls/raphw/byte-buddy/master.svg)](https://coveralls.io/r/raphw/byte-buddy?branch=master)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/net.bytebuddy/byte-buddy-parent/badge.svg#)](https://maven-badges.herokuapp.com/maven-central/net.bytebuddy/byte-buddy-parent)
[![CII Best Practices](https://bestpractices.coreinfrastructure.org/projects/6251/badge)](https://bestpractices.coreinfrastructure.org/projects/6251)

Byte Buddy is a code generation and manipulation library for creating and modifying Java classes during the runtime of a
Java application and without the help of a compiler. Other than the code generation utilities
that [ship with the Java Class Library](https://docs.oracle.com/javase/8/docs/api/java/lang/reflect/Proxy.html), Byte
Buddy allows the creation of arbitrary classes and is not limited to implementing interfaces for the creation of runtime
proxies. Furthermore, Byte Buddy offers a convenient API for changing classes either manually, using a Java agent or
during a build.

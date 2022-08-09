---
title: libstrophe
subtitle: An XMPP library for C
layout: base
---

libstrophe is a minimal XMPP library written in C. It has almost no
external dependencies, only an XML parsing library (expat or libxml
are both supported). It is designed for both POSIX and Windows
systems.

# Quick Links

* [Latest documentation](doc/0.12.2)
* [GitHub project page](https://github.com/strophe/libstrophe)
* [Mailing list](http://groups.google.com/group/libstrophe)
* [Bug tracker](https://github.com/strophe/libstrophe/issues)

# License

libstrophe is dual licensed under the
[MIT](https://github.com/strophe/libstrophe/raw/master/MIT-LICENSE.txt)
and
[GPLv3](https://github.com/strophe/libstrophe/raw/master/GPL-LICENSE.txt)
licenses.

# Author

libstrophe was originally created by [Jack Moffitt](http://metajack.im)
and has been maintained by the community since 2014.

# Features

* Authentication with [RFC4422](https://www.rfc-editor.org/rfc/rfc4422) `SASL`.

	Supported methods are: `PLAIN`, `DIGEST-MD5`, `ANONYMOUS`, `SCRAM-SHA{1,256,512}`, `EXTERNAL`.

* Secure connection with [TLS](https://www.rfc-editor.org/rfc/rfc8446)
via [GnuTLS](https://gnutls.org/), [LibreSSL](https://www.libressl.org/),
[OpenSSL](https://www.openssl.org/) or SCHANNEL (only on Windows).

	Supported mechanisms are: `STARTTLS` on port `5222` and legacy mode on port `5223`.

* TLS client authentication with [XEP-0178](https://xmpp.org/extensions/xep-0178.html) `SASL EXTERNAL` (only with GnuTLS, LibreSSL or OpenSSL).
* Stream Management with [XEP-0198](https://xmpp.org/extensions/xep-0198.html).
* DNS resolution via an internal implementation or [c-ares](https://c-ares.org/).

# Documentation

Older versions of the documentation can be found here

* [0.12.1](doc/0.12.1)
* [0.12.0](doc/0.12.0)
* [0.11.0](doc/0.11.0)
* [0.10.0](doc/0.10.0)
* [0.9.2](doc/0.9.2)

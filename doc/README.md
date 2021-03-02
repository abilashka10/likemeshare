Likemeeeshare Core
=============

Setup
---------------------
Likemeeeshare Core is the original Likemeeeshare client and it builds the backbone of the network. It downloads and, by default, stores the entire history of Likemeeeshare transactions (which is currently more than 7 GBs); depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more.

To download Likemeeeshare Core, visit [likemeeeshare.org](https://likemeeeshare.org).

Running
---------------------
The following are some helpful notes on how to run Likemeeeshare on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/likemeeeshare-qt` (GUI) or
- `bin/likemeeeshared` (headless)

### Windows

Unpack the files into a directory, and then run likemeeeshare-qt.exe.

### OS X

Drag Likemeeeshare-Core to your applications folder, and then run Likemeeeshare-Core.

### Need Help?

* See the documentation at the [Likemeeeshare Wiki](https://likemeeeshare.info/)
for help and more information.
* Ask for help on [#likemeeeshare](http://webchat.freenode.net?channels=likemeeeshare) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net?channels=likemeeeshare).
* Ask for help on the [LikemeeeshareTalk](https://likemeeesharetalk.io/) forums.

Building
---------------------
The following are developer notes on how to build Likemeeeshare on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [OS X Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The Likemeeeshare repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Source Code Documentation (External Link)](https://dev.visucore.com/likemeeeshare/doxygen/)
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [Travis CI](travis-ci.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)

### Resources
* Discuss on the [LikemeeeshareTalk](https://likemeeesharetalk.io/) forums.
* Discuss general Likemeeeshare development on #likemeeeshare-dev on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net/?channels=likemeeeshare-dev).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Fuzz-testing](fuzzing.md)
- [Reduce Traffic](reduce-traffic.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)
- [ZMQ](zmq.md)

License
---------------------
Distributed under the [MIT software license](/COPYING).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.

101 Coin Core
=====================

Setup
---------------------
[101 Coin Core](101coin.io/wallet) is the original 101 Coin client and it builds the backbone of the network. However, it downloads and stores the entire history of 101 Coin transactions; depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more. Thankfully you only have to do this once.

Running
---------------------
The following are some helpful notes on how to run 101 Coin on your native platform.

### Unix

Unpack the files into a directory and run:

- bin/32/101coin-qt (GUI, 32-bit) or bin/32/101coind (headless, 32-bit)
- bin/64/101coin-qt (GUI, 64-bit) or bin/64/101coind (headless, 64-bit)

### Windows

Unpack the files into a directory, and then run 101coin-qt.exe.

### OSX

Drag 101coin-Qt to your applications folder, and then run 101coin-Qt.

### Need Help?

For help and more information.
* Join our Discord server [Discord Server](https://discord.101coin.io)

Building
---------------------
The following are developer notes on how to build 101 Coin on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [OSX Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The 101coin repo's [root README](https://github.com/101-Coin/101CoinCore/blob/master/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Multiwallet Qt Development](multiwallet-qt.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Source Code Documentation (External Link)](https://dev.visucore.com/bitcoin/doxygen/) ***TODO***
- [Translation Process](translation_process.md)
- [Unit Tests](unit-tests.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Dnsseed Policy](dnsseed-policy.md)


### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)

License
---------------------
Distributed under the [MIT/X11 software license](http://www.opensource.org/licenses/mit-license.php).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.

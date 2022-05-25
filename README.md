BTCPPrivate Classic 1.0.0
<img align="right" width="120" height="80" src="doc/imgs/logo1.png">
===========

What is BTCPrivate Classic?
---------------------------

[BTCPrivate Classic](https://btcprivateclassic/) is an implementation of the "Zerocash" protocol.
Based on Zcash's code, BTCPrivate Classic intends to offer a standard of privacy
through a sophisticated zero-knowledge proving scheme that preserves
confidentiality of transaction metadata. More technical details are available
in our [Protocol Specification](https://zips.z.cash/protocol/protocol.pdf).

This software is the BTCPrivate Classic client. It downloads and stores the entire history
of BTCPrivate Classic transactions; depending on the speed of your computer and network
connection, the synchronization process could take a day or more once the
blockchain has reached a significant size.

<p align="center">
  <img src="doc/imgs/zcashd_screen1.gif" height="500">
</p>

What is BTCPrivate Classic project planning?
--------------------------------------------

Fase 1 Development BTCPrivate Classic v1
- 1 : Create BTCP Classic v1, based on Zcash latest stable release (1:1) - status not ready
- 2 : Get running BTCP Classic v1 on local server environment - status not ready
- 3 : Test BTCP Classic v1 on local server environment- status not ready
- 4 : Analyse BTCP chaindata (adresses and amount) - status not ready
- 5 : Create strategy how to deal with btcp holdings and how to distribute - status not ready
- 7 : Deploy BTCP Classic v1 on remote server environment - status not ready
- 8 : Test BTCP Classic v1 on remote server environment - status not ready

Fase 2 Development BTCPrivate Classic v1.0.1
- 1 : Implement BTCP specifics in BTCP Classic - status not ready
- 2 : Test BTCP Classic v1 on remote server environment - status not ready

#### :lock: Security Warnings

See important security warnings on the
[Security Information page](https://z.cash/support/security/).

**BTCPrivate Classic is experimental and a work in progress.** Use it at your own risk.

## Getting Started

Please see our [user guide](https://btcpc.readthedocs.io/en/latest/rtd_pages/rtd_docs/user_guide.html) for joining the main BTCPrivate Classic network.

### Need Help?

* :blue_book: See the documentation at the [ReadTheDocs](https://btcpc.readthedocs.io)
  for help and more information.
* :incoming_envelope: Ask for help on the [BTCPrivate Classic](https://forum.btcpc/) forum.
* :speech_balloon: Join our community on [Discord](https://discordapp.com/invite/PhJY6Pm)

Participation in the BTCPrivate Classic project is currently not possible.

### Building

Build BTCPrivate Classic along with most dependencies from source by running the following command:

```
./btcpcutil/build.sh -j$(nproc)
```

Currently, BTCPrivate Classic is only officially supported on Debian and Ubuntu. See the
[Debian / Ubuntu build](https://btcpc.readthedocs.io/en/latest/rtd_pages/Debian-Ubuntu-build.html)
for detailed instructions.

License
-------

For license information see the file [COPYING](COPYING).

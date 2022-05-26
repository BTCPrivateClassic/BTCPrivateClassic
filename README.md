BTCPrivate Classic 1.0.0 (under construction)
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

The development of BTCPrivate Classic is not related to BTCP. There has not been any form of communication between BTCP 
and this project.

<p align="center">
  <img src="doc/imgs/zcashd_screen1.gif" height="500">
</p>

Why BTCPrivate Classic?
---------------------------
- BTCP is inactive for more than 3 years and its unclear if it ever will be set live again. The intention is not to replace BTCP but to serve as a working alternative in the case the BTCP development will be stopped or delayed again for another ? period
- Poor communication about the development status (for the community its a blackbox whats really happening, the current dev is doing his best to reanimate the project but currently there is no proof that this will be succesfull).
- No roadmap and lack of vision
- Poor projectmanagement (no timelines, commitment etc..)

When will BTCPrivate Classic project start?
--------------------------------------------
- BTCPrivate Classic development will start if the current development activities have not resulted in running product 01-aug-2022.

Who does the BTCPrivate Classic development?
--------------------------------------------
- Senior software developer with the nescesarry programming skills (C, C#, Java, UNix, Shell, Web) but no blockchain coding experience.
(porting Zcash tot BTCP Classic will give insight in the internals). But most important is that we not should think this is all rocketscience
because in the end its programma code.

What will happen if BTCP is active before BTCPrivate Classic project finished?
------------------------------------------------------------------------------
- BTCPrivate Classic development will be stopped.

What is BTCPrivate Classic project planning?
--------------------------------------------
Fase 1 Preparing for developing and testing
- 1 : Get development and test environment up and running - status not ready
- 1 : Deployment Zcash latest stable release v5.0.0 (as it is) test environment- status not ready
- 2 : Create some basic testscripts - status not ready
- 3 : Test ZCash on the test environment  - status not ready

Fase 2 Create BTCPrivate Classic v1.0.0
- 1 : Create BTCP Classic v1, based on Zcash latest stable release v5.0.0 (port code 1:1) - status not ready
- 2 : Get running BTCP Classic v1 on test server environment - status not ready
- 3 : Create testscripts and documentation - status not ready
- 4 : Test BTCP Classic v1 on test server environment- status not ready

Fase 3 Define airdrop strategy
- 5 : Analyse BTCP blockchain data (adresses and holdings just before snapshot) - status not ready
- 6 : Create strategy how to deal with btcp holdings and how to distribute. BTCP holders will get an airdrop 1:1 BTCP - BTCP Classic 
      (fraud addresses will be excluded, the analyse from BTCP project will be used) - status not ready
- 7 : Distribution on test server environment - status not ready
- 8 : Verify distribution - status not ready

Fase 4 Review and documentation
- 9 : Create test documentation - status not ready
- 10 : Review code and distribution - status not ready

Fase 5 Set BTCPrivate Classic live (how to exclude exchanges because they are almost all bad actors)
- 11 : Deployment BTCP Classic v1.0.0 on production server - status not ready
- 12 : Distribution BTCP Classic coins - status not ready

Fase 6 Create BTCPrivate Classic v1.0.1
- 13 : Add BTCP specific features

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

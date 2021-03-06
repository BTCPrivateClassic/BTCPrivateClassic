---
name: Bug report
about: Create a report about a bug in btcpcd.
title: ''
labels: 'bug'
assignees: ''

---

<!--
This issue tracker is only for technical issues related to zcashd.

General BTCPrivate Classic questions and/or support requests and are best directed to the
BTCPrivate Classic Forum: https://forum.btcprivateclassiccommunity.com/

For reporting security vulnerabilities or for sensitive discussions with our
security team, please email security@z.cash . You can use this GPG key to send
an encrypted message:
    https://btcpc/gpg-pubkeys/security.asc
    fingerprint: AF85 0445 546C 18B7 86F9  2C62 88FB 8B86 D8B5 A68C

The key and fingerprint are duplicated on our Public Keys page:
https://btcpc/support/pubkeys.html
-->

### Describe the issue
Please provide a general summary of the issue you're experiencing

### Can you reliably reproduce the issue?
#### If so, please list the steps to reproduce below:
1. 
2. 
3. 

### Expected behaviour
Tell us what should happen

### Actual behaviour + errors
Tell us what happens instead including any noticeable error output (any messages
displayed on-screen when e.g. a crash occurred)

### The version of BTCPrivate Classic you were using:
Run `btcpcd --version` to find out

### Machine specs:
- OS name + version:
- CPU:
- RAM:
- Disk size:
- Disk Type (HD/SDD):
- Linux kernel version (uname -a):
- Compiler version (gcc --version):
- Linker version (ld -v):
- Assembler version (as --version):

### Any extra information that might be useful in the debugging process.
This includes the relevant contents of `~/.btcpc/debug.log`. You can paste raw
text, attach the file directly in the issue or link to the text via a pastebin
type site. Please also include any non-standard things you did during
compilation (extra flags, dependency version changes etc.) if applicable.

### Do you have a backup of `~/.btcpc` directory and/or take a VM snapshot?
- Backing up / making a copy of the `~/.btcpc` directory might help make the
  problem reproducible. Please redact appropriately.
- Taking a VM snapshot is really helpful for interactively testing fixes

# Awesome XMPP [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome XMPP servers, libraries, software and resources.

## Contents

 - [Specifications](#specifications)
 - [Clients](#clients)
 - [Servers](#servers)
 - [Libraries](#libraries)
 - [Advanced Usages](#advanced-usages)
 - [Miscellaneous](#Miscellaneous)
 - [Most robust XMPP providers](#most-robust-xmpp-providers)

## Specifications

* [RFC6120](https://datatracker.ietf.org/doc/rfc6120/) - Core.
* [RFC6121](https://datatracker.ietf.org/doc/rfc6121/) - Instant Messaging and Presence.
* [RFC7622](https://datatracker.ietf.org/doc/rfc7622/) - Address Format.
* [XEPs](https://xmpp.org/extensions/) - Extensions to XMPP.

## Clients

* [Adium](https://adium.im/) - Open source multi-protocol instant messaging client for Mac OS X.
* [ChatSecure](https://chatsecure.org/) - Encrypted Messenger for iOS.
* [Conversations](https://github.com/siacs/Conversations) - Open source XMPP/Jabber client for the Android.
* [Converse](https://conversejs.org/) - Free and open-source XMPP chat client in your browser.
* [Coyim](https://github.com/coyim/coyim) - Safe and secure chat client.
* [Dino](https://github.com/dino/dino) - Modern Jabber/XMPP Client using GTK+/Vala.
* [Kaiwa](http://getkaiwa.com/) - Modern and apen source Web client for XMPP. 
* [JSXC](https://www.jsxc.org/) - Modern, open source and available as Owncloud/Nextcloud plugin web client.
* [Pidgin](https://www.pidgin.im/) - Chat program with support for multiple networks, crossplatform.
* [Profanity](http://www.profanity.im/) - Console based XMPP, Linux, FreeBSD, OSX, Windows and Android.
* [Swift](https://swift.im/) - Elegant, secure, adaptable and intuitive XMPP Client.
* [Psi](https://psi-im.org/) - Qt client (Linux, Windows, OSX).

## Servers 

* [Ejabberd](https://www.ejabberd.im/) - Distributed fault-tolerant Jabber server which is mainly written in Erlang.
* [Jabberd2](http://jabberd2.org/) - Next generation of the jabberd project, c++.
* [Jabberd3](https://github.com/smokku/jabberd3) - Evolution of jabberd2.
* [Openfire](https://www.igniterealtime.org/projects/openfire/) - XMPP server written in Java.
* [Prosody](https://prosody.im/) - Lightweight, open source Jabber server, written in Lua.
* [Metronome](https://metronome.im/) - Fork of Prosody server, more complete with a dual license.

## Libraries

* [PyXMPP](https://github.com/Jajcus/pyxmpp) - Python Jabber/XMPP implementation.
* [SleekXMPP](https://github.com/fritzy/SleekXMPP) - Python 2.6+/3.1+ XMPP Library.
* [Swiften](https://swift.im/swiften.html) - Cross-platform, and performant C++.
* [xmpp.js](https://github.com/xmppjs/xmpp.js) - XMPP for JavaScript.

## Advanced Usages

* [Movim](https://github.com/movim/movim) - Distributed social network built on top of XMPP.
* [Saros](http://www.saros-project.org/) - Real-time collaborative editor for eclipse projects.

## Miscellaneous

* [Buyddcloud](http://buddycloud.com/) - Tools, libraries and services for secure cloud & on-premise user and group messaging.
* [XMPP Compliance](https://conversations.im/compliance/) - Service checking compliance of the XMPP servers.
* [XMPP Observatory](https://xmpp.net/) - Testing the security of the Jabber/XMPP network.
* [The Jabber Spam Fighting Manifesto](https://github.com/ge0rg/jabber-spam-fighting-manifesto/) - Federated Server Policies against the spam.
* [XMPP Manifesto for Freedom](https://gitlab.com/senpie/xmpp-manifesto-for-freedom) - Freedom Manifesto, response to above.

## Most robust XMPP providers

XMPP Providers with more than 15 years uptime and with an *A* security grade. Extracted with:

```
links -dump https://xmpp.net/directory.php |grep -p '200[0-3]' |grep ' A '
```

* [jabber.cz](jabber.cz)
* [jabber.meta.net.nz](jabber.meta.net.nz)
* [jabberpl.org](jabberpl.org)
* [jwchat.org](jwchat.org)
* [njs.netlab.cz](njs.netlab.cz)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Rafal Zawadzki](https://bluszcz.net) has waived all copyright and related or neighboring rights to this work.

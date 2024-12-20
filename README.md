# BIND 9

### Contents

1. [Introduction](#intro)
1. [Installation](#install)
1. [Configuration](#config)
1. [Operation](#operate)
1. [Documentation](#doc)
1. [Acknowledgments](#ack)

### <a name="intro"/> Introduction

A user-space Dig installation for Windows (from DNS Bind9).

Institutional and corporate secure Windows desktops are often restricted to user-space and have limited software installation rights.
However for software develoeprs, systems integrators, and network operators it would be essential to have a modicum of network tools.
Dig, which ships with the official DNS Bind9 daemon is the accepted standard tool to query DNS, as NSlookup does not cut the mustard.

Unfortunately, Bind9 no longer ships binaries for windows:

	Note: 
	Bind9 Subscription Edition Native Windows builds are no longer available. 
	Bind9 now offers features not found in the open source version of BIND, 
	including EDNS Client-Subnet Identifier and Cisco Umbrella integration. 
	Click below to request additional information.

WinBind, an open-source project for a native Windows integration also relied on these official binaries.

This means we will have to compile it from source (we chose to do the hard way).


### <a name="install"/> Installation

[https://kb.isc.org/docs/aa-01392](Bind9 binaries - including Windows x64)



### <a name="config"/> Configuration


### <a name="operate"/> Operation


### <a name="docs"/> Documentation


[Bind9.md](Orginal Bind9 README.md)


### <a name="ack"/> Acknowledgments


[https://chriswoods.co.uk/2019/06/quickly-install-dig-on-windows-without-full-bind9-install/](Dig on Windows without full Bind9)

[https://www.winbind.org/installing-bind-on-windows/](WinBind - Bind9 for windows)

[https://kb.isc.org/docs/aa-01392](Bind9 binaries - including Windows x64)


### <a name="license"/> License

Most of the project is verbatim Bind9 and is covered by its Mozilla Public License - MPL 2.0.

This README is licensed under: Creative Commons - By-Attribution, Non-Commercial, Share-Alike.

* [LICENSE](main Bind9 licence - MPL-2.0)
* [LICENSES/](additional embedded licenses)
* [https://creativecommons.org/licenses/by-nc-sa/4.0/deed.en/](CC_BY_NC_SA)


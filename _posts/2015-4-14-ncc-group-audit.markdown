---
layout: post
title: "ISRG Engages NCC Group for Let's Encrypt Audit"
date: 2015-4-14T07:00
author: Josh Aas, ISRG Executive Director
excerpt: ISRG has engaged the NCC Group Crypto Services team to perform a security review of Let's Encrypt's certificate authority software, boulder, and the ACME protocol.
---

ISRG has engaged the <a href="https://cryptoservices.github.io/">NCC Group Crypto Services team</a> to perform a security review of Let's Encrypt's certificate authority software, <a href="https://github.com/letsencrypt/boulder">boulder</a>, and the <a href="https://github.com/letsencrypt/acme-spec/">ACME protocol</a>. NCC Group's team was selected due to their strong reputation for cryptography expertise, which brought together Matasano Security, iSEC Partners, and Intrepidus Group.

The NCC Group audit will take place prior to the general availability of Let's Encrypt's service, and is intended to provide additional assurance that our systems are secure. The NCC Group audit does not replace the WebTrust audit, which will happen after general availability.

"I'm very much looking forward to the general availability of Let’s Encrypt - lowering the bar both technically and financially for people to deploy TLS will result in a more encrypted Internet that helps increase security and preserve people's privacy," said Tom Ritter, Practice Director, NCC Group.

Let's Encrypt's certificate authority software is called <a href="https://github.com/letsencrypt/boulder">boulder</a>. It's largely written in the go language and makes use of CloudFlare's <a href="https://github.com/cloudflare/cfssl">CFSSL</a> tools, which are also written in go. Our boulder software contains modules including a web front-end and registration, validation, certificate, and storage authorities.

<a href="https://github.com/letsencrypt/acme-spec/">ACME</a>, short for Automated Certificate Management Environment, is the protocol that Let's Encrypt will use for automatic certificate issuance and managemement. We hope to standardize ACME in the <a href="https://www.ietf.org/">IETF</a>, starting with the formation of a working group later this year.

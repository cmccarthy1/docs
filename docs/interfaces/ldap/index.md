---
title: LDAP interface for kdb+ – Interfaces – kdb+ and q documentation
description: This interface allows KDB+ to interact with the Lightweight Directory Access Protocol (LDAP).
hero: <i class="fab fa-superpowers"></i> Fusion for Kdb+
keywords: interface, kdb+, library, q, ldap
---
# LDAP interface for kdb+

:fontawesome-brands-github:                                                                                                                                  [KxSystems/ldap](https://github.com/KxSystems/ldap)


LDAP is a vendor neutral protocol to gain interaction with directory services. The open protocol that client/servers should implement is detailed on [RFC 4511](https://docs.ldap.com/specs/rfc4511.txt).

The protocol is often used by organizations for centralized authentication and storage of their resources such as users, groups, services, applications, etc. For example, a client application can find if a user is a member of a particular group to allow access to their service.

## Use Cases

In addition to authentication/authorization uses, depending on the data stored on your LDAP server, it could be used to access data for analytics e.g.

- company staff turnover (if user creation date/leave dates/etc recorded)
- IT equipment approaching end of life (if hardware details recorded)
- staff departmental memberships

## Kdb+/LDAP integration

This interface allows KDB+ to interact with the Lightweight Directory Access Protocol (LDAP). This API permits a client to authenticate & search against an LDAP server. The interface is a thin wrapper against the open source [OpenLDAP](https://openldap.org/) library. General info on this API is available [here](https://www.openldap.org/software/man.cgi?query=ldap&sektion=3&apropos=0&manpath=OpenLDAP+2.4-Release). Not all server vendors may provide the same set of features, so this API aims to be vendor neutral to gain maximum flexibility.
<br>
:fontawesome-brands-github: 
[Install guide](https://github.com/KxSystems/ldap#installation)

## Status

The interface is currently available as a beta version under an Apache 2.0 licence and is supported on a best effort basis by the Fusion team. This interface is currently in active development, with additional functionality to be released on an ongoing basis.

:fontawesome-brands-github: 
[Issues and feature requests](https://github.com/KxSystems/ldap/issues) 
<br>
:fontawesome-brands-github: 
[Guide to contributing](https://github.com/KxSystems/ldap/blob/master/CONTRIBUTING.md)
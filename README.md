# The Decentralized Internet Manifesto
Version: 1.1

Last Revision: 2017-06-25

Originally Authored: 2017-06-24

## Overview
In 1996, John Perry Barlow penned his now famous "[A Declaration of the Independence of Cyberspace](https://www.eff.org/cyberspace-independence)". Since then, we've seen privacy violations which have been attributed to instigating human rights violations. Even the UN recognizes the "[Right to Privacy in the Digital Age](http://www.un.org/press/en/2013/gashc4094.doc.htm)". This document describes one possible solution to this problem, namely the basic tenets to decentralize the internet in a manner consistent with the common good and good security practice.

## Tenets
### 1. Confidentiality and Privacy must always be maintained
 * Objects MUST be autonomous so they can be acted upon individually
 * Objects, including network transports, MUST be encrypted by default
 * Objects MUST be private by default
 * Services MUST be opt-in

Examples of objects include, but are not limited to:

* peers and connection information
* transport conduits
* posts - the content and the poster
* people and personal details
* identity information including user information, IP address, and any personally identifiable information
* financial information
* statistics

User Stories to consider:

* As a user concerned about my privacy, I want to be able to post content without my identity (including IP) to be revealed unless I choose to do so, so I can maintain my privacy.
  * Notes
    * This requires transports to be encrypted for the conveyance of public data along with peering data. The contents of the user's post may be unencrypted at the end location but we must maintain full security during the transport process.


### 2. Availability
 * Objects MUST be decentralized in nature, or support decentralization of an object store
 * Objects MUST be designed for high latency environments
 * Objects MUST capable of operating in near real-time
 * Non-network objects MAY be blockable by end users but network conduits MUST NOT be blockable so as to ensure availability

User Stories to consider:

* As a user concerned that content might be blocked by a country, I want all content to be freely distributed, such that I can view material that may be denied in my present location.

### 3. Integrity
 * Objects MUST be immutable to guarantee integrity
 * Objects MUST contain, and check for, a strong hash to demonstrate integrity


### 4. Common Good
 * Components MUST be open source
 * Components MUST have APIs where appropriate
 * There MUST NOT be any backdoors for any reason


## FAQs
 * Why is decentralization only listed in the availability section and not elsewhere?
   * While decentralization contributes to confidentiality, privacy, and integrity, to reduce duplication decentralization was placed in availability as it is a hard and fast requirement for this category.
 * I want to block objectionable and illegal material
   * Since objects are autonomous, they can be blocked.  However, blocking weakens the overall availability of the network. The default stance of this document is to permit all network traffic while allowing end users to block non-network objects. The author feels this is the best compromise between the two opposing viewpoints without violating the tenets.


## Compliance
If you develop a system, network, application, or component which respects the above tenets you are encourage to declare your compliance with this document.

## Contributing
Contributions to this document are welcomed. Together, we can build something usable worthwhile. See the CONTRIBUTING document in this repository.

### Contributors
 1. [Joey Stanford](https://github.com/rinchen) - Initial Author

## License
This work is licensed under the Creative Commons Attribution-ShareAlike 4.0 International License. To view a copy of this license, visit <http://creativecommons.org/licenses/by-sa/4.0/>.

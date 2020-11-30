# DIF DIDcomm WG – Rolling Agenda & Minutes

[![hackmd-github-sync-badge](https://hackmd.io/pUsOUZa8QHKJTSgf5O6HfQ/badge)](https://hackmd.io/pUsOUZa8QHKJTSgf5O6HfQ)



[**WG projects** ](https://github.com/decentralized-identity?q=wg-didcomm&type=&language=) | [ DIF page ](https://identity.foundation/working-groups/did-comm.html) | [Mailing list](https://lists.identity.foundation/g/didcomm-wg) | [**Old Meeting page**](https://docs.google.com/document/d/1BpTm5SmgfOJcEsXfizO0ZmH1r7imTJDGKudAZtYsm0M/edit)

_For this call, you are encouraged to turn your video on. This is a good way to build rapport given we are a large, disparate group experiencing a lot of churn._

_This document is live-edited DURING each call, and stable/authoritative copies live on our github repo under /agenda.md . 
Please note that we might not notice a pullrequest in time, but you are free to propose agenda items for future meetings via hackmd._

<details>
<summary> Meeting information </summary>

* Before your contribute - [**join DIF**](https://identity.foundation/join) and [sign the WG charter](https://bit.ly/DIF-WG-select1) (both are required!) 
* Time: Every Monday, 15:00-16:00 ET
* [Calendar entry](https://calendar.google.com/event?action=TEMPLATE&tmeid=dHVmZWYxaXBzY2ZnaWk1MGhqN2NsdjYxc21fMjAyMDExMDlUMjAwMDAwWiBkZWNlbnRyYWxpemVkLmlkZW50aXR5QG0&tmsrc=decentralized.identity%40gmail.com&scp=ALL)
* [Zoom room](https://us02web.zoom.us/j/81621403519?pwd=TXJqMWcvYjlQcjhJVzJ0b2FpSGU2UT09), Meeting ID: 816 2140 3519, Password: 049153
</details>

 

#### Future topics: 

<details>
<summary> Topics for upcoming meetings</summary>

* Sections that need work: 
    * Encryption section - should point to JWM
* Radar Reports / Assignments
redecentralize.org
* Contact/involve Stranger Labs folks about [offline credentials](https://etc.g2xchange.com/statics/news-release-dhs-awards-197k-for-digital-credentials-that-work-offline/)? Or at least check their documentation?
* Link between DIDComm Messaging and JWM
* Needed JWE improvements
    * https://www.npmjs.com/package/jose#plugins 
        * OKP X25519 curve keys ECDH-ES
        * aead_chacha20_poly1305 and aead_xchacha20_poly1305
    * xchacha
    * Authenticated encryption (e.g., https://tools.ietf.org/html/draft-madden-jose-ecdh-1pu-03)
    * Detached JWE payloads to optimize multi-layer messages. - avoid for now?



</details>

## Meeting - 30 Nov 2020 - (1500 ET)
 
### Attendees
- [Sam Curren](telegramsam@gmail.com) ()
 
### Agenda

- Welcome / Introductions
- Milestones
    - First Complete Draft - reads correctly from beginning to end Nov 30th.
    - Next Complete Draft - Eliminate all TODOs
- DIDComm.org Progress
    - Repo exists 
   https://github.com/decentralized-identity/didcomm.org
   - First content is present.
   - domain config?

- DID Use Cases
    - Original: https://github.com/w3c/did-use-cases/pull/100
    - Nader: https://github.com/w3c/did-use-cases/pull/122
    - Needs New PR.
    - Progress?
- PR/Issues: 
    - [127](https://github.com/decentralized-identity/didcomm-messaging/pull/127) - structured headers
    - [128](https://github.com/decentralized-identity/didcomm-messaging/pull/128) - to header semantics
    - [129](https://github.com/decentralized-identity/didcomm-messaging/pull/129) - post quantum
    - [126](https://github.com/decentralized-identity/didcomm-messaging/issues/126) - DIDDocs for Peer DIDs

- DIDComm Bootstrapping and Discovery Technique
    - [Social Profile Association Credential](https://hackmd.io/IZgDPFy6QiaZXbUk7Ik87Q?view)

### Proposals
-proposals here-




## Meeting - 23 Nov 2020 - (1500 ET)
 
### Agenda

- Welcome / Introductions
- Milestones
    - First Complete Draft - reads correctly from beginning to end Nov 30th.
    - Next Complete Draft - Eliminate all TODOs
- DIDComm.org Progress
    - Repo exists 
   https://github.com/decentralized-identity/didcomm.org
   - First content is present.
   - domain config?

- https://github.com/w3c/did-use-cases/pull/100
    - Needs New PR.
    - Progress?
- PR/Issues: 
    - [117](https://github.com/decentralized-identity/didcomm-messaging/pull/117) - forward secrecy
    - [124](https://github.com/decentralized-identity/didcomm-messaging/pull/124) - mime types
    - [127](https://github.com/decentralized-identity/didcomm-messaging/pull/127) - structured headers
    - [128](https://github.com/decentralized-identity/didcomm-messaging/pull/128) - to header semantics
    - [129](https://github.com/decentralized-identity/didcomm-messaging/pull/129) - post quantum
    - [126](https://github.com/decentralized-identity/didcomm-messaging/issues/126) - DIDDocs for Peer DIDs

- DIDComm Bootstrapping and Discovery Technique
    - [Social Profile Association Credential](https://hackmd.io/IZgDPFy6QiaZXbUk7Ik87Q?view)

### Proposals
-proposals here-

### Attendees
- [Sam Curren](telegramsam@gmail.com) ()
- [George Aristy](george.aristy@securekey.com) (SecureKey)
- [Ivan Temchenko](ivan@jolocom.com)(Jolocom)
- [Drummond Reed](drummond.reed@evernym.com) (Evernym)


## Meeting - 16 Nov 2020 - (1500 ET)
 
### Agenda

- Welcome / Introductions
- Milestones
    - First Complete Draft - reads correctly from beginning to end Nov 30th.
    - Next Complete Draft - Eliminate all TODOs
- DIDComm.org Progress
    - Repo exists 
    - https://github.com/decentralized-identity/didcomm.org
- Github/Hackmd agenda and notes?
    - Done!
- https://github.com/w3c/did-use-cases/pull/100
    - Needs New PR.
- DIDComm for binary protocols (gRPC) - Tomislav
    - https://github.com/trinsic-id/didcomm-extension-grpc
- PR/Issues: (not discussed, will happen online and next week as appropriate.)
    - [117](https://github.com/decentralized-identity/didcomm-messaging/pull/117) - forward secrecy
    - [124](https://github.com/decentralized-identity/didcomm-messaging/pull/124) - mime types
    - [127](https://github.com/decentralized-identity/didcomm-messaging/pull/127) - structured headers
    - 


### Proposals
-proposals here-

### Attendees
- [George Aristy](https://github.com/llorllale) (SecureKey) <george.aristy@securekey.com>
- [Oliver Terbu](https://github.com/awoie) (ConsenSys AG) <oliver.terbu@mesh.xyz>
- [Daniel Hardman](daniel.hardman@evernym.com)
- [Ivan Temchenko](ivan@jolocom.com)
- [Stephen Curran](swcurran@cloudcompass.ca) Cloud Compass Computing Inc.
- [Steve McCown](https://github.com/mccown) (Anonyome Labs) <smccown@anonyome.com>
- [Sam Curren](telegramsam@gmail.com) ()
- [Tobias Looker](tobias.looker@mattr.global)


## Prior Meeting Agendas
Prior meeting agendas were recorded in [this Google Doc](https://docs.google.com/document/d/1BpTm5SmgfOJcEsXfizO0ZmH1r7imTJDGKudAZtYsm0M/edit#).
# DIF DIDcomm WG – Rolling Agenda & Minutes

[![hackmd-github-sync-badge](https://hackmd.io/pUsOUZa8QHKJTSgf5O6HfQ/badge)](https://hackmd.io/pUsOUZa8QHKJTSgf5O6HfQ)



[**WG projects** ](https://github.com/decentralized-identity?q=wg-didcomm&type=&language=) | [ DIF page ](https://identity.foundation/working-groups/did-comm.html) | [Mailing list](https://lists.identity.foundation/g/didcomm-wg) | [**Old Meeting page**](https://docs.google.com/document/d/1BpTm5SmgfOJcEsXfizO0ZmH1r7imTJDGKudAZtYsm0M/edit) |
[Agenda Archive](https://github.com/decentralized-identity/didcomm/tree/main/agenda-archive)

_For this call, you are encouraged to turn your video on. This is a good way to build rapport given we are a large, disparate group experiencing a lot of churn._

_This document is live-edited DURING each call, and stable/authoritative copies live on our github repo under /agenda.md . 
Please note that we might not notice a pullrequest in time, but you are free to propose agenda items for future meetings via hackmd._

<details>
<summary> Meeting information </summary>

* Before your contribute - [**join DIF**](https://identity.foundation/join) and [sign the WG charter](https://bit.ly/DIF-WG-select1) (both are required!) 
* Time: Every Monday, 15:00-16:00 ET
* [Calendar entry](https://calendar.google.com/event?action=TEMPLATE&tmeid=dHVmZWYxaXBzY2ZnaWk1MGhqN2NsdjYxc21fMjAyMDExMDlUMjAwMDAwWiBkZWNlbnRyYWxpemVkLmlkZW50aXR5QG0&tmsrc=decentralized.identity%40gmail.com&scp=ALL)
* [Zoom room](https://us02web.zoom.us/j/81013549769?pwd=eDVBM0hONTAra0ZqSVBuazZRc1pxZz09), Meeting ID: 816 2140 3519, Password: 049153
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

Meeting Link: https://us02web.zoom.us/j/81013549769?pwd=eDVBM0hONTAra0ZqSVBuazZRc1pxZz09

http://whenisgood.net/d8dkhgi

## Meeting - 14 February 2022 - (1500 ET)
 
### Attendees
- [Sam Curren](sam@indicio.tech)
- [Steve McCown](smccown@anonyome.com)
- 

### Agenda

- Welcome / Introductions
- Announcements
    - DIF F2F (24 Feb) https://www.eventbrite.com/e/difcon-f2f-virtual-3-tickets-162786327287
    - [Call for session ideas](https://forms.gle/boKDY113GBDMvvbW6)
    - DIDComm UG?

  
- Discussion
    - NIST algos https://github.com/decentralized-identity/didcomm-messaging/issues/213#issuecomment-1032215470
    - ACKs https://github.com/decentralized-identity/didcomm-messaging/issues/147
  
- PRs
    - https://github.com/decentralized-identity/didcomm-messaging/pulls
    - 


- Issue Triage
    - [pending close](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aopen+is%3Aissue+label%3A%22pending+close%22)
    - [needs discussion](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aissue+is%3Aopen+label%3A%22needs+discussion%22)

- Tasks
    - [PR Needed Issues](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aissue+is%3Aopen+label%3A%22PR+Needed%22)

## Meeting - 07 February 2022 - (1500 ET)
 
### Attendees
- [Sam Curren](sam@indicio.tech)
- [Steve McCown](smccown@anonyome.com)
- [Gabe Cohen](gcohen@squareup.com)

### Agenda

- Welcome / Introductions
- Announcements
    - DIF F2F (24 Feb) https://www.eventbrite.com/e/difcon-f2f-virtual-3-tickets-162786327287
    - [Call for session ideas](https://forms.gle/boKDY113GBDMvvbW6)
    - Time Survey for new DIDComm Users Group: http://whenisgood.net/d8dkhgi

  
- Discussion
  
- PRs
    - https://github.com/decentralized-identity/didcomm-messaging/pulls
    - 


- Issue Triage
    - [pending close](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aopen+is%3Aissue+label%3A%22pending+close%22)
    - [needs discussion](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aissue+is%3Aopen+label%3A%22needs+discussion%22)

- Tasks
    - [PR Needed Issues](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aissue+is%3Aopen+label%3A%22PR+Needed%22)

## Meeting - 31 January 2022 - (1500 ET)
 
### Attendees
- [Sam Curren](sam@indicio.tech)
- [Steve McCown](smccown@anonyome.com)
- [Chris Kelly](chris@identity.foundation)

### Agenda

- Welcome / Introductions
- Announcements
    - DIF F2F (24 Feb) https://www.eventbrite.com/e/difcon-f2f-virtual-3-tickets-162786327287
    - [Call for session ideas](https://forms.gle/boKDY113GBDMvvbW6)
    - Time Survey for new DIDComm Users Group: http://whenisgood.net/d8dkhgi

  
- Discussion
  
- PRs
    - https://github.com/decentralized-identity/didcomm-messaging/pulls
    - 


- Issue Triage
    - [pending close](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aopen+is%3Aissue+label%3A%22pending+close%22)
    - [needs discussion](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aissue+is%3Aopen+label%3A%22needs+discussion%22)

- Tasks
    - [PR Needed Issues](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aissue+is%3Aopen+label%3A%22PR+Needed%22)

## Meeting - 24 January 2022 - (1500 ET)
 
### Attendees
- [Sam Curren](sam@indicio.tech)
- [Drummond Reed](drummond.reed@evernym.com)
- [Steve McCown](smccown@anonyome.com)
- [Chris Kelly](chris@identity.foundation)

### Agenda

- Welcome / Introductions
- Announcements
    - DIF F2F (24 Feb) https://www.eventbrite.com/e/difcon-f2f-virtual-3-tickets-162786327287
    - Call for content - https://docs.google.com/forms/d/1pwVEaITW1ehEjTVLTYo3DDBAgawW3zJtRsUT0MRKt3Y/ed
    - Time Survey for new DIDComm Users Group: http://whenisgood.net/d8dkhgi


  
- Discussion
    - TOIP Papers
        - https://trustoverip.org/permalink/Introduction-to-ToIP-V2.0-2021-11-17.pdf
        - https://trustoverip.org/permalink/Design-Principles-for-the-ToIP-Stack-V1.0-2022-11-17.pdf

  
- PRs
    - https://github.com/decentralized-identity/didcomm-messaging/pulls
    - 


- Issue Triage
    - [pending close](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aopen+is%3Aissue+label%3A%22pending+close%22)
    - [needs discussion](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aissue+is%3Aopen+label%3A%22needs+discussion%22)

- Tasks
    - [PR Needed Issues](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aissue+is%3Aopen+label%3A%22PR+Needed%22)

## Meeting - 17 January 2022 - (1500 ET)
 
### Attendees
- [Sam Curren](sam@indicio.tech)
- 

### Agenda

- Welcome / Introductions
  
- Discussion
  
- PRs
    - https://github.com/decentralized-identity/didcomm-messaging/pulls
    - 


- Issue Triage
    - [pending close](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aopen+is%3Aissue+label%3A%22pending+close%22)
    - [needs discussion](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aissue+is%3Aopen+label%3A%22needs+discussion%22)

- Tasks
    - [PR Needed Issues](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aissue+is%3Aopen+label%3A%22PR+Needed%22)


## Meeting - 10 January 2022 - (1500 ET)
 
### Attendees
- [Sam Curren](sam@indicio.tech)
- [Steve McCown](smccown@anonyome.com)
- [Tomislav Markovski](tomislav@trinsic.id)
- 

### Agenda

- Welcome / Introductions
  
- Discussion
  
- PRs
    - https://github.com/decentralized-identity/didcomm-messaging/pulls
    - 


- Issue Triage
    - [pending close](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aopen+is%3Aissue+label%3A%22pending+close%22)
    - [needs discussion](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aissue+is%3Aopen+label%3A%22needs+discussion%22)

- Tasks
    - [PR Needed Issues](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aissue+is%3Aopen+label%3A%22PR+Needed%22)


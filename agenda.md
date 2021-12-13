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


### Notice: Next Meeting is 10 January 2022

## Meeting - 13 December 2021 - (1500 ET)
 
### Attendees
- [Sam Curren](sam@indicio.tech)
- [Steve McCown](smccown@anonyome.com)
- [Chris Kelly](chris@identity.foundation)
- Andrew Whitehead

### Agenda

- Welcome / Introductions

- CoChair - Oficially Steve.

- Holiday meeting canceled: Dec 20, 27, and Jan 3
  
- Discussion
    
  
- PRs
    - https://github.com/decentralized-identity/didcomm-messaging/pulls
    - https://github.com/decentralized-identity/didcomm-messaging/pull/316 - OOB Fix


- Issue Triage
    - [pending close](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aopen+is%3Aissue+label%3A%22pending+close%22)
    - [needs discussion](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aissue+is%3Aopen+label%3A%22needs+discussion%22)

- Tasks
    - [PR Needed Issues](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aissue+is%3Aopen+label%3A%22PR+Needed%22)


## Meeting - 6 December 2021 - (1500 ET)
 
### Attendees
- [Sam Curren](sam@indicio.tech)
- [Steve McCown](smccown@anonyome.com)
- [Chris Kelly](chris@identity.foundation)
- [Drummond Reed](drummond.reed@evernym.com)
- 

### Agenda

- Welcome / Introductions

- CoChair

- DIDComm User Group
    - Discord: (coming soon)
    - No objection from the TSC
    - Announcement soon - schedule discovery
    - Get signed up via the announcement.

- Holiday meeting canceled: Dec 20, 27, and Jan 3
  
- Discussion
    - DIDComm-js Repo Archive
        - https://github.com/decentralized-identity/DIDComm-js
    - DIDComm & Hub Discussion
        Scope and Organization
        - Horton video: https://www.youtube.com/watch?v=NAfjEnu6R2g
        - https://www.usenix.org/legacy/event/hotsec07/tech/full_papers/miller/miller.pdf

  
- PRs
    - https://github.com/decentralized-identity/didcomm-messaging/pulls
    - [313](https://github.com/decentralized-identity/didcomm-messaging/pull/313) - Discover Features v2 
    - [314](https://github.com/decentralized-identity/didcomm-messaging/pull/314) - From in OOB. 
    - typ in wrong places? (Sam)

- Issue Triage
    - [pending close](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aopen+is%3Aissue+label%3A%22pending+close%22)
    - [needs discussion](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aissue+is%3Aopen+label%3A%22needs+discussion%22)

- Tasks
    - [PR Needed Issues](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aissue+is%3Aopen+label%3A%22PR+Needed%22)



## Meeting - 29 November 2021 - (1500 ET)
 
### Attendees
- [Sam Curren](sam@indicio.tech)
- 
- 

### Agenda

- Welcome / Introductions

- Status Updates
  * Room for a WG Chair here in the spec WG.
  * DIDComm UG on Discord: https://discord.gg/byAmu6TY
  * Potential DIDComm Users Group
      * Proposal sent to Steering Committee
  
- PRs
    - https://github.com/decentralized-identity/didcomm-messaging/pulls
    - [313](https://github.com/decentralized-identity/didcomm-messaging/pull/313) - Discover Features v2 
    - [314](https://github.com/decentralized-identity/didcomm-messaging/pull/314) - From in OOB. 
    - typ in wrong places? (Sam)

- Issue Triage
    - [pending close](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aopen+is%3Aissue+label%3A%22pending+close%22)
    - [needs discussion](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aissue+is%3Aopen+label%3A%22needs+discussion%22)

- Tasks
    - [PR Needed Issues](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aissue+is%3Aopen+label%3A%22PR+Needed%22)


## Meeting - 22 November 2021 - (1500 ET)
 
### Attendees
- [Sam Curren](sam@indicio.tech)
- 
- 

### Agenda

- Welcome / Introductions

- Status Updates
  * DIDComm UG on Discord: https://discord.gg/byAmu6TY
  * Potential DIDComm Users Group
      * Proposal sent to Steering Committee
  
- PRs
    - https://github.com/decentralized-identity/didcomm-messaging/pulls
    - [312](https://github.com/decentralized-identity/didcomm-messaging/pull/312) - OOB web redirect 
    - [313](https://github.com/decentralized-identity/didcomm-messaging/pull/313) - Discover Features v2 
    - typ in wrong places? (Sam)

- Issue Triage
    - [pending close](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aopen+is%3Aissue+label%3A%22pending+close%22)
    - [needs discussion](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aissue+is%3Aopen+label%3A%22needs+discussion%22)

- Tasks
    - [PR Needed Issues](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aissue+is%3Aopen+label%3A%22PR+Needed%22)


## Meeting - 15 November 2021 - (1500 ET)
 
### Attendees
- [Sam Curren](sam@indicio.tech)
- [Drummond Reed](drummond.reed@evernym.com)
- 

### Agenda

- Welcome / Introductions

- Status Updates

  * Sharable video from Daniel Hardman about the potential of DIDComm: https://www.youtube.com/watch?v=ovhSWg_E_54
  * Potential DIDComm Users Group
      * Proposal sent to Steering Committee
  
- PRs
    - https://github.com/decentralized-identity/didcomm-messaging/pulls
    - [312](https://github.com/decentralized-identity/didcomm-messaging/pull/312) - OOB web redirect 
    - [313](https://github.com/decentralized-identity/didcomm-messaging/pull/313) - Discover Features v2 

- Issue Triage
    - [pending close](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aopen+is%3Aissue+label%3A%22pending+close%22)
    - [needs discussion](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aissue+is%3Aopen+label%3A%22needs+discussion%22)

- Tasks
    - [PR Needed Issues](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aissue+is%3Aopen+label%3A%22PR+Needed%22)


## Meeting - 8 November 2021 - (1500 ET)
 
### Attendees
- [Sam Curren](sam@indicio.tech)
- [Steve McCown](smccown@anonyome.com)

### Agenda

- Welcome / Introductions

- Status Updates

  * Potential DIDComm Users Group
      * Proposal sent to Steering Committee
  
- PRs
    - https://github.com/decentralized-identity/didcomm-messaging/pulls

- Issue Triage
    - [pending close](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aopen+is%3Aissue+label%3A%22pending+close%22)
    - [needs discussion](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aissue+is%3Aopen+label%3A%22needs+discussion%22)

- Tasks
    - [PR Needed Issues](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aissue+is%3Aopen+label%3A%22PR+Needed%22)

## Meeting - 1 November 2021 - (1500 ET)
 
### Attendees
- [Sam Curren](sam@indicio.tech)
- 

### Agenda

- Welcome / Introductions

- Status Updates

  * Potential DIDComm Users Group
      * Proposal sent to Steering Committee
  
- PRs
    - https://github.com/decentralized-identity/didcomm-messaging/pulls

- Issue Triage
    - [pending close](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aopen+is%3Aissue+label%3A%22pending+close%22)
    - [needs discussion](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aissue+is%3Aopen+label%3A%22needs+discussion%22)

- Tasks
    - [PR Needed Issues](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aissue+is%3Aopen+label%3A%22PR+Needed%22)



## Meeting - 25 October 2021 - (1500 ET)
 
### Attendees
- [Sam Curren](telegramsam@gmail.com)
- [Steve McCown](smccown@anonyome.com)
- [Brian Richter](brian@aviary.tech)

### Agenda

- Welcome / Introductions

- Status Updates

  * Potential DIDComm Users Group
  * https://hackmd.io/UTIirjBXTSCDwhbfDK5CUQ
  
- PRs
    - https://github.com/decentralized-identity/didcomm-messaging/pulls



- Issue Triage
    - [pending close](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aopen+is%3Aissue+label%3A%22pending+close%22)
    - [needs discussion](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aissue+is%3Aopen+label%3A%22needs+discussion%22)

- Tasks
    - [PR Needed Issues](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aissue+is%3Aopen+label%3A%22PR+Needed%22)



## Meeting - 18 October 2021 - (1500 ET)
 
### Attendees
- [Sam Curren](telegramsam@gmail.com)
- [Drummond Reed](drummond.reed@evernym.com)
- [Kyle Den Hartog](kyle.denhartog@mattr.global)
- [Steve McCown](smccown@anonyome.com)

### Agenda

- Welcome / Introductions

- Status Updates

  * Potential DIDComm Users Group

  * IIW Sessions Review
      * Tour of DIDComm Libraries - Alex & Slava
      * DIDComm Mythconceptions - Daniel
      * Future of DIDComm -> IETF Movement (didn't happen)
      * DIDComm Protocols - Sam
      * Moving medical data over DIDComm - community member
      * P2PLib & DIDComm - Oliver 
  
- Sam mentioned that DIDComm V3 could specify how to start a "cryptographic" session that could be synchronous and very efficient.

- There is a general sense that the next version of DIDComm will be at IETF. But DIF can still remain the home of the DIDComm User's Group. The User's Group can become the focus for implementation help, maintain didcomm.org, and work on the Implementer's Guide. 

- PRs
    - https://github.com/decentralized-identity/didcomm-messaging/pulls



- Issue Triage
    - [pending close](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aopen+is%3Aissue+label%3A%22pending+close%22)
    - [needs discussion](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aissue+is%3Aopen+label%3A%22needs+discussion%22)

- Tasks
    - [PR Needed Issues](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aissue+is%3Aopen+label%3A%22PR+Needed%22)



## Meeting - 4 October 2021 - (1500 ET)
 
### Attendees
- [Sam Curren](telegramsam@gmail.com)
- [Oliver Terbu](oliver.terbu@mesh.xyz)
- 



### Agenda

- Welcome / Introductions

- Status Updates

  * Potential DIDComm Users Group

  * IIW Sessions
      * Tour of DIDComm Libraries - Alex & Slava
      * DIDComm Mythconceptions - Daniel
      * Future of DIDComm -> IETF Movement
      * DIDComm Protocols - Sam
  

- PRs
    - https://github.com/decentralized-identity/didcomm-messaging/pulls



- Issue Triage
    - [pending close](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aopen+is%3Aissue+label%3A%22pending+close%22)
    - [needs discussion](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aissue+is%3Aopen+label%3A%22needs+discussion%22)

- Tasks
    - [PR Needed Issues](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aissue+is%3Aopen+label%3A%22PR+Needed%22)


## Meeting - 4 October 2021 - (1500 ET)
 
### Attendees
- [Sam Curren](telegramsam@gmail.com)
- [Oliver Terbu](oliver.terbu@mesh.xyz)



### Agenda

- Welcome / Introductions

- Status Updates


  * IIW Sessions
      * Tour of DIDComm Libraries - Alex & Slava
      * DIDComm and how it relates to other tech - Daniel
      * Future of DIDComm -> IETF Movement
      * DIDComm Protocols - Sam
  
  * didcomm.org update -> can be already used to register new protocols
      * https://github.com/decentralized-identity/didcomm.org/pulls



- Contributor List
    - Need proper recoginition
    - Call for author PRs by authors

- PRs
    - 

- Key Negotiation
    - [238](https://github.com/decentralized-identity/didcomm-messaging/issues/238) - Multiple keys of different types and Keys negotiation (by  ashcherbakov)
    - [218](https://github.com/decentralized-identity/didcomm-messaging/issues/218) - Need info about multiple recipients (by Daniel H.) Already PR Needed?

- Other Discussion Topics
    - [220](https://github.com/decentralized-identity/didcomm-messaging/issues/220) - Differentiating different forms of DIDComm messages (by Kyle)
    - [138](https://github.com/decentralized-identity/didcomm-messaging/issues/138) - foundation / core protocols (by Daniel H.)
    - [250](https://github.com/decentralized-identity/didcomm-messaging/issues/250) - combining OOB and feature discovery (by Kyle)

- Issue Triage
    - [pending close](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aopen+is%3Aissue+label%3A%22pending+close%22)
    - [needs discussion](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aissue+is%3Aopen+label%3A%22needs+discussion%22)

- Tasks
    - [PR Needed Issues](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aissue+is%3Aopen+label%3A%22PR+Needed%22)


## Meeting - 27 September 2021 - (1500 ET)
 
### Attendees
- [Sam Curren](telegramsam@gmail.com)
- [Oliver Terbu](oliver.terbu@mesh.xyz)
- [Daniel Hardman](daniel.hardman@sicpa.com)
- [Steve McCown](smccown@anonyome.com)
- [Drummond Reed](drummond.reed@evernym.com)


### Agenda

- Welcome / Introductions

- Status Updates


  * Volunteers for blog post ECDH-1PU - Done! Followup?

  * IIW Sessions
      * Tour of DIDComm Libraries - Alex & Slava
      * DIDComm and how it relates to other tech - Daniel
      * Future of DIDComm -> IETF Movement
      * DIDComm Protocols - Sam
  
  * didcomm.org update -> can be already used to register new protocols
      * https://github.com/decentralized-identity/didcomm.org/pullsZAZ



- Contributor List
    - Need proper recoginition
    - Call for author PRs by authors

- PRs
    - [267](https://github.com/decentralized-identity/didcomm-messaging/pull/267) - ECDH-1PU article -> in progress, Chris to reach out to Daniel
    - [277](https://github.com/decentralized-identity/didcomm-messaging/pull/277) - Clarifies purpose of to attribute -> ok to merge but conflicts
    - [275](https://github.com/decentralized-identity/didcomm-messaging/pull/275) - body attribute required -> agreed to merge, but merge conflicts need to resolved
    - [274](https://github.com/decentralized-identity/didcomm-messaging/pull/274) - Make from required -> agreed to merge, but merge conflicts need to resolved
    - [270](https://github.com/decentralized-identity/didcomm-messaging/pull/270) - update the number of recipients keys in a JWE envelope -> merged
    - [272](https://github.com/decentralized-identity/didcomm-messaging/pull/272) - Update trustping.md
    - [268](https://github.com/decentralized-identity/didcomm-messaging/pull/268) - serviceendpoint no url or object

- Key Negotiation
    - [238](https://github.com/decentralized-identity/didcomm-messaging/issues/238) - Multiple keys of different types and Keys negotiation (by  ashcherbakov)
    - [218](https://github.com/decentralized-identity/didcomm-messaging/issues/218) - Need info about multiple recipients (by Daniel H.) Already PR Needed?

- Other Discussion Topics
    - [220](https://github.com/decentralized-identity/didcomm-messaging/issues/220) - Differentiating different forms of DIDComm messages (by Kyle)
    - [138](https://github.com/decentralized-identity/didcomm-messaging/issues/138) - foundation / core protocols (by Daniel H.)
    - [250](https://github.com/decentralized-identity/didcomm-messaging/issues/250) - combining OOB and feature discovery (by Kyle)

- Issue Triage
    - [pending close](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aopen+is%3Aissue+label%3A%22pending+close%22)
    - [needs discussion](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aissue+is%3Aopen+label%3A%22needs+discussion%22)

- Tasks
    - [PR Needed Issues](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aissue+is%3Aopen+label%3A%22PR+Needed%22)



## Meeting - 20 September 2021 - (1500 ET)
 
### Attendees
- [Sam Curren](telegramsam@gmail.com)
- 


### Agenda

- Welcome / Introductions

- Status Updates


  * Volunteers for blog post ECDH-1PU (posted on nimbus blog) -> Baha (lead), Oliver, Chris (editorial). Timeframe: 2-3 weeks
  
  * didcomm.org update -> can be already used to register new protocols
      * https://github.com/decentralized-identity/didcomm.org/pullsZAZ

- Contributor List
    - Need proper recoginition
    - Call for author PRs by authors

- PRs
    - on GitHub
    -

- Key Negotiation
    - [238](https://github.com/decentralized-identity/didcomm-messaging/issues/238) - Multiple keys of different types and Keys negotiation (by  ashcherbakov)
    - [218](https://github.com/decentralized-identity/didcomm-messaging/issues/218) - Need info about multiple recipients (by Daniel H.) Already PR Needed?

- Other Discussion Topics
    - [220](https://github.com/decentralized-identity/didcomm-messaging/issues/220) - Differentiating different forms of DIDComm messages (by Kyle)
    - [138](https://github.com/decentralized-identity/didcomm-messaging/issues/138) - foundation / core protocols (by Daniel H.)
    - [250](https://github.com/decentralized-identity/didcomm-messaging/issues/250) - combining OOB and feature discovery (by Kyle)

- Issue Triage
    - [pending close](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aopen+is%3Aissue+label%3A%22pending+close%22)
    - [needs discussion](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aissue+is%3Aopen+label%3A%22needs+discussion%22)

- Tasks
    - [PR Needed Issues](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aissue+is%3Aopen+label%3A%22PR+Needed%22)


## Meeting - 13 September 2021 - (1500 ET)
 
### Attendees
- [Sam Curren](sam@indicio.tech)
- 


### Agenda

- Welcome / Introductions

- Status Updates


  * Volunteers for blog post ECDH-1PU (posted on nimbus blog) -> Baha (lead), Oliver, Chris (editorial). Timeframe: 2-3 weeks
  
  * didcomm.org update -> can be already used to register new protocols

- Contributor List
    - Need proper recoginition
    - Call for author PRs by authors

- PRs
    - [267](https://github.com/decentralized-identity/didcomm-messaging/pull/267) - ECDH-1PU article -> in progress, Chris to reach out to Daniel
    - [277](https://github.com/decentralized-identity/didcomm-messaging/pull/277) - Clarifies purpose of to attribute -> ok to merge but conflicts
    - [275](https://github.com/decentralized-identity/didcomm-messaging/pull/275) - body attribute required -> agreed to merge, but merge conflicts need to resolved
    - [274](https://github.com/decentralized-identity/didcomm-messaging/pull/274) - Make from required -> agreed to merge, but merge conflicts need to resolved
    - [270](https://github.com/decentralized-identity/didcomm-messaging/pull/270) - update the number of recipients keys in a JWE envelope -> merged
    - [272](https://github.com/decentralized-identity/didcomm-messaging/pull/272) - Update trustping.md
    - [268](https://github.com/decentralized-identity/didcomm-messaging/pull/268) - serviceendpoint no url or object

- Key Negotiation
    - [238](https://github.com/decentralized-identity/didcomm-messaging/issues/238) - Multiple keys of different types and Keys negotiation (by  ashcherbakov)
    - [218](https://github.com/decentralized-identity/didcomm-messaging/issues/218) - Need info about multiple recipients (by Daniel H.) Already PR Needed?

- Other Discussion Topics
    - [220](https://github.com/decentralized-identity/didcomm-messaging/issues/220) - Differentiating different forms of DIDComm messages (by Kyle)
    - [138](https://github.com/decentralized-identity/didcomm-messaging/issues/138) - foundation / core protocols (by Daniel H.)
    - [250](https://github.com/decentralized-identity/didcomm-messaging/issues/250) - combining OOB and feature discovery (by Kyle)

- Issue Triage
    - [pending close](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aopen+is%3Aissue+label%3A%22pending+close%22)
    - [needs discussion](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aissue+is%3Aopen+label%3A%22needs+discussion%22)

- Tasks
    - [PR Needed Issues](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aissue+is%3Aopen+label%3A%22PR+Needed%22)

## Meeting - 6 September 2021 - (1500 ET)
 
### Attendees
- [Oliver Terbu](oliver.terbu@mesh.xyz)


### Agenda

- Welcome / Introductions

- Status Updates
  * Adrian (Main Incubator) wants to contribute BLE to DIF in the Name of IDunion.
      * In process (working with Balazs)

  * Volunteers for blog post ECDH-1PU (posted on nimbus blog) -> Baha (lead), Oliver, Chris (editorial). Timeframe: 2-3 weeks
  
  * didcomm.org update -> can be already used to register new protocols

- Contributor List
    - Need proper recoginition
    - Call for author PRs by authors

- PRs
    - [259](https://github.com/decentralized-identity/didcomm-messaging/pull/259) - removed processing model -> merged
    - [260](https://github.com/decentralized-identity/didcomm-messaging/pull/260) - from_prior now MUST -> merged
    - [267](https://github.com/decentralized-identity/didcomm-messaging/pull/267) - ECDH-1PU article -> in progress, Chris to reach out to Daniel
    - [277](https://github.com/decentralized-identity/didcomm-messaging/pull/277) - Clarifies purpose of to attribute -> ok to merge but conflicts
    - [276](https://github.com/decentralized-identity/didcomm-messaging/pull/276) - minor DID alternative endpoints clarifications -> merged
    - [275](https://github.com/decentralized-identity/didcomm-messaging/pull/275) - body attribute required -> agreed to merge, but merge conflicts need to resolved
    - [274](https://github.com/decentralized-identity/didcomm-messaging/pull/274) - Make from required -> agreed to merge, but merge conflicts need to resolved
    - [270](https://github.com/decentralized-identity/didcomm-messaging/pull/270) - update the number of recipients keys in a JWE envelope -> merged
    - [272](https://github.com/decentralized-identity/didcomm-messaging/pull/272) - Update trustping.md
    - [268](https://github.com/decentralized-identity/didcomm-messaging/pull/268) - serviceendpoint no url or object

- Key Negotiation
    - [238](https://github.com/decentralized-identity/didcomm-messaging/issues/238) - Multiple keys of different types and Keys negotiation (by  ashcherbakov)
    - [218](https://github.com/decentralized-identity/didcomm-messaging/issues/218) - Need info about multiple recipients (by Daniel H.) Already PR Needed?

- Other Discussion Topics
    - [220](https://github.com/decentralized-identity/didcomm-messaging/issues/220) - Differentiating different forms of DIDComm messages (by Kyle)
    - [138](https://github.com/decentralized-identity/didcomm-messaging/issues/138) - foundation / core protocols (by Daniel H.)
    - [250](https://github.com/decentralized-identity/didcomm-messaging/issues/250) - combining OOB and feature discovery (by Kyle)

- Issue Triage
    - [pending close](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aopen+is%3Aissue+label%3A%22pending+close%22)
    - [needs discussion](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aissue+is%3Aopen+label%3A%22needs+discussion%22)

- Tasks
    - [PR Needed Issues](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aissue+is%3Aopen+label%3A%22PR+Needed%22)

## Meeting - 30 August 2021 - (1500 ET)
 
### Attendees
- [Sam Curren](sam@indicio.tech)
- [Oliver Terbu](oliver.terbu@mesh.xyz)


### Agenda

- Welcome / Introductions

- Status Updates
  * Adrian (Main Incubator) wants to contribute BLE to DIF in the Name of IDunion.
      * In process (working with Balazs)

  * Volunteers for blog post ECDH-1PU (posted on nimbus blog) -> Baha (lead), Oliver, Chris (editorial). Timeframe: 2-3 weeks.
- Progress Check
    - 2 Months left
    - How are we doing?
    - Feature Freeze?
- Contributor List
    - Need proper recoginition
    - Call for author PRs by authors

- PRs
    - DIDComm.org [PR 6](https://github.com/decentralized-identity/didcomm.org/pull/6)
    - [258](https://github.com/decentralized-identity/didcomm-messaging/pull/258) - editorial
    - [259](https://github.com/decentralized-identity/didcomm-messaging/pull/259) - removed processing model
    - [260](https://github.com/decentralized-identity/didcomm-messaging/pull/260) - from_prior now MUST
    - [267](https://github.com/decentralized-identity/didcomm-messaging/pull/267) - ECDH-1PU article
    - [268](https://github.com/decentralized-identity/didcomm-messaging/pull/268) - serviceendpoint no url or object

- Protecting Sender
    - [219](https://github.com/decentralized-identity/didcomm-messaging/issues/219) - Need more details about protected skid



- Key Negotiation
    - [238](https://github.com/decentralized-identity/didcomm-messaging/issues/238) - Multiple keys of different types and Keys negotiation (by  ashcherbakov)
    - [218](https://github.com/decentralized-identity/didcomm-messaging/issues/218) - Need info about multiple recipients (by Daniel H.) Already PR Needed?

- Other Discussion Topics
    - [220](https://github.com/decentralized-identity/didcomm-messaging/issues/220) - Differentiating different forms of DIDComm messages (by Kyle)
    - [138](https://github.com/decentralized-identity/didcomm-messaging/issues/138) - foundation / core protocols (by Daniel H.)
    - [250](https://github.com/decentralized-identity/didcomm-messaging/issues/250) - combining OOB and feature discovery (by Kyle)

- Issue Triage
    - [pending close](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aopen+is%3Aissue+label%3A%22pending+close%22)
    - [needs discussion](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aissue+is%3Aopen+label%3A%22needs+discussion%22)

- Tasks
    - [PR Needed Issues](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aissue+is%3Aopen+label%3A%22PR+Needed%22)

## Meeting - 23 August 2021 - (1500 ET)
 
### Attendees
- [Oliver Terbu](oliver.terbu@mesh.xyz) ()
- [Adrian Doerk](adrian.doerk@main-incubator.com)
- [Chris Kelly](chris@identity.foundation)
- [Daniel Hardman](daniel.hardman@sicpa.com)
- [Troy Ronda](troy.ronda@securekey.com)

### Agenda

- Welcome / Introductions

- Status Updates
  * Adrian (Main Incubator) wants to contribute BLE to DIF in the Name of IDunion.
  * Daniel H. on ECDH-1PU contribution
      * nimbus (JAVA) -> done
      * authlib (Python) -> done
      * no TypeScript/JavaScript -> but can be done through Rust (WASM)
      * Volunteers for blog post ECDH-1PU (posted on nimbus blog) -> Baha (lead), Oliver, Chris (editorial). Timeframe: 2-3 weeks.

- PRs

- Protecting Sender
    - [197](https://github.com/decentralized-identity/didcomm-messaging/issues/197) - 
Do we need to Encrypt the Sender?
    - [219](https://github.com/decentralized-identity/didcomm-messaging/issues/219) - Need more details about protected skid
    - [191](https://github.com/decentralized-identity/didcomm-messaging/issues/191) - 
SKID: Value or Reference?

- Routing
    - [210](https://github.com/decentralized-identity/didcomm-messaging/issues/210) - Questions and comments re routing/forward (by Oliver)

- Key Negotiation
    - [238](https://github.com/decentralized-identity/didcomm-messaging/issues/238) - Multiple keys of different types and Keys negotiation (by  ashcherbakov)
    - [218](https://github.com/decentralized-identity/didcomm-messaging/issues/218) - Need info about multiple recipients (by Daniel H.)

- Other Discussion Topics
    - [220](https://github.com/decentralized-identity/didcomm-messaging/issues/220) - Differentiating different forms of DIDComm messages (by Kyle)
    - [138](https://github.com/decentralized-identity/didcomm-messaging/issues/138) - foundation / core protocols (by Daniel H.)
    - [250](https://github.com/decentralized-identity/didcomm-messaging/issues/250) - combining OOB and feature discovery (by Kyle)

- Issue Triage
    - [pending close](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aopen+is%3Aissue+label%3A%22pending+close%22)
    - [needs discussion](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aissue+is%3Aopen+label%3A%22needs+discussion%22)

- Tasks
    - [PR Needed Issues](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aissue+is%3Aopen+label%3A%22PR+Needed%22)

Meeting Link: https://us02web.zoom.us/j/81013549769?pwd=eDVBM0hONTAra0ZqSVBuazZRc1pxZz09

## Meeting - 16 August 2021 - (1500 ET)
 
### Attendees
- [Sam Curren](telegramsam@gmail.com) ()
- 


### Agenda

- Welcome / Introductions

- Status Updates
    - PR against authlib in python for ECDH-1PU support
    - similar for Nimbus library in Java
    - rust underway, will provide wasm base for js, and switft via wrapper
    - builder style apis in the works, language ideomadic
    - didcomm.org work
    - video update: https://cloud.dsr-corporation.com/index.php/s/C9f28oorbP5CjtH


- Key Negotiation

- PRs


- Discussion Topics
    - [138](https://github.com/decentralized-identity/didcomm-messaging/issues/138) - foundation / core protocols
    - [250](https://github.com/decentralized-identity/didcomm-messaging/issues/250) - combining OOB and feature discovery
    - [220](https://github.com/decentralized-identity/didcomm-messaging/issues/220) - related and wandering
    - 
    - Issue Triage
        - [pending close](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aopen+is%3Aissue+label%3A%22pending+close%22)
        - [needs discussion](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aissue+is%3Aopen+label%3A%22needs+discussion%22)


- Tasks
    - [PR Needed Issues](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aissue+is%3Aopen+label%3A%22PR+Needed%22)



- Next Week

## Meeting - 09 August 2021 - (1500 ET)
 
### Attendees
- [Sam Curren](telegramsam@gmail.com) ()
- 


### Agenda

- Welcome / Introductions

- PRs
    - [246](https://github.com/decentralized-identity/didcomm-messaging/pull/246) - clarify that rewrapping means reencryption


- Discussion Topics
    - [138](https://github.com/decentralized-identity/didcomm-messaging/issues/138) - foundation / core protocols
    - [250](https://github.com/decentralized-identity/didcomm-messaging/issues/250) - combining OOB and feature discovery
    - [220](https://github.com/decentralized-identity/didcomm-messaging/issues/220) - related and wandering
    - 
    - Issue Triage
        - [pending close](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aopen+is%3Aissue+label%3A%22pending+close%22)
        - [needs discussion](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aissue+is%3Aopen+label%3A%22needs+discussion%22)
        - pr needed


- Tasks
    - [PR Needed Issues](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aissue+is%3Aopen+label%3A%22PR+Needed%22)



- Next Week



## Meeting - 02 August 2021 - (1500 ET)
 
### Attendees
- [Sam Curren](telegramsam@gmail.com) ()
- 


### Agenda

- Welcome / Introductions

- PRs

    - [244](https://github.com/decentralized-identity/didcomm-messaging/pull/244) - CBOR commentary
    - [240](https://github.com/decentralized-identity/didcomm-messaging/pull/240) - attachments
    - [235](https://github.com/decentralized-identity/didcomm-messaging/pull/235) - i18n

- Discussion Topics
    - Issue Triage
        - [pending close](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aopen+is%3Aissue+label%3A%22pending+close%22)
        - [needs discussion](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aissue+is%3Aopen+label%3A%22needs+discussion%22)
        - pr needed


- Tasks
    - [PR Needed Issues](https://github.com/decentralized-identity/didcomm-messaging/issues?q=is%3Aissue+is%3Aopen+label%3A%22PR+Needed%22)



- Next Week



## Meeting - 26 July 2021 - (1500 ET)
 
### Attendees
- [Sam Curren](telegramsam@gmail.com) ()
- [Steve McCown](smccown@anonyome.com) (Anonyome Labs)


### Agenda

- Welcome / Introductions

- PRs

    - [227](https://github.com/decentralized-identity/didcomm-messaging/pull/227) - sender key protection
    - [232](https://github.com/decentralized-identity/didcomm-messaging/pull/232) - error section
    - [235](https://github.com/decentralized-identity/didcomm-messaging/pull/235) - i18n

- Discussion Topics
    - Language Investigation
        - Python JOSE: https://hackmd.io/qJhPmgM3RIOy1D_evwjQHg
        - Java/Kotlin JOSE: https://hackmd.io/@FCN75Uk9TCqMmxSE6vEn5A/rkhCBUP0O
        - JS/TS JOSE: https://hackmd.io/@IyhpRay4QVC_ozugDsQAQg/S1QlYJN0d
    - Issue Triage
        - pending close
        - needs discussion
        - pr needed


- Tasks
    - ...



- Next Week



## Meeting - 19 July 2021 - (1500 ET)
 
### Attendees
- [Sam Curren](telegramsam@gmail.com) ()


### Agenda

- Welcome / Introductions

- PRs

    - [225](https://github.com/decentralized-identity/didcomm-messaging/pull/225) - thid and pthid
    - [227](https://github.com/decentralized-identity/didcomm-messaging/pull/227) - sender key protection
    - 230-235 Daniel PRs

- Discussion Topics
    - Issue Triage
        - pending close
        - needs discussion
        - pr needed


- Tasks
    - ...



- Next Week



## Meeting - 12 July 2021 - (1500 ET)
 
### Attendees
- [Sam Curren](telegramsam@gmail.com) ()
- [Baha A Shaaban](baha.shaaban@securekey.com) (SecureKey)



### Agenda

- Welcome / Introductions

- PRs
    - [198](https://github.com/decentralized-identity/didcomm-messaging/pull/198) - typ/cty language
    - [209](https://github.com/decentralized-identity/didcomm-messaging/pull/209) - sequencing extension
    - [212](https://github.com/decentralized-identity/didcomm-messaging/pull/212) - ECDH 1PU Draft 4
    - [225](https://github.com/decentralized-identity/didcomm-messaging/pull/225) - thid and pthid

- Discussion Topics
    - SICPA Support
        - Tracking Repo: https://github.com/sicpa-dlab/didcomm-gemini
    - Issue Triage
        - What is most important that we work on?


- Tasks
    - Issue Attention
    - Fix rendering? - Sam
    - Correct language around encrypted senders, language about what is exposed to who. - Andrew



- Next Week

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



## Meeting - 28 June 2021 - (1500 ET)
 
### Attendees
- [Sam Curren](telegramsam@gmail.com) ()
- [Steve McCown](smccown@anonyome.com) (Anonyome Labs)



### Agenda

- Welcome / Introductions

- PRs
    - [198](https://github.com/decentralized-identity/didcomm-messaging/pull/198) - typ/cty language
    - [200](https://github.com/decentralized-identity/didcomm-messaging/pull/200) - threading
    - [209](https://github.com/decentralized-identity/didcomm-messaging/pull/209) - sequencing extension
    - [211](https://github.com/decentralized-identity/didcomm-messaging/pull/211) - attachment format attribute
    - [212](https://github.com/decentralized-identity/didcomm-messaging/pull/212) - ECDH 1PU Draft 4

- Discussion Topics
     - DIDComm v2 library interface comparison (pack and unpack interface comparison)
        - DIDComm-rs - Rust - Jolocom (who?) Ivan
        - did-jwt/veramo - Typescript - Oliver
        - Go - Securekey - Baha


- Tasks
    - Fix rendering? - Sam
    - Correct language around encrypted senders, language about what is exposed to who. - Andrew



- Next Week



## Meeting - 21 June 2021 - (1500 ET)
 
### Attendees
- [Sam Curren](telegramsam@gmail.com) ()
- [Oliver Terbu](oliver.terbu@mesh.xyz) (ConsenSys Mesh)
- [Baha Shaaban](baha.shaaban@securekey.com) (SecureKey Technologies)
- Juan Caballero (DIF/Spruce)
- Balázs Nemethi (DIF)
- Brian Richter (Aviary or Whatever)
- Devin Fisher (Evernym)
- Drummond Reed (Evernym)
- Ivan Temchenko (Jolocom)
- Stephen Curran (Cloud Compass Computing)
- Troy Ronda (SecureKey)
- Daniel Hardman (SICPA)


### Agenda

- Welcome / Introductions

- PRs
    - [198](https://github.com/decentralized-identity/didcomm-messaging/pull/198) - typ/cty language
    - [200](https://github.com/decentralized-identity/didcomm-messaging/pull/200) - threading
    - [202](https://github.com/decentralized-identity/didcomm-messaging/pull/202) - refactor attachments
    - [206](https://github.com/decentralized-identity/didcomm-messaging/pull/206) - advanced sequencing
    - [205](https://github.com/decentralized-identity/didcomm-messaging/issues/205) - APU/APV values

- Discussion Topics
     - DIDComm v2 library interface comparison (pack and unpack interface comparison)
        - DIDComm-rs - Rust - Jolocom (who?) Ivan
        - did-jwt/veramo - Typescript - Oliver
        - Go - Securekey - Baha


- Tasks
    - Fix rendering - Sam
    - Correct language around encrypted senders, language about what is exposed to who. - Andrew
    - Threading section - Daniel Hardman
    - cty details included Issue #165 - Oliver


- Next Week


## Meeting - 14 June 2021 - (1500 ET)
 
### Attendees
- [Sam Curren](telegramsam@gmail.com) ()
- [Oliver Terbu](oliver.terbu@mesh.xyz) (ConsenSys Mesh)
- [Troy Ronda](troy.ronda@securekey.com) (SecureKey Technologies)
- [Juan Caballero](juan@identity.foundation) (DIF/Spruce)
- Steve McCown
- Devin Fisher
- Andrew Whitehead
- Daniel Hardman 

### Agenda

- Welcome / Introductions

- PRs
    - [195](https://github.com/decentralized-identity/didcomm-messaging/pull/195) - anoncrypt warning (updated)
    - [185](https://github.com/decentralized-identity/didcomm-messaging/pull/185) - kid and skid headers. Merge, then correct encrypted headers?
    - [172](https://github.com/decentralized-identity/didcomm-messaging/pull/172) - Fix inconsistencies with to/next attributes in a forward message. 

- Discussion Topics
    - [Q3 Done Plan](https://hackmd.io/d9AYc6uWScOCWMrFLp-iwA)
    - Keys by Value or By ID
        - [191](https://github.com/decentralized-identity/didcomm-messaging/issues/191) Issue
    - Sender Key/ID Encryption
        - Do we need to?
        - How is that done?
    - Alternative Transport
        - Bluetooth (Timo at Animo)
        - NFC (Daniel at SICPA)


- Tasks
    - Fix rendering - Sam
    - Correct language around encrypted senders, language about what is exposed to who. - Andrew
    - Threading section - Daniel Hardman
    - cty details included Issue #165 - Oliver


- Next Week
    - DIDComm v2 library interface comparison (pack and unpack interface comparison)
        - DIDComm-rs - Rust - Jolocom (who?) Ivan
        - did-jwt/veramo - Typescript - Oliver
        - Go - Securekey - Baha


## Meeting - 7 June 2021 - (1500 ET)
 
### Attendees
- [Sam Curren](telegramsam@gmail.com) ()
- [Oliver Terbu](oliver.terbu@mesh.xyz) (ConsenSys Mesh)

### Agenda

- Welcome / Introductions

- Discussion Topics
    - [Q3 Done Plan](https://hackmd.io/d9AYc6uWScOCWMrFLp-iwA)
    - Keys by Value or By ID
        - [191](https://github.com/decentralized-identity/didcomm-messaging/issues/191) Issue
    - Sender Key/ID Encryption
        - Do we need to?
        - How is that done?

- PRs
    - [161](https://github.com/decentralized-identity/didcomm-messaging/pull/161) - Attachments
    - [195](https://github.com/decentralized-identity/didcomm-messaging/pull/195) - anoncrypt warning (updated)
    - [185](https://github.com/decentralized-identity/didcomm-messaging/pull/185) - kid and skid headers
        - keys vs key refs
    - [172](https://github.com/decentralized-identity/didcomm-messaging/pull/172) - Fix inconsistencies with to/next attributes in a forward message. 




- Next Week
    


## Meeting - 24 May 2021 - (1500 ET)
 
### Attendees
- [Sam Curren](telegramsam@gmail.com) ()
- [Troy Ronda](troy.ronda@securekey.com) (SecureKey)
- [Steve McCown](smccown@anonyome.com) (Anonyome Labs)


### Agenda

- Welcome / Introductions
    - US Memorial Day (will skip next monday)

- Discussion Topics
    - Keys by Value or By ID
        - [191](https://github.com/decentralized-identity/didcomm-messaging/issues/191) Issue
    - XChaCha / Ethereum Compatible Key Wrapping - Oliver
    - Sender Key/ID Encryption
        - Do we need to?
        - How is that done?
     - Blog Post (Juan)
- PRs
    - [195](https://github.com/decentralized-identity/didcomm-messaging/pull/195) - anoncrypt warning (updated)
    - [185](https://github.com/decentralized-identity/didcomm-messaging/pull/185) - kid and skid headers
        - keys vs key refs
    - [172](https://github.com/decentralized-identity/didcomm-messaging/pull/172) - Fix inconsistencies with to/next attributes in a forward message. 
    - [161](https://github.com/decentralized-identity/didcomm-messaging/pull/161) - Attachments



- Next Week
    


## Meeting - 17 May 2021 - (1500 ET)
 
### Attendees
- [Sam Curren](telegramsam@gmail.com) ()
- [Kyle Den Hartog](kyle.denhartog@mattr.global)
- [Oliver Terbu](oliver.terbu@mesh.xyz)
- [Steve McCown](smccown@anonyome.com)
- [Troy Ronda](troy.ronda@securekey.com) (SecureKey)

### Agenda

- Welcome / Introductions

- Discussion Topics
    - Keys by Value or By ID
        - [191](https://github.com/decentralized-identity/didcomm-messaging/issues/191) Issue
    - XChaCha / Ethereum Compatible Key Wrapping - Oliver
    - Sender Key/ID Encryption
        - Do we need to?
        - How is that done?
- PRs
    - [195](https://github.com/decentralized-identity/didcomm-messaging/pull/195) - anoncrypt warning
    - [185](https://github.com/decentralized-identity/didcomm-messaging/pull/185) - kid and skid headers
        - keys vs key refs
    - [172](https://github.com/decentralized-identity/didcomm-messaging/pull/172) - Fix inconsistencies with to/next attributes in a forward message. 
    - [161](https://github.com/decentralized-identity/didcomm-messaging/pull/161) - Attachments



- Next Week
    

## Meeting - 10 May 2021 - (1500 ET)
 
### Attendees
- [Sam Curren](telegramsam@gmail.com) ()
- 

### Agenda

- Welcome / Introductions

- PRs
    - [190](https://github.com/decentralized-identity/didcomm-messaging/pull/190) - restoring anoncrypt 
        - (already merged)
        - Needs note about value of authcrypt, and why you should not invent another way to authenticate messages (future PR)
    - [185](https://github.com/decentralized-identity/didcomm-messaging/pull/185) - kid and skid headers
        - keys vs key refs
    - [172](https://github.com/decentralized-identity/didcomm-messaging/pull/172) - Fix inconsistencies with to/next attributes in a forward message. 
    - [161](https://github.com/decentralized-identity/didcomm-messaging/pull/161) - Attachments

- Discussion Topics
    - Etherium Compatible Key Wrapping - Oliver
    - JSON-LD Contexts - Oliver
    - Keys by Value or Ref

- Next Week
    

## Meeting - 3 May 2021 - (1500 ET)
 
### Attendees
- [Sam Curren](telegramsam@gmail.com) ()
- [Steve McCown](smccown@anonyome.com) ()
- [Troy Ronda](troy.ronda@securekey.com) (SecureKey)


### Agenda

- Welcome / Introductions

- PRs
    - [190](https://github.com/decentralized-identity/didcomm-messaging/pull/190) - restoring anoncrypt
        - Needs note about value of authcrypt, and why you should not invent another way to authenticate messages (future PR)
    - [185](https://github.com/decentralized-identity/didcomm-messaging/pull/185) - kid and skid headers
        - keys vs key refs
    - [172](https://github.com/decentralized-identity/didcomm-messaging/pull/172) - Fix inconsistencies with to/next attributes in a forward message. 
    - [161](https://github.com/decentralized-identity/didcomm-messaging/pull/161) - Attachments

- Discussion Topics
    - Etherium Compatible Key Wrapping - Oliver

- Next Week
    

## Meeting - 26 Apr 2021 - (1500 ET)
 
### Attendees
- [Sam Curren](telegramsam@gmail.com) ()
- [Troy Ronda](troy.ronda@securekey.com) (SecureKey)
- [Kyle Den Hartog](kyle.denhartog@mattr.global)(MATTR)
- [Oliver Terbu](oliver.terbu@mesh.xyz) (ConsenSys AG)
- [Baha AbuShaaban](baha.shaaban@securekey.com) (SecureKey)
- [Stephen Curran](swcurran@cloudcompass.ca) (Cloud Compass Computing Inc. / BC Gov)

### Agenda

- Welcome / Introductions

- Discussion Topics
    - IIW Happenings
        - Jello Bowl Death Match
    - ECDH-1PU vs everything else (chat related discussion)
        - ECDH-ES
        - Authenticated Encryption
        - 
        - Andrew's Idea: https://hackmd.io/gC4ItH4IQKS_at8P8RyQOQ?view
    - KID/SKID Related Topics
        - ESKID
        - Encrypted Sender

- PRs
    - [185](https://github.com/decentralized-identity/didcomm-messaging/pull/185) - kid and skid headers
    - [172](https://github.com/decentralized-identity/didcomm-messaging/pull/172) - Fix inconsistencies with to/next attributes in a forward message. 

- Next Week
    

## Meeting - 19 Apr 2021 - (1500 ET)
 
### Attendees
- [Sam Curren](telegramsam@gmail.com) ()
- [Oliver Terbu](oliver.terbu@mesh.xyz) ()


### Agenda

- Welcome / Introductions

- PRs
    - [183](https://github.com/decentralized-identity/didcomm-messaging/pull/183) - OOB Accept
    - [185](https://github.com/decentralized-identity/didcomm-messaging/pull/185) - kid and skid headers
    -  Complexity vs re-encryption bloat
        -  [182](https://github.com/decentralized-identity/didcomm-messaging/issues/182) - Discussion Issue
        - [161](https://github.com/decentralized-identity/didcomm-messaging/pull/161) - Attachments WIP
        - [174](https://github.com/decentralized-identity/didcomm-messaging/pull/174) - Encrypted Attachments
    -  [172](https://github.com/decentralized-identity/didcomm-messaging/pull/172) - Fix inconsistencies with to/next attributes in a forward message. 

- Discussion Topics
    
    - Issues
    - DIDComm RecipientKeys: Signing vs Encryption 
    - KERI Event Logs
- Next Week
    - SKID Related Topics (Tobias)

## Meeting - 12 Apr 2021 - (1500 ET)
 
### Attendees
- [Sam Curren](telegramsam@gmail.com) ()
- [Oliver Terbu](oliver.terbu@meshx.yz) (ConsenSys Mesh)
- [Troy Ronda](troy.ronda@securekey.com) (SecureKey)
- [Ivan Temchenko](ivan@jolocom.com) (Jolocom)
- [Steve McCown](smccown@anonyome.com) (Anonyome Labs)

### Agenda

- Welcome / Introductions

- PRs
    - [177](https://github.com/decentralized-identity/didcomm-messaging/pull/177) - Profiles
        - [Negotiation Topics](https://hackmd.io/p-ci0BZfQQirvNiN0poHHA)
        - [181](https://github.com/decentralized-identity/didcomm-messaging/pull/181) - accept property with profiles
    - [173](https://github.com/decentralized-identity/didcomm-messaging/pull/173) - accept property in service block
    - [180](https://github.com/decentralized-identity/didcomm-messaging/pull/180) - Align service Type with Aries
        - [179](https://github.com/decentralized-identity/didcomm-messaging/issues/179) - Issue with commentary
    -  [172](https://github.com/decentralized-identity/didcomm-messaging/pull/172) - Fix inconsistencies with to/next attributes in a forward message. 
    - [161](https://github.com/decentralized-identity/didcomm-messaging/pull/161) - Attachments WIP
        - [174](https://github.com/decentralized-identity/didcomm-messaging/pull/174) - Encrypted Attachments


- Discussion Topics
    
    - DIDComm RecipientKeys: Signing vs Encryption 
    - KERI Event Logs
    


## Meeting - 05 Apr 2021 - (1500 ET)
 
### Attendees
- [Sam Curren](telegramsam@gmail.com) ()

### Agenda

- Welcome / Introductions

- PRs
    - [172](https://github.com/decentralized-identity/didcomm-messaging/pull/172) - Fix inconsistencies with to/next attributes in a forward message. 
    - [173](https://github.com/decentralized-identity/didcomm-messaging/pull/173) - accept property in service block
    - [161](https://github.com/decentralized-identity/didcomm-messaging/pull/161) - Attachments WIP
        - [174](https://github.com/decentralized-identity/didcomm-messaging/pull/174) - Actual PR


- Discussion Topics
    - [Negotiation Topics](https://hackmd.io/p-ci0BZfQQirvNiN0poHHA)
    - DIDComm RecipientKeys: Signing vs Encryption 
    


## Meeting - 29 Mar 2021 - (1500 ET)
 
### Attendees
- [Sam Curren](telegramsam@gmail.com) ()
- [Troy Ronda](troy.ronda@securekey.com) (SecureKey)

### Agenda

- Welcome / Introductions

- New Meeting Link Reminder

- PRs
    - [172](https://github.com/decentralized-identity/didcomm-messaging/pull/172) - Fix inconsistencies with to/next attributes in a forward message. 
    - [173](https://github.com/decentralized-identity/didcomm-messaging/pull/173) - accept property in service block
    - [161](https://github.com/decentralized-identity/didcomm-messaging/pull/161) - Attachments WIP
        - Encrypted Attachments https://hackmd.io/jx8W0boDSzmLe2r6LKQU5w
        - [174](https://github.com/decentralized-identity/didcomm-messaging/pull/174) - Actual PR

- Issues
    - [162](https://github.com/decentralized-identity/didcomm-messaging/issues/162) - Rewrapping forwarded messages. - awaiting PR

- Discussion Topics
    - Aries / DIDComm V2
    


## Meeting - 22 Mar 2021 - (1500 ET)
 
### Attendees
- [Sam Curren](telegramsam@gmail.com) ()
- [Oliver Terbu](oliver.terbu@mesh.xyz) ()
- [Troy Ronda](troy.ronda@securekey.com) (SecureKey)
- [Baha A-Shaaban](baha.shaabah@securekey.com) (SecureKey)


### Agenda

- Welcome / Introductions

- New Meeting Link Reminder

- PRs
    - [170](https://github.com/decentralized-identity/didcomm-messaging/pull/170) - Restructure to solve image display issues.
    - [172](https://github.com/decentralized-identity/didcomm-messaging/pull/172) - Fix inconsistencies with to/next attributes in a forward message. 
    - [171](https://github.com/decentralized-identity/didcomm-messaging/pull/171) - media type discussion
    - [167](https://github.com/decentralized-identity/didcomm-messaging/pull/167) - accept property
    - [161](https://github.com/decentralized-identity/didcomm-messaging/pull/161) - Attachments WIP
        - Encrypted Attachments https://hackmd.io/jx8W0boDSzmLe2r6LKQU5w

- Issues
    - [165](https://github.com/decentralized-identity/didcomm-messaging/issues/165) - cty of JWM
    - [162](https://github.com/decentralized-identity/didcomm-messaging/issues/162) - Rewrapping forwarded messages. - awaiting PR

- Discussion Topics
    - 
    


## Meeting - 15 Mar 2021 - (1500 ET)
 
### Attendees
- [Sam Curren](telegramsam@gmail.com) ()
- [George Aristy](george.aristy@securekey.com) (SecureKey)
- [Troy Ronda](troy.ronda@securekey.com) (SecureKey)


### Agenda

- Welcome / Introductions

- New Meeting Link Reminder

- PRs
    - [167](https://github.com/decentralized-identity/didcomm-messaging/pull/167) - accept property
    - [161](https://github.com/decentralized-identity/didcomm-messaging/pull/161) - Attachments WIP
        - Encrypted Attachments https://hackmd.io/jx8W0boDSzmLe2r6LKQU5w
    - [171](https://github.com/decentralized-identity/didcomm-messaging/pull/171) - media type in envelope
- Issues
    - [165](https://github.com/decentralized-identity/didcomm-messaging/issues/165) - cty of JWM
    - [162](https://github.com/decentralized-identity/didcomm-messaging/issues/162) - Rewrapping forwarded messages. - awaiting PR

- Discussion Topics
    - Peer DID Method 2 - https://github.com/decentralized-identity/peer-did-method-spec/pull/26
    


## Meeting - 08 Mar 2021 - (1500 ET)
 
### Attendees
- [Sam Curren](telegramsam@gmail.com) ()
- [Oliver Terbu](oliver.terbu@mesh.xyz)


### Agenda

- Welcome / Introductions

- New Meeting Link

- PRs
    - [157](https://github.com/decentralized-identity/didcomm-messaging/pull/157) - JSON-LD Context (conflicts)
    - [166](https://github.com/decentralized-identity/didcomm-messaging/pull/166) - Curve P-384
    - [167](https://github.com/decentralized-identity/didcomm-messaging/pull/167) - accept property
    - [161](https://github.com/decentralized-identity/didcomm-messaging/pull/161) - Attachments WIP
- Issues
    - [165](https://github.com/decentralized-identity/didcomm-messaging/issues/165) - cty of JWM
    - [162](https://github.com/decentralized-identity/didcomm-messaging/issues/162) - Rewrapping forwarded messages. - awaiting PR

- Discussion Topics
    - Peer DID Method 2 - https://github.com/decentralized-identity/peer-did-method-spec/pull/26


## Meeting - 01 Mar 2021 - (1500 ET)
 
### Attendees
- [Sam Curren](telegramsam@gmail.com) ()
- 


### Agenda

- Welcome / Introductions

- PRs
    - [157](https://github.com/decentralized-identity/didcomm-messaging/pull/157) - JSON-LD Context (conflicts)
    - [163](https://github.com/decentralized-identity/didcomm-messaging/pull/163) - Thread language
- Issues
    - [165](https://github.com/decentralized-identity/didcomm-messaging/issues/165) - cty of JWM
    - [162](https://github.com/decentralized-identity/didcomm-messaging/issues/162) - Rewrapping forwarded messages. - awaiting PR
    - mimetype gap
        - https://github.com/hyperledger/aries-rfcs/pull/587
        - https://identity.foundation/didcomm-messaging/spec/#https
        - https://identity.foundation/didcomm-messaging/spec/#didcomm-encrypted-message
  
- Discussion Topics



Recording: - to be posted -

## Meeting - 22 Feb 2021 - (1500 ET)
 
### Attendees
- [Sam Curren](telegramsam@gmail.com) ()
- [Oliver Terbu](oliver.terbu@mesh.xyz)()
- [Steve McCown](smccown@anonyome.com) (Anonyome Labs)


### Agenda

- Welcome / Introductions

- PRs
    - [157](https://github.com/decentralized-identity/didcomm-messaging/pull/157) - JSON-LD Context
    - [163](https://github.com/decentralized-identity/didcomm-messaging/pull/163) - Thread language
- Issues
    - [162](https://github.com/decentralized-identity/didcomm-messaging/issues/162) - Rewrapping forwarded messages. 
    - [159](https://github.com/decentralized-identity/didcomm-messaging/issues/159) - Which keys are used for encryption.
- Discussion Topics
    - Peer DID Method 2: https://github.com/decentralized-identity/peer-did-method-spec/pull/26

Recording: https://us02web.zoom.us/rec/share/H96XojOUKqDBpcDi8q826u0U-tJfhSTRChWbX6NA8mFBGF3zE6O1GIgSoMxCwm7j.8yDw3qSUL7xQvl5w

## Meeting - 15 Feb 2021 - (1500 ET)
 
### Attendees
- [Sam Curren](telegramsam@gmail.com) ()


### Agenda

- Welcome / Introductions

- PRs
    - [157](https://github.com/decentralized-identity/didcomm-messaging/pull/157) - JSON-LD Context
    - [160](https://github.com/decentralized-identity/didcomm-messaging/pull/160) - Remove old queue reference/TODOs
- Issues
    - [162](https://github.com/decentralized-identity/didcomm-messaging/issues/162) - Rewrapping forwarded messages.
    - [159](https://github.com/decentralized-identity/didcomm-messaging/issues/159) - Which keys are used for encryption.
- Discussion Topics
    - Peer DID Method 2: https://github.com/decentralized-identity/peer-did-method-spec/pull/26

Recording: https://us02web.zoom.us/rec/share/H6tr8FGm8P_NU87tZBDZPDiUWBlTD8WSzUQ5tCMS8Mc4MIPS_KcUsORlXEM6U-i9.xoP19_0UgU5vGVBE

## Meeting - 08 Feb 2021 - (1500 ET)
 
### Attendees
- [Sam Curren](telegramsam@gmail.com) ()
- Troy Ronda (SecureKey)
- [Oliver Terbu](oliver.terbu@mesh.xyz)
- [Steve McCown](smccown@anonyome.com) Anonyome Labs

### Agenda

- Welcome / Introductions

- DID Use Cases
    - Merged!
    - https://w3c.github.io/did-use-cases/#messaging
- PRs
    - [157](https://github.com/decentralized-identity/didcomm-messaging/pull/157) - JSON-LD Context
    - [160](https://github.com/decentralized-identity/didcomm-messaging/pull/160) - Remove old queue reference/TODOs
- Issues
    - [159](https://github.com/decentralized-identity/didcomm-messaging/issues/159) - Which keys are used for encryption.
- Discussion Topics
    - https://github.com/w3c/did-core/issues/599

Recording: https://us02web.zoom.us/rec/share/cqnWgNI8NweatY1vGGx3vb4MjujVuIuaz8OxVpMlQLY89aW1UbZtiHer7x0Fig47.aGWlrp24UnZ7sTx0

## Meeting - 01 Feb 2021 - (1500 ET)
 
### Attendees
- [Sam Curren](telegramsam@gmail.com) ()
- [George Aristy](george.aristy@securekey.com) (SecureKey)
- [Oliver Terbu](oliver.terbu@mesh.xyz) (ConsenSys Mesh)
- [Balazs Nemethi](balazs@identity.foundation) (DIF)
- [Steve McCown](smccown@anonyome.com) (Anonyome Labs)
- [Nader Helmy](nader.helmy@mattr.global) (MATTR)

### Agenda

- Welcome / Introductions
- DID Registry DIDComm service type
    - https://difdn.slack.com/archives/CRMKSUE8M/p1611678442008000
    - https://identity.foundation/didcomm-messaging/spec/#did-document-service-endpoint
- DID Use Cases
    - Extended discussion: https://github.com/w3c/did-use-cases/pull/126
    - New PR: https://github.com/w3c/did-use-cases/pull/139
    - New PR Preview: https://pr-preview.s3.amazonaws.com/w3c/did-use-cases/pull/139.html#messaging
- PRs
    - 
- Discussion Topics
    - Localization 
        -   https://hackmd.io/Bcomd6hqTVOVh7oWjlo6kQ
    - Attachments 
        - https://hackmd.io/zPQHVHtpTiShXG64TYHyiQ
    
Recording: https://us02web.zoom.us/rec/share/sutwdvIBjGpUswprTqvSDE_xKg9gcS2nT65KrxHrxzauqJIqDvSzk69d6lJZv7wN.BaFxDrTw3Xx5uup4

## Meeting - 25 Jan 2021 - (1500 ET)
 
### Attendees
- [Sam Curren](telegramsam@gmail.com) ()
- [George Aristy](george.aristy@securekey.com) (SecureKey)
- [Steve McCown](smccown@anonyome.com) (Anonyome Labs)
- [Oliver Terbu](oliver.terbu@mesh.xyz) (ConsenSys Mesh)
- [Nader Helmy](nader.helmy@mattr.global) (MATTR)


### Agenda

- Welcome / Introductions

- DIF F2F

- DID Use Cases
    - Extended discussion: https://github.com/w3c/did-use-cases/pull/126
    - New PR: https://github.com/w3c/did-use-cases/pull/139
    - New PR Preview: https://pr-preview.s3.amazonaws.com/w3c/did-use-cases/pull/139.html#messaging
- PRs
    - https://github.com/decentralized-identity/didcomm-messaging/pull/140
- Discussion Topics
    - DIDCom V2 Library - Rust
        - https://github.com/jolocom/didcomm-rs
        - https://www.youtube.com/watch?v=SaNvIorKQ9I
        - 
 - Walkthrough and Q&A

    - Localization 
        -   https://hackmd.io/Bcomd6hqTVOVh7oWjlo6kQ
    - Attachments 
        - https://hackmd.io/zPQHVHtpTiShXG64TYHyiQ
    
Recording: https://us02web.zoom.us/rec/share/kzc-Rsm_XOBvBMoSttIupf3MO8WmP-tEopTPh7WD9qykRWT1tvBGTrDMsMN8TCLq.qf1jJEwjs8A6xhwX

## Meeting - 18 Jan 2021 - (1500 ET)
 
### Attendees
- [Sam Curren](telegramsam@gmail.com) ()


### Agenda

- Welcome / Introductions
    - DIF F2F Tommorrow!
    - https://docs.google.com/spreadsheets/d/1hVnwrnU7QOp_rA7AcK2NTQkflSAg0zvQ3-We2DqyRpk/edit#gid=445783158


- Bluetooth Updates
- F2F WG Update
    - https://docs.google.com/presentation/d/1YiL-A9YaNgQpFBraJJOLLUPyFfZ6uQ1uqtTCiDZxNqI/edit?usp=sharing
- DID Use Cases
    - https://github.com/w3c/did-use-cases/pull/126
- PRs
    - https://github.com/decentralized-identity/didcomm-messaging/pull/141
    - https://github.com/decentralized-identity/didcomm-messaging/pull/140
    - https://github.com/decentralized-identity/didcomm-messaging/pull/150
    - https://github.com/decentralized-identity/didcomm-messaging/pull/151
    - https://github.com/decentralized-identity/didcomm-messaging/pull/153
- Discussion Topics
    - DIDCom V2 Library - Rust

## Meeting - 11 Jan 2021 - (1500 ET)
 
### Attendees
- [Sam Curren](telegramsam@gmail.com) ()
- [Oliver Terbu](oliver.terbu@mesh.xyz)
- [George Aristy](george.aristy@securekey.com) (SecureKey)
- [Ivan Temchenko](ivan@jolocom.com) (Jolocom)
- [Steve McCown](smccown@anonyome.com) (Anonyome Labs)
- [Troy Ronda](troy.ronda@securekey.com) (SecureKey)

### Agenda

- Welcome / Introductions
- Demo
    - Jolocom DIDComm Demo (Ivan)
- Bluetooth Discussion
- DID Use Cases
    - https://github.com/w3c/did-use-cases/pull/126
- PRs
    - https://github.com/decentralized-identity/didcomm-messaging/pull/141
    - https://github.com/decentralized-identity/didcomm-messaging/pull/140
    - https://github.com/decentralized-identity/didcomm-messaging/pull/150
    - https://github.com/decentralized-identity/didcomm-messaging/pull/151
    - https://github.com/decentralized-identity/didcomm-messaging/pull/153
- Discussion Topics
    - DIF F2F

## Meeting - 04 Jan 2021 - (1500 ET)
 
### Attendees
- [Sam Curren](telegramsam@gmail.com) ()
- [Oliver Terbu](oliver.terbu@mesh.xyz)

### Agenda

- Welcome / Introductions
- Milestones
    - First Complete Draft - reads correctly from beginning to end Nov 30th.
    - Next Complete Draft - Eliminate all TODOs
- Bluetooth Discussion
    - Jan 6, 6pm CET
    - Will announce on channel

- DID Use Cases
    - Original: https://github.com/w3c/did-use-cases/pull/100
    - PR: https://github.com/w3c/did-use-cases/pull/126
        - Preview: https://pr-preview.s3.amazonaws.com/creatornader/did-use-cases/pull/126.html#messaging
- PR/Issues: 
    - [140](https://github.com/decentralized-identity/didcomm-messaging/pull/140) - Anonymous From
    - [141](https://github.com/decentralized-identity/didcomm-messaging/pull/141) - expires_time semantics

- Discussion Topics
    - ACK - inclusion and status.
    - [139](https://github.com/decentralized-identity/didcomm-messaging/pull/139) - Proposed Reply Header Text










## Meeting - 21 Dec 2020 - (1500 ET)
 
### Attendees
- [Sam Curren](telegramsam@gmail.com) ()
- [Oliver Terbu](oliver.terbu@mesh.xyz) (ConsenSys AG)
- [Steve McCown](smccown@anonyome.com) (Anonyome Labs)

### Agenda

- Welcome / Introductions
- Meetings through holidays:
    - 21st, 28th
- Milestones
    - First Complete Draft - reads correctly from beginning to end Nov 30th.
    - Next Complete Draft - Eliminate all TODOs


- DID Use Cases
    - Original: https://github.com/w3c/did-use-cases/pull/100
    - Nader: https://github.com/w3c/did-use-cases/pull/122
        - Preview: https://pr-preview.s3.amazonaws.com/creatornader/did-use-cases/pull/122.html#messaging
    - Phil Archer: https://github.com/w3c/did-use-cases/pull/126
        - Preview: https://pr-preview.s3.amazonaws.com/creatornader/did-use-cases/pull/126.html#messaging
- PR/Issues: 
    - [134](https://github.com/decentralized-identity/didcomm-messaging/issues/134) - `reply_*` headers and the support of DIDs without endpoints
    - [135](https://github.com/decentralized-identity/didcomm-messaging/issues/135) - Size (byte length) Specification for DIDComm Messages
- Interop Testing?
- Ack? as part of V2 
- Daniel Issues

## Meeting - 14 Dec 2020 - (1500 ET)
 
### Attendees
- [Sam Curren](telegramsam@gmail.com) ()
- [George Aristy](george.aristy@securekey.com) (SecureKey)
- [Timo Glastra](timo@animo.id) (Animo Solutions)
- [Oliver Terbu](oliver.terbu@mesh.xyz) (ConsenSys)
- [Tobias Looker](tobias.looker@mattr.global)(Mattr)
- [Steve McCown](smccown@anonyome.com) (Anonyome Labs)
- [Nader Helmy](nader.helmy@mattr.global) (MATTR)
- [Tomslav Markovski](tomislav@trinsic.id) (Trinsic)
- [Troy Ronda](troy.ronda@securekey.com) (SecureKey)
 
### Agenda

- Welcome / Introductions
- Meetings through holidays:
    - 21st, 28th
- Milestones
    - First Complete Draft - reads correctly from beginning to end Nov 30th.
    - Next Complete Draft - Eliminate all TODOs


- DID Use Cases
    - Original: https://github.com/w3c/did-use-cases/pull/100
    - Nader: https://github.com/w3c/did-use-cases/pull/122
        - Preview: https://pr-preview.s3.amazonaws.com/creatornader/did-use-cases/pull/122.html#messaging
    - Phil Archer: https://github.com/w3c/did-use-cases/pull/126
        - Preview: https://pr-preview.s3.amazonaws.com/creatornader/did-use-cases/pull/126.html#messaging
- PR/Issues: 
    - [128](https://github.com/decentralized-identity/didcomm-messaging/pull/128) - to header semantics
- Support DID Methods without endpoint support
    - Strategy: Rotate to something that does
    - Strategy: Allow indication of endpoint information in a message.
        - Endpoint, routing
        - `reply_url`
        - `reply_to` does not indicate routing. Perhaps `reply_routing` = []?
        - Requires message from DID owner first.
    - Scope: message, conversation, everything?
        - Not all messages will be replies
    - use cases:
        - existing relationship use local connetion like bluetooth. Does the DID Doc need to be updated? Reply info could be used to manage using a temporary local connection.
        - DID method that doesn't support an endpoint, or won't for legal reasons.
        - modify mediation path dynamically
    - Carrying Cost
        - maintaining temporary state
        - increased comlexity of sending message
        - different replication of service block in reply headers




## Meeting - 07 Dec 2020 - (1500 ET)
 
### Attendees
- [Sam Curren](telegramsam@gmail.com) ()
- [Tobias Looker](tobias.looker@mattr.global) ()
- [Oliver Terbu](oliver.terbu@mesh.xyz) ()
- [Stephen Curran](swcurran@cloudcompass.ca) Cloud Compass Computing Inc.
- [Timo Glastra](timo@animo.id) (Animo Solutions)
- [Steve McCown](smccown@anonyome.com) Anonyome Labs
- [Drummond Reed](drummond.reed@evernym.com) Evernym
- [Nader Helmy](nader.helmy@mattr.global) (MATTR)
 
### Agenda

- Welcome / Introductions
- Milestones
    - First Complete Draft - reads correctly from beginning to end Nov 30th.
    - Next Complete Draft - Eliminate all TODOs
- DIDComm.org Progress
    - Repo exists 
   https://github.com/decentralized-identity/didcomm.org
   - First content is present.
   - domain config? - done!
   - https://didcomm.org / https://www.didcomm.org (http redirects)
   - Next Steps

- DID Use Cases
    - Original: https://github.com/w3c/did-use-cases/pull/100
    - Nader: https://github.com/w3c/did-use-cases/pull/122
        - Preview: https://pr-preview.s3.amazonaws.com/creatornader/did-use-cases/pull/122.html#messaging
    - Needs New PR.
    - Expansion of messaging into protocols?
- PR/Issues: 
    - [128](https://github.com/decentralized-identity/didcomm-messaging/pull/128) - to header semantics
    - [131](https://github.com/decentralized-identity/didcomm-messaging/pull/131) - from/to DID Query Parameters
- Bluetooth Transport
    - status/questions
    - https://hackmd.io/@animo/didcomm-bluetooth-transport



### Proposals
-proposals here-


## Meeting - 30 Nov 2020 - (1500 ET)
 
### Attendees
- [Sam Curren](telegramsam@gmail.com) ()
- [George Aristy](george.aristy@securekey.com) (SecureKey)
- [Ivan Temchenko](ivan@jolocom.com)(Jolocom)
- [Steve McCown](smccown@anonyome.com) (Anonyome Labs)
- [Stephen Curran](swcurran@cloudcompass.ca) (Cloud Compass Computing Inc.)
- [Tobias Looker](tobias.looker@mattr.global)(Mattr)
- [Nader Helmy](nader.helmy@mattr.global) (Mattr)
- [Drummond Reed](drummond.reed@evernym.com) (Evernym)
- [Timo Glastra](timo@animo.id) (Animo Solutions)
- [Juan Caballero](twitter.com/by_caballero) (DIF/LearningProof)
 
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
        - Preview: https://pr-preview.s3.amazonaws.com/creatornader/did-use-cases/pull/122.html#messaging
    - Needs New PR.
    - Progress?
- PR/Issues: 
    - [127](https://github.com/decentralized-identity/didcomm-messaging/pull/127) - structured headers
    - [128](https://github.com/decentralized-identity/didcomm-messaging/pull/128) - to header semantics
    - [129](https://github.com/decentralized-identity/didcomm-messaging/pull/129) - post quantum
    - [126](https://github.com/decentralized-identity/didcomm-messaging/issues/126) - DIDDocs for Peer DIDs

- DIDComm Bootstrapping and Discovery Technique
    - [Social Profile Association Credential](https://hackmd.io/IZgDPFy6QiaZXbUk7Ik87Q?view)
- Rebase: 
    -https://www.w3.org/community/blog/2020/11/19/proposed-group-rebase-community-group/


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
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
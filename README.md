Charter for Working Group

Interactive Connectivity Establishment (ICE) is at the same time a NAT traversal technique, a multihomed address selection technique, and a dual stack address selection technique that works by including a multiplicity of IP addresses and ports in both the request and response messages of a connectivity establishment transaction. It makes no assumptions regarding network topology on the local or remote side.

Interactive Connectivity Establishment was published as RFC 5245 in April 2010. Until recently the protocol had seen rather limited deployment. This situation has changed drastically as ICE is mandatory to implement
in WebRTC, a set of technologies developed at the IETF and W3C to standardize Real Time Communication on the Web. ICE was originally defined for the Offer-Answer (RFC 3264) protocol used by SIP (RFC 3261). Later XMPP (XEP-0176), RTSP (draft-ietf-mmusic-rtsp-nat), RTCWeb (draft-ietf-rtcweb-jsep) and other realtime media establishment protocol have used the protocol. ICE is also used by non-realtime media protocols, like HIP (RFC 5770) and RELOAD (RFC 6940).

The goal of the ICE Working Group is to consolidate the various initiatives to update and improve ICE, and to help ensure suitability and consistency in the environments ICE operates in. Current work in this area includes an updated version of the ICE RFC (ICEbis), Trickle ICE and dualstack/multihomed fairness. It is worth noticing that this work will make ICE more flexible, robust and more suitable for changing mobile environments without major changes to the original ICE RFC. The ICE workgroup will consider new work items that follow this pattern.

ICE is an application controlled protocol that leverages a set of network defined protocols. The STUN (RFC 5389), TURN (RFC 5766) and related protocol work done in the TRAM working group must be closely synchronized with the work in this working group. To avoid interoperability issues and unwanted behavior it is desired to increase the interaction with other working groups dealing with network protocols closer to the wire. Example of such work may be, but not limited to; issues regarding multi-homing, multi subnet and prefixes, QoS, transport selection and congestion control. From the application side, the users of ICE, there is a need to make sure what is specified is actually usable. Getting input from the application working groups will be helpful (RTCWEB, HIP, MMUSIC, P2PSIP, PPSP).



Milestones

- Jan 2016 Submit Dual-stack Fairness with ICE as Proposed Standard
  draft-ietf-mmusic-ice-dualstack-fairness
- Apr 2016 Submit a revision of ICE (RFC 5245) as Proposed Standard
  draft-ietf-mmusic-rfc5245bis
  (draft-ietf-mmusic-ice-sip-sdp remains in MMUSIC)
- Jan 2016 Submit Trickle ICE as Proposed Standard
  draft-ietf-mmusic-trickle-ice
  (draft-ietf-mmusic-trickle-ice-sip remains in MMUSIC)

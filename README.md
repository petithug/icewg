Charter for Working Group

Interactive Connectivity Establishment was published as RFC 5245 in April 2010. Until recently the protocol had seen rather limited deployment. ICE was slow to achieve widespread adoption, as other mechanisms were already
being used by the VoIP industry. This situation has changed drastically as ICE is mandatory to implement
in WebRTC, a set of technologies developed at the IETF and W3C to standardize Real Time Communication on the Web.

Interactive Connectivity Establishment (ICE) is at the same time a NAT traversal technique, a multihomed address selection technique, and a dual stack address selection technique that works by including a multiplicity of IP addresses and ports in both the request and response messages of a connectivity establishment transaction.  The IP addresses and ports provided by each side are paired and tested by peer-to-peer connectivity checks until one of these pair is selected to transport data.

ICE was originally defined for the Offer-Answer (RFC 3264) protocol used by SIP (RFC 3261) and later XMPP (XEP-0176), RTSP (draft-ietf-mmusic-rtsp-nat), RTCWeb (draft-ietf-rtcweb-jsep) and other realtime media establishment protocol.  But it is also used by non-realtime media protocols, like HIP (RFC 5770) and RELOAD (RFC 6940).

The goal of the ICE Working Group is to consolidate the various initiatives to update ICE to make it more suitable for the WebRTC environment but also to all the current usages of ICE.  The Working Group will closely coordinate with the appropriate Working Groups, including RTCWEB, MMUSIC, TRAM, MIF, HIP and P2PSIP.

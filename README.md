# LAN PARTY Proof of Concept (PoC)

Proof-of-concept for a WebRTC connection between two browser pages in the same Local Area Network (LAN).

This PoC features a static site, with a chat app. It runs fully without a server.
You can visit the webpage on 2 different devices in the same LAN.
One device will initiate the handshake as `Alice`.
The other device will respond to the handshake as `Bob`.
Then you can send messages between the two devices.

Goal: Provide serverless WebRTC (no need for signal server / relay servers) for LAN gaming parties.

- Can just use messaging apps to do signalling.
- Relay not needed in most LAN setups.
- Just need to compress the handshake size down.
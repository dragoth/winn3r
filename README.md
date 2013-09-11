winn3r
======

Worldwide Interconnected Neural Network of 3-D Realities Project

Milestones

### Basic infrastructure
- Reliably generate a cryptographic identity that is guaranteed to be unique to a Nyquist order of min. 10 trillion
- Implement PSK encryption derived from the generated identity
- Respond to network requests for your public key & discover other nodes on the network without the aid of a centralized server
- Negotiate encrypted communications between other nodes of the P2P network using PSK encryption

### Secure file transfer
- Load, clean and encrypt a file from a normal filesystem and assign it a magnet: link
- Serve a magnet: file to a peer along with a link to the file's public key

### Streaming Data
- Send and receive streaming audio data (via Speex) to and from a connected peer
- Send and receive streaming video data (via Webm) to and from a connected peer

### Position data & ranging
- Stream position and heading vector with velocity to any interested parties
- Identify self with XML describing avatar mesh(es) and behavior(s) via magnet links
- Determine a maximum viewable range for free space vs. on a planet

### Servers
- Implement a server (planet)
- Servers serve geometry, rules (eg: gravity) and event snapshots (destructables)
- Servers connect the same way players do, but can also serve new players with IPs of "nearby" players to facilitate faster login

### 3D engine
- Implement a basic 3D engine that can draw entities using built-in meshes and materials
- Implement an asynchronous movement system using data from connected peers
- Implement or borrow a COLLADA model loader
- More...

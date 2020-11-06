# Links
------

## 2020
List of links with things I don't want to forget or I want to explore in the future (a perfect way of alleviating the large number of tabs opened in my browser).
### Networking
* [Fast Network Simulation Setup](https://github.com/fnss/fnss): Fast Network Simulation Setup (FNSS) is a toolchain allowing network researchers and engineers to simplify the process of setting up a network experiment scenario. 
* [Fluence Network](https://fluence.network/): Distributed applications without platforms. Fluence is a peer-to-peer computing protocol and a software licensing system. Fluence enables hostless, sovereign applications that are free from proprietary platforms and don’t require infrastructure or even maintenance once published. 
* [Datagram Transport Layer Security (DTLS)](https://tools.ietf.org/html/rfc6347):  The DTLS protocol provides communications privacy for datagram protocols.  The protocol allows client/server applications to communicate in a way that is designed to prevent eavesdropping, tampering, or message forgery.
* [NAT Slipstreaming](https://samy.pl/slipstream/): NAT Slipstreaming allows an attacker to remotely access any TCP/UDP service bound to a victim machine, bypassing the victim's NAT/firewall (arbitrary firewall pinhole control), just by the victim visiting a website.
* [Terragraph](https://terragraph.com/): Terragraph is a technology that operates on 60 GHz unlicensed band delivering fiber-like speeds.
* [Open Routing Protocol](https://github.com/facebook/openr): Open Routing, OpenR, is Facebook's internally designed and developed Interior Routing Protocol/Platform. OpenR was originally designed and built for performing routing on the Terragraph mesh network. OpenR's flexible design has led to its adoption in other networks, including Facebook's new WAN network, Express Backbone.

 
### P2P
* [Looking Into the Eye of the Interplanetary Storm](https://www.bitdefender.com/files/News/CaseStudies/study/376/Bitdefender-Whitepaper-IPStorm.pdf?clickid=U83WZOxw3xyLTWRwUx0Mo3EAUkExytV5SUS9Sc0&irgwc=1&MPid=10078&cid=aff%7Cc%7CIR): Good insight about the Interplanetary Storm Botnet.
* [Scuttlebot](https://scuttlebutt.nz/): It is a fast growing decentralized social network.
* [Beaker Browser](https://beakerbrowser.com/): A peer-to-peer browser for Web hackers.
* [Streaming video in the browser with js-ipfs and hls.js](https://github.com/ipfs/js-ipfs/tree/master/examples/browser-video-streaming)
* [Vapor.Network](https://vapor.network/): Decentralized Web over Bitcoinized HTTP.

### CRDTs
* [CRDT datastore in Go](https://github.com/ipfs/go-ds-crdt)
* [YJS](https://github.com/yjs/yjs): Yjs is a CRDT implementation that exposes its internal data structure as shared types. Shared types are common data types like Map or Array with superpowers: changes are automatically distributed to other peers and merged without merge conflicts.
* [Atom Teletype CRDTs](https://github.com/atom/teletype-crdt): The string-wise sequence CRDT powering peer-to-peer collaborative editing in Teletype for Atom
* [I was wrong. CRDTs are the future](https://josephg.com/blog/crdts-are-the-future/)

### Cryptography
* [Enarx](https://github.com/enarx/enarx/wiki/Enarx-Introduction): Enarx is an application deployment system enabling applications to run within Trusted Execution Environments (TEEs) without rewriting for particular platforms or SDKs. It handles attestation and delivery into a run-time “Keep” based on WebAssembly, offering developers a wide range of language choices for implementation. Enarx is CPU-architecture independent, enabling the same application code to be deployed across multiple targets, abstracting issues such as cross-compilation and differing attestation mechanisms between hardware vendors. Work is currently underway on AMD SEV and Intel SGX.

### Storage
* [FASTER](https://github.com/microsoft/FASTER): 
Managing large application state easily, resiliently, and with high performance is one of the hardest problems in the cloud today. The FASTER project offers two artifacts to help tackle this problem.
  -   **FASTER Log** is a high-performance concurrent persistent recoverable log, iterator, and random reader library in C#. It supports very frequent commit operations at low latency, and can quickly saturate disk bandwidth. It supports both sync and async interfaces, handles disk errors, and supports checksums. Learn more about the FASTER Log in C# here: [github](https://github.com/microsoft/FASTER/blob/master/docs/cs/FasterLog.md) | [web](https://microsoft.github.io/FASTER/cs/fasterlog).
  -   **FASTER KV** is a concurrent key-value store + cache (available in C# and C++) that is designed for point lookups and heavy updates. FASTER supports data larger than memory, by leveraging fast external storage (local or cloud). It also supports consistent recovery using a new checkpointing technique that lets applications trade-off performance for commit latency. Learn more about the FASTER KV in C# here: [github](https://github.com/microsoft/FASTER/blob/master/docs/cs/FasterKV.md) | [web](https://microsoft.github.io/FASTER/cs/fasterkv). For FASTER C++, check here: [github](https://github.com/microsoft/FASTER/blob/master/docs/cc) | [web](https://microsoft.github.io/FASTER/cc).
 
### Golang
* [JS Promises in Golang](https://withblue.ink/2020/10/03/go-webassembly-http-requests-and-promises.html)

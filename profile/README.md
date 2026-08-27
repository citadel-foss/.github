# Citadel FOSS
**Decentralizing the Bitcoin ecosystem's critical infrastructure.** 

## About
We build protocols and infrastructure on Bitcoin and other L2S to enhance interoperability, censorship resistance, and decentralization. Built with love by diverse communities of open source developers from the Global South, under pure FOSS licenses.  

**OpenSwap** is our first foundational protocol; it facilitates trustless Atomic Swaps over a decentralized marketplace embedded in the Bitcoin blockchain, and discoverable via Nostr. Allowing anyone to participate in the swap market, provide liquidity, and earn fees. The marketplace is sybil-resistant using Fidelity Bonds. Swaps can be routed through multiple makers and can bridge between other layers from Bitcoin, like Lightning, Ecash, Liquid, etc. 

Providing a decentralized alternative to create a healthy and resilient swap market, without any Central Point of Failure.

Website: https://citadelfoss.xyz/

## Projects
*Core libraries and applications*
| Project | Repository | Description |
|---------|------------|-------------|
| **OpenSwap Core** | [openswap](https://github.com/citadel-foss/openswap) | Core libraries and infrastructures for [Maxwell-Belcher AtomicSwap Protocol](https://gist.github.com/chris-belcher/9144bd57a91c194e332fb5ca371d0964) |
| **OpenSwap-FFI** | [openswap-ffi](https://github.com/citadel-foss/openswap-ffi) | Language bindings over OpenSwap Core library |
| **Taker App** | [taker-app](https://github.com/citadel-tech/taker-app) | An example desktop client built in Nodejs using the openswap-ffi |
| **Maker Dashboard** | [maker-dashboard](https://github.com/citadel-tech/maker-dasboard) | A GUI dashboard for managing multiple maker servers. Built to run on home node servers |
*Auxiliary Infrastructures*
| Project | Repository | Description |
|---------|------------|-------------|
| **mill-io** | [mill-io](https://github.com/citadel-tech/mill-io) | A lightweight, performant io library in Rust, for efficient non-blocking io operations without heavyweight async runtimes |
| **rust-coinselect** | [rust-coinselect](https://github.com/citadel-tech/rust-coinselect) | A coin-selection library in Rust to perform CS via multiple algorithms and choose the best result based on waste metrics, inspired by CS algorithms of Bitcoin Core |
## Documentation & Research
*Protocol specifications and experimental implementations*
| Project | Repository | Description |
|---------|------------|-------------|
| **Protocol Specification** | [OpenSwap-Protocol-Specification](https://github.com/citadel-foss/OpenSwap-Protocol-Specification) | Technical specification for the OpenSwap Protocol |

## Security
We take the security of our protocols and infrastructure seriously. If you discover a vulnerability, please report it responsibly.

**Please do not open public GitHub issues for security vulnerabilities.**

To report a security issue, email **security@citadelfoss.xyz** with a description of the vulnerability, steps to reproduce, and its potential impact. We will acknowledge your report and work with you on disclosure and remediation.

## Community
We believe in not just Open Source, but Open Development too. Whether you are a protocol nerd or a casual user,  
join our [Matrix Forum](https://matrix.to/#/#ciatdel-foss:matrix.org) to discuss development, app usage, or just to hang around with the dev community.

# Lean Ethereum Resources

Last updated: 2026-02-22

## 1. Documentation

### Official entry points
- [Lean Ethereum](https://blog.ethereum.org/2025/07/31/lean-ethereum) - Official Ethereum blog post introducing the Lean Ethereum direction (published 2025-07-31).
- [Lean Consensus Roadmap](https://leanroadmap.org/) - Live roadmap board tracking Lean Consensus workstreams and milestone status.

### Communication / updates
- [Lean Ethereum on X](https://x.com/leanEthereum) - Social channel for announcements, call reminders, and ecosystem updates.
- [PQ Interop Notes](https://github.com/leanEthereum/pm/tree/main/breakout-rooms/leanConsensus/pq-interop) - Meeting notes and coordination docs for Lean Consensus PQ interop.
- [leanEthereum/pm](https://github.com/leanEthereum/pm) - Main process repository for Lean Ethereum breakout rooms and call materials.

## 2. Specs and Ecosystem Tooling

### Core spec + reference implementations
- [leanSpec](https://github.com/leanEthereum/leanSpec) - Core specification repository for Lean Ethereum protocol components.
- [leanSig](https://github.com/leanEthereum/leanSig) - Post-quantum signature implementation work for Lean Ethereum.
- [leanMultisig](https://github.com/leanEthereum/leanMultisig) - Signature aggregation and minimal-zkVM-oriented multisig research code.
- [leanMetrics](https://github.com/leanEthereum/leanMetrics) - Metrics/spec tooling for evaluating Lean Consensus behavior.

### Ecosystem article (engineering practice)
- [Ethlambda Shared Tooling](https://blog.lambdaclass.com/ethlambda-building-a-post-quantum-ethereum-client-with-the-help-of-shared-tooling) - Engineering write-up on building a post-quantum Ethereum client with shared tooling.
- [Introducing Ethlambda](https://blog.lambdaclass.com/introducing-ethlambda-a-lean-consensus-client-for-ethereums-next-era/) - Intro article for a Lean-consensus-oriented client effort.

## 3. Lean Consensus

### Devnet / interop tracking
- [PQ Interop Devnet Tracking and Breakout Meetings](https://github.com/leanEthereum/pm/blob/main/breakout-rooms/leanConsensus/pq-interop/)

### Implementations
- [Ream](https://github.com/ReamLabs/ream) - Lean Consensus client implementation in Rust.
- [Zeam](https://github.com/blockblaz/zeam) - Lean Consensus client implementation in Zig.
- [Ethlambda](https://github.com/lambdaclass/ethlambda) - A minimalist and fast Lean Consensus client in Rust by LambdaClass.
- [Lighthouse](https://github.com/sigp/lighthouse) - Widely used consensus client, useful as baseline and interoperability reference.
- [Lantern](https://github.com/Pier-Two/lantern) - Lean-related client implementation in C, often used for lightweight system-level experimentation.
- [Qlean-mini](https://github.com/qdrvm/qlean-mini) - Lean Ethereum PQ devnet client implementation in C++.

## 4. Lean Data

Current status: dedicated "Lean Data" canonical doc is still mostly referenced through the main Lean Ethereum vision + related research threads.

- [Lean Ethereum Data Direction](https://blog.ethereum.org/2025/07/31/lean-ethereum) - High-level description of Blobs 2.0 and related data-layer direction.
- [3SF + PeerDAS Integration](https://ethresear.ch/t/integrating-3sf-with-epbs-focil-and-peerdas/22909) - Research discussion connecting finality and data availability design.

### Implementations

## 5. Lean Execution

Current status: dedicated canonical execution spec is still evolving; practical references are around zkVM + aggregation and formal verification tracks.

- [Lean Ethereum Execution Direction](https://blog.ethereum.org/2025/07/31/lean-ethereum) - High-level EVM 2.0 and SNARK-friendly execution vision.
- [PQ Signature Aggregation (Folding)](https://ethresear.ch/t/post-quantum-signature-aggregation-a-folding-approach/23639) - Research proposal for post-quantum aggregation.
- [Verified zkEVMs](https://verified-zkevm.org/) - Project site for formal verification efforts around zkEVM components.
- [ArkLib](https://github.com/Verified-zkEVM/ArkLib) - Lean formalization codebase used in verified zkEVM research.
- [ArkLib Blueprint](https://verified-zkevm.github.io/ArkLib/blueprint/index.html) - Generated technical docs for ArkLib.

### Implementations

## 6. Research Reading List

### Poseidon Cryptanalysis Initiative
- [Poseidon Cryptanalysis Initiative](https://www.poseidon-initiative.info/) - EF-led initiative tracking bounties, grants, and cryptanalysis progress for Poseidon/Poseidon2.
- [Poseidon2: A Faster Version of the Poseidon Hash Function](https://eprint.iacr.org/2023/323) - Baseline Poseidon2 paper used as a core reference in this track.
- [Attacking Poseidon via Graeffe-Based Root-Finding over NTT-Friendly Fields](https://eprint.iacr.org/2025/937) - Cryptanalysis result explicitly listed in roadmap resources.
- [Breaking Poseidon Challenges with Graeffe Transforms and Complexity Analysis by FFT Lower Bounds](https://eprint.iacr.org/2025/950) - Follow-up analysis included in roadmap-linked resources.
- [Poseidon and Neptune: Groebner Basis Cryptanalysis Exploiting Subspace Trails](https://eprint.iacr.org/2025/954) - Additional cryptanalysis reference from the same track.

### Hash-Based Multi-Signatures
- [Hash-Based Multi-Signatures for Post-Quantum Ethereum](https://eprint.iacr.org/2025/055) - Foundational post-quantum multisignature proposal.
- [At the Top of the Hypercube (ePrint 2025/889)](https://eprint.iacr.org/2025/889) - Follow-up optimization research for hash-based signatures.
- [Towards Hash-Based Multi-Signatures for Post-Quantum Distributed Validators](https://github.com/ObolNetwork/pqdv/blob/main/doc/main.pdf) - Distributed validator-focused design document listed by roadmap resources.
- [hash-sig (Rust reference implementation)](https://github.com/b-wagn/hash-sig) - Prototype implementation linked from roadmap resources.

### Minimal Zero-Knowledge Virtual Machines
- [Benchmark Hash in SNARK](https://hackmd.io/%40han/bench-hash-in-snark) - Benchmarking notes for hash performance in SNARK settings.
- [Hash-based Signature Aggregation](https://hackmd.io/%40han/hash-sig-agg) - Working notes on aggregation strategies for hash-based signatures.
- [Circuit gadgets](https://hackmd.io/%40tcoratger/SyWbmVPckx) - Circuit-level exploration notes for minimal zkVM pathways.
- [WHIR paper overview](https://gfenzi.io/papers/whir/) - Reference material for WHIR-related exploration listed in roadmap resources.

### Formal Verification
- [Verified zkEVMs](https://verified-zkevm.org/) - Project hub for formal verification workstreams.
- [ArkLib](https://github.com/Verified-zkEVM/ArkLib) - Lean formalization code for arguments of knowledge.
- [leanblueprint](https://github.com/PatrickMassot/leanblueprint) - Blueprint tooling referenced by roadmap formal verification resources.
- [ArkLib Blueprint](https://verified-zkevm.github.io/ArkLib/blueprint/index.html) - Generated blueprint/docs for the formalization effort.

### P2P Networking
- [Practical Rateless Set Reconciliation](https://arxiv.org/abs/2402.02668) - Paper reference listed in roadmap networking resources.
- [Research Track: P2P Networking](https://leanroadmap.org/#research-tracks) - Canonical entry point for the Generalised Gossipsub and Gossipsub v2.0 spec links.

## 7. Learning and MOOCs

### Videos
- [Lean Ethereum Playlist](https://www.youtube.com/watch?v=Dad2UonQ9Ag&list=PLJqWcTqh_zKGGuO_q1dgYLsfUoX1sNhWM) - Core videos introducing Lean Ethereum background and goals.
- [Post-Quantum Transaction Signature Playlist](https://www.youtube.com/watch?v=QCkLjyTVCT0&list=PLJqWcTqh_zKEOum3uR0odkH59fmGUYuZB) - Talks focused on PQ transaction signatures.
- [Post-Quantum (PQ) Interop Call Playlist](https://www.youtube.com/watch?v=AeCY-vabyuY&list=PLJqWcTqh_zKF_Q9HNXBLW_AtktsjToTIu) - Interop call recordings and progress discussions.
- [Lean Consensus Call Playlist](https://www.youtube.com/watch?v=hAIp_JHrr4I&list=PLJqWcTqh_zKF4GUIrzfikZ6hKebVVRc30) - Ongoing Lean Consensus call series in playlist form.

### Suggested learning path for this topic
1. Read the Lean Ethereum vision post.
2. Track roadmap progress and devnet milestones.
3. Follow one client repo (Ream or Zeam) end-to-end.
4. Read 3SF + PQ aggregation threads.
5. Start experimenting with leanSpec test vectors.

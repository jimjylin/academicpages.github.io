---
title: "Formally Verified Memory Protection for a Commodity Multiprocessor Hypervisor"
collection: publications
permalink: /publication/2021-11-13-paper-title-number-2
excerpt: 'Hypervisors are widely deployed by cloud computing providers to support virtual machines, but their growing complexity poses a security risk, as large codebases contain many vulnerabilities. We present SeKVM, a layered Linux KVM hypervisor architecture that has been formally verified on multiprocessor hardware. Using layers, we isolate KVM&apos;s trusted computing base into a small core such that only the core needs to be verified to ensure KVM&apos;s security guarantees. Using layers, we model hardware features at different levels of abstraction tailored to each layer of software. Lower hypervisor layers that configure and control hardware are verified using a novel machine model that includes multiprocessor memory management hardware such as multi-level shared page tables, tagged TLBs, and a coherent cache hierarchy with cache bypass support. Higher hypervisor layers that build on the lower layers are then verified using a more abstract and simplified model, taking advantage of layer encapsulation to reduce proof burden. Furthermore, layers provide modularity to reduce verification effort across multiple implementation versions. We have retrofitted and verified multiple versions of KVM on Arm multiprocessor hardware, proving the correctness of the implementations and that they contain no vulnerabilities that can affect KVM&apos;s security guarantees. Our work is the first machine-checked proof for a commodity hypervisor using multiprocessor memory management hardware. SeKVM requires only modest KVM modifications and incurs only modest performance overhead versus unmodified KVM on real application workloads.'
date: 2021-11-13
venue: 'USENIX Security 2021'
paperurl: 'https://www.usenix.org/conference/usenixsecurity21/presentation/li-shih-wei'
---

<a href='https://www.usenix.org/conference/usenixsecurity21/presentation/li-shih-wei'>Download paper here</a>

Hypervisors are widely deployed by cloud computing providers to support virtual machines, but their growing complexity poses a security risk, as large codebases contain many vulnerabilities. We present SeKVM, a layered Linux KVM hypervisor architecture that has been formally verified on multiprocessor hardware. Using layers, we isolate KVM&apos;s trusted computing base into a small core such that only the core needs to be verified to ensure KVM&apos;s security guarantees. Using layers, we model hardware features at different levels of abstraction tailored to each layer of software. Lower hypervisor layers that configure and control hardware are verified using a novel machine model that includes multiprocessor memory management hardware such as multi-level shared page tables, tagged TLBs, and a coherent cache hierarchy with cache bypass support. Higher hypervisor layers that build on the lower layers are then verified using a more abstract and simplified model, taking advantage of layer encapsulation to reduce proof burden. Furthermore, layers provide modularity to reduce verification effort across multiple implementation versions. We have retrofitted and verified multiple versions of KVM on Arm multiprocessor hardware, proving the correctness of the implementations and that they contain no vulnerabilities that can affect KVM&apos;s security guarantees. Our work is the first machine-checked proof for a commodity hypervisor using multiprocessor memory management hardware. SeKVM requires only modest KVM modifications and incurs only modest performance overhead versus unmodified KVM on real application workloads.
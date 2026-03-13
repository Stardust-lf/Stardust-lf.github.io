---
permalink: /publications/
title: "Publications"
author_profile: true
---

<!-- ASPLOS 2026 -->
<div>
{% include pubcard.html
    img="/assets/paper_poster/ASPLOS.png"
    venue="ACM ASPLOS 2026 (Top-tier)"
    title="ReliaFHE: Resilient Design for Fully Homomorphic Encryption Accelerators"
    authors="<strong>Fan Li</strong>, Mayank Kumar, Ruizhi Zhu, Mengxin Zheng, Qian Lou, Xin Xin*"
    desc="We integrate lightweight checksum-based protection into FHE accelerators, tailored for NTT, base conversion, and element-wise kernels. ReliaFHE improves reliability by over 10,000x with only ~1.5% performance overhead."
%}
</div>

<!-- HPCA 2026 -->
<div>
{% include pubcard.html
    img="/assets/paper_poster/HPCA.png"
    venue="IEEE HPCA 2026 (Top-tier)"
    title="ASPA: Reassigning DDR5 Parity Bandwidth"
    authors="<strong>Fan Li</strong>, Qiufeng Li, Yanan Guo, Weidong Cao, Xin Xin*"
    link="https://ieeexplore.ieee.org/document/11408447"
    desc="We reclaim the 25% parity bandwidth overhead in DDR5 by leveraging on-die CRC units to generate lightweight second-tier parity, boosting effective bandwidth without sacrificing reliability."
%}
</div>

<!-- PACT 2025 -->
<div>
{% include pubcard.html
    img="/assets/paper_poster/PACT.png"
    venue="ACM/IEEE PACT 2025 (Top-tier)"
    title="SCREME: A Scalable Framework for Resilient Memory Design"
    authors="<strong>Fan Li</strong>, Mimi Xie, Yanan Guo, Huize Li, Xin Xin*"
    link="https://ieeexplore.ieee.org/document/11282510"
    desc="We break the assumption that ECC chips must match data chip performance, repurposing cost-effective slower chips and underutilized on-DIMM I/O resources to build a scalable memory protection framework."
%}
</div>

<!-- ICCD 2025 -->
<div>
{% include pubcard.html
    img="/assets/paper_poster/ICCD.png"
    venue="IEEE ICCD 2025"
    title="PIM-SUM: Fast and Reliable In-Memory Summation for Recommendation Systems"
    authors="<strong>Fan Li</strong>, Ruizhi Zhu, Huize Li, Di Wu, Xin Xin*"
    link="https://ieeexplore.ieee.org/document/11311106"
    desc="We reformulate in-DRAM vector summation as column-wise popcount accumulation, eliminating long carry propagation. PIM-SUM achieves up to 5.14x speedup on DLRM workloads with Reed-Solomon-inspired error correction."
%}
</div>

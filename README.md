# 「文献检索与科技论文写作」课程大作业

题目: 网络审查与抗审查技术综述

![许多人拿梯子翻越一堵冒着火的高墙](./image/cover.png)

## 摘要

近些年来，随着互联网的飞速发展和加密技术的不断革新，信息传播的方式和渠道变得更加多样化。
然而，这种技术进步在推动信息自由流动的同时，也对传统的安全审查系统带来了前所未有的挑战。
传统的审查手段在面对加密通信、去中心化网络以及信息熵规避等新技术时，往往显得力不从心。
为此，本文将对近年来审查与抗审查技术的最新进展进行分析，探讨这些技术的演化趋势、核心机制及其对互联网安全与隐私的影响，为相关领域的研究和实践提供参考和启示。

## 关键词

- 网络安全
- 加密技术
- 混淆技术
- 审查系统

## 绪论

自网络诞生以来，网络安全一直是一个备受关注的核心议题。最初，人们对网络安全的重视程度较低，这种疏忽导致了大量的数据泄露和经济损失。然而，随着网络技术的不断发展，人们逐渐意识到保护网络信息的重要性，并开始探索各种安全防护手段。从最初的简单防火墙到后来的代理技术，网络安全防护手段经历了多个发展阶段。

随着技术的进步，加密通信逐渐成为网络安全的核心手段。SSL (Secure Sockets Layer) 和 TLS (Transport Layer Security) 协议的出现，为网络通信提供了基础的加密保护。随后，更多先进的技术手段被开发出来，例如 VPN 隧道实现通过广域网传输的安全通信、以及 Tor 网络提供匿名性和抗审查能力。

近年来，更加复杂和先进的技术陆续涌现，例如 Shadowsocks 的数据包全加密技术、V2Ray 的多协议支持和新型加密方式、Trojan 通过 HTTPS 伪装流量、Hysteria 利用 QUIC 协议进行伪装通信，以及 NaiveProxy 基于 Chromium 网络栈以避免 TLS 指纹识别的先进伪装技术。这些技术为用户提供了更高效、更隐蔽的通信方式。

与此同时，审查技术也在不断进化。传统的 DNS 污染和 TCP 数据流关键字匹配逐渐发展为更复杂的手段，例如 TCP 中间人 Reset 攻击、路由黑洞、数据流熵检测、重放攻击和主动探测等。每一种新的审查技术都对抗审查手段提出了更高的要求，形成了技术与反技术的持续博弈。

在这种对抗过程中，大量创新性技术被发明并应用于网络安全领域。这些技术的不断演化不仅推动了网络安全的进步，也为学术研究和工程实践提供了丰富的参考。本研究旨在系统分析近年来网络审查与抗审查技术的进展，总结其发展脉络和核心机制，并探讨这些技术对未来网络安全的潜在影响。

## 结论

[^1]: Wu M, Sippe J, Sivakumar D, et al. How the Great Firewall of China detects and blocks fully encrypted traffic[C]//32nd USENIX Security Symposium (USENIX Security 23). 2023: 2653-2670.
[^2]: Xue D, Kallitsis M, Houmansadr A, et al. Fingerprinting Obfuscated Proxy Traffic with Encapsulated {TLS} Handshakes[C]//33rd USENIX Security Symposium (USENIX Security 24). 2024: 2689-2706.
[^3]: Hoang N P, Dalek J, Crete-Nishihata M, et al. {GFWeb}: Measuring the Great Firewall's Web Censorship at Scale[C]//33rd USENIX Security Symposium (USENIX Security 24). 2024: 2617-2633.
[^4]: Wedwards E. Bleeding Wall: A Hematologic Examination on the Great Firewall[J]. Free and Open Communications on the Internet, 2024.
[^5]: Alice, Bob, Carol, et al. How china detects and blocks shadowsocks[C]//Proceedings of the ACM Internet Measurement Conference. 2020: 111-124.

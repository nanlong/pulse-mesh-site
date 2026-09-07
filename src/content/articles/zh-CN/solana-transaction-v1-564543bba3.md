---
decisionKey: "564543bba3b794b74c5e9c8bc70bbfdd5fd4e8aa703800e5139202b241519288"
language: "zh-CN"
title: "Solana 即将激活 Transaction v1，交易体量扩大至三倍"
summary: "Solana 计划于周三激活 Transaction v1 功能，交易大小上限提升至原来的三倍，以支持更复杂的证明和大型多签操作放入同一笔交易。协议升级同时要求依赖链上数据的服务商进行相应更新。"
publishedAt: "2026-09-07T16:49:27.925Z"
score: 0.8
topics:
  - "Solana"
  - "Protocol Upgrade"
  - "Transaction v1"
  - "Network Scalability"
sourceUrls:
  - "https://www.coindesk.com/tech/2026/09/07/solana-to-triple-transaction-size-as-apps-get-room-for-more-complex-trades"
---

Solana 协议升级 Transaction v1 将于本周三（2026年9月9日）正式激活。据 CoinDesk 报道，此次升级将使单笔交易可承载的数据量扩大至现有上限的三倍，为复杂证明和大规模多签操作在单笔交易内完成提供空间。

这是 Solana 在交易处理能力方面的一次结构性调整，直接面向需要更高单笔交易容量的链上应用场景。此前受限于交易大小，部分复杂的验证逻辑或大型多签需要拆分为多笔交易或依赖链下处理。Transaction v1 激活后，开发团队可以将更多执行逻辑和签名数据直接整合到一笔交易中。

需要明确的是，此次升级并非简单的参数调整，还涉及交易格式或验证规则的改变。凡是负责读取或解析 Solana 链上交易的服务节点——包括网络浏览器、交易分析平台和部分基础设施提供商——都需要在升级时同步更新，否则可能出现对交易数据结构解析错误或无法识别的情况。

该升级目前仅处于激活阶段，后续生态内各应用能否充分利用扩大的交易空间，仍需根据各自合约实现与业务需求加以评估。对于普通用户而言，在激活初期部分第三方服务若尚未完成更新，可能在显示历史交易或部分链上操作时出现短暂异常。

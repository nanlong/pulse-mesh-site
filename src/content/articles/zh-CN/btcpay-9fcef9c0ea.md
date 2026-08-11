---
decisionKey: "9fcef9c0ead935365ca157b4607f826ac5fbaa5a074352b8c3701b4309ebda32"
language: "zh-CN"
title: "BTCPay 支持者悬赏比特币，追回钱包漏洞中被盗资金"
summary: "针对攻击者获取关联 LND 钱包访问权限后盗走比特币的事件，BTCPay 支持者发起比特币赏金，旨在追回被盗资产。此事件凸显自托管支付基础设施中关联钱包的安全风险，提醒用户关注 LND 钱包配置与访问控制。"
publishedAt: "2026-08-11T22:00:56.366Z"
score: 0.9
topics:
  - "Security"
  - "Bitcoin"
  - "Wallet Exploit"
  - "BTCPay"
sourceUrls:
  - "https://decrypt.co/375376/btcpay-bitcoin-bounty-critical-wallet-exploit"
---

**事件概述**

BTCPay Server 的支持者提供了一笔比特币赏金，用于追回在钱包漏洞中被盗的比特币。据现有信息，攻击者成功获取了与 BTCPay 关联的 LND（Lightning Network Daemon）钱包的访问权限，并盗走了其中的比特币。

**已确认事实**

- BTCPay 相关支持者设置了一项比特币赏金，目的是追回被盗资金。
- 攻击者获取了关联 LND 钱包的访问权限，并实施了盗币行为。

**影响与推断**

- BTCPay Server 广泛应用于自托管比特币支付场景，此事件表明即使自托管基础设施也可能因 LND 钱包配置或访问控制缺陷而遭受资金损失。
- 赏金的设立反映了社区对追回资产的迫切需求，同时也提醒运行 BTCPay 的用户重新审视自身节点的安全设置，特别是 LND 钱包的密钥管理、备份和访问权限。
- 目前公开信息有限，具体漏洞细节、被盗金额及受影响范围尚未披露，需等待官方进一步公告。

**风险提示**

本文仅为事件信息整理，不构成任何投资建议。比特币和数字资产存在较高风险，用户应做好安全防护并关注官方渠道的更新。

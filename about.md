---
layout: info
permalink: /about/
title: 方案简介
---

区块链 Layer 2 是指构建在现有区块链系统之上的辅助框架或协议。 这些协议的主要目标是解决主要加密货币网络面临的交易速度和扩展困难。例如，比特币和以太坊仍然无法每秒处理数千笔交易（TPS），这不利于它们的长期应用。 在可以有效地采用和更广泛地使用这些网络之前，需要更高的吞吐量。
在这种情况下，术语“Layer 2”是指针对区块链可扩展性问题提出的多种解决方案, 其中两个主要示例是比特币闪电网络和以太坊 Plasma。 尽管有自己的工作机制和特殊性，但这两种解决方案都在努力为区块链系统提供更高的吞吐量。



从更广泛的意义上讲，Layer 2 协议创建了一个辅助框架，其中区块链交易和流程可以独立于第 1 层（主链）进行。 出于这个原因，这些技术也可以称为“链下”扩展解决方案。例如，具体来说，闪电网络基于状态通道 (state channel)，状态通道基本上是在线下执行区块链操作然后将它们报告给主链的附加通道。 状态通道主要用作支付通道。 另一方面，Plasma 框架由侧链 （side chain）组成，侧链本质上是排列成树状结构的小型区块链。

使用链下解决方案的主要优势之一是主链不需要经过任何结构变化，因为第二层是作为额外的层添加的。 因此，第 2 层解决方案有可能在不牺牲网络安全性的情况下实现高吞吐量。
换句话说，由主链执行的大部分工作都可以转移到第二层。 因此，虽然主链（第 1 层）提供安全性，但第二层提供高吞吐量，每秒能够执行数百甚至数千个事务。

目前市场上存在的layer 2 设计方案，例如，zk-Rollup，Plasma, Nocust 他们都引入了一个交易托管来线下处理用户的交易。 这些方案致力于将大量的计算从线上移到线下，但大多数方案没有考虑到用户的隐私性。 用户的余额和交易数据在这些系统中都是透明的，这一点很不利于用户的隐私。 然而，想要同时具有扩展性和隐私性很难，因为增加系统的隐私形势比增加更多的数据和计算量，从而降低区块链的吞吐量， 增加交易的费用。扩展性和隐私性，是硬币的两面，需要适当的取舍。
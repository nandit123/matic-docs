---
id: approve-all
title: approveAll
keywords:
- 'pos client, erc721, approveAll, polygon, sdk'
description: 'อนุมัติโทเค็นทั้งหมด'
---

ใช้เมธอด `approveAll` เพื่ออนุมัติโทเค็นทั้งหมดได้

```
const erc721RootToken = posClient.erc721(<root token address>, true);

const approveResult = await erc721RootToken.approveAll();

const txHash = await approveResult.getTransactionHash();

const txReceipt = await approveResult.getReceipt();

```
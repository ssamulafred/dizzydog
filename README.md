# Introduction (/docs/risex)

import { Card, Cards } from 'fumadocs-ui/components/card';
import { Activity, FileCode } from 'lucide-react';

## Introduction to RISEx

RISEx is a fully onchain perpetuals exchange built on RISE Chain. Every trade, every position, and every piece of collateral exists onchain, settled in real-time with the same guarantees as any other RISE transaction.

Today, that means institutional-grade crypto perps with flexible collateral and programmable trading accounts. Tomorrow, that means equities, forex, commodities, and any asset with a price feed.

## What Makes RISEx Different?

Before RISEx Orderbook DEXs took two approaches, the offchain matching or dual-core execution. Both of these approaches introduce fragmentation between the exchange and the rest of DeFi.

RISEx makes no such tradeoff. The orderbook lives onchain and shares state with all of DeFi. Same block. Same transaction. Full atomicity. When you trade on RISEx, your order, your collateral, and every DeFi protocol on RISE exist in a single execution environment with unified liquidity.

This isn't just a better exchange. It's programmable market infrastructure. Use any ERC20 as collateral. Build modular sub-accounts that automate strategies or create new order types. Compose across lending markets, vaults, and the orderbook in one transaction. The design space that opens up when execution and liquidity are truly unified. That's what we're building for.

We call this Programmable Markets. Leverage anything, trade everything.

## Key Features

**For Users**

* **Permissionless Portfolio Margin**: Leverage everything. Use any supported collateral, LP positions, lending deposits, yield-bearing assets—as margin for your trades, with risk calculated across your entire portfolio.
* **AutoYield**: Put your idle collateral to work. Earn yield on your collateral while you trade, powered by onchain yield.

**For Builders**

* **Unmatched Performance**: As little as 1ms execution with a target of 100k TPS, powered by RISE's continuous execution pipeline and sub-50ms block times.
* **Synchronous Composability**: Orderbooks share state with AMMs, lending markets, and vaults in the same block, unlocking a design space impossible on fragmented venues.
* **Modular Sub-accounts**: Programmable trading accounts that anyone can build on. Automate strategies, delegate execution, or create entirely new trading primitives—all permissionlessly.

## Investors

RISE is backed by industry leaders investors including Galaxy Digital, Finality Capital, DACM, Vitalik Buterin and more.

## Documentation

<Cards>
  <Card icon={<Activity className="text-(--rise-purple)" />} title="API" href="/docs/risex/api/" description="REST API documentation with examples for trading, order management, and account operations" />

  <Card icon={<FileCode className="text-(--rise-purple)" />} title="Contract" href="/docs/risex/contracts/deployments" description="Smart contract interfaces, deployment addresses, and on-chain interaction guides" />
</Cards>

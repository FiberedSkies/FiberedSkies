### Hey I'm Estelle!

I'm an extremely curious transgender head of research at [Primitive](https://github.com/primitivefinance). My current academic obsession is molecular biophysics. Recently have taken the dive into financial derivative research.

- 🔭 Currently working on robust and capitally-efficient treasury management
- 🌱 I’m currently learning Rust
- 🥰 Pronouns: She/her
- ⚡ Fun fact: I'm purely obsessed with [This Must Be The Place - Talking Heads](https://www.youtube.com/watch?v=fsccjsW8bSY)

### Education

BSc - Mathematical Physics (In-progress)

Working through my degree in mathematical physics while I work in DeFi research! In my free time, I'm currently learning how to be a better simulation engineer and data scientist.

### DeFi Papers

- 📈 [Replicating Portfolios: Constructing Permissionless Derivatives](https://www.primitive.xyz/papers/Constructing_Permissionless_Derivatives.pdf)

**Abstract**: The current design space of derivatives in Decentralized Finance (DeFi) relies heavily on oracle systems. Replicating market makers (RMMs) provide a mechanism for converting specific payoff functions to an associated Constant Function Market Makers (CFMMs). We leverage RMMs to replicate the approximate payoff of a Black-Scholes covered call option. RMM-01 is the first implementation of an on-chain, black scholes priced, expiring option mechanism that relies on arbitrage rather than an external oracle for price. We provide frameworks for derivative instruments and structured products achievable on-chain without relying on oracles. We construct long and binary options and briefly discuss perpetual covered call strategies commonly referred to as "theta vaults." Moreover, we introduce a procedure to eliminate liquidation risk in lending markets. The results suggest that CFMMs are essential for structured product design with minimized trust dependencies.

- 🕹️ [Financial Virtual Machine](https://www.primitive.xyz/papers/yellow.pdf)

**Abstract**: This document descibes the design implications of building a Finite State Machine (FSM) with its own opcodes on top of the Ethereum Virtual Machine (EVM). We examine this design pattern in the context of Decentralized Finance (DeFi) in what we call the Financial Virtual Machine (FVM). The FVM is designed to be a general purpose FSM that can be used to in- teract with variety of financial primitives. Also, it provides an interface over atomicity and the ability to reason about program correctness. In particular, FVM enables users to take multiple actions on their portfolios within an single commit to Ethereum. The individual transactions in FVM can also ac- crue transient debt, but no lasting debt will be written to the blockchain due to the validation of state after processing. For example, rebalancing an arbitrary amount of positions can be done atomically which drastically simplifies both the design and removes the need for signing multiple transactions. The FVM is a critical component of Primitive’s Portfolio protocol, which builds on top of Constant Function Market Maker (CFMM) Liquidity Provider (LP) positions.

- 🏛️ [Primitive RMM-01](https://www.primitive.xyz/papers/Whitepaper.pdf)

**Abstract**: Constant function market makers (CFMMs) have evolved from a small group of decentralized exchanges (DEXs) to a broad and largely undiscovered class of automated market makers (AMMs). CFMMs are decentralized exchanges fully backed by a community of liquidity providers seeking to earn a yield on their deposited assets. The portfolio of a liquidity provider follows a payoff structure specific to the CFMM they are providing liquidity too. It was recently shown that the space of concave, non-negative, non-decreasing, 1-homogeneous payoff functions and the space of convex CFMMs are equivalent, along with a method to convert between a given payoff of the above type with an associated CFMM. These CFMMs, which replicate specific, desired payoff functions, are called replicating market makers (RMMs). In this paper, we present an implementation of an RMM that approximates a Black–Scholes covered call, which we call RMM-01.

### Blog Posts

- 🌱 [Introduction to On-Chain Portfolio Management](https://www.primitive.xyz/posts/RMMTech)

**ELI5**: Details the mechanism of action behind two key use cases of Replicating Market Makers (RMMs): replicating specific portfolios and dynamically allocating spot liquidity with reduced rebalance needs. Proceeds to highlight how these use cases make great tools in on-chain portfolio management, particularly in the context of treasury management.

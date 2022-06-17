### Hey I'm Estelle!

I'm the mildly crazy and extremely nerdy transgender head of research at [Primitive](https://github.com/primitivefinance). My research interests include computational approaches the gravitational physics and stellar structures and evolution. Recently have taken the dive into AMM and financial derivative research.

- 🔭 Currently building a generalized CFMM simulation package with [@experiencedft](https://github.com/experiencedft). Intention is to structure a large variety of sim needs at Primitive around this including our Theta Vault simulations.
- 🌱 I’m currently learning about MEV
- 🥰 Pronouns: She/her
- ⚡ Fun fact: I'm purely obsessed with [This Must Be The Place - Talking Heads](https://www.youtube.com/watch?v=fsccjsW8bSY)

### Education

BSc (currently on break) - Mathematical Physics

Paused my pursuit of a Bachelor's to focus on building and researching whatever my heart desires in the DeFi derivatives space for Primitive.

### DeFi Research

- 📈 [Replicating Portfolios: Constructing Permissionless Derivatives](https://primitive.xyz/rmm-derivatives.pdf)

**Abstract**: The current design space of derivatives in Decentralized Finance (DeFi) relies heavily on oracle systems. Replicating market makers (RMMs) provide a mechanism for converting specific payoff functions to an associated Constant Function Market Makers (CFMMs). We leverage RMMs to replicate the approximate payoff of a Black-Scholes covered call option. RMM-01 is the first implementation of an on-chain, black scholes priced, expiring option mechanism that relies on arbitrage rather than an external oracle for price. We provide frameworks for derivative instruments and structured products achievable on-chain without relying on oracles. We construct long and binary options and briefly discuss perpetual covered call strategies commonly referred to as "theta vaults." Moreover, we introduce a procedure to eliminate liquidation risk in lending markets. The results suggest that CFMMs are essential for structured product design with minimized trust dependencies.

- 🏛️ [Primitive RMM-01](https://primitive.xyz/whitepaper-rmm-01.pdf)

**Abstract**: Constant function market makers (CFMMs) have evolved from a small group of decentralized exchanges (DEXs) to a broad and largely undiscovered class of automated market makers (AMMs). CFMMs are decentralized exchanges fully backed by a community of liquidity providers seeking to earn a yield on their deposited assets. The portfolio of a liquidity provider follows a payoff structure specific to the CFMM they are providing liquidity too. It was recently shown that the space of concave, non-negative, non-decreasing, 1-homogeneous payoff functions and the space of convex CFMMs are equivalent, along with a method to convert between a given payoff of the above type with an associated CFMM. These CFMMs, which replicate specific, desired payoff functions, are called replicating market makers (RMMs). In this paper, we present an implementation of an RMM that approximates a Black–Scholes covered call, which we call RMM-01.

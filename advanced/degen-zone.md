---
description: STRATEGIES AND GAME THEORY FOR THE MODERN DEGENERATE
---

# ⚠ DEGEN ZONE

The typical setup is to have 2 tokens, a stablecoin pegged to another asset, and a share token.

* The "peg" or "stable" or "algo" token (2OMB/3OMB)
* The share token (2SHARES/3SHARES)

The share value should appreciate as the protocol grows and more new money comes in. The price of the SHARES token correlates with how positive or negative the market sentiment is, and how fast the protocol grows. Another way to look at the SHARES is as a measure of peoples faith in the protocol. If this is an abundance, the price should reflect this positively.

Staking SHARES in the BOARDROOM/3ROOM is the main mechanic that prints and rewards 2OMB/3OMB to stakers. So, to get started one needs to either market buy some 2SHARES/3SHARES from on SpookySwap (Fast way), or buy 2OMB/3OMB and create LP with it then stake it in the FARMS and wait for share rewards to come in - and then stake those in BR/3ROOM. (Slow way)

The name of the game is accumulate 2SHARES/3SHARES to build up in the BOARDROOM/3ROOM stake. As long as the 2OMB/3OMB stays above peg, the BOARDROOM/3ROOM will keep printing, respectively.

The FARMS/3FARMS are for staking various asset LP, to earn rewards in 2SHARES/3SHARES to be staked into the BOARDROOM/3ROOM and this creates a sort of flow if you will, that drives the protocol

The 2OMB Smart Contracts, implement a Seignorage protocol. A protocol, in this context refers Solidity code that's being executed by the contract(s) on the blockchain. The protocol defines rules, parameters, definitons, functions, math, etc that make up the 2OMB system. This includes the algoritm(s) used by the protocol for various things. Protocol/Contract are often are used interchangeably, which is a semantics issue, not to put to fine a point on it. Anyhow, these protocols are useful for a few reasons;

* They are good at driving liquidity
* Works as an effective hedge against the pegged asset (FTM)
* Mirrored/liquid asset that is pegged to price of FTM,algorithmically

THE MAIN FLOW IS:

1. CREATE AND STAKE LP IN FARMS TO EARN 2SHARES/3SHARES
2. STAKE SHARES in the BR/3ROOM TO EARN INFLATIONARY 2OMB/3OMB REWARDS
3. CREATE MORE LP WITH _(some amount of BOARDROOM rewards)_ 3OMB/2OMB and wFTM
4. STAKE THE LP IN FARMS/3FARM

{% hint style="danger" %}
**THE FOLLOWING IS NOT FINANCIAL ADVICE, AND SHOULD NOT BE CONSIDERED AS SUCH - IT IS FOR ENTERTAINMENT AND EDUCATIONAL PURPOSES ONLY!!**
{% endhint %}

{% hint style="warning" %}
**SOME OF THESE STRATEGIES INVOLVE USING VAULTS/POOLS/SERVICES THAT ARE THIRD PARTY, WE ARE NOT LIABLE FOR ANY LOSS OF FUNDS, FOR ANY REASON, INCLUDING SMART CONTRACT RISK, SO PLEASE BE WARNED.**&#x20;
{% endhint %}

{% hint style="info" %}
The 2OMB/3OMB Smart Contracts,  implement a type of [**Seigniorage**](https://www.investopedia.com/terms/s/seigniorage.asp) protocol. A _protocol_, in this context refers Solidity code that was written, and has now been compiled and executed on the blockchain. The protocol itself defines the rules, parameters, definitions, functions, math, etc that make up the 2OMB/3OMB system. This includes the algorithm(s) used by the protocol for various things. Protocol/Contract are often are used interchangeably, which is a semantics issue, not to put to fine a point on it
{% endhint %}

## STRATEGIES

### _**60/40**_  "**The OG Seignorage strategy**"

Create 2OMB-wFTM LP as well as buying some 2SHARES with your BOARDROOM reward. Typically, doing this every time 'the money printer goes brrr' (every EPOCH) or at very least once a day. This creates buy pressure on FTM and buy pressure on SHARES.

Sometimes referred to as '60/40' and it is popular because it is healthy for the project and also a simple way of compounding that yields good results. It goes as follows;

The BOARDROOM prints every 6 hours (once at start of each EPOCH) Take your 2OMB rewards from the BOARDROOM

1. Take 60% and swap half of it for FTM
2. Create 2OMB-wFTM LP with the FTM you just got
3. Stake the 2OMB-wFTM LP in FARMS
4. Take the remaining 40% and swap for 2SHARES
5. Stake the 2SHARES in the BOARDROOM
6. Rinse & Repeat

### _50/50_ "The coin flip"

This is another popular strategy, if you are more conservative/patient and do not want to worry about buying 2SHARES (other than than/after the initial stake in BOARDROOM, obviously)

1. Take 50% of BOARDROOM rewards and sell for FTM
2. Take the other 50% and use it create 2OMB-wFTM LP with the FTM you just got
3. Stake the 2OMB-wFTM LP in the FARMS
4. Stake the 2SHARES earned from FARMS into the BOARDROOM


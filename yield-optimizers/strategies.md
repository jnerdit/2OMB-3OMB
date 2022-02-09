---
description: STRATEGIES AND GAME THEORY FOR THE MODERN DEGENERATE
---

# 📏 Strategies

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

{% hint style="info" %}
The following strats/examples I use '100' 2OMB/3OMB as the daily 24hr rewards from the BR/3ROOM (4 x 6 hour Epochs) because it makes math easy to do/visualize. Do note that these strats can be applied to any amount/value of 2OMB/3OMB. The numbers in the strategy names are percentages.&#x20;
{% endhint %}

{% hint style="warning" %}
None of the above strategies factor in profit taking. it is highly advisable and you would be smart to take profits when your position is up. Therefore, I have comprised a few strategies that use some of the tactics from the above strats, with daily profit taking.
{% endhint %}

{% hint style="success" %}
**To calculate the % of an integer remember;**

{100 x 0.60 = 60} == {60 = 60% of 100}&#x20;

{375 x 0.40 = 150} == {150 = 40% of 375}
{% endhint %}

## PROFIT TAKING STRATEGIES

### _**50/40/10**_** "10% ROI Marauder"**

This strategy achieves similar results to 60/40 or 50/50, but everyday you take profit out:

1. Take 50% of rewards (50) and sell for FTM
2. Take another 40% of tokens (40) and use them to pair up with FTM to create 2OMB-wFTM LP
3. The leftover 10% (10) tokens take as profit.

<mark style="color:red;">-- 2OMB</mark> | <mark style="color:green;">++wFTM</mark>

### _50/45/5_ "Nickel Bag"

Same as _50/40/10_ above except this is only taking out (realizing) 5% profits daily, while creating 5% more LP

1. Take 50% of rewards (50) and sell for FTM
2. Take another 45% of tokens (45) and use them to pair up with FTM to create 2OMB-wFTM LP
3. The leftover 5% (5) tokens take as profit.

<mark style="color:red;">--2OMB</mark> | <mark style="color:green;">++wFTM</mark>

### _**50/40/5/5**_** "FiveFive (10)"**

1. Take 50% of rewards and sell or FTM
2. Take 40% of rewards and create 2OMB-wFTM LP and stake in FARMS
3. Take 5% of rewards and buy 2SHARES and stake in BOARDROOM
4. Take 5% of rewards as profit

<mark style="color:red;">--2OMB</mark> | <mark style="color:green;">++wFTM</mark> | <mark style="color:green;">++2SHARES</mark>

### _60/30/10_ "Triple Cheese McBiscuit w/ Fries & Shake"

1. Take 30% of rewards (30) and sell for FTM
2. Take another 30% of tokens (30) and use them to pair up with FTM from step(1) to create 2OMB-wFTM LP and stake in FARMS
3. Take another 30% (30) and swap for 2SHARES and stake in BOARDROOM
4. The leftover 10% (10) tokens take as profit

<mark style="color:red;">--2OMB</mark> | <mark style="color:green;">++wFTM</mark> | <mark style="color:green;">++2SHARES</mark>

### _25/25/25_ "The Triple Quarter-Bonder w/ 3Cheese"

Another one to do after you have rewards or are breaking open LP. Also a good one if under-peg as the BOARDROOM stop printing while under peg so no reason to stake them there until its back above peg.

1. Sell 25% for FTM
2. Sell 25% for 2SHARES
3. Sell 25% for 3SHARES
4. BOND ALL THE 2SHARES and 3SHARES in the 3DAO
5. Claim VEST over 3 days in 3OMB
6. Create 3OMB-wFTM LP and stake into 3FARMS

<mark style="color:red;">--2OMB</mark> | <mark style="color:green;">++wFTM</mark> | <mark style="color:green;">++2SHARES</mark> | <mark style="color:green;">++3SHARES</mark>

### _**60/40/3**_** "The GOAT"**

{% hint style="success" %}
**Might be a good one while 3OMB is over peg and in price discovery and still landing**
{% endhint %}

Assuming you are in 2SHARES already, and maybe not yet as much in 3OMB, this is an option because it creates sell pressure on 3OMB helping bring it closer to stable, and also buy pressure on both 2OMB and FTM, as well as buy pressure on 3SHARES. Also helps fill treasury.

So, take your BOARDROOM rewards (2OMB) and do the following;

1. Take 60% of rewards and create 2OMB-wFTM LP, and stake in FARMS for more 2SHARES
2. Take 40% and buy 3SHARES with it and stake in 3ROOM
3. Take the 3OMB made from 3ROOM rewards and buy 50% 2OMB / 50% wFTM
4. Create 2OMB-wFTM LP from step (3)
5. Sell LP to the 3DAO for vested 3OMB
6. Sell the 3OMB for 2SHARES and stake them in the BOARDROOM
7. REPEAT

<mark style="color:red;">--3OMB</mark> | <mark style="color:red;">--2SHARES</mark> | <mark style="color:green;">++wFTM</mark> | <mark style="color:green;">++2OMB</mark> | <mark style="color:green;">++3SHARES</mark>

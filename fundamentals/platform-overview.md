---
description: UNDERSTANDING THE T|2|3 FINANCE PLATFORM
---

# 📢 Platform Overview

## Boardroom

* **Epoch duration**: 6 hours
* **Deposits / Withdrawal** of 2SHARES into/from Boardroom will lock 2SHARES for (2) epochs and 2OMB rewards for 1 epochs.&#x20;
* **2OMB rewards claim** will lock staked 2SHARES for 2 epochs and the next 2OMB rewards can only be claimed 1 EPOCH later
*   Distribution of 2OMB during **Expansion**

    **100%** as rewards for Boardroom stakers\
    **0%** goes to DAO fund

    **0%** goes to DEV fund
* **Epoch Expansion:** Current expansion cap base on 2OMB supply, if there are bonds to be redeemed, 65% of minted 2OMB goes to treasury until its sufficiently full to meet bond redemption. If there is no debt it will follow max capped expansion rate.

### Boardroom Dashboard Information <a href="#masonry-ui-available-information" id="masonry-ui-available-information"></a>

**Next Epoch:** Time remaining until end of current epoch. As **** indicated by the countdown timer.  Counting down the time until to the next epoch when it resets. (The duration of each epoch is 6 hours)

**Current Epoch:** This number represents the current epoch and how many epochs have passed since project launched

**2OMB Price (TWAP):** The price of 2OMB relative to FTM, this is the current **peg ratio**. Ex. if this number is 1.5 - this would indicate a 1 2OMB = 1.5 FTM (1:1.5)

**APR** refers to the simple returns in USD value relative to the amount of 2SHARES staked (USD value). _Note: **** APR fluctuates from time to time and is dependent on certain factors such as:_

* Price of 2OMB
* Price of 2SHARES
* Amount of 2SHARES staked in Masonry (Locked Value)

**2SHARES Staked:** This number represents the total amount of 2SHARES currently staked in the Boardroom.&#x20;

### Contraction Periods <a href="#masonry-on-contraction-periods" id="masonry-on-contraction-periods"></a>

{% hint style="warning" %}
Boardroom will **not** mint any 2OMB while TWAP < 1.01 (_NO REWARDS ON BOARDROOM_)
{% endhint %}

### :moneybag:Debt Phase <a href="#masonry-on-debt-phase" id="masonry-on-debt-phase"></a>

A Debt Phase takes place on the Expansion epochs that _**start after a**_ _**Contraction Period  and where there are still 2BOND to be redeemed**_. 65% of the normal Expansion rate (2OMB emission/supply) during a Debt Phase is allocated to the Treasury to prepare for 2BOND Redemption. This amount is still reserved whether or not 2BOND holders are redeeming bonds or not.&#x20;

Once the amount of 2OMB in the Treasury is sufficient to meet all circulating bond redemption, the expansion rates will return to normal.

## Shares

**2SHARES - 2OMB share token**

{% embed url="https://ftmscan.com/address/0xc54a1684fd1bef1f077a336e6be4bd9a3096a6ca" %}
Click here to view on the block explorer (https://ftmscan.com)
{% endembed %}

&#x20;Stake your LP in the FARMS tab to earn 2SHARES tokens

* 2OMB-wFTM LP: 35500 Shares
* 2SHARES-wFTM LP: 24000 Shares
* 2OMB-2SHARES LP: xxxxxx Shares

{% hint style="info" %}
**Farm pools (2SHARES Reward) will be available for 3 months**
{% endhint %}

## Bonds <a href="#pit-bonds" id="pit-bonds"></a>

**2BOND - 2OMB bond token**

{% embed url="https://ftmscan.com/address/0x9fe05f56c9a644eb92ee8f6987fd4edacb6da87d" %}
Click here to view on the block explorer (https://ftmscan.com)
{% endembed %}

2BOND (bond tokens) are available for purchase when 2OMB falls below the peg. If the 2OMB TWAP value is between 1.00 and 1.01, neither 2BOND nor 2OMB will be issued.

{% hint style="success" %}
Example: If the 2OMB (TWAP) < 1, 2BOND is issued and can be exchanged by swapping 2OMB for 2BOND at a 1:1 ratio (10 2OMB gets you 10 2BOND)
{% endhint %}

2BOND (bond tokens) are able to be redeemed when 2OMB (TWAP) >= 1&#x20;

To encourage the redemption of 2BOND for 2OMB when 2OMB (TWAP) > 1.1 and safely above peg, The incentive for users to do so, 2BOND redemption will be more profitable the higher the 2OMB (TWAP) value.&#x20;

2BOND to 2OMB ratio will be 1:R, where R can be calculated in the formula as shown below where coeff = 0.7

$$
R = 1 + [(2OMB(twapprice)-1)*coeff)]
$$

### What is 2BOND (Bonds)?

Bonds are unique tokens that can be utilized to help stabilize 2OMB price around peg (1 FTM) by reducing the circulating supply of 2OMB if the TWAP (time-weighted-average-price) goes below peg (1 FTM).

### When can I buy 2BOND (Bonds)?

2BOND can be purchased only on contraction periods when TWAP of 2OMB is below 1.

Every new epoch on contraction periods, 2BOND are issued in the amount of 3% of the current 2OMB circulating supply, with a max debt amount of 35%. This means that if bonds reach 35% of the circulating supply of 2OMB, no more bonds will be issued.

Note: 2BOND TWAP (time-weighted average price) is based on 2OMB price TWAP from the previous epoch as it ends.  This means that 2OMB TWAP is real-time and 2BOND TWAP is not.

### Where can I buy 2BOND (Bonds)?

You can buy 2BOND if any are available, through [**BONDS**](https://2omb.finance/bonds) page. Anyone can buy as many 2BOND as they want as long as they have enough 2OMB to pay for them, and there is some available.

There is a limit amount (3% of 2OMB current circulating supply) of available 2BOND per epoch while on contraction periods, and are sold as first come first serve.

### Why should I buy 2BOND (Bonds)?

First and most important reason is that bonds help maintain the peg, but will not be the only measure used to keep the protocol on track.

2BOND don't have an expiration date, so you can view them as an investment in the protocol because long term you get benefits from holding bonds.

#### Incentives for holding 2BOND&#x20;

The idea is to reward 2BOND buyers for helping the protocol, while also protecting the protocol from being manipulated by big players.

So after you buy 2BOND using 2OMB, you get 2 possible ways to get your 2OMB back:

1. Sell back your 2BOND for 2OMB while peg is between 1 - 1.1 (FTM) with no redemption bonus. This is to prevent instant dump after peg is recovered
2. Sell back your 2BOND for 2OMB while peg is above 1.1 (FTM) with a bonus redemption rate

The longer you hold, the more both the protocol and you benefit from 2BOND.

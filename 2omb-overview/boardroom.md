---
description: SINGLE-SIDED 2SHARES STAKING
---

# Boardroom

* **Epoch duration**: 6 hours
* **Deposits / Withdrawal** of 2SHARES into/from Boardroom will lock 2SHARES for (2) epochs and 2OMB rewards for 1 epochs.
* **2OMB rewards claim** will lock staked 2SHARES for 2 epochs and the next 2OMB rewards can only be claimed 1 EPOCH later
*   Distribution of 2OMB during **Expansion**

    **100%** as rewards for Boardroom stakers\
    **0%** goes to DAO fund

    **0%** goes to DEV fund
* **Epoch Expansion:** Current expansion cap base on 2OMB supply, if there are bonds to be redeemed, 65% of minted 2OMB goes to treasury until its sufficiently full to meet bond redemption. If there is no debt it will follow max capped expansion rate.

### Boardroom Dashboard Information <a href="#masonry-ui-available-information" id="masonry-ui-available-information"></a>

**Next Epoch:** Time remaining until end of current epoch. As \*\*\*\* indicated by the countdown timer. Counting down the time until to the next epoch when it resets. (The duration of each epoch is 6 hours)

**Current Epoch:** This number represents the current epoch and how many epochs have passed since project launched

**2OMB Price (TWAP):** The price of 2OMB relative to FTM, this is the current **peg ratio**. Ex. if this number is 1.5 - this would indicate a 1 2OMB = 1.5 FTM (1:1.5)

**APR: R**efers to the simple returns in USD value relative to the amount of 2SHARES staked (USD value). _Note: \*\*\*\* APR fluctuates from time to time and is dependent on certain factors such as:_

* Price of 2OMB
* Price of 2SHARES
* Amount of 2SHARES staked in Masonry (Locked Value)

**2SHARES Staked:** This number represents the total amount of 2SHARES currently staked in the Boardroom.

### Contraction Periods <a href="#masonry-on-contraction-periods" id="masonry-on-contraction-periods"></a>

{% hint style="warning" %}
Boardroom will **not** mint any 2OMB while TWAP < 1.01 (_NO REWARDS ON BOARDROOM_)
{% endhint %}

### :moneybag:Debt Phase <a href="#masonry-on-debt-phase" id="masonry-on-debt-phase"></a>

A Debt Phase takes place on the Expansion epochs that _**start after a**_ _**Contraction Period and where there are still 2BOND to be redeemed**_. 65% of the normal Expansion rate (2OMB emission/supply) during a Debt Phase is allocated to the Treasury to prepare for 2BOND Redemption. This amount is still reserved whether or not 2BOND holders are redeeming bonds or not.

Once the amount of 2OMB in the Treasury is sufficient to meet all circulating bond redemption, the expansion rates will return to normal.

## Frequently Asked Questions

{% hint style="warning" %}
**Q: What happens when I interact with the BOARDROOM?**
{% endhint %}

{% hint style="success" %}
**A: Any interaction with the boardroom will reset both timers. That's 1 epochs (6 hours) to withdraw your 3OMB rewards, and 2 epochs to unstake your 3SHARES (12 rs).**
{% endhint %}



{% hint style="warning" %}
#### **Q: Are the BOARDROOM rewards pro-rated by time? I.E. if I stake three hours before the end of an epoch vs. five hours before the end of an epoch, do I get different rewards?**
{% endhint %}

{% hint style="success" %}
**A: No, it's determined by how much you have staked at the time of printing (i.e. end of one epoch and start of the other). It doesn't matter if you stake 3 hours before or 30 seconds before the emissions occur.**
{% endhint %}



{% hint style="warning" %}
#### Q: If I remove my SHARES from 3ROOM/BOARDROOM without first collecting my 2|3OMB, will it be lost forever?&#x20;
{% endhint %}

{% hint style="success" %}
#### **A: No, it will still be there to collect whenever you need.**
{% endhint %}



{% hint style="warning" %}
#### Q: The APR dropped because we're in a 'debt phase.' What does this mean?
{% endhint %}

{% hint style="success" %}
**A: A debt phase takes place on the expansion epochs that start after a contraction period where there are still 2|3BOND to be redeemed. 65% of Expansion during Debt Phase is allocated to the Treasury Fund to prepare for the 2BOND Redemption. This amount is still reserved whether or not 2|3BOND holders are redeeming bonds or not. Once 2|3OMB in treasury is sufficiently full to meet all circulating bond redemption, expansion rates will resume to normal.**
{% endhint %}



{% hint style="warning" %}
#### Q: If we're in a debt phase, how long will it last until BOARDROOM(s) continues printing as normal?
{% endhint %}

{% hint style="success" %}
**A: The debt phase will last as long as is necessary to adequately pay back outstanding 2BOND debt. Please keep in mind that the DAO will also need to collect a little extra, as there needs to be a cushion to cover the bonuses when people redeem 2/3BOND over peg.  There's no exact way of calculating how many epochs it takes, since we don't know exactly when people will redeem their $2BOND. If the debt phase is ended too early, and then the treasury doesn't have enough $2OMB to repay the $2BOND bonus, then the APR restriction would need to be turned back on.**
{% endhint %}



{% hint style="warning" %}
#### Q: If 2|3OMB continues climbing above the price of the peg, will that influence how long the debt epoch lasts?
{% endhint %}

{% hint style="success" %}
**A: Depending on the price of 3OMB, the Boardroom print will have to adjust to provide a buffer for any unclaimed 2BOND. As the price of 2OMB climbs above the peg, more 2OMB needs to be distributed to the treasury to account for 2BOND bonus redemption.**
{% endhint %}



{% hint style="warning" %}
#### Q. At the end of the epoch, the Boardroom did not print $2OMB, and then no $2BOND(s) were issued in the pit. Why?
{% endhint %}

{% hint style="success" %}
#### **A: There is a balanced state "at peg" when the $2OMB TWAP is between 1.00 and 1.01, and this means there is neither contraction nor inflation.**
{% endhint %}

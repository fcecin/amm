---
sidebar_position: 6
---

# Liquidity

This section explains what Liquidity Providers are and how liquidity works in the UtilityX platform.

## What is a Liquidity Provider?

A Liquidity Provider (LP), in the context of Automated Market Makers (AMMs) like UtilityX, is an entity that lends their tokens to the AMM, so that the AMM may sell them for other tokens to AMM users, following an automatically-determined price. The LP benefits by receiving a share of the AMM's trading fees.

The idea is that the tokens deposited by the LP into the AMM provide _liquidity_ to the automated market. As the liquidity of an AMM increases it can absor and process more and larger buy and sell orders for the various assets it offers.

LPs on UtilityX deposit their tokens in one or more _liquidity pools_, and they obtain a _share_ of the pool, in the form of LP tokens (the actual token symbol varies; each pool issues its own pool share token). As the pool performs token swaps to users, it retains a fee in the form of one or more tokens that it supports. Thus, all other parameters being equal, the value of the pool share would tend to increase as every trade pays a fee to the growing pool.

## Example

The figure below shows an example list of user liquidity positions, which helps to illustrate:

![](fig/liquidity_positions.png)

(The page above can be accessed under the **Trade** menu, option **AMM Liquidity**, under the **Liquidity Positions** tab. But before you actually start providing liquidity, your Liquidity Positions tab will be empty, of course.)

The table lists all the pools that the user has a liquidity position in, together with the type of pool, the total amount of liquidity in the pool, an instant estimate of the APY (Annual Percentage Yield) being earned by the positions, the user's provided amount of liquidity, and the percent share of the pool that the user's position represents.


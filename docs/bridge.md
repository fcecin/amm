---
sidebar_position: 5
---

# Bridge

This section shows how to use the UtilityX Bridge.

## What is token bridging?

Before we begin using the UtilityX Bridge, let's delve a bit into what it is, what it does, and how it works.

The UtilityX Bridge allows you to transfer tokens from one of your accounts on one blockchain, to another account on another blockchain, in a decentralized and secure manner. This inter-blockchain transfer of tokens is called _bridging_.

Basically, token bridging begins by _locking_ a quantity of tokens on the token's source chain (that is, the blockchain that the token is _native_ to), and then issuing an equivalent quantity of a _bridged_ (also referred to as _wrapped_) version of the token on the destination chain.

For example, the `UTX` token is native to the UX Network blockchain, but through the UtilityX Bridge, it can be transferred to the EOS blockchain. So, for example, if you have `10 UTX` tokens available on an account `myutxaccount` in the UX Network, you can send them to the bridge, where they are locked. Then, on the chosen destination chain, such as the EOS blockchain, you also choose a destination account there, such as `myeosaccount`. The bridge will then issue `10 UTX` on the EOS network, and deposit those tokens on that EOS account.

In this example, it is important to note that the bridged `UTX` tokens on an EOS blockchain account are really tokens that are on the EOS blockchain. So, for example, you can't take `UTX` token on an EOS account and stake them for your UX Network account. Nevertheless, these `UTX` tokens on the EOS network are equivalent to the native `UTX` tokens that were locked (taken out of circulation) on the UX Network side of the bridge. For all intents and purposes, both the native and bridged versions of `UTX` tokens, regardless of the blockchain they are in, will have the same trade value.

The bridge also allows you to return bridged tokens to their source blockchain. For example, you can send bridged `UTX` tokens from your EOS blockchain account to your UX Network account. In that case, the bridge will retire (burn, destroy) the bridged `UTX` on EOS, and unlock the corresponding amount of native `UTX` tokens on the UX Network.

The blockchain technology underlying the UtilityX Bridge is called Antelope Inter-Blockchain Communication (IBC). You can read the in-depth technical documentation of Antelope IBC [here](https://ibc-docs.uxnetwork.io/).

## Planning a token bridging operation

To use the UtilityX Bridge, you need to go through the following checklist first:

* Choose a **source blockchain**, that is, the blockchain that will be sending tokens;

* Choose a **source account**, that is, the account on the source blockchain that will be sending the tokens. You must control (i.e. have the private key) this account, and it must be configured in your Web3 wallet;

* Choose a **destination blockchain**, that is, the blockchain that will be receiving the tokens;

* Choose a **destination account**, that is, the account on the destination blockchain that will be receiving the tokens. Like the source account, you must also control this account and have it loaded in your Web3 wallet;

* Choose a **token** to send. You must have this token on your source account, and the chosen token must be supported by the UtilityX Bridge;

* Choose a **quantity** of the token to send. You must have this quantity liquid and available on your source account;

* Make sure both your source account and destination account have **sufficient resources** (CPU, NET, and RAM, in the case of Antelope blockchains) to complete the bridging operation. If your blockchain supports the PowerUp resource model (e.g. the EOS mainnet) then you may need to power up your account. You should also have sufficient free RAM available on your accounts.

If either your source or destination account turns out to not have sufficient resources, you don't have to worry, as you will be able to securely retry the bridging operation with more account resources, or revert (cancel) the bridging operation. There is no way to lose tokens in the process.

After satisfying the checklist, we are ready to execute our first token bridging operation.

## Open the Bridge page

Click on the thing

here it is

## Log in to blockchain accounts

choose both blockchains

choose both accounts

log in to both

## Select token and amount

Select the token to send and the amount

## Execute bridge

Click the do it thing

## Wait for completion

Here is the runtime stuff: wait or confirm the second transaction

## Check Bridge report

Check bridge report and be happy

## Idiosyncrasies / pending incomplete transfers etc.

Pending transfers, retry tab? etc.



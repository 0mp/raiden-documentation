---
description: >-
  To get your tokens back on-chain you need to either withdraw them from a
  channel or close and settle the channel.
---

# Settle Payments and Close Channels

You have a couple of ways for getting your tokens back on-chain:

* [Withdraw tokens from an open channel](close-channels-and-settle-payments.md#withdraw-tokens) 
* [Close a channel](close-channels-and-settle-payments.md#close-a-channel)
* [Leave a token network](close-channels-and-settle-payments.md#leave-a-token-network)

## Withdraw tokens

In the **"Channels"** screen:

1. Click the three dots on the channel from which you would like to make the withdraw and then the **"Withdraw"** button.
2. Enter the amount for your withdraw.
3. Click "Withdraw".

The token amount will be added to your on-chain token balance. **Your payment channel with the partner will remain open and you can continue exchanging payments \(if your balance allows it\).**

## Close a channel

If you don't plan to use a specific channel anymore you can close it. A closed channel is no longer available for making payments.

In the **"Channels"** screen:

1. Click the three dots on the channel you wish to close and then the **"Close Channel"** button.
2. Click "Confirm" to finish closing the channel.

As soon as the channel is settled the token amount will be payed out in accordance to the transfers that have been made between the channel participants.

{% hint style="info" %}
When the channel is closed the settle timeout period will start. The channel is settled once the settle timeout period is over. The tokens can then be used on-chain.
{% endhint %}

## Leave a token network

Leaving a network has the same outcome as [closing a channel](close-channels-and-settle-payments.md#close-a-channel) with the difference that _all_ channels belonging to the network you're leaving get closed.

In the **"Transfers"** screen:

1. Select the token network you wish to leave.
2. Click the three dots and then the **"Leave network"** button. 
3. Click "Confirm" to finish leaving the network.


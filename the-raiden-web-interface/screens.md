---
description: >-
  To get you familiarized with the Raiden WebUI we have put together a short
  introduction to the most important screens of the application.
---

# Navigate the WebUI

You will find the navigation menu on the right and on the top is a bar which contains general information.

The **top bar** displays:

1. Your **ETH balance**. This ETH will be used whenever an on-chain activity happens. If you are using any testnet you'll also find a button which redirects you to the respectiva faucet for acquiring ETH.
2. The **address** of your Raiden node \(you can display the address as a QR code\).
3. A **search** field which filters all items on the page based on search term.
4. The **notification** button.

## Home

The home screen provides an overview of your account. Since you can do the same things on Home screen as on each subpage we won't cover the Home screen in detail here but rather focus on the navigation menu options.

* [Transfers](screens.md#transfers)
* [Contacts](screens.md#contacts)
* [Channels](screens.md#channels)

## Transfers

In order to start making payments you need to be connected to a token network by having a open channel.

1. Select the token network in which you want to make a payment in the center of the screen.
2. Once you have selected a token network the sum of your channel balance is displayed. You can use the buttons on the top right to **leave the token network** or **mint tokens** \(if you are on a testnet\).
3. Click the **Transfer** button to make a payment in your selected token network. If you don't have any open channels you will get prompted to use the **Quick Connect** option to join the network.

On the bottom you will see the history of all the payments you've made. The history is filtered by the selected token network.

{% hint style="info" %}
If you have selected a network when using a testnet you can use the **"Add new network"** button for registering new token networks.
{% endhint %}

## Contacts

Contact lets you save Ethereum addresses and label them. To add a new contact:

1. Click the button in the bottom.
2. Enter the address and whichever label you want the address to be associated with.

Clicking on a contact also gives you the options to make payments, edit or delete the choosen contact.

{% hint style="info" %}
Contacts can be imported and exported by using the button on the top right.
{% endhint %}

## Channels

To make payments you need to hava a channel with at least one other Raiden node. To open cannels either:

1. Use **Quick Connect**. This is the simplest way for opening channels.
2. Use the button on the top left to opena new channel.

In the center of the screen you'll see all your channels and their token balance. By clicking the three dots you can:

* Deposit into the channel.
* Withdraw from the channel.
* Close the channel.

{% hint style="info" %}
**What is a channel?**

A payment channel enables tokens to be exchanged back and forth between parties without invloving the actual blockchain. A payment channel in Raiden is always backed by a on-chain deposit of token.
{% endhint %}


---
description: Explanation of the different WebUI screens
---

# Screens

## Overview

This guide explains the following screens in detail

* [Home](screens.md#home)
* [Navigation](screens.md#navigation)
* [Tokens](screens.md#tokens)
* [Channels](screens.md#channels)
* [Address Book](screens.md#address-book)

## Home

The first screen you'll see when the WebUI launches is the **"Home"** screen which has a short introduction to Raiden.

## Navigation

There is the navigation menu and status information on the top right.

![](../.gitbook/assets/web_ui_home_screen.png)

1. The address of your Raiden node together with your current ETH balance. Some of this ETH gets consumed anytime an on-chain activity happens.
2. The navigation menu for interacting with Raiden.
   * [Tokens](screens.md#tokens)
   * [Channels](./#channels)
   * [Address Book](screens.md#address-book)

## Tokens

In order to open channels and make payments, you need to be connected to a token network. For each ERC20 token there is a separate token network.

![](../.gitbook/assets/web_ui_tokens_screen.png)

1. List of all tokens that have been registered in Raiden.
2. Details about each token which includes:
   * The token **symbol** \(WIZ\)
   * The token **name** \(WizardToken\)
   * Your current token **balance**
   * Buttons where you can [**join a network**](./#join-a-token-network) or **mint tokens**
3. **+** button for [**registering new tokens**](./#register-a-new-token-and-join-its-network) and options for **filtering** and **sorting** your tokens list.

## Channels

To make payments you need to have channels to at least one other Raiden Node

{% hint style="info" %}
You can make payments to nodes where you don't have a direct channel to as long as there is are nodes connected to you and to the target node.
{% endhint %}

![](../.gitbook/assets/web_ui_channels_screen.png)

1. List of all your open channels.
2. Details about each open channel which includes:
   * The address of the **partner** node you're connected to via the channel.
   * The token **symbol** \(WIZ in the example below\) and the token **address** which gets displayed when hovering over the symbol.
   * Your current **balance** of tokens in the channel.
   * The **status** of your channel and whether its [**open**, **closed**, or **settled**](./#close-channels-and-settle-payments).
   * Buttons where you can [**pay**](./#pay-from-the-tokens-screen) ****\(both the "PAY" and the "SEND TOKENS" button works the same as when paying from the "Tokens" screen after joining a token network\), [**deposit**](./#add-more-tokens), [**withdraw**](./#withdraw-tokens), or [**close a channel**](./#close-a-channel).
3. A **+** button for opening a channel with a counterpart of your choosing and options for **filtering** and **sorting** your channels list.

{% hint style="info" %}
If you haven't opened any channels this screen will just display a _"no channels found"_ message. The simplest way to get started is to open channels by [joining a token network](./#join-a-token-network).
{% endhint %}

## Address Book

The address book gives you the possibility to save and label addresses you need to use often.

![](../.gitbook/assets/web_ui_address_book_screen.png)

1. List of all your saved peers and their addresses.
2. Two options for saving a new address:
   * Type the address and label manually.
   * Drag and drop a JSON file containing all your addresses.


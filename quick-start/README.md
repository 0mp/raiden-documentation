---
description: Install Raiden and run a Raiden node using the Raiden Wizard
---

# Quick Start

## Overview

This tutorial will teach you how to:

* [Download the Raiden Wizard](./#download-the-raiden-wizard)
* [Setup and run a Raiden node](./#setup-and-run-a-raiden-node)

on the public Ethereum blockchain \(this is sometimes referred to as `mainnet`\).

## Prerequisites

In order to run the Raiden Wizard, you will need

* A computer running Linux or macOS X.
* An [infura ID](https://blog.infura.io/getting-started-with-infura-28e41844cc89/) \(click [here](./#get-an-infura-project-id) for a quick start guide\).
* A web browser with [Metamask](https://metamask.zendesk.com/hc/en-us/articles/360015489531-Getting-Started-With-MetaMask-Part-1-).
* An Ethereum account with at least `0.13` ETH in Metamask.

## Download the Raiden Wizard

You can download the Raiden Wizard for either macOS or Linux:

* [**macOS download**](https://github.com/raiden-network/raiden-installer/releases/download/v0.32.0-testnet/raiden_wizard.macOS.zip)\*\*\*\*
* [**Linux download**](https://github.com/raiden-network/raiden-installer/releases/download/v0.32.0-testnet/raiden_wizard.linux-gnu.bin.tar.gz)\*\*\*\*

You will need to unpack the downloaded archive. In it you will find an executable program named `raiden_wizard`.

## **Setup and run a Raiden node**

{% hint style="warning" %}
You need an internet connection to run the Raiden Wizard. The Wizard will launch in your default browser.

The setup process can take up to five minutes, make sure not to close the browser.
{% endhint %}

1. Extract and open the `raiden_wizard` program.
2. Your web browser should open a new window \(if not, type [http://localhost:1994](http://localhost:1994) in your browser, to manually open it\).
3. Follow the configuration steps of the Wizard \(the animation below shows you a quick walkthrough\)

![The Raiden Wizard setup process](../.gitbook/assets/raiden_wizard_installation_process.gif)

In the process you will

* Create a new Ethereum account for use with Raiden \(the "Raiden Account"\).
* Fund the Raiden Account with `ETH`.
* Acquire `RDN` tokens for use with the User Deposit Contract.
* Acquire `DAI` tokens for making payments in the Raiden Network.

When you have finished the steps of the Wizard, you can `LAUNCH` Raiden and start interacting with:

{% page-ref page="../using-raiden/the-raiden-web-interface/" %}

## Need help?

If you run into problems or discover bugs, you can:

* Ask for help in the [Raiden gitter chat](https://gitter.im/raiden-network/raiden)
* Create a [GitHub issue](https://github.com/raiden-network/raiden/issues/new/choose) for either a bug report or feature request


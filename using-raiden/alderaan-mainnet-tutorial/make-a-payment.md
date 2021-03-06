# Make a Payment

Payments are made from the [`payments`](../../raiden-api-1/resources/payments.md#initiate-a-payment) endpoint via a POST request that has to include:

1. The address of the W-ETH token as a path parameter.
2. The address of the node receiving your payment as a path parameter.
3. The amount you would like to pay as a body parameter.

```text
curl -i -X POST \
http://localhost:5001/api/v1/payments/0xC02aaA39b223FE8D0A0e5C4F27eAD9083C \
-H 'Content-Type: application/json' \
--data-raw '{"amount":"42"}'
```

Payments in Raiden can be done either as:

* [Direct payments](make-a-payment.md#direct-payments)
* [Mediated payments](make-a-payment.md#mediated-payments)

{% hint style="info" %}
It is possible to receive tokens through the Raiden Network without having any initial Ether or tokens. The receiving peer just needs to have a Raiden full node running and the sender must be willing to pay the fees for the on-chain transactions.
{% endhint %}

## Direct payments

You can open a channel directly with any node you know the address of. You might want to open a direct channel if you know you'll be making frequent payments to a specific peer. Each payment will then go straight to that peer via the open channel. This is called a direct payment.

## Mediated payments

If you don't have a direct channel to a node for whom you want to send a payment, Raiden will try to find a path from you to the recipient node through the network of channels. This is called mediated payments.

Mediated payments are a powerful feature in Raiden since it lets you pay anyone in the network by leverging the path of connected payment channels.

By making no more than two API calls - one call to join the token network and one call to make the payment - we can send payments to anyone who is part of the W-ETH token network.


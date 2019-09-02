# Glossary

### Payments and Transfers

#### Balance

The balance determines how many tokens one specific channel participant holds. 

You can calculate the balance by taking the total amount of tokens deposited, adding the total amount of tokens received and subtracting the total amount of tokens sent for a participant.

$$
B_{participant} = P_{total\,token\,deposit} + P_{total\,tokens\,received} - P_{total\,tokens\,sent}
$$

#### Channel Capacity

The channel capacity determines how many tokens a channel holds. You can calculate the capacity by either:

* Taking the total amount of tokens deposited and subtracting the total amount of tokens withdrawn by both participants that have a channel open with each other.
* Taking the sum of both channel participants [balance](glossary.md#balance).

#### Payment

A payment in Raiden is the process of sending tokens from one account to another. Each payment has an initiator and a target.

#### Payment Channel

A payment channel allows for back and forth Raiden payments between participants without involving the actual blockchain.

A on-chain payment channel is opened whenever an initial deposit of tokens are made for a token network.

#### Transferred Amount

The transferred amount is the total amount of tokens sent from a participants account to the account of a counterparty.

### Participants

#### Counterparty

The counterparty of a channel is the other channel participant with whom we have opened a channel.

#### Initiator

The initiator is the Raiden node which initiates \(starts\) a payment.

#### Payee

The payee is the participant who receives a payment.

#### Payer

The payer is the participant who sends a payment.

#### Target

The target is the Raiden node which receives a payment from the [initiator](glossary.md#initiator).

#### Transfer

A transfer in Raiden happens each time tokens are sent inside a payment channel.


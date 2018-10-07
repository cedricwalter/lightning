# Bitcoin Lightning

!\[logo\]  
\([https://raw.githubusercontent.com/cedricwalter/lightning/master/Logo\_of\_Lightning\_Bitcoin.png](https://raw.githubusercontent.com/cedricwalter/lightning/master/Logo_of_Lightning_Bitcoin.png)\)

## What is lightning

Lightning Bitcoin \(LBTC\) is a fully decentralized Internet-of-value protocol for global payments. The specific applications include peer-to-peer transactions and exchange platforms. Any users that operate on the LBTC protocol can enjoy instant, secure and nearly free global financial transactions of any size.

[http://lightningbitcoin.io/](http://lightningbitcoin.io/)

## Use cases

#### Global Scale Payment Network

Scaling Bitcoin network to millions of more users

#### Micropayments

The benefit of Lightning is that it enables high frequency micro-micro transactions that can be cleared "instantly" for negligible fees with no chargebacks. E.g. paying intellectual property rights per minutes of watch movie.

#### Machine-to-Machine Payments

Automating opening of channels between machines

#### "streaming money"

Lightning makes it possible for companies to offer instant use of your payroll earnings up to the current moment with no risk. Charging per unit of time would work to keep contractors more honest and competitive.

#### More use cases

see more [https://gist.github.com/tyzbit/f1d0cf4904c61ec510bd4779eb8f1cdc](https://gist.github.com/tyzbit/f1d0cf4904c61ec510bd4779eb8f1cdc)

## Experimenting with lightning

### Risks, Work in Progress

#### Improper channels backup = loss of funds

Channels that are not close properly, e.g during a crash of your node, and if you submit a wrong, outdated transaction in the wrong order, may be considered as an attack: you will loose your stake!

#### Different lightning implementation have different Tx fees costs calculation = no loss of funds, but no usage

If during node hops, not enough funds are locked to pay for fees, the channel will close automatically.

#### Opening channel with no fund locked on the other side = no loss of funds, but no usage

### Docker



### Raspberry Pi 3



### AWS

  



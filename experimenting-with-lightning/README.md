# Experimenting with lightning

### Risks, Work in Progress

#### Improper channels backup = loss of funds

Channels that are not close properly, e.g during a crash of your node, and if you submit a wrong, outdated transaction in the wrong order, may be considered as an attack: you will loose your stake!

#### Different lightning implementation have different Tx fees costs calculation = no loss of funds, but no usage

If during node hops, not enough funds are locked to pay for fees, the channel will close automatically.

#### Opening channel with no fund locked on the other side = no loss of funds, but no usage

### 


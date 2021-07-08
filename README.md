# options
HFT robot for options trading with risk control and hedging.

Short description:
The bot operates with four types of option strategies: regular, market maker and two hedging.
Within each strategy, pricing parameters are set with reference to the relative displacement relative to the central strategy.
Operator order:
- definition of constants
- selection of underlying assets
- definition of parameters for underlying assets
- determination of options pricing options
- determination of options for optional strategies
The order of the bot:
- definition of traded tickers (rarely)
- calculation of the total price
- calculation of risk control parameters
- calculation of the number of applications
- pricing for bids
- decision making on sending an application
- control of civil defense
- transaction analysis
- logging

1. Exchange data:
- the best
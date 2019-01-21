# Options and Betting Markets (Econ Agents and Market-Based Systems IV)

## Short-Selling

Terminology:

- To *go long X*:
    - to buy X, expecting the price to rise
    - a *bullish* position
- To *go short X*:
    - to sell X, expecting the price to fall
    - a *bearish* position

Often abbreviated to just long/short, e.g. "im short IBM".

How it works:

1. Borrow n\*XYZ from a lender
2. Sell n\*XYZ now (time=t1) at price P1
3. Price of XYZ falls to P2
4. At time=t2, buy n\*XYZ at P2 and return to lender
5. Profit = n \* (P1 - P2) - LenderFee - costs
    - costs: storage, insurance, transport

## Derivative Contracts

A contract that *derives* its value from some other asset:

The asset is known as the **underlying**.

- lots of types of derivatives

**Future: contract that _will_ be executed by/on a set _delivery_ date**:

- Futures contracts are required, obligated, to be executed/exercised
- When contract is issued, it specifies the *forward price*
- On the delivery, the contract is executed at the forward price
- Buyer of a forward is the *long position*, seller is *short position*

**Option: contract that _may_ be executed by/on the _expiry_ date**:

- Options contracts confer a right (but not an obligation) to exercise
- Options specifies a _strike price_ (or _strike_) aka the _exercise price_
- Options to sell are _puts_, options to buy are _calls_

Both futures and options are _standardised_ and _exchange-traded_.

- Standardised: size of contract _n_ and delivery/expiry date are prespecified.
- Exchange-traded: traded in a secondary market, on an exchange, like stocks and shares

### Derivatives Exchanges

- Chicago Board of Trade
- Chicago Mercantile Exchange (CME)
- CBOE
- NYMEX (NY Mercantile Exchange)
- NYSE
- LIFFE
- EURONEXT
- ICE

24x7 electronic trading

- CME Group
- NYSE Liffe
- NYSE Euronext Liffe
- NYSE Euronext

### Options basics

- One options contract: right to buy/sell N shares
- Price of option depends on price of underlying & risk premium
- Strike price: the price at which you can buy/sell underlying on exercise
- Expiry: last date on which you can exercise option
    - American-style options: exercise can happen any date up to expiry
    - European-style options: exercise happens only on expiry date (*at maturity*)
- Option is written/issued by its seller, held/exercised by its buyer.

Option price determined by:

- Intrinsic: money received if the option is exercised now
- Volatility: premium dependent on underlying's price volatility
- Time value: potential risk-free return on money saved wrt buying underlying

- Black-Scholes pricing model used to determine European-style option prices

#### Calls vs Puts

##### Calls (options to buy)

- Buy a call option (long call) if **you think stock price will rise**
- Gives you right to buy at strike price (may be less than market price at expiration) (you can then sell at market price)
 
- Right to buy N units of underlying
- Option-holder can buy at strike price
- If exercised, option-writer (seller) must sell shares at strike price
- **In-the-money (ITM)**: if the underlying price is greater than the strike price
- **Out-of-the-money (OTM, underwater)**: if underlying price is less than strike
- **At-the-money**: if underlying=strike

##### Puts (options to sell)

- Buy a put option (long put) if **you think stock price will drop**
- Gives you right to sell at strike price (may be more than market price at expiration)

- Right to sell N units of underlying
- Option-holder can sell at strike price
- If exercised, option-writer (seller) must buy shares at strike price
- **In-the-money (ITM)**: if the underlying price less than the strike price
- **Out-of-the-money (OTM, underwater)**: if underlying price is greater than strike
- **At-the-money**: if underlying=strike


#### Options strategies

##### Bullish Call Spread

- You think U will be in range [K1, K2] or better at maturity
    - long call K1
    - short call K2
    - max loss and max win are less

##### Bullish Put Spread

- Long put K1 and short put K2

##### Bear Spread

- You think U will be in range [K1, K2] or worse at maturity
- Bear Put Spread: short put K1 and long put K2
- Bear Call Spread: short call K1 and long call K2

##### Long Butterfly

- You think U will remain close to K2 at maturity
- Long call K1 and short 2 calls K2 and long call K3

##### Long Straddle

- You think, by some date, stock will either tank or rise (major price movement)
- -> buy (long) put and call option

- If stock goes down (to 0), exercise the put option
    - can buy for zero, exercise put, sell for strike price.
    - call option is useless
- If stock goes up, exercise the call option
    - can exercie call and buy for stike price, then sell for underlying value


##### Long strangle

- You think will either go below K1 or above K2
- Short put K1 + long call K2

##### Short strangle

- You think will be between K1 and K2 in maturity

##### Ratio Call Spread

- Between K1 and K2 but bias to K2 (much bigger win at K2, small loss at K1)
- Long 1 call K1 + short 2 calls K2

##### Ratio Put Spread

- As above but bias to K1
- 2 short puts K1 + long 1 puts K2

##### Ratio Call Backspread

- Short call K1 + long 2+ calls K2

##### Ratio put backspread

- short 1 put K2 and long 2+ puts K1

## Betting

### Betting Exchanges

- Betting exchanges are electronic marketplaces where gamblers interact to find someone to take the opposite side of their bet:
    - the buy (*back*) or sell (*lay*) the outcome of an event
- Traditional bookmaker: the customer backs the event, the bookie lays.
- Betting exchange:
    - All customers can either back or lay (exchange operator is neutral)
    - Buys and sells are displayed in manner similar to LOB
    - Customers trade bets "in play" while event is happening, until final outcome
- Traditional bookmakers have argued that allowing anonymous customers to lay events encourages corruptoin: it's easier to throw a race than it is to win it
- Betting exchanges are internet-economy success story

### Betfair

- Launched in 2000
- Valued in 2006 at 1.5bn
- World's largest betting exchange
- UKs largest online betting company
- Acquired various oversears gambling/bookmaking companies + media providers
- Relocated to Gibraltar in 2011: reduced tax payments, different regulator
- Claims to offer better odds than traditional bookmakers, but imposes additional fees on super-successful customers
- Feb 2016 merged with Paddy Power (Traditional bookie)

- Backed curbs on fixed-odds betting machines

### Betting exchanges as predictors

- If enough people are risking their own real money by backing/laying outcomes of real-world events, is that a useful predictive signal?
- NB assuming the gamblers are rational (as opposed to just hopeful) they're betting on what they thin most likely outcome is (as opposed to what they want to happen)
- -> The money on the book might be good indicator of what is likely to happen
- **The state of the betting-exchange market is a _prediction_**
- -> We can set up dedicated **_prediction markets_**

### Prediction Markets

- E.g. IEM @ Uni of Iowa



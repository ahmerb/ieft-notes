# Bristol Stock Exchange

Market impact of transactions themselves cannot be present in a simulator based on past time-series data of stock prices.

BSE allows this.

# Limit Order Book (LOB)

- Traders make limit orders (e.g. i want 10 ibm @ £x). It goes on the order book. At any point, another trader can come and take that bid (lift the ask)
- All these offers/bids are anonymised and logged in the LOB


- Bid side of the book and ask (/offer) side of the book
- Best bid and offer shown at top of the book
- Remaining bids and offers shown in tables in sorted order
    - Best bid - highest price
    - Best offer - lowest price
- Bid and ask tables have two columns
    - price and quantity available
    - the quantity aggregates over all orders at same price (from multiple traders)
        - if multiple orders at same price, they're executed in time priority

- LOB price depth: range of prices available in the book
- POB volume depth: quantity of stock
- More liquird market -> more depth -> more volume -> individual trader cannot shift the price as quickly.

- LOB also shows the time till market closes

- From LOB, we can draw CDA Supply and Demand curves

- Bid-offer spread: difference between best bid and offer
- Midprice: arithmetic mean between best bid and offer
- Microprice: volume adjusted estimate of the underlying equilibrium price
- Microprice: takes midprice but weights it by quantities
    -> e.g. so if quantity supplied is a lot higher (on ask side) then microprice is a smaller than midprice
    - can use to guess direction price is moving in befor

- Top of LOB: most recent order

- Tape: timestamped record of all transactions

## Lollipop plots

- Quantity on vertical axis, prices on horizontal axis.
- Equib price is somewhere on horizontal axis
- Supply vs demand 'lollipops' in different colour


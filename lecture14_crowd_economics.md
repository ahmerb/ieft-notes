# Crowd Economics

The crowd economy

- citizen engagement (social media etc)
- crowd intelligence
- open innovation
- mass collaboration
- online communities
- crowd tasks and creativity
- crowd causes
- social buinsess
- customer co-creation
- sharing economy
- non equity based crowdfunding
- equity based crowdfungin
- p2p lending/commerce
- crowd currencies

Web 1.0 (1990s)

- Content creators are few
- most users consume content
- personal web paegs common
- static pages hosted on ISP-run web servers
- "guestbooks" for visitors to leave comments

Web 2.0 (2000s)

- User contribution /participating
- user generated content (Youtube, wikipedia)
- blogging (wordpress)
- apps (SaaS)
- dynamic scripting (js, python, ruby, pert)
- social networks (Facebook)
- Rich user experience, dynamic content, scalability

Structural change in 'network' structure we are seeing:

- First, we had **centralised** networks
    - central content creation
    - consumers are **spectators** only

- Now, **decentralised** network
    - followers, ambassadors
    - likes, shares, comments

- Next, **distributed** network
    - pro-sumers
    - collaborators

- Network designed organisation fuels the crowd economy.
- These network organisations are more resilient, adaptabe and faster because of the distributed information capacity in the network.
- **The crowd evolves from specators** to connected, to finally **protagonists**.
- AirBnb, Uber, etc access resources through this model
- Exponential growth and crowd distributed activities become possible

- Citizen engagement: Zooniverse, Cancer Research UK
- Crowd intelligence: Prediction markets
- Crowd tasks and creativity: Amazon Mechanical Turk, Google reCAPTCHA
- Crowdfunding: Kickstarter
- p2p lending: Zopa


## Prediction Markets

**Prediction markets**: exchange traded markets created for the purpose of trading the outcome of events. A form of *crowd intelligence*.

- Trading of units which pay based on real world events (e.g. election result)

Two approaches:

1. *Winner-take-all*: paying if something happens (e.g. given candidate wins election)
2. *% payment*: based on quantitative outcome (e.g. share of seats)

- Market run like CDA - participants can state what prices they're willing to buy/sell at and trade takes place when crossing occurs
- Trade price is considered a measure of the *believed* probability of a given event by the collective of traders
- *Money speaks louder than opinion polls*

### Rationale

- Predicting outcome of uncertain event in future
- Each event is uncertain, but eventually we can verify the outcome
- What is the best way to predict what happens?
    - We can use a *prediction market*
    - Similar to betting markets (odds in betting markets offer reasonable forecase of event outcomes)

### Iowa Electronics Market (IEM)

- Opened 1988 by Iowa uni.
- Small scale real-money *futures market* where *contract payoffs* depend on economic / political events
    - **not-for-profit**: research and teaching
    - **stakes are small**: hard limit of 500 dollars per trader
    - **low number of traders**: typicall low thousands
- IEM not considered gambling, although most other prediction markets are
    - *only prediction market in US with license to allow real-money trading*
- Other real-money prediction markets: InTrade (InTrade) and PredictIt (New Zealand)
- *play-money* prediction markets are legal in US - e.g. Hollywood Stock Exchange predicts OXcar winners, box office receipts, etc

### How prediction markets work

Prediction markets use investors' opinions to generate a price for 'shares' in a given event.

Example: predict which of two candiates A and B will win election. Note, outcomes win(A) and win(B) are mutually exclusive

- Create two futures contracts, C_A and C_B
- Each share of C_A pays out £1 if A wins, £0 otherwise
- Each share of C_B pays out £1 if B wins, £0 otherwise
- Contracts are *initially offered* by allowing any trader to buy one share of C_A and one share of C_B for a total price of £1 (50p each)

IEM rules:

- only sell shares you own (i.e. not shorting)
- only buy shares with money you have (i.e. no buying on the margin)

Trading shares

- Securities are traded using a CDA mechanism
- Enter limit order with direction (buy/sell), limit price (max/min) and quantity to trade
- Trading strategy: if your opinion is that candidate A will win with prob p (your expected value for A winning is p)
    - Buy C_A when price C_A < p, Buy C_B when price C_B < 1-p
    - Sell C_A when price C_A > p, Sell C_B when price C_B > 1-p
- Current prices of C_A and C_B can be considered as collective opinion/belief of probabilities of outcomes win(A) and win(B)

#### Multiple outcomes

Issue a contract for each separate _mutually exclusive_ outcome.

#### Arbitrage Opportunities

- If prices win(A) + win(B) < 1, then you can simultaneously buy/sell across markets for *risk-free profit*.
- This is arbitrage.
- The arbitrage will have market impact of raising price till it equilibrates £1.
    - Arbitrage thus aligns marktes (removing inefficienies)
    - The signal is 'arbed' away
    - The converse happens if sum price > £1 (sell both, reduces price)

#### IEM - Percentage Outcome 

- Percentage outcome is a *security contract* that pays out according to the percentage of votes that a candidate gets
    - E.g. is A gets 55% of vote, the per-share value of corresponding contract is £0.55
    - The market price of the security can be interpreted as the market's *prediction* for the *vote share* of a candidate.

--

## Crowdsourcing

**Crowdsourcing is to enlist a crowd of humans to help solves a problem defined by the system owners.**

- *Collaboratively build* some artifact: Wiki, OpenSource software
- *Execute part of large task*: Amazon Turk, Galaxy Zoo
- *Contribute to some evaluation*: Amazon Reviews
- *Implicit*: Google Ad experiments (moving ads around the page and observing effect on behaviour)

Crowdsourcing is helpful for tasks that can be difficult for a computer to perform.

Allows many people to contribute to solving a problem: the long tail of work.

### Amazon Mechanical Turk

- Crowd based labour market
- "employers" offer small tasks to complete in return for small pay
- Useful for tasks that a difficult/costly for a computer
- Recent paper showed average 'wages' very low
    - only 4% of workers can earn more than UK/USA minimum wage
    - Mean wage: $1.77 / hour

### reCAPTCHA

- Designed to establish that computer user is a human
- At the same time, assists in digitization of books
- Originally Carnegie Mellon uni, acquired by Google in 2009

### How to recruit and retain contributers

- Pay them e.g. MTurk
- Crowd source as a side effect (eg reCAPTCHA, or Google ads)

- Or, recruit volunteers. They need to be motivated:
    - intrinsic motivation of doing a task that interests them or they believe is worth doing
    - Fun
    - Recognition or rewards for contribution (gamification)
    - competition with others

## Citizen Engagement / Science

Using crowds to perform scientific challenges (save costs)

### Zooniverse

- Looking for planets using NASAs huge dataset
- When a planet goes infront of a start the light will dip
- Why not use ML
    - no tagged dataset for supervised learning
    - Aim to use public tagging to train ML algo

### Cancer Research UK

- Gamification of classification / data analysis challenges related to cancer research.
- Latest project:
    - Trailblazer web-app designed to continuously improve citizen
    scientists’ ability to spot cancer cells in tissue samples.
    - Players shown images of tissue cores and asked to mark areas of cancerous
    cells after going through a tutorial.
    - 90% accuracy compared with scientists’ classifications

## Crowdfunding & P2P Lending

### Crowdfunding

- Money paid at end of pledging period
- Goods given at the end (Reward is the product you invested in)
- E.g. Oculus Rift

#### Beyond traditional capitalism

- Pre-commitment of buyers allows more money to be raised to fund development. No need for privately raised funing
- 'Menu pricing' of premium options. Is this Versioning?
- Psychology effect:
    - sense of being 'part of project'
    - charitable action

### P2P Lending

-  Lending and borrowing traditionally performed by banks, credit cards,
loan sharks!
    - Lending interest rates often very high (HSBC classic credit card 29.9% APR; QuickQuid Payday Loan 1294.1% APR)
    - Savings interest rates often very low (most banks, <1.5% for easy access)
- Idea: cut out the banks, and match up lenders with borrowers
    - Borrower gets a lower interest rate than they would from traditional lender
    - Lender gets higher interest return than they would otherwise receive
    - Examples: Funding Circle, LendingCrowd, RateSetter, Zopa (the first P2P lender)
- Zopa: investment returns between 3% - 7% a year
- Zopa: borrowing APRs range from 2.9% - 34.9%.
- Diversify portfolio to reduce risk (split investment between lots of borrows as some will default)
- Light regulation:
    - Now regulated by FCA, can be invested using IFISA (innovative investment ISA)
    - But not covered by FSCS (so not as safe as money in bank)


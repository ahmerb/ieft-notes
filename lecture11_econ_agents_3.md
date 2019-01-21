# Technology Trends in the Financial Markets: A 2020 Vision (Markets and Economic Agents III)

# Summary

- As well as opportunities, ICT development in financial markets has brought risks (many non-obvious, counterintuitive) for which there is an immediate requirement for careful and thorough evaluation.
- The shift to HFT is underway without external regulation and intervention.
- Net result of trends: significant reduction in number of employees required by major financial institutions
- "depopulation of the trading floors" lead to situation where London as major global trading hub is seriously threatened by clusters of automated trading systems operational elsewhere on the planet
- Also threat of increased risk - range of mitigation stragies alarmingly limited
- Quantify risk in new forms of derivatives, new algorithms deployed in algo trading, and the systemic phenomena of "flash crashes"
- New tools to do this are urgently required

# Brief History of Tech in Financial Markets

#### Automated Execution System (AES)
- Computer does not make decision to buy or sell block of shares/commodity/forex; it just handled execution
- Free up humans for dealing with complicated trades
- Use AES to reduce market impact on large transactions
    - divide big order into smaller slices and trickle-feed slices into market so to reduce market impact of each order

- Salami-slicer -> feed equal slices at fixed time intervals
    - not good; may sell at time of thin market activity
- Volume participation -> volume sensitive slicing (predict future volume from statistical model of past trading activity)

#### HFT

- Automated traders buy/sell on electronic exchange venues, sometimes holding a position for seconds or less
- Exploit small price variations but large frequency of trading

##### Frlash Crash

- May 6th 2010 - NY equity markets lost more than 600 points in a few minutes (1tn dollars) and then regaining much of that loss over following 10 or 15 minutes.
- CFTC/SEC: Traditional fundamental trader places $4bn sell order. Then, HFT algos accelerated the drop and subsequent recovery
- Nannex Corp: disputes CFTC/SEC version


## Current state of tech

### Latency issues drive co-location

- Proximity to exchange gives major advantage (36ms round trip time NY to London; in which time quad-core 2.3 GHz single core machine executes 330 million instructions
- Industry response: *co-locate* the automated trading machinery with the server computers operated by the major exchanges.
- Co-lo or proximity servers used to give institutions guarenteed same latency time (e.g. making cables from server to main exchange server same length)

### Custom Hardware

- Algo traders run on 'blades' (just server racks in datacenters)
- Servers arose that are targeted at financial applications
- Switch from general purpose chips to ever-more trading specific hardware
    1. GPUs: and already mass produced due to demand from gaming (GPGPU make it easy to re-purpose for financial applications)
    2. FPGAs: Make the program be the specification of a dedicated processor (no fetching executions from RAM). Without FPGAs, this is infeasible (huge expenses)

### New software techniques

- More advanced math can be beaten by a faster implementation of simpler maths
- Faster maths: stochastic ML techniques (ANNs, SWMs, PAC learning) as alternatives to rigorous analytical methods

- Big data: use scalable distributed programming (e.g. MapReduce) to do computations on huge datasets (e.g. finding correlations between any stocks). Also a shift from frequentist to non-parametric or Bayesian approaches.

- Event stream management techniques: CEP/ESP/BEP

- Smarter algorithms:
    - Pipeline Financial use advanced statistical tools and "algorithm switching engine"
    - Semantic / sentiment analysis of qualitative data
    - Statistical techniques to establish causation (active research in academia)

### Fresh Risks

Risk exacerbated by:

- highly liquid and global markts (raise volumes of everything traded)
- HFT (issue many orders per unit time)
- Complex derivatives and structured instruments (make evaluation of risk comlex)
- Automated trading (73% of trading volume)
- New forms of trading (e.g. Dark pools)
- New ways of sharing the spread (e.g. maker-taker pricing in US equity markets)

Failure to model risk correctly seen as at the heart of most economic crises and failed trading firms.

Persaud Paradox: observation of safety creates risk (where large numbers of market participants take very similar risk-reducing 'safe' positions and thereby, via near-homogeneity of their positions, greatly increase the overall systemic risk

> As discussed, one of the greatest challenge facing the financial services industry, regulators
and government is the quantification of risk. This urgently requires the resources of the
academic community to be harnessed, and a new risk management culture to be established in
financial institutions and regulators. 

## View to 2022

## Disruptive Technologies

Chosen technologies due to their like *disruptive* role.

- HPC in the Cloud
- Proximity servers replaced by proximity silicon
    - FPGA, or
    - Software-defined Silicon (SDS) (phrase by May at XMOS)
        - XMOS XCore chips are field-programmable but fast silicon chips of systolic arrays that can be programmed in XC language
- Adaptive algorithms (untouched by human hands)
    - algorithms (e.g. ZIP, MD) themselves learn to update their behaviour online, but with increasing use of:
    - Genetic algorithms (GA) or Estimation of Distribution Algorithms (EDA) to optimize hyperparameters to trading ML algos

## Sunset on London

- If above predictions pan out, then no reason London stays hub
- Instead, can be mirror to another area where main exchange hosted
- many exchanges already merging
- other country's may invest heavily in developing cloud infrastructure, eduction and financial regulation to enable this

## Cyber-security

Two adversarial groups:

- profit seeking criminals wishing to steal money/assets
- enemgy agents who aim to disrupt/destroy system, eg terrorists of nation-states in times of warfare
    - this latter adversary may be unconcerned with being undetected, as long as damage is done
    - any damage they inflict in financial markets, as markets so globally connected, may reverberate back to them anyway

- Nasdaq exchange attacks by malware 2011
- LSE website (not exchange) hacked with malware 2011
- Russian stock exchange closed by virus infection 2006

- National security services and regulatory authorities almost solely concerned with such cyber attacks
- But, also real prospect of large-scale systemic failure caused by benign endogenous causes
    - everyday traders are fighters in a zero sum war
    - e.g. Flash Crash



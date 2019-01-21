# Network Effect & Reaching Critical Mass Cont...

## Switching Costs and Lock-in

- Switching from one product/service to another similar one can have additional cost - **switching costs**
- Switching costs in digital world are very common and often great
    - e.g. switching operating system has many extra effects
- When switching costs are high, buyers are said to be **locked in** to one provider.
    - *The costs of switching supplier is so higher than potential cost savings or service benefits of new product, that they consumer cannot afford to switch.


### Sources of switching costs in digital domain

1. Training on how to use the system

Software can be complex - users need to be trained / gain experience to use it.

2. The Network Effect

If the product not used by others who the user interacts with, and its not compatible with competitive products, then the user would need to convince others to change at the same time (or find workaround).

3. Setup costs

New software needs to be set up with, e.g., personal details and prefences

4. Reduced service quality due to loss of information

CRM information stored by service provider over time can improve the quality of service. This is lost if moving provider, therefore reducing quality of service of other product to the consumer. (e.g. Amazon recommendations, Spotify Daily playlists)

## Digital Monopolies

*Where both network effect and lock-in is great, we expect to see monopolies emerging.* Where they are less so, competition is easier.

## Breaking into a Network

**Proprietary formats** are powerful means of enforcing monopoly over network of users. e.g. .doc format of MSOffice.

In 2007 OpenOffice reverse-engineered this format allowing OpenOffice to compete:

- Significantly reduced the network lock-in
- but still switching costs: training, support, and simply inertia
- result: MS still dominant, but OpenOffice upto 20% in some countries

## Opening up network through standards

Adopting *industry-wide standards* allows network to be shared between providers:

- your network size increases, bringing in new customers to the overall market network.
- the network effect of competitor's users give value to your users.
- but, your part of the network is opened up to competition.

### Standards

1. Standards **leader**: one player, often the major player, sets the standard by opening up proprietary format
2. Standards **war**: two+ players compete to determine which standard is adopted.
3. Standards **negotiation**: two+ players negotiate a standard collectively

#### Standards leaders

Leader opens up propreitary format with aim of increasing size of overall network of users. E.g. Adobe made pdf format public.

- Exploit leadership position to produce the best products in competition with others
- Produce propreitary value-added products and services which build on this standard

#### Standards War

Competing parties have too much invested to allow negotiation -> battle in marketplace.
Usually bad for either sellers or buyers.

Tactics:

- penetration pricing to reach critical mass / build market share
- alliances with those selling complementary products
- 'expectations management': customer wants to buy winnder, so declare victory early

#### Standards Negotiation

- Negotiation more common today as players talk early
- Leads to less commercial risk than a standards war
- But, diferent players still want to have upper hand in new market that is opened up
- Each party can threaten withdrawal to win negotiation. but for this to be credible, they must be in a strong position if standardisation fails.
- Hence, parties are likely to continue researching their propietary formats as a fall-back and bargaining chip

# "Free products" economics

Near zero variable costs of digital goods mean price is driven to zero by competition. How can organizations make money?

- Differentiate based on quality and charge. e.g. introduce paywall, capitalise on brand (Guardian members)
- Sell complementary goods (support contracts, music merchandise).
    - can also affiliate with providers of complementary goods and revenue share on sales
- Advertise

## Advertising

> "Two-sided businesses based on using bait to attract eyeballs and selling access to those eyeballs to advertisers." ~ D. Evans, UCL, 2008

- Advertising is more valuable the more one knows about recipient
    - background, context, intentions
- Some digital services have advantage here, but some not (e.g. headline news)
- 74% of Facebook US ad revenue from ads for local services

### Online Advertising Market

- Digital channels overtake traditional media soon

### Online vs Offline Advertising

Traditional: advertising is valued based on estimate of number of people viewing the advert

Online, this can be accurately measured.

1. Cost per ***impression***:
    - charged whenever advert is *displayed* to viewer
2. Cost per ***click***:
    - charged whenever advert is *clicked* to access advertisers page
3. Cost per ***lead***:
    - charged whenever site passes an interested customer's *details* on to an advertiser (e.g. customer searches 'cheap car insurance')


- Online advertising has far more sophisticated market for matching advertisers with advertising opportunities. Automated. Google, Facebook, use **auction market mechanism**.
- Content providers devolve the selling of advertising space to specialist advertising platforms
    - Google AdSense

### Google AdSense

- Allows content providers to specify areas of their site to be for advertising, and this to be dynamically filled by Google
- Advert placement can be determined by page content and explicitly entered information about the site
- Selection of adverts is determined by the Google Ad Auction

### Social Network Advertising

*Earned* vs *Paid* media:
    - Earned media: such as word of mouth anecdotes on a site
    - Combination: such as advert including names of user's friends for a 'facebook fans'. These are *ads with Social advocacy'*.

### Search Advertising

Varian estimated:

 - good CTR to be 3%
 - with 3% of clickers making purchase
 - -> fewer than 1 in 1000 viewers making purchase
 - far better than traditional advertising

Google Ad Auction: two sided matching mechanism, aiming to maximise money Google received from click-throughs, i.e. (price per click) \* (number of clicks).

# Auctions

**Auctions**: the mechanism for buyers and sellers to meet and trade.

**English Auction: Open ascending price auction**:

- bidders continue bidding until no-one wants to raise their bid
- highest bid wins and pays that price

**Dutch Auction: Open descending price auction**:

- auctioneer lowers offer until buyer accepts. Buyer pays that price.

**Sealed bid auction**:

- all bidders enter bids to auctioneer, and the highest bid wins.
- **First price sealed auction**: winners pay the price they bid
- **Second price sealed (Vickrey) auction**: winner pays the second-highest big price

**Continuous Double Auction**:

- buyers and sellers can enter a bid/offer at any time

## Incentive Compatibility

An auction is **incentive compatible** if it encourages bidders to bid their **true value** of the good to be purchased.

- this is a form of 1st degree price discrimination

**English auction is incentive compatible**: bidder bids up until they win or someone else bids more than their private valuation.

**Dutch auction is _not_ incentive compatible**: bidder tries to guess what others' private valuations are, and attempts to stop the auction just before that price.

**First-price sealed is _not_ incentive compatible**: bidder will try to bid less than private valuation, based on what they believe others' private valuation is.

**Vickrey is incentive compatible**: bidder can safely reveal their true valuation, knowing it won't affect the price they pay if they win.

### Equivalence of Vickrey and English Auctions

If you have a private value for the good, then Vickrey and English almost equivalent:

- In English auction, winner continues bidding until others stop, so pay 1 bid higher than max of others' private valuations
- In Vickrey auction, winner pays the max of others' private valuations

Under certain conditions including *risk neutrality* of bidders, the *revenue equivalence theorem* shows Dutch and First price sealed are also equivalent in terms of closing price.

**But bidders are not always rational! Psychological factors!**

## Online Auctions

### eBay

- Mainly b2c, c2c, but some b2b.
- Near-monopoly as auction provider: Amazon tried to break in and failed.
- because of network effect and lock-in, auction provision is market that tends towards monopoly

#### eBay auctions

Enlglish auctions but rather than 'going, going, gone...', a fixed time limit is used.

This leads to rush of last miniute bidding, with 'snipers'. This is not optimal.

Solutions:

1. Extend the deadline whenever a bid is placed. This turns it into a proper English auction.
2. Everyone uses a sniper. eBay does this with automated 'proxy' bidding functionality.

Everyone uses automated bidding and enters true maximum bid: becomes Vickrey auction.

- In many ways Vickrey is better model for online auctions as it does not require monitoring.
- Except, it assumes people know in advance their private valuation.
- This is assuming rational economic behaviour, ignoring real-world psychological factors.

### B2B Reverse Auction

- **Reverse auction**: suppliers bid to meet a contract.
- Often suppliers need be qualified in order to participate
- More formalised version of 'Request for Quotes' and encourages explicit competition between quoters.
- Used by many companies, and the US government.
- Sometimes found to be too rigid.

### Google Ad Auction

- Largest number of auctions in world by far (followed by Facebook)
    - auction per search + per display ad page
    - -> billions per week
- 11 slots auctioned, with up to 3 premium slots above the search

#### Hal Varian Ad Auction video

3 parties:

- Advertiser: wants to show relevant ads so that user clicks on them
- User: want to see relevant ads, so not bothered by spam
- Google: wants good experience for both above so that they continue to use service

Each advert has a quality score. **Quality score** has 3 components:

1. Click through rate (~60%) - users' clicks vote for which ads are better quality
2. Relevancy (~30%) - relevancy of keywords to ads and search query.
    - only useful ads are shown to users
    - advertisers can't pay their way onto searches unrelated to their service
3. Landing page quality (~10%) 
    - ad is only useful to user if landing page it leads to is useful to user

**Ad rank:**

`Max Bid` \* `Quality Score` = `Ad rank`

where `Max Bid` is the max bid that advertiser is willing to pay to show their ad.

Ads are then ranked on the page by their `Ad rank`.

**Determining cost per click:**

Second class auction: advertisers pay minimum price to retain their position in the Ad rank.

- Advertiser 1 is competing with Advertiser 2
- Amount he pays is:
    - `p_1 \* Q_1 = b_2 * Q_2`
    - -> `p_1 = b_2 * Q_2 / Q_1`
    - -> `cpc =  (ad rank of advertiser below) / (quality of advertiser)`
- For last advertiser, the price he pays is a minimum price determined for auction

**Effect of quality**: by increasing your quality score, you can decrease your cpc.

#### Sealed bid second price

- Originally, Google considered first-price auction: pay what you bid
- Quickly realised bidders load servers by constantly monitoring system to work out if they could reduce their bid
- -> use second price approach instead

- The auction being incentive compatible reduces monitoring overheads
- Note: algorithmic motivations resulted in them 'rediscovering' economic result from auction theory (i.e. vickrey auction)

#### Quality

Quality score aims to do two things:

1. Estimate the likely probability of click-through for this particular display:
    - historic CTR and relevance
    - **maximising short-term revenue** = price \* probability of clicking

2. Ensure that people who do click through are not disappointed, thus reducing their chance of clicking through (on even very different searches) in the future:
    - landing page quality
    - **protects 'longer term' revenue**

- To approx, quality `q` estimates `Pr{ad is clicked}`.
- Google not interested in bid price `p`, but `p\*q`.
- But bidder doesn't pay this, they pay
- -> second price times ratio of probabilities of being clicked
- -> `= (p'\*q')/q = p'\*(q'/q)`


##### Estimating prob of being click

- prob. ad is clicked is dependen on *ad quality* and *ad placement* on the page.
- Google needs to model for the latter: its independent of ad quality
- It does this by randomly allocating ads to different positions to estimate the position-specific effect
- They also offer a similar random-placement service to advertisers to allow them to experiment with different adverts and see which is most effective
- **Economic experimentation**:
    - experiments fast and cheap online
    - algorithsm enable economic experimentation, rather than relying on forecasting

##### Effect of competition

- Price depends on other bidders (second-price auction)
- -> Competion important -> oversold auction makes more than undersold auction
- To simulate competition in ad auctions, Google makes advertisers choose whether their ad should be entered into auction for a search result using 'partial matching' keywords, rather than 'exact match'.

# Impacts of Internet Economics

**Direct**: environmental impact of using products/services

- 2.5% of UK energy emissions.
- Equal emissions to aviation industry
- 47% user devices, 29% data centres, 24% networks.

**Indirect**: changes in behaviour

- home shopping
- working remotely / from home

**Systemic**: structural changes in society

- people taking jobs further than they used to
- travelling less often to workplace, but further

**Social impacts**:

- employment and self-employment. Gigging
- internet-facilitated tax avoidance
- privacy
- transparency

## Hi-tech companies employ fewer people?

Apple: 1bn market cap -> 92k employees
Alphabet: 780m market cap -> 54k employees
Facebook: 450m market cap -> 9k employees
Amazon: 900m market cap -> 117k employees

Boeing: 215m market cap -> 168k employees

Walmart: 280m market cap -> 2.2 million employees!!!

## Do hi-tech companies stimulate small business?

- **Cost** of starting small business decreased - home office, online connectivity
- **Reach** has increased
- **Niche** businesses are therefore more viable.
    - customers can be anywhere (no overheads of many physical locations)
    - Big tech (amazon, google, paypal, etc) provide the infrastructure

**Gigging**: few rights, no unions, pensions, minimum wage, holiday pay, etc

## Internet Facilitated Tax Avoidance

Internet makes tax avoidance easier:

- tax laws apply to individual company or region (e.g. EU) but internet companies can easily set up as multi-national
- transactions can take place away from country of actual customer
- its easier for an organisation to conduct business in a state or country while preserving a 'skeleton staff' there (or none at all)

### Round tripping

- Play.com 1998 in Jersy, Channel Islands, selling CDs/DVDs/games to UK customers
- **Low Value Consignment Relief (LVCR)** - no VAT on goods under £18 sold to EU from Channel islands.
- -> Play.com saving VAT (15-20%) over UK retailers

Amazon, Tesco followed, after trying to stop Play.com:

- **Round tripping**: CDs/DVDs shipped to Channel Islands then mailed back individually
- 2012: EU declare round tripping not in spirit of LVCR
- TheHut/Zavvi allegedly round-tripping via USA
- Amazon eBooks are sold from Luxembourg - only 3% VAT

### The Double Irish Dutch Sandwich

- Loophole closed to new companies in 2015
- Will close in 2020 to companies previously using the loophole
- 1000+ companies including Apple, Google, Amazon
- 2016 Alphabet moved 19.2bn to Bermudan shell company

1. US Parent Corp licenses IP to Irish/Bermudan Holding Company (incorpoarted in Ireland with no employees and tax resident in Bermuda (management and control in Bermuda)). Ireland, Bermuda are tax havens.
2. Holding Company sublicenses IP to Dutch Holding Company. It has no profit = no tax
3. Dutch holding company sublicenses IP to Irish Operational Company
4. Business revenue from non-US operations goes into Irish Operational Company
5. Irish Operational company pay royalties (no Irish witholding tax within EU) to Dutch holding company
6. Dutch holding company pay royalties to Bermudan Holding Company (no Dutch witholding tax to Bermuda)
7. Bermudan Holding company pay royalties / dividends to US parent Corp

US parent Corp. is just paying US tax on net income on royalties paid from Irish/Berumdan Holdco. Most income ends up in Irish/Bermudan holding company. Bermuda has zero corporation tax. Money re-invested into non-US operations, or repatriated via dividens.


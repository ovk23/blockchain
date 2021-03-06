# blockchain for adtech

A blockchain based alternative to the opaque openRTB based programmatic advertising marketplace.

## 1. Background 

The programmatic advertising marketplace is opaque, inefficient, and does not enjoy the trust of the media buyers. Reports show how fraud, ad misplacement and misreporting are widespread issues in the current openRTB based marketplace. Based on very rough modelling, we find that online advertising technology is responsible for a single digit percentile of the global energy footprint. 

Our first contribution in this field is to clearly outline an alternative blockchain based model for programmatic advertising, where on a decentralized platfrom transactions are performed without possibility of fraud, misreporting or 3rd-party interference. We present a marketplace where by its very design, all participants embrace 100% transparency in a democratic eco-system.

Our second contribution is to prove that using a pseudo-blockchain based marketplace model, in addition to being authentic, transactions can be performed with a small fraction of the energy that it woudld take to perform the same transactions under typical conditions im the openRTB marketplace.  

## 2. Solution

The solution consist of three primary functions: 

1) facilitate for programmatic advertising transactions (as openRTB now)
2) enrich each transction with meta-data (e.g. "fraud score") 
3) reduce energy overhead of typical blockchain without losing value  

## 3. Marketplace interactions

1) internet users interact with websites 
2) advertising exchanges interact with websites 
3) trading desks interact with ad exchanges
4) media budget holders interact with trading desks

### 3.1 Outline of an ad placement

Note that we've concisedered the DSP and trading desk both under "trading desks". 

- internet user goes to a webpage
- the webpage source code includes ad tags
- the ad tags have the function of connecting the user with exchange 
- once the exchange receives the connection it creates an auction 
- trading desks compete against each other for the bid
- once the exchange knows it sends an ad to be placed on the webpage
- the user sees the ad

### 3.2 Ad placement related moneyflow

- the exchange pays to the publisher 
- the trading desk pays to the exchange
- the media buyer pays to the trading desk 

### 3.3 Ad placement related disclosure

- referrer of the ad placement
- IP address of the visitor 
- user-agent of the visitor
- exchange that did the transaction 
- time of the event

Based on these factors, a unique id is created for every event, entirely eliminating the possibility of arbitrage or other non value adding practices where events are in effect duplicated. 

### 3.4 Scoring of sites 

Every site has a score that is re-computed frequently, and the score is provided as part of the auction invite the exchange provides to the trading desk. The mechamism we're proposing for scoring of sites have been outlined with great level of detal in two separate academic papers and is endorsed by leading researchers and the World Federation of Advertisers. 

## 4. Stakeholders and Motitations

1) Internet users 
2) Media buyers
3) Media agents
4) Media networks/exchanges
5) Media onwers
6) Various middle-men

### 4.1 Internet users 

- users are concerned with privacy
- users are concerned with security 
- users are concerned with bandwidth cost 
- users are concerned with user experience 
- users are concerned with misleading ads 
- users are concerned with harmful advertising

### 4.2 Media buyers

- reaching the right audience
- brand safety
- contextual relevance
- age verification
- user is human 
- ad is viewable
- ad effectiveness
- transparent reporting 
- spending enough money

### 4.3 Media Agents

- maximize media trading volume
- renewing their accounts 
- spending enough money
- maximizing their commissions
- find "alternative" revenue sources

### 4.4 Media networks/exchanges 

- maximize media trading volume
- maximize fillrates for media owners 
- maximize commissions from buyers 
- maximize number of websites in the network 
- maximize number of visitors in the network 
- maximize number of pageviews in the network
- minimize cost of technology

### 4.5 Media owners

- maximize media trading volume
- maximize fill-rate 
- maximize pageviews 
- maximize retention 
- maximize earning per visit
- monetize user data

## 5. Supply-chain models 

1) currency
2) delivery chain

### 5.1 Currency

- quantity based buying
- time based buying (seconds / minutes)
- period based buying (one week)
- placement based buying (whole landing page)

### 5.2. Delivery Chain 

- publisher and buyer do tag exchange 
- publisher and exchange do tag exchange 

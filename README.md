# FinTech Case Study - IEX Group

![Logo](https://mms.businesswire.com/media/20180912005578/en/677814/2/IEX_Logotype_%28standard%29.jpg)

## Overview and Origin

* **Incorporated:**  2012

* **Founders:**  Brad Katsuyama & Ronan Ryan

* **Genesis of Business:** While working together on the global electronic trading team at Royal Bank of Canada, the founders discovered that the biggest stock exchanges were incentivizing predatory trading behaviour that was negatively impacting long-term, institutional investors that represented the savings of million of people.  The founders felt the best way to effect change was to create a new exchange where the interests of the investor came first.     

* **Funding:** To date the company has raised $100.9M over 5 rounds of funding.  Its largest investors include Spark Capital and Sapphire Ventures along with smaller investments made by a diverse group of institutional market participants.  

## Business Activities

### **Reshaping the Incentive Structure and Building Fairer Markets**

IEX aims to dismantle and re-engineer the incentive structure that most modern stock exchanges currently operate under.  Under this system, the exchanges incentivize liquidity providers to co-locate servers and deploy an ever increasing amount of computing power in an effort to shave thousandths of a millisecond off of trade times to exploit this speed incentive.  Ultimately, the actions of these market participants adversely affect institutional investors (who represent the 401k’s and pensions of millions of people) by obscuring true price discovery, depressing real liquidity and exacerbating periods of market instability.  

### **Target Market & Beneficiaries**

The only market participants that wouldn't benefit immensely from IEX's innovations and business model are predatory high-frequency traders that exploit structural deficiencies in the current market landscape.  

By promoting better price discovery, transparency, stability and quality liquidity true transaction costs will be lower for everybody.  Ultimately, IEX offers a truly level playing field for all market participants, something that competing exchanges, by the very nature of how they are set up, can not offer. 

### **Tools in the Arsenal - Innovations and Technology Used**

To combat the advantages that only “structural insiders” have access to, IEX has made numerous innovations in their effort to put all market participants on an equal footing:

#### *The IEX Signal a.k.a "The Crumbling Quote Indicator"*

> This is a predictive model that forecasts when the price of a stock is about to change.  By leveraging their massive speed advantage, high-frequency traders are able to forecast when prices are about to change drastically and "pick-off" slower participants, a form of latency arbitrage.  The IEX signal protects orders from getting picked off by pulling the order until the price changes.

#### *"The Speed Bump"*
>
><img src="https://2.bp.blogspot.com/-7H1sHn8iHfw/V2FhWBZyJ7I/AAAAAAAAEsM/E7bcloE7heUSeyvIMyaifAE7qTZFmyYzwCLcB/s1600/magic-shoe-box.png" width="250" height="250">
>
>The speed bump is a 38-mile long fiber optic cable that slows down price information coming into and out of IEX by 350 microseconds.  This is an effort to mitigate the advantage that co-location of servers at exchange data processing centers offers high-frequency traders.  Often times these market participants will have quicker access to market information than the exchanges themselves.  

#### *IEX Cloud*

>Financial data sets are often messy and incomplete.  In addition to having to sort through vast amounts of data, participants that need information on different markets or parameters might have to access dozens of different APIs in order to find what they are looking for.  To solve this problem, IEX Cloud provides highly curated, scrubbed and organized financial data on stocks, forex and crypto all through one API.  The ultimate goal is to democratize access to quality financial data for everybody.
>
>*Sample API Code:*

```python
    curl 'https://cloud.iexapis.com/v1/stock/aapl/ohlc/?token={your_token}'
    {
        open: {
        price: 199.01,
        time: 1542033000818
    },
    close: {
        price: 204.47,
        time: 1541797200568
    },
    high: 199.85,
    low: 193.79
    }
```

#### *Rules Engine*
>
>As a subset of the Cloud platform, IEX has developed a "Rules Engine" tailored to users without coding experience.  Through an inutitive and simple interface users can build models and screens based on simple rules (eg. show me stocks whose price has increased >8% over the past 10 days whose PEG ratio is higher than 20).  By combining multiple data sets and handling all the computing and data storage in their cloud, users don't need to set up any storage infrastructure.

## Market Landscape:

* **Domain:** Investment Management

* **Trends and Innovations in this Area**

    Despite the specter of the 2010 “Flash Crash” looming over markets for the past 10 years;  little has been done to change or challenge the status quo.  The latency arms race rages on as entrenched firms with majority of market share double-down on incentivizing practices that harm smaller investors (Case in point: [Competing wireless data transmission towers owned by two HFT vie for precious inches to get closer to the CME derivatives server in a small Chicago suburb](https://www.bloomberg.com/news/features/2019-03-08/the-gazillion-dollar-standoff-over-two-high-frequency-trading-towers)).

    The majority of innovations in Investment Management have come from ....(FINISH)


* **Major Players in Domain:** 

    | Old Guard      | New Comers |
    | -----------    | ----------- |
    | NYSE/ICE       | MEMX      |
    | Nasdaq         | Coinbase (Stablecoin)       |
    | AMEX           |    Clarity - Bidrate   |
    | BATS           | BTS Spark       |


## Results

**Impact**

After peaking at a little over 2.5% in July of 2019, IEX currently has around 1.8%  of listed US equities market share.

   >![Historical Market Share](marketshare.jpg)

A lot of pundits have struggled to explain why IEX hasn't faired better since they got approval as a national securities exchange in 2016.  As the Financial Times stated in mid-2019:
        
   >>To some, it is a missed opportunity: a sign that the structures IEX hoped to dismantle have remained in place. The incumbent groups have retained their hegemony and HFTs still threaten to pick off the best prices from slower investors.
   >>       
   >>“I’m surprised [IEX’s] market share isn’t higher,” said Kevin Cronin, global head of trading for Invesco, the $955bn-in-assets firm based in Atlanta, who tried to hire Mr Katsuyama before he launched the exchange. “They have achieved a lot — but there’s a long way to go for IEX to achieve what many thought they would have.”  ([Source](https://www.ft.com/content/fc1a0d44-827a-11e9-b592-5fe435b57a3b))

One key underestimation the founders made was how much of the industry centered around exchanges paying for order flow.  IEX doesn't offer rebates to market makers based on how much they trade whereas most other exchanges do (See Chart Below).  For example, the exchange will credit traders on a monthly basis a certain amount of cents per share based on their overall trading volume for that month.  The allure of this credit has been too strong to pass up for a lot of traders.  Anecdotally, at a previous hedge fund I worked at (which wasn't even a HFT shop rather a derivatives focused fund that traded a lot of underlying stock to hedge their derivatives exposure) the equity desk received these rebates.  They viewed it as a way to cut down on their overall brokerage and exchange fees. 

>![Rebates by Exchange](rebates.jpg)

**Performance Metrics**

There are few indicators used to evaluate the "market quality" of various exchanges.

* *Liquidity:* As mentioned above, IEX's market share, and therefore overall trading volume, is smaller compared to more established exchanges.  However, because these exchanges offer an incentive in the form of a rebate to provide liquidity, it is import to assess liquidity not just in terms of quantity but also the *quality* of that liquidity:

    * Midpoint Volume: Utilizing key innovations such as the *Crumbling Quote Indicator* and the speed bump, IEX has constructed a market that is very conducive to mid-point trading.  Because midpoint liquidity is not displayed, it is a useful way for investors to move large blocks of stocks without revealing their intention to buy or sell to the broader market.  Trades that occur at the midpoint are also cheaper because they don't have to cross the bid-ask spread.  For an exchange as small as IEX, the percentage of trades done at the midpoint are impressive:

    ![IEX Midpoint Volume](midpointvolume.jpg)     
   

* How is your company performing relative to competitors in the same domain?


## Recommendations

* If you were to advise the company, what products or services would you suggest they offer? (This could be something that a competitor offers, or use your imagination!)

* Why do you think that offering this product or service would benefit the company?

* What technologies would this additional product or service utilize?

* Why are these technologies appropriate for your solution?


>## *Research Notes:*
>
>* https://www.crunchbase.com/organization/iex
>* https://en.wikipedia.org/wiki/IEX
>* https://iextrading.com/
>* Flash Boys: A Wall Street Revolt, Michael Lewis
>* https://iextrading.com/docs/The%20Evolution%20of%20the%20Crumbling%20Quote%20Signal.pdf
>* https://youtu.be/-a10cCR9HoM
>* https://iexcloud.io/
>* https://www.bloomberg.com/news/features/2019-03-08/the-gazillion-dollar-standoff-over-two-high-frequency-trading-towers
>* https://ideas.darden.virginia.edu/innovations-for-fairer-markets-in-the-era-of-high-frequency-and-algorithmic-trading
>* https://www.ft.com/content/fc1a0d44-827a-11e9-b592-5fe435b57a3b
>* https://iextrading.com/docs/A%20Comparison%20of%20Execution%20Quality%20across%20U.S.%20Stock%20Exchanges.pdf
>* https://www.tradersmagazine.com/am/the-iex-d-limit-proposal-its-goodbut-what-if-its-too-good/









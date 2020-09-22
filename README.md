# FinTech Case Study - IEX Group

![Logo](https://mms.businesswire.com/media/20180912005578/en/677814/2/IEX_Logotype_%28standard%29.jpg)

## Overview and Origin

>* **Incorporated:**  2012
>
>* **Founders:**  Brad Katsuyama & Ronan Ryan
>
>* **Genesis of Business:** While working together on the global electronic trading team at Royal Bank of Canada, the founders discovered that the biggest stock exchanges were incentivizing predatory trading behaviour that was negatively impacting long-term, institutional investors that represented the savings of million of people.  The founders felt the best way to effect change was to create a new exchange where the interests of the investor came first.     
>
>* **Funding:** To date the company has raised $100.9M over 5 rounds of funding.  Its largest investors include Spark Capital and Sapphire Ventures along with smaller investments made by a diverse group of institutional market participants.  

>
>
## Business Activities

### **Reshaping the Incentive Structure**

IEX aims to dismantle and re-engineer the incentive structure that most modern stock exchanges currently operate under.  Under this system, the exchanges incentivize liquidity providers to co-locate servers and deploy an ever increasing amount of computing power in an effort to shave thousandths of a millisecond off of trade times to exploit this speed incentive.  Ultimately, the actions of these market participants adversely affect institutional investors (who represent the 401k’s and pensions of millions of people) by obscuring true price discovery, depressing real liquidity and exacerbating periods of market instability.  

### **Tools in the Arsenal**

To combat the speed advantage that only “structural insiders” have access to, IEX has made numerous innovations in their effort to put all market participants on an equal footing:

#### *The IEX Signal a.k.a "The Crumbling Quote Indicator"*

> This is a predictive model that forecasts when the price of a stock is about to change.  By leveraging their massive speed advantage, high-frequency traders are able to forecast when prices are about to change drastically and "pick-off" slower participants, a form of latency arbitrage.  The IEX signal protects orders from getting picked off by pulling the order until the price changes.

#### *"The Speed Bump"*

><img src="https://2.bp.blogspot.com/-7H1sHn8iHfw/V2FhWBZyJ7I/AAAAAAAAEsM/E7bcloE7heUSeyvIMyaifAE7qTZFmyYzwCLcB/s1600/magic-shoe-box.png" width="250" height="250">

>The speed bump is a 38-mile long fiber optic cable that slows down price information coming into and out of IEX by 350 microseconds.  This is an effort to mitigate the advantage that co-location of servers at exchange data processing centers offers high-frequency traders.  Often times these market participants will have quicker access to market information than the exchanges themselves.  

#### *IEX Cloud*

>Financial data sets are often messy and incomplete.  In addition to having to sort through vast amounts of data, participants that need information on different markets or parameters might have to access dozens of different APIs in order to find what they are looking for.  To solve this problem, IEX Cloud provides highly curated, scrubbed and organized financial data on stocks, forex and crypto all through one API.  The ultimate goal is to democratize access to quality financial data for everybody.


>
    Sample API Code:

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

As a subset of the Cloud platform, IEX has developed a "Rules Engine" tailored to users without coding experience.  Through an inutitive and simple interface users can build models and screens based on simple rules (eg. show me stocks whose price has increased >8% over the past 10 days whose PEG ratio is higher than 20).  By combining multiple data sets and handling all the computing and data storage in their cloud, users don't need to set up any storage infrastructure.


### **Target Market & Beneficiaries**

The only market participants that wouldn't benefit immensely from IEX's innovations and business model are predatory high-frequency traders that exploit structural deficiencies in the current market landscape.  

By promoting better price discovery, transparency, stability and quality liquidity true transaction costs will be lower for all market participants.    


## Landscape:

* What domain of the financial industry is the company in?

* What have been the major trends and innovations of this domain over the last 5-10 years?

* What are the other major companies in this domain?


## Results

* What has been the business impact of this company so far?

* What are some of the core metrics that companies in this domain use to measure success? How is your company performing, based on these metrics?

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





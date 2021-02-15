

## Introduction

The last two weeks bestowed the pleasure of learning about the UK's Renewable Obligation Scheme; specifically the fundamentals and market risks associated with trading certificates signifying compliance.

In this post - I delve into the UK's mandate to reduce its carbon footprint, and the effect in creating demand and supply for a tradeable product.

## The United Kingdom

I've various fascinations with the United Kingdom. From its controversial kings, the castles held by the marvelous green lawns - the finely tuned British dialect and strong female figures from Queen Elizabeth I to Margaret Thatcher. You may even find my mornings glistering to the drums and fifes of the "British Grenadiers" in preparation for battle against the multitude of unread emails on Outlook.

And alas my newest fascination on the UK's performance in reducing carbon emissions.

Below are the YoY percentage changes of a country's CO2 output. With the exception of the USA, I selected a comparable set of countries, striving to reduce their carbon footprint.

<div align="center">
<iframe width="700" height="500" frameborder="0" scrolling="no" src="//plotly.com/~gmontano/1.embed"></iframe></div>

The graph, although convoluted in sight - highlights the UK edging ahead, with the best 10-year average of -2.78%

||AUS|CHN|FRN|GER|JPN|UK|USA|
|--|--|--|--|--|--|--|--|
|10-Yr Avg|0.10%|2.82%|-1.56%|-1.12%|-0.44%|-2.78%|-0.35%|

But *how* is this happening?

## OFGEM and The Renewable Obligation Scheme

The Office of Gas and Electricity Markets (OFGEM) is an independent UK regulator striving towards a greener UK. One mechanism it mandates is the Renewables Obligation scheme to incentivise large-scale renewable electricity supply. Every MWh of non-renewable energy receives an obligation. At the end of the period (yearly) -  obligations are totaled and must be fulfilled.

### Renewable Obligation Certificates

At this stage - *obligation* requires a little more abstraction to establish a measurable construct. Thus enters Renewable Obligation Certificates (ROCs), which are pseudo-tangible and measurable objects of compliance.

For the period beginning in April 2021 and ending March 2022 - every MWh of non-renewable energy in Great Britain receives an obligation of 0.492 ROCs. Said differently, every 2.032 MWh demands a single ROC.


### Obtaining ROCs

So far the idea of generating an obligation through ROCs has been presented. However, how does one *obtain* an obligation offset, or a ROC? The answer is simple: supply renewable energy.

A supplier generating green energy - will receive a number of ROCs depending on (i) the technology used; (ii) the time accreditation; and (iii) the station’s installed capacity. For example in 2017 offshore wind generated 1.8 ROCs per MWh whereas onshore wind only gave 0.9.

### Fulfilling the Obligation

At the end of obligation period, every accredited supplier is required to deliver a number of ROCs to OFGEM. Alternatively, they may choose to  *buy out* their mandate at a prescribed price per ROC. These "buy-out" prices, starting from 2010, are shown below.

| Date          | 2010  | 2011  | 2012  | 2013  | 2014  | 2015  | 2016  | 2017  | 2018  | 2019  | 2020  | 2021  | 2022  |
|---------------|-------|-------|-------|-------|-------|-------|-------|-------|-------|-------|-------|-------|-------|
| Price | 37.19 | 36.99 | 38.69 | 40.71 | 42.02 | 43.30 | 44.33 | 44.77 | 45.58 | 47.22 | 48.78 | 50.05 | 50.80 |

The following graph illustrates how suppliers in a given year met their obligations by either (i) buying out; (ii) presenting ROCs.

<div align="center">
<iframe width="700" height="500" frameborder="0" scrolling="no" src="//plotly.com/~gmontano/3.embed"></iframe></div>

It's clear that most obligations are met through ROC presentation. However, one may notice an increasing trend in the ROCs bought out. This may be attributed to decreasing compliance or the factual increases in the ROC rate per unit of non-renewable energy. Assuming stern views on a greener economy - the first case is ruled out.

### The Recycle Value

Taking one step back - it seems suppliers have 2 choices: (i) Pay to invest in a renewable source of energy; or (ii) buy-out their obligation. While both options are viewed as a cost - there is a monetary incentive to comply.

Suppliers may then be categorised into three groups:

1. Those who complied having at least as many ROCs as required
2. Those who did not comply and paid a cash amount equivalent to their ROC requirement
3. Those who did not comply, did not buy-out and made a late and enforced payment

Payments from (ii) and (iii) are pooled into a fund, and after netting administration costs are distributed to (i) on a pro-rata basis. This distribution per ROC is called the **Recycle Value**, and is the monetary incentive to comply.

The table below provides detail of this mechanism across the years. The first row is the pool of funds, the second is the number of ROCs provided by complying suppliers and the third is the recycle value.

|                       | 10     | 11     | 12     | 13     | 14    | 15    | 16    | 17     | 18     | 19     |
|-----------------------|--------|--------|--------|--------|-------|-------|-------|--------|--------|--------|
| Buy Out and Late (MM) | 324.00 | 358.00 | 123.00 | 164.00 | 42.00 | 25.00 | 0.00  | 460.00 | 604.00 | 842.00 |
| Num ROCs              | 21.30  | 25.00  | 34.40  | 44.80  | 60.80 | 71.30 | 84.40 | 90.20  | 103.20 | 107.60 |
| Rec. Value            | 15.17  | 14.35  | 3.58   | 3.67   | 0.7   | 0.35  | 0     | 5.1    | 5.85   | 7.82   |

## The Value of a ROC



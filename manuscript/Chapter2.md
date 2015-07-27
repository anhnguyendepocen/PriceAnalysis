html\_document: toc: true theme: readable

This chapter serves as an introduction to real-time and historical data
sources, as well as an introduction to the analysts that conduct price
analysis professionally and help us make sense of commodity prices.
First, we will introduce the reader to some entities that provide market
commentary and price analysis. Next, we will provide a very brief
introduction to futures markets as the source of real-time price
information for commodities. This section also covers where and how to
obtain current futures price quotes. In the section that follows we
cover sources for historical data such as the United States Department
of Agriculture and others. These sources will be useful in developing
fundamental price models in later chapters. The goal of this chapter is
to get the reader up to speed on where to get commodity price data and
reading the professional analysis daily. The more you follow commodity
markets, the more you learn. Absorb the insights of the professionals
who live and breath commodity markets every day, and you will begin to
have a feel for what price analysis is all about and how it works.

Resources for Market Commentary
===============================

The best way to learn commodity price analysis is to listen to the
professionals who provide commentary on the markets on a regular basis.
Land grant universities located in major commodity producing states all
have components of their outreach programs dedicated to market
commentary. The University of Illinois' web extension program, FARMDOC,
is particularly good. Also, public radio in major commodity producing
areas has excellent coverage. Champaign-Urbana's WILL, and Iowa Public
Televisions' Market to Market are very good. There are *many* other
great sources providing regular commentary, but this will get the reader
started.

<table>
<caption>Table 1. Resources for commodity market commentary</caption>
<thead>
<tr class="header">
<th align="left">Outlet</th>
<th align="left">Description</th>
<th align="left">Link</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">Farmdoc Daily</td>
<td align="left">Extension web presence by the department of ACE</td>
<td align="left"><a href="http://farmdocdaily.illinois.edu/" class="uri">http://farmdocdaily.illinois.edu/</a></td>
</tr>
<tr class="even">
<td align="left">WILL Agriculture</td>
<td align="left">WILL and the University of Illinois Extension</td>
<td align="left"><a href="http://will.illinois.edu/agriculture" class="uri">http://will.illinois.edu/agriculture</a></td>
</tr>
<tr class="odd">
<td align="left">Market to Market</td>
<td align="left">Agricultural programming by Iowa Public Television</td>
<td align="left"><a href="http://www.iptv.org/mtom/" class="uri">http://www.iptv.org/mtom/</a></td>
</tr>
</tbody>
</table>

Futures Contracts as Sources of Real-time Price Information
===========================================================

Futures contracts (contracts to buy/sell a specific quantity of, say,
corn at a specific price on a specific date in the future) can be
distinguished from forward contracts in that quantity and quality are
standardized. This facilitates the ability of futures contracts to be
traded on an exchange. Whereas a forward contract has specific
counterparties (buyers and sellers), with futures contracts the exchange
becomes the seller to every buyer and the buyer to every seller. If
enough market participants are present it is very easy to get into and
out of these futures contracts because you do not have to come to an
agreement with the original buyer/seller. You simply take an offsetting
position (sell if you originally bought and buy if you originally sold)
at the currently prevailing price. The exchange takes your contractual
obligation off the books and you just pay (or receive) the difference in
price between when you bought and when you sold. Fully understanding the
function of futures markets is well beyond the scope of this book, but
the interested reader is encouraged to refer to Kub (2012) for a
practical introduction and Hull (Hull 1991) for a more technical
approach.

Futures Data Sources
--------------------

For agricultural commodities in the United States, the [CME
Group](http://www.cmegroup.com/) is the most important futures exchange
for price discovery. Grain and oil-seed contracts traded at the CME
Group include corn, soybeans, soybean oil, soybean meal, soft red winter
wheat, hard red winter wheat. They also list futures contracts for
livestock products such as live cattle, lean hogs, and feeder cattle.
'Soft' commodities that trade on the CME Group are cocoa, coffee, and
sugar. The CME Group also lists energy commodity products for crude oil,
natural gas, ethanol, and other products. This book will focus most
intently on the grain and oil-seed contracts, with some topics related
to the cattle and energy contracts considered. Many of these futures
contracts are considered to be the main price setting function for the
commodity in the world. Chicago Board of Trade (owned by the CME Group)
futures prices of corn and soybeans are considered the 'World Price' of
corn and soybeans. Meaning that all over the globe, prices for these
commodities are set based on what the price of corn and soybeans are
trading on the CME Group exchanges.

Real-time (10-min delay) data can be obtained directly from the CME
Group's website. There you can view the most recent quotes, and some
charting capability is provided as well. Typically, however, it is more
convenient to obtain market quotes from third party vendors like [Yahoo
Finance](http://finance.yahoo.com/),
[Quandl](https://www.quandl.com/collections/futures),
[barchart](http://www.barchart.com/futures/marketoverview) (subscription
required), or others. Those sources offer a more flexible interface for
viewing on the web, and provide utility to download recent price
history.

Futures Symbols and Looking up Data by Contract Expiration
----------------------------------------------------------

Contracts for several different expiry dates trade at the same time.
There is a useful shorthand for finding contracts for a specific
commodity and expiration month that varies only slightly among data
vendors; all follow a general convention for building futures ticker
symbols customizing only to meet the needs of their individual systems.
The table below lists selected grain and oilseed, livestock, and energy
contract symbols, expiration symbols, and common ticker formats used to
search for price quotes. For example, the first row of the table
illustrates that the general convention for representing the CBOT corn
futures contract expiring in December of 2015 is CZ15. The first letter
represents the commodity symbol, C for corn; the second letter
represents the expiration month, Z for December; and the final two
numerals represent the year of expiry, 15 for 2015.

<table>
<caption>Table 2. Conventions for building futures contract ticker symbols for selected commodities</caption>
<thead>
<tr class="header">
<th align="left">Commodity</th>
<th align="center">Symbol</th>
<th align="left">Expiration Months and Symbol</th>
<th align="left">General Ticker</th>
<th align="left">Yahoo Finance Ticker</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">Corn</td>
<td align="center">C</td>
<td align="left">March (H), May (K), July (N), September (U), December (Z)</td>
<td align="left">CZ15, December 2015 Corn</td>
<td align="left"><a href="http://finance.yahoo.com/q;_ylt=Aq08zZO8Y0A5GdeM2aZSNJJ.FJF4?uhb=uhb2&amp;fr=uh3_finance_vert_gs&amp;type=2button&amp;s=cz15.cbt">CZ15.cbt</a></td>
</tr>
<tr class="even">
<td align="left">Soybeans</td>
<td align="center">S</td>
<td align="left">January (F), March (H), May (K), July (N), August (Q), September (U), November (X)</td>
<td align="left">SX15, November 2015 Soybean</td>
<td align="left"><a href="http://finance.yahoo.com/q;_ylt=Ajq44ku8k3rd1HzDOLpIozEnv7gF?uhb=uhb2&amp;fr=uh3_finance_vert_gs&amp;type=2button&amp;s=sx15.cbt">SX15.cbt</a></td>
</tr>
<tr class="odd">
<td align="left">SRW Wheat</td>
<td align="center">W</td>
<td align="left">March (H), May (K), July (N), September (U), December (Z)</td>
<td align="left">WZ15, December 2015 SRW Wheat</td>
<td align="left"><a href="http://finance.yahoo.com/q;_ylt=Ajq44ku8k3rd1HzDOLpIozEnv7gF?uhb=uhb2&amp;fr=uh3_finance_vert_gs&amp;type=2button&amp;s=wz15.cbt">WZ15.cbt</a></td>
</tr>
<tr class="even">
<td align="left">Lean Hogs</td>
<td align="center">HE</td>
<td align="left">Feb (G), Apr (J), May (K), Jun (M), Jul (N), Aug (Q), Oct (V), Dec (Z)</td>
<td align="left">HEZ15, December 2015 Lean Hogs</td>
<td align="left"><a href="http://finance.yahoo.com/q;_ylt=Ajq44ku8k3rd1HzDOLpIozEnv7gF?uhb=uhb2&amp;fr=uh3_finance_vert_gs&amp;type=2button&amp;s=HEZ15.CME%2C">HEZ15.cme</a></td>
</tr>
<tr class="odd">
<td align="left">Crude Oil</td>
<td align="center">CL</td>
<td align="left">All months</td>
<td align="left">CLU15, September 2015 Light Sweet Crude Oil</td>
<td align="left"><a href="http://finance.yahoo.com/q;_ylt=Ajq44ku8k3rd1HzDOLpIozEnv7gF?uhb=uhb2&amp;fr=uh3_finance_vert_gs&amp;type=2button&amp;s=clu15.nym">CLU15.nym</a></td>
</tr>
</tbody>
</table>

While every market participant needs to know the current price,
forecasting and decision making requires the study of historical prices
and other important market variables. Historical futures price data is
available for free and from subscription based services from
[Quandl](https://quandl.com) and [Barchart](https://barchart.com)
mentioned in the paragraph above. Historical [futures price
data](http://farmdoc.agricharts.com/markets/historic.php) and [average
price
recieved](http://www.farmdoc.illinois.edu/manage/pricehistory/price_history.html)
is also available from [farmdoc](http://www.farmdoc.illinois.edu), the
online extension presence of the University of Illinois' [Agricultural
and Consumer Economics](http://ace.illinois.edu/) department.

Reports and Data from the USDA
==============================

The United States Department of Agriculture has a long history of
extensively surveying market conditions, reporting to the public and
maintaining accessible databases. Because of their efforts to provide
consistent and accurate (as is possible) estimates of key variables like
acres planted, yield, production, stocks, consumption, and exports,
market participants follow USDA reports about market conditions very
closely. Their impacts on prices can be seen immediately amd sometimes
cause rapid, if not instantaneous price moves as the market digests the
new information from the report. The most closely watched reports are
summarized below.

USDA Reports Influential in Commodity Markets
---------------------------------------------

**Prospective Plantings:** The Prospective Plantings report is an
estimate of grower intentions for planted acres during the first two
weeks of March. The report is released on the last day of March every
year. Planted acres for each crop varies considerably from year-to-year
and this report give the market important guidance about expected supply
of the covered commodities. The most important reason prospective
plantings change from year-to-year is the relative prices of crops that
compete for acres. Growers look to the prices of futures with a expiry
around the time of harvest for an estimate of expected profit from
planting competing crops. For example, if the price of corn is
relatively high compared to soybeans, and expected profitability from an
acre of corn is higher than from an acre of soybeans, the farmer is
likely to shift some of his planting intentions from soybeans to corn
compared to the crop mix typically planted. In this case you might hear
market commentary include language like, "... corn is bidding for
acres." Meaning that price of corn is trying to entice growers to shift
acres into corn production.

**Acreage:** While the Prospective Plantings Report estimates growers'
*intentions* to plant, Acreage is an estimate of the acres actually
planted. This report is based on surveys conducted during the first two
weeks of June and released on the last day of June. Weather and changes
in the relative price of crops that compete for acres are the most
important reason for differences between Prospective Plantings and
Acreage reports. Weather can play a factor becasue crops that compete
for acres are not nessessarily planted at the same time. Corn, for
example, is typically planted a few months before soybeans. The Corn
Belt, where the biggest production of corn and soybeans occur, can often
be very wet in the Spring. In some years this makes is physically very
difficult to get to plant the number of acres of corn they intended when
surveyed during the first two weeks of March. The relative price of
crops competing for acres can also change between March and June for any
number of reasons and cause the Acreage report to be substantially
different than Prospective Plantings.

**Grain Stocks** The Grain Stocks report is issued quarterly and
contains information about how much of selected commodities are in
storage in the United States, by state. Information in this report is
pertinent to the price level, as well as the calendar spread between two
futures maturities. When stocks are tight, naturally the price of the
commodity will be high. Also, prices futures contracts soon to expire
should exceed those with longer dated maturities for two reasons. 1) Low
prices for distant futures contracts reflects the tendency for high
prices to ration demand and for future harvests to resolve shortages. 2)
Low prices for distant futures contracts should disincentivize storage
and bring stocks onto the market to relieve current shortages. Thus,
this report is important both for price level and spread analysis.

**World Agricultural Supply and Demand Estimates (WASDE)** The WASDE
report is released monthly and provides the USDA's forecasts for U.S.
and world supply and use balence sheets for grains, soybeans and its
products, and cotton. It contains supply and use forecasts for U.S.
sugar and livestock commodities. These reports are among the most
important and eagerly anticipated by market participants. The report is
currently released at 12pm EST and release of the report commonly
results in limit price moves in futures markets. It is among the most
involved to prepare. To quote the USDA's own documentation:

> #### How the WASDE is Prepared - Lock-up Conditions
>
> To assure the highly market-sensitive information is released
> simultaneously to all end-users, and not prematurely to any one, the
> WASDE report is prepared under tight security in a specially designed
> area of USDA’s South Building. The morning of release, doors in the
> “lockup” area are secured, window shades are sealed, and telephone and
> Internet communications are blocked. Once analysts present their
> credentials to a guard, they enter the secured area to finalize the
> WASDE report. Communications with the outside world are suspended
> until the report is released at 12:00 noon Eastern time.

Source, [USDA Office of the Cheif
Economist](http://www.usda.gov/oce/commodity/wasde/prepared.htm)

Given the USDA reports' ability to move futures markets, the lock up
condition described in the last paragraph is imperitive. The prospect
that USDA reports could be leaked is the inpiration behind the final
scene in [Trading Places](https://www.youtube.com/watch?v=1tmI867fAYU),
probably the best and only popular movie made about commodity markets.
In this scene, Eddie Murphey and Dan Ackroid's characters learn that the
rich antagonists obtained advance access to the 'crop report' (they do
not say which report) pertinent to orange juice futures contianing
information that would make the price go down. Eddie Murphey and Dan
Ackroid intercept the information and feed the rich antagonists a false
report with bogus information that would cause the futures price to
rise. Before the report is released the rich antagonists buy A LOT of
orange juice futures contracts, driving the price up. Then Eddie Murphey
and Dan Ackroid start selling when the price is high. When the 'crop
report' comes out the price crashes. The rich guys loose a ton of money
and Eddie Murphey and Dan Ackroid become wealthy and retire wealthy to a
tropical paradise.

**Crop Production** The Crop Production report includes estimates of
yeild, acres harvested, and total production for covered commodities.
This report is released in tandem with the WASDE report.

USDA Data Sources
-----------------

All of the information contained in the reports described above are
useful for in depth analysis over a long time horizon. As a service the
USDA maintains databases of information contained in historical reports
that are easy to query for analysis. Three important agencies
maintaining databases within the USDA are the [National Agricultural
Statistics Service](http://www.nass.usda.gov/) (NASS), the [Foreign
Agricultural Service](http://apps.fas.usda.gov/psdonline/psdHome.aspx)
(FAS), and the [Economics Research
Service](http://www.ers.usda.gov/data-products.aspx) (ERS). Each service
mentioned here hosts a wide variety of data and analyses, so concise
descriptions are difficult. However some of the data products commonly
used for commodity price analysis are ACRES PLANTED, PRODUCTION, YIELD,
and PRICE RECIEVED by NASS; the PRODUCTION SUPPLY AND DISTRIBUTION
report from FAS (much of the WASDE report is archived here); and COST
and RETURNS from ERS.

<table>
<caption>Table 3. Summary of USDA Reports and Data Sources.</caption>
<thead>
<tr class="header">
<th align="left">Report</th>
<th align="left">Link</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">Prospective Plantings</td>
<td align="left"><a href="http://usda.mannlib.cornell.edu/MannUsda/viewDocumentInfo.do?documentID=1136" class="uri">http://usda.mannlib.cornell.edu/MannUsda/viewDocumentInfo.do?documentID=1136</a></td>
</tr>
<tr class="even">
<td align="left">Acreage</td>
<td align="left"><a href="http://usda.mannlib.cornell.edu/MannUsda/viewDocumentInfo.do?documentID=1000" class="uri">http://usda.mannlib.cornell.edu/MannUsda/viewDocumentInfo.do?documentID=1000</a></td>
</tr>
<tr class="odd">
<td align="left">WASDE</td>
<td align="left"><a href="http://usda.mannlib.cornell.edu/MannUsda/viewDocumentInfo.do?documentID=1194" class="uri">http://usda.mannlib.cornell.edu/MannUsda/viewDocumentInfo.do?documentID=1194</a></td>
</tr>
<tr class="even">
<td align="left">Crop Production</td>
<td align="left"><a href="http://usda.mannlib.cornell.edu/MannUsda/viewDocumentInfo.do?documentID=1046" class="uri">http://usda.mannlib.cornell.edu/MannUsda/viewDocumentInfo.do?documentID=1046</a></td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr class="header">
<th align="left">Data Source</th>
<th align="left">Link</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">NASS</td>
<td align="left"><a href="http://www.nass.usda.gov/" class="uri">http://www.nass.usda.gov/</a></td>
</tr>
<tr class="even">
<td align="left">FAS</td>
<td align="left"><a href="http://www.fas.usda.gov/data" class="uri">http://www.fas.usda.gov/data</a></td>
</tr>
<tr class="odd">
<td align="left">ERS</td>
<td align="left"><a href="http://www.ers.usda.gov/data-products.aspx" class="uri">http://www.ers.usda.gov/data-products.aspx</a></td>
</tr>
</tbody>
</table>

Conclusion
==========

This concludes chapter 2. We learned resources for accessing commodity
market data, USDA reports, and daily market commentary. Aimed with these
resources one can begin to follow the ups and downs of commdodity prices
and get a feel for how fundamental supply and demand factors cause
fluctuations in prices. In the next section we will cover fundamental
analysis in detail. Fundamental analysis is driven by building balence
sheets for components of supply and demand. Using the balence sheet
approach, the analyst attempts to forecast the price that will cause
quantities supplied and quantities demanded to be equal. This market
equilibrium, if the fundamental model is correctly specified, should be
a reasonable forecast of price.

© Mindy L. Mallory 2015

References
==========

Hull, J. 1991. *Introduction to futures and options markets*. Englewood
Cliffs, NJ: Prentice Hall.

Kub, E. 2012. *Mastering the grain markets: How profits are really
made*. CreateSpace Independent Publishing Platform.
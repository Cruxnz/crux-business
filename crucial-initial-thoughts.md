# Crucial

In this day and age, the internet is _crucial_ to our society. We are online more than ever, and lack of internet access is considered an indicator of poverty ([source](http://www.stuff.co.nz/business/96482475/Internet-access-a-stepping-stone-out-of-poverty)).

The Stuff article I just linked is even more relevant given that Stuff, a news website, has recently decided to become a broadband provider, offering services that undercut existing ISPs by a reasonable margin (they offer a 3 month contract at $49).

I tried looking up reviews of Stuff's service, naturally ignoring Stuff articles as they would probably be somewhat biased.

The New Zealand Herald posted a piece about Stuff being criticised by the Commerce Commission around its claims of "the fastest fibre available".

"The internet speed claim is a matter of scientific fact that consumers would expect to be known and verified," commissioner Anna Rawlings said.

Interesting. Internet speed is a matter of scientific fact? If so, how does Stuff verify its 100MBPS speed for its customers?

Here's a hypothesis. Stuff gets its speed directly from its wholesale provider of broadband, which is _likely_ Chorus (or one of the other fibre providers that got a share of CFH).

## Speed

Why does speed matter? Some would argue that a 100MPBS speed is _good enough_, and anything more than this is just greedy. Who typically wants better internet speeds? One common consumer is the online gamer.

MyRepublic, an ISP that originated in Singapore but now also operates in NZ, has cleverly realised this and offered a special "gamer" plan to consumers for an addition $10. There is a slight flaw in their model, though - the product is basically identical to their "fibre pro" package, and is identical in terms of up/down speed.

Who would want the "fibre pro" package? Well, first of all gamers who aren't stupid enough to be swindled out of an extra $10 per month. Secondly, basically anyone who values their time. In a massive amount of jobs today there is online work, and online work means downloads/uploads. Depending on the nature of the job, a better internet connection can save seconds or even minutes per day. This can add up to massive time saves in the long term, freeing up resources for leisure/more productivity, and ultimately increasing the wellbeing of a society.

## Money

What does Chorus charge for its wholesale fibre plans? According to [this](https://company.chorus.co.nz/chorus-launches-gigabit-wholesale-broadband-services-nationwide) Chorus offers wholesale gigabit broadband at $60 per month, increasing to $65 and then $75 once it officially launches.

This provides decent markup opportunity for an ISP, as ISPs at the moment retail for the consumer at around $105 per month. The exception is in Dunedin, where fibre retails at $75 (a special case as they won the "gigatown" competition that Chorus set up). It is not exactly clear what markup is available to ISPs from Dunedin customers.

However, I believe that there is a massive opportunity here, to retail gigabit fibre at a much lower price. From [this](https://www.nbr.co.nz/opinion/chorus-triples-speed-cheapest-ufb-fibre-plans-adds-200mbits-residential-service) article, 100MBPS fibre broadband has been available at a wholesale price of $40 per month, increasing each year.

Where is the opportunity? Both 100MBPS and 1GBPS connections are throttled versions of fibre. If any ISP claims not to throttle connection speeds, chances are they are either being disingenious or passing the buck onto Chorus, who handle the throttling via the ONT at each end of the cable.

In fact, much faster speeds are possible. [Here](https://blog.chorus.co.nz/we-have-1-gig-broadband-whats-next/) Chorus explains that they are doing research to allow 10GPBS connections, which again requires no change in the fibre cabling infrastructure but rather the processors (ONTs) at either end of each connection.

Stuff has the right idea, offering bargain contracts to consumers that undercut current ISPs, but they still offer a throttled version of fibre that does not provide the best customer experience.

What's a business model that could work in today's business climate? Simply offer a fibre pro package at $80 dollars a month and get 100,000 customers on board. The big assumption, of course, is that consumers will want to pay a lower price for fibre pro (this is how the large number of 100,000 customers is obtained). Now, the ISP is making enough revenue to cover costs - which would be marketing (less needed in this model as only 1 plan is being offered, and prices speak for themselves to an extent), a call center and development of a web frontend that would link up with the Chorus portal.

| Object        | Cost           | Number  | Party |
| ------------- |:-------------:| -----:| -----: |
|   Fibre pro (1GPBS)    | $80 per month | 100,000 | Crucial |
| Wholesale fibre | $60 per month | 100,000 | Chorus |
|                 |            |    Revenue: | $2 million per month |

Remember, this is (on average) $25 dollars cheaper per month than the average ISP fibre pro price, so the 100,000 connection market share is entirely plausible.

However, there could even be something better than this simplistic approach.

## Fibre Facts

Although the Ultra-Fast Broadband initiative has the best intentions, consumers are either not fully aware of the potential for much faster internet or do not want it. Given the asymmetrical nature of information within the telecommunications industry, the former seems more likely. Fibre is available to nearly 1.2M households and businesses, but only 397,000 have connected ([source](http://archive.stats.govt.nz/browse_for_stats/industry_sectors/information_technology_and_communications/InternetServiceProviderSurvey_MR2017.aspx), year ended June 2017 so numbers will have increased somewhat).

A big reason for this is because consumers must go through their ISPs before Chorus will install the fibre connection to their home, and there are often delays such as consent issues before the full connection is made.

Fibre uptake is rapidly increasing - [stats here](http://archive.stats.govt.nz/browse_for_stats/industry_sectors/information_technology_and_communications/ISPSurvey_HOTP2016/Commentary.aspx#fibre) show that fibre connections more than doubled from 2015 to 2016 (but still made up only 12 percent of broadband connections).

$1.5 billion dollars were invested as part of the initiative, and Crown Fibre Holdings Limited manages the project. The issue is that CFH's main incentive isn't really consumers using fibre, but rather consumer access to fibre. Their [annual report](https://www.crowninfrastructure.govt.nz/wp-content/uploads/2011/10/2017-Annual-report.pdf) gives a slight discrepancy from the government number of 397,000 fibre connections (it states 413,047). Also, it states that only 12,288 gigabit connections have been made, which is less than 3% of total fibre connections. The financials of the report are complicated to follow (the norm for financial reporting) but seem to involve purchasing a lot of Chorus stock. This allows them to get ROI and cover the costs, so that the money isn't being thrown away. It's a sound business decision.

[The wiki](https://en.wikipedia.org/wiki/Ultra-Fast_Broadband) for the initiative states that the government expects that the project will cost $600M in "opportunity cost" (this is a quote from former communications minister Steven Joyce). It's hard to know exactly what this means, but it makes sense that the initiative will recover money as it will make gains via the stock market, barring a crash.

## Goal

The goal is for both Chorus and Crucial to work together and create lower cost broadband at the maximum speed possible given the infrastructure, increasing consumer fibre connections. It sounds simple, but there are 2 key questions:

1. What is the difference in cost between an ONT capable of handling a 100MPBS connection and an ONT capable of handling a 1GPBS connection?

2. What are the theoretical numbers on Chorus' infrastructure being able to handle large amounts of gigabit connections, to reduce the risk of network congestion as consumer use of bandwidth increases due to the increased caps?

Information relevant to question 1 is here - https://www.crowninfrastructure.govt.nz/media/19366/chorus%20published%20ufb%20price%20book%20summary%20(15%20july%202011).pdf.

The price difference seems to be relatively small. A "P2P access product" that allows 1GPBS up/down is $75 more expensive than one that allows 100MBPS up/down ($380 vs $455). I'm assuming that the P2P access product is what is used for 1GPBS connections, however there may be additional costs (eg. the E-NNI 2/3 ports, costing $100 for 1GPBS).

I do not have enough information to answer question 2 effectively. This is where I ask Chorus for transparent data on their network usage and capabilities.

However, there are many elements to consider with question 2. By giving someone a 1GPBS connection over a 100MBPS connection, do we assume that their internet usage will increase? If so, by how much? It's hard to predict what effect this would actually have on a network. More data is needed.

Here is the "ideal scenario" - Crucial offers flexible plans to consumers (no contracts) at a much lower cost than current ADSL,VDSL or even fibre plans with existing ISPs. $42 per month is the price, as this number is apparently the meaning of life. This price is subsidised by Chorus/maybe other CFH fibre providers, and in turn CFH.

Crucial immediately obtains massive consumer market share. Remember, the goal here is _not_ to make money (a foreign concept, I know). This initiative was government funded, and returns on capital should be secondary to the intended purpose.

The goal is to get as many consumers as possible onto a gigabit connection. I believe that a consumer cost of $42 per month is entirely possible given the current capital available to CFH and Chorus. By offering this cost, consumption of gigabit services increases exponentially. Customers who were on a copper connection will have massive incentive to switch to fibre.

In the long term, I do not expect Crucial to retain its role in the market. Healthy competition is a key part to the system, and smart ISPs will realise that they can lower their costs and improve services to consumers. This is the corollary to an increase in fibre connections for consumers.

To a traditional business-minded individual, I understand that this approach could sound like insanity - economic suicide. I encourage the reader to keep an open mind and try to see the bigger picture. There is more at stake than just money here. Ask yourself the question: does better internet for everyone lead to a healthier society overall?

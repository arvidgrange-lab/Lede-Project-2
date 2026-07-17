# Lede Project 2  -   Arvid Grange  - Polymarket's court of public opinion and the murder of Charlie Kirk

## Project purpose - Exploring the world view of those betting on the Charlie Kirk murder case by mapping their bets
The project aims to map the fringes of increasingly mainstream prediction market Polymarket, by analysing a market for betting on the guilt or innocence of Charlie Kirk's accused killer Tyler Robinson.

        Analysing that particular market allowed for a deeper understanding of current mass consciousness, since the market, to a degree, represents public opinion.

        By analysing what other markets these people bet on we can create a cross section of the world view of the ones engaging in this market.

        At first, the idea was to also compare this with a similar market that has been resolved: "Diddy found guilty of sex trafficking?"
        For that reason some of the files are named things like "tyler_diddy_markets" etc. However, I decided to scrap the comparison since I felt it made the story more confusing.

## Findings
The market of betting on Tyler Robinson's guilt or innocence is heavily concentrated in the hands of very few traders.
While the side betting on his innocence is projected to win the market, the traders betting on his guilt are historically more successful Polymarket traders, averaging 53 percent more profits than the no-side.

        Through AI-categorizing of the top traders' other bets I found that the most popular other markets to bet on are elections, general U.S politics, the Iran war and sports.

## Data collection process
The data was collected using the public polymarket data and gamma APIs
Through the gamma API I got data on the market and through the data API I got data on the individual traders.
I collected data on July 6th and again a week later, allowing a volume comparison over time.


## Data analysis
I analysed the distribution of the market among the traders.
Then I analysed the rate of Yes/No bettors as well as the average all-time profits of the top bettors, as well as their most popular markets to bet on in terms of both bet volume and the rate of individual traders betting on a particular market.

Furthermore, I extracted the most recent 1000 trades by the top 100 traders on the Tyler Robinson homicide case market. Not all of those traders had made 1000 trades in their polymarket careers, so the number of trades per trader varied.

Narrowing that down to only purchases of shares created a dataset of roughly 40 000 trades. I analyzed these trades using a claude LLM, which I trained on a sample data set to reach an accuracy rate of 95 %, categorizing each trade based on the topic. I had API errors on 7000 trades and a time shortage on top of that, which led me to end up categorizing around 27 000 trades successfully. However I consider this a successful analysis regardless, accurately representing reality

Using this data I could map the most common topics to bet on, scaled both in terms of bet volume and cash volume.


## New skills and approaches
Understanding Polymarket documentation was challenging and this project increased my literacy in that regard. My pandas and python skills were improved through analysis.


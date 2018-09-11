---
title:  "Lessons Learned From Building a Cryptocurrency Mine During the Biggest Boom/Bust to Date"
categories:
 - blockchain
author: Geoff Sullivan
excerpt: "For those who have been following the Crypto Noob Mining Club's
journey to production, we're finally here! The miners are up and running and
we've just completed our testing phase. Here's what we've learned"
header:
  image: #"posts/coalmine.gif"

---

For those who have been following the Crypto Noob Mining Club's journey to
production, we're finally here! The miners are up and running and we've just
completed our testing phase. During testing, we wanted to ensure that our
miners are stable and optimized in terms of their energy draw and their
hashing rate, or "mining power." We are now at a point where we are
comfortable with how the operation is running and we will be looking to
on-board our next round of members soon. With that said, we plan to never
stop optimizing, and will continue to make decisions transparently on the
club's behalf to protect and grow the long term profitability of the operation.

**Here is what our club is looking like as of right now:**

- 9 x Moonlander2 ASIC stick miners currently mining Litecoin with an average
hashing rate of 29,833 kH/s.

- 3 x GPU miners currently mining Sumokoin with an average hashing rate of
934H/S.

## Market Struggles and the Impact on the Club

The global market capitalization of cryptocurrencies has taken a $500
billion hit over the last month resulting in a lot of fear uncertainly and
doubt (FUD.) We've been watching the markets closely and have observed some
interesting trends that will impact our club - and we see areas for opportunity.

### Decreases in Short-term Mining Profitability

The recent market downturn saw the price of cryptos decline in relation to
fiat currency like the CAD. The cost inputs of a mining operation (hardware,
electricity, space) are incurred in fiat, whereas the outputs of a mining
operation are in cryptos.

Since the present value of a mining operation's outputs are declining, and
the costs are remaining relatively flat, mining profitability in the
short-term has decreased. As we referenced in our very first [post](https://cryptonoob.club/mining/crypto-crowdmining/),
we are banking on the long term growth and adoption of blockchain assets, so
we see this as an opportunity for the club. As the cryptocurrency markets
gain back strength against fiat currencies, so will our collective outputs.

### Decreased Mining Difficulty

Mining difficulty is a variable that determines how difficult it is, or how
much hashing power is required to discover a new block on the blockchain.
Difficulty fluctuates depending on the amount of miners and the aggregate
hashing power on the network. Recently, as miners powered off their mining
devices, presumably because of the poor performing market, the mining
difficulty on many blockchain networks has decreased significantly. This
creates opportunity for the club to increase the outputs of our mining operation.

For more information about mining difficulty, check out this
[post](https://themerkle.com/what-is-the-mining-difficulty/) by the Merkle.

### GPU Supply Constraints

While the markets were running hot, the global supply of GPUs from
manufacturers like NVIDA and AMD was highly constrained. These manufacturers
put limits on the amount GPUs that individuals could purchase. GPUs were
nearly impossible to source online and in retail locations.

Since the recent market decline, we've seen an increase in supply of GPUs on
secondary markets like eBay. Miners who were scared off from the market
decline are trying to recover their short term loses by liquidating their
GPU assets.

This is advantageous for the club, as we now have line of sight to a new
supply of GPUs. Sourcing miners has been one of the biggest challenges we've
faces since starting the club, so we are excited about this opportunity.

## Lessons Learned (so far)

We've learned a few hard lessons from our initial setup that we will take
into consideration when making future decisions.

### Moonlanders are out

When we first heard about them, the Moolanders seemed like an ideal miner
to start with. They were ASICs designed to mine Litecoin - which we loved
(and still do,) and they were ultra efficient.

Since then, the price of Litecoin increased from around $70 CAD up to over
$400 CAD, then back down to around $150 CAD where it sits today. This has
had a tremendous impact on the mining difficulty of Litecoin and our
profitability as a result.

Moving forward we will not be investing in anymore Moonlanders for the
following reasons:

1. **Limited mining options** - Because they are ASIC-based, meaning their
   chip was specifically designed for a specific use case, the Moonlanders
   are limited in which coins they can mine. Since we want the ability to
   change what we are mining on a whim based on the market, the Moonlanders
   will not be a viable option for us moving forward. We will look to GPU
   and perhaps CPU based technologies which will give us choice and
   flexibility in the cryptos we mine.
2. **Whimpy Outputs** - The Moonlanders were designed to be super efficient.
   Because of this, they do not produce the same output of larger, less
   efficient miners. This problem has been exacerbated by the increased
   mining difficulty of Litecoin. For individuals looking to mine for
   themselves or as a hobby, this output may be suitable, but for a mining
   club like ours, we require more juice!

### Agility is Everything

It has been fascinating to watch how fluctuations in the crypto market have
impacted adjacent markets like the constraints it has put on the GPU market.
One thing that this unpredictability has taught us is that
**<u>agility is everything</u>**. Losses can be mitigated and gains
amplified if you have the ability to make decisions and take action quickly.

We've identified three major areas where agility will be critical for the
long term success of the club:

- **Purchasing power** - We need to ensure that the club has enough capital,
  in the right currency (crypto or fiat) to buy more resources when they become available.
- **Deployment speed** - We need to be able to deploy new resources quickly
  in an automated way.
- **Coin switching** - We need the ability to change which coins we are
  mining on-demand in real time based on market behavior. Ideally this is
  something we can automate over time.

## Next Steps

To address these lessons learned, we've prioritized our roadmap and strategy
accordingly. In the coming months we will tackle the aforementioned
challenges two ways.

### Automate All Things

Luckily, our team has been in the cloud computing business for a very long
time. Operating clouds and operating crypto mines share a lot of the same
challenges - hardware, software and lots of processes that need to be
automated to ensure performance, scale and security.

We have some neat ideas of how to apply our expertise to address our agility
challenges.

### Journey to an Off-Grid Architecture

Since cryptocurrency price is a variable that we cannot control, the best
way to increase short term mining profitability is to reduce our costs. As
of right now, all of the club's miners are taking power from the grid. We
are in the early stages of implementing a phased approach to going 100%
off-grid, therefore reducing the clubs operating costs.

Phase 1 will be connecting the miners to a bank of lithium ion batteries
that will power the miners during the day when energy from the grid is more
expensive, and charge during the evenings when power is cheaper.

For more information on our journey to an off-grid architecture check out
our post on [Blockchain’s Energy Problem and the Need for Renewable Processing Power](https://cryptonoob.club/mining/energy-manifesto/).

### Join the Club

In the coming weeks we will be reaching out to folks on our waiting list to
on-board them into the club. If you are interested in joining, learn how to
join [here](https://cryptonoob.club/docs/mining-club/how-to-join), and we'll
be in touch soon.

Series 57 Key Concepts
Version: 2022 V
CONFIDENTIAL

# Series 57 Key Concepts

This document highlights the most important and heavily tested concepts on the

Series 57 exam. Please review them multiple times before your actual test. They

are not intended as a substitute for the textbook, video lectures, or practice

examinations but instead will help you focus your study efforts as the exam

approaches.

# Contents

Chapter 1: The Nasdaq Stock Market ............................................................................................... 2

Chapter 2: Over-the-Counter (OTC) Equities .................................................................................. 5

Chapter 3: Trading Rules........................................................................................................................ 5

Chapter 4: Handling Customer Orders ............................................................................................ 10

Chapter 5: Trade Reporting ................................................................................................................ 15

Chapter 6: New-Issue Market ............................................................................................................. 16

Chapter 7: Equity Markets Securities Regulations ........................................................................ 19

Chapter 8: Options Contracts and Strategies ............................................................................... 21


Series 57 Key Concepts

Chapter 1: The Nasdaq Stock Market

1. Broker-dealers are required to be members of SIPC, which protects
    customer accounts if a broker-dealer is insolvent.
2. For firms registered as a market maker, the required minimum net capital is
    a function of the number of stocks the firm is quoting, subject to a minimum
    net capital of $100,000, regardless of the number of stocks be quoted. For
    stocks with a bid price of $5 or less, the market maker must have a net
    capital of $1,000 per security, and for stocks with a bid price of more than
    $5, a market maker must have a minimum net capital of $2,500 per security.
3. “Bona fide” means real or actual. Bona fide quotes (aka firm quotes) are
    quotes that a market maker must be able and willing to execute. Failing to
    do so is considered backing away. Complaints regarding backing away
    should be filed with regulators within five minutes. However, a failure to do
    so does not forgive the offending firm from liability.
4. The displayed size for a quote is in round lots of 100 shares. A customer’s
    order for a mixed lot (e.g., 378 shares) would be entered into the system
    and displayed as three round lots (300 shares), although all the shares (378)
    would be available for execution.
5. When a firm becomes a market maker in an additional name, it is typically
    effective on the same business day. The market maker must begin quoting
    the security by the open of trading five business days later.
6. A firm’s primary MPID must be used for market maker quotes, passive
    market making and stabilization.
7. A market maker's quotation obligation requires it be prepared to trade at
    least one normal unit of trading, which is defined as 100 shares.
       a. Example: A market maker displays a quote of 32.10 x 32.15. The
          assumption is that the bid and offer are available for 100 shares. A
          customer seeking to buy 300 shares at 32.15 could expect
          execution of 100 shares at 32.15 from this market maker.
8. For listed stocks, quotes of four decimals are only permitted for stocks
    trading for less than $1.00.
9. Orders are first executed based on price priority. For example, a customer
    limit order to buy at $15 and entered at 11:00am would have priority over
    another customer limit order to buy at $14.99 that was entered at 10:55am.
10. Any potential price improvement goes to the taker of liquidity, which is the
    party that crosses the spread to execute an order against an existing
    quote. For example, if the current best bid on a stock is $30.25 on 1,
    shares and a customer enter an order to sell 500 shares at $30.23, the order
    will be executed at $30.25. In this situation, the seller is the taker of liquidity


Series 57 Key Concepts

```
and receive a price improvement of $.02 as their order to sell at $30.23 is
marketable because an investor is willing to pay up to $30.25.
```
11. New quotes entered by a market maker must be within a designated
    percentage (typically 8%) of the NBBO. Once the quote is entered, it must
    remain within defined limit of the NBBO (typically 9.5%). Importantly, the
    designated percentage rule applies to new quotes, while the defined limit
    rule applies to existing quotes.
12. Under the Nasdaq designated percentage rule, market makers can
    maintain quotes further from the inside market before 9:45 am and after
    3:35 pm.
13. A market maker can seek an excused withdrawal for up to 60 days for legal
    or regulatory reasons such as an involuntary termination of a clearing
    agreement.
14. A Nasdaq MM who voluntarily withdraws its quotes cannot re-register in that
    name for 20 business days.
15. Firms may not submit locking or crossing quotes— instead, such quotes
    should be treated as marketable and executed.
       a. For example, the NBBO is 9.50 × 9.55. If a customer places a sell limit
          at 9.49, the firm should treat the order as a market order and
          execute against the 9.50 best bid.
16. A market maker is permitted to enter a quote that would lock the market if
    the exchange showing the locked quote is experiencing a system
    malfunction.
17. During a trading halt, a market order that is received should be held by the
    broker-dealer until trading resumes with a halt cross process.
18. During a trading halt, no trades can be executed (i.e., a market maker
    cannot match buys and sells). There is NOT any exception for block trades.
19. The ADF does not route orders; instead, market participants using the ADF
    must execute using their own private connectivity systems (e.g., an ATS).
       a. The ADF does handle trade reports, including accepting or declining
          trade reports.
20. Make sure to review Nasdaq’s opening and closing cross process.

```
a. Nasdaq disseminates the opening cross order imbalance information
every second between 9:28 and 9:30 am ET.
b. The Nasdaq closing process begins at 3:55 pm ET.
i. Nasdaq disseminates the closing cross order imbalance
information every second between 3:55 and 4:00 pm ET.
```

Series 57 Key Concepts

```
ii. Market-on-close (MOC), limit-on-close (LOC), and imbalance
only (IO) orders can be entered, modified, or cancelled until 3:
pm ET.
iii. At 3:55 pm ET, MOC orders are no longer accepted. LOC orders
can be entered until 3:58 pm ET but can no longer be cancelled
or modified.
iv. At 3:58 pm ET, LOC orders are no longer accepted. IO orders
may still be submitted, though no longer modified or cancelled,
until the close.
```
21. Summary of the types of crossing orders and an example of each.

```
a. If a market maker wants to buy shares at the opening price and
ensure that it receives a particular price or better, the MM should
enter a limit-on-open (LOO) order.
```
```
Example: Buy LOO $28.00 means that if the market opens at $28.
or less, the order will be filled. If the market opens above $28.00, the
order will not be filled.
b. If a market maker wants to buy shares at the open whatever the
opening price, the MM should enter a market-on-open (MOO)
order.
```
```
Example: A buy MOO order will be executed at the opening price,
whatever that may be ($22.00, $28.00, $34.00, etc.). A MOO
guarantees execution at the open but offers no guarantee as to
price.
c. An imbalance-only (IO) order is a priced order to be executed at
the opening or closing price. An IO order’s price will be adjusted as
the cross occurs, subject to the price instruction.
```
```
Example: If an IO buy order is entered with a price of $21.00, and
the highest bid is $20.95, the IO order is repriced to $20.95. If the
highest bid drops further, to $20.89, the IO order will be repriced
again so it can be executed at the best bid. If, however, the highest
bid moves to $21.15, the IO order will not be repriced above the
$21.00 price instruction and will not execute in the cross.
```
22. Limit-on-close orders (LOC) will always have a size and price. Opening and
    closing cross orders can never be noted as all-or-none (AON).
23. A market maker cannot accept any payments to initiate quotations. If an
    issuer were to offer payment for a market maker to initiate quotes, the firm
    must refuse the payment but could still quote the security.


Series 57 Key Concepts

24. Riskless principal trades are permitted for NMS stocks and OTC equities,
    including penny stocks.
25. Floor brokers, floor market makers, specialists, and designated market
    makers are all associated with exchanges. The term market maker can be
    used in reference to exchanges (e.g., Nasdaq) or OTC securities.
26. Reg NMS covers, among other things, market access (Rule 610), order
    protection (Rule 611), and sub-penny pricing increments (Rule 612).
27. NYSE stocks can be quoted over-the-counter on the Consolidated
    Quotation System (CQS).

Chapter 2: Over-the-Counter (OTC) Equities

1. The OTC Pink is only used for quoting equities. Bonds, including senior
    debentures, are not quoted on the OTC venues.
2. Priced quotes on the OTC Pink sheets may be designated as a non-firm
    quotation (i.e., a subject quote) by the broker-dealer.
3. An exception to the Form 211 filing is available if the quotes represent
    unsolicited customer interest (i.e., customer orders). Once the customer’s
    order is filled, or if the customer withdraws (cancels) its interest, the market
    maker can no longer quote the stock.
4. A market maker that quotes an OTC equity that was subject to a 10-day,
    SEC trading suspension must refile Form 211 to resume quotations.
5. There is no penalty for a quote withdrawal by an OTC market maker as OTC
    equities do not have a continuous, firm-quote requirement.
6. If a stock is delisted from Nasdaq or NYSE, it can immediately be quoted on
    the OTC markets (e.g., OTC Pink).

Chapter 3: Trading Rules

1. The maximum access fee to quote on various systems is $.003.
2. When executing a short sale, it is the introducing (or receiving) broker-
    dealer’s obligation to obtain a locate. The executing and clearing firms
    need not get a locate.
3. For long-term customers selling shares, a broker-dealer may rely on their
    assurances that they are long stock and can make delivery at settlement.


Series 57 Key Concepts

4. An investor owns convertible preferred ABC stock. An order to sell 100
    shares of common ABC stock must be marked short unless the investor has
    tendered the preferred for conversion.
5. A customer who is long 8,000 shares of stock and is also short 30 call options
    is net long 5,000 shares, because each call option is worth 100 shares.
6. An investor selling stock futures is not required to borrow the shares first,
    since delivery is not made immediately.
7. A prime broker performs a suite of services on behalf of hedge funds and
    other large institutional clients. Examples of services include margin,
    settlement, position consolidation, and securities lending. However, prime
    brokers do not assist with anti-money laundering compliance.
8. Prime brokers are must maintain minimum net capital of at least $1.5mm.
9. When a broker-dealer is determining its own net long or short position in a
    security it must aggregate all of its positions in that security unless it qualified
    for independent trading unit aggregation. Independent aggregation allows
    each trading desk (i.e., unit) to determine its own position, if all of the below
    requirements are met:

```
a) The broker-dealer has a written plan to identify each unit.
```
```
b) Each unit determines its own net position for every security.
```
```
c) Traders are assigned to only one unit.
```
```
d) Traders from one unit do not coordinate with trades in another unit.
```
10. The “threshold security list,” a list of securities with significant outstanding
    fails, is prepared and disseminated by the SRO that maintains the primary
    listing for the security.

```
a. FINRA publishes a list of OTC threshold securities.
b. Other SROs such as Nasdaq and NYSE publish their own threshold
security lists.
```
11. If a broker-dealer has executed a transaction in a threshold security but has
    failed to deliver the security and the fail consists for 13 consecutive
    settlement days, the broker-dealer must close out the position on the 14th.
12. For the closing out of short sales, it is important to note not only that the
    close out is required on T+3 (settlement is T+2), but also that it must be done
    at the beginning of the day.


Series 57 Key Concepts

13. Orders tickets may be marked short exempt when a broker-dealer is
    executing a riskless principal trade for a customer provided that the
    customer’s order is in place prior to the offsetting transaction and both legs
    of the trade are executed within 60 seconds of each other. Also, the
    broker-dealer must maintain records that readily reconstruct the trades.
14. A trade being a non-regular way transaction is a reason for marking an
    order ticket short exempt. Note, however, that being a regular way trade is
    not a reason to mark an order ticket short exempt.
15. Key takeaway from the uptick rule: If a stock’s price declines 10% from the
    prior day’s close, no short sales may be executed in that stock for the
    remainder of that day or the next trading day. An exception is available for
    short sales above the national best bid (NBB), which can be executed and
    marked short exempt. The short sale circuit breaker only applies during
    normal market hours (9:30 am–4:00 pm).

```
a) Example: XYZ’s price declines 12% on Tuesday. For the remainder of
Tuesday and all-day Wednesday, XYZ may not be sold short unless
the sale occurs at a price higher than the NBB.
```
16. Under Reg SHO, if a stock falls by 10% on Monday and then an additional
    10% on Tuesday, the short sale price restriction will apply to Wednesday’s
    trading day and be lifted at the close of business on Wednesday (unless the
    price also falls by 10% on Wednesday, in which case it would be further
    extended).
17. Under Reg NMS Rule 611 (The Trade-Through Rule) it is prohibited to execute
    trades at prices inferior to protected quotations.
18. An exception from the Order Protection Rule means an order can be
    executed at a price that is inferior to, or not executed against (i.e., traded-
    through), a better price on another exchange. Exceptions from the Order
    Protection Rule include the second leg of a riskless principal trade, qualified
    contingent trades, crossed market trades, self-help (described below), and
    ISO orders.
19. A broker-dealer or an exchange raises a “self-help” alert when another
    broker-dealer or exchange is experiencing a technical problem and should
    be bypassed when routing orders.

```
a) For example, Broker-Dealer X could raise a self-help against Broker-
Dealer Z when Broker-Dealer Z is having a technical problem.
Broker-Dealer X would then route orders elsewhere. Self-help is also
```

Series 57 Key Concepts

```
usually claimed if a market center does not respond to orders within
one second.
```
```
b) Once the “self-help” flag is raised, a BD or exchange can trade
through the protected quotes on the exchange experiencing
difficulties and would not violate the trade through rules.
```
```
c) When a market maker claims self-help, it must notify the market
center with the issue that its quotes will not be protected.
```
20. The exam may reference a benchmark trade. It is not an exception to the
    trade-through rule. A benchmark trade is an order executed at a price that
    is not based on the then-current quoted price—benchmark trades are very
    specific types of orders only permitted in connection with a pilot program
    on small-cap stocks (Rule 608 of Reg NMS). This type of trade should be
    selected as an answer only if all these characteristics are indicated. In all
    other cases, benchmark trade will not be the correct answer.
21. If a Level 3 Market Decline (20%) occurs at any time during the trading day,
    FINRA shall halt trading for the remainder of the trading day. Trading will
    resume at the open the next market day.
22. If a Level 3 trading halt stopped trading for the rest of the day all MOC
    orders are cancelled. The Official Closing Price is the last trade executed
    before the halt.
23. To calculate the Level 3 (20% decline) trading halt against the prior day’s
    close, if only given today’s opening price which is 10% down from
    yesterday’s close, do the following:

```
a) Assume today’s opening price is $1,800.
b) Calculate yesterday’s close (divide by .9)
i. $1,800 / (1 – 10%)
ii. $1,800/(0.90) = $2,
c) Calculate a 20% decline (multiply by .8)
i. $2,000 x (1- 20%) =
ii. $2,000 x (0.80) = $1,
d) If the market drops to $1,600 (a 20% decline against yesterday’s
$2,000 close) it will trigger a Level 3 trading halt for the rest of the
day.
```
24. The SEC can halt all trading on any exchange for 90 calendar days with
    notice to the President of the United States.


Series 57 Key Concepts

25. FINRA can halt OTC trading for an extraordinary event for up to 10 business
    days. After 10 days FINRA must confirm that the extraordinary event is
    ongoing in order to extend the halt.
26. SEC Market Access rules (15c3-5) require firms have risk management
    controls and supervisory procedures that prevent market access customers
    from entering orders that exceed appropriate pre-set credit or capital
    thresholds.
27. During normal market hours, any trade in an NMS stock with a price greater
    than $50 outside a 3% band from the reference price will be deemed
    clearly erroneous.
28. A member must submit a written complaint about a clearly erroneous trade
    within 30 minutes of the execution time.
29. OTC transactions (third market) that are clearly erroneous are addressed by
    FINRA's Market Regulation Department, not NASDAQ. If clearly erroneous,
    FINRA may declare a trade null and void.
30. FINRA anti-money laundering rules require that the person designated as
    the AML compliance person must be an associated person of the broker-
    dealer. It cannot be delegated to another firm.
31. Financial risk management controls prevent the entry of erroneous orders,
    such as duplicative orders or orders that exceed appropriate price or size
    parameters. These are distinct from a firm’s regulatory risk management
    (which deals with regulation compliance) and credit risk management
    (which deals with the extension of credit).
32. Risk management controls cannot be designated or delegated to a third-
    party or outside vendor.
33. A firm’s CEO must certify the effectiveness of a firm’s controls.
34. Firms should have pre-trade controls (a type of risk management control) in
    place to prevent “fat finger” errors – e.g., entering extra zeroes or duplicate
    orders. Pre-trade controls will screen orders prior to entry to prevent
    duplicates, unusual dollar amounts and size, and a price too far from the
    current market price.
35. A firm using automated trading systems must also use automated pre-trade
    controls.
36. A firm must take into account its trades during the day to determine if it is
    long or short in a security. For example, BD A begins the day long 2,


Series 57 Key Concepts

```
shares of ABC Corp. During the day it enters three orders: Sell 1,500, Buy
1,500, Sell 500. Based off the three trades it is still long 1,500 shares at the
end of the day because the two trades in the middle netted out to zero.
```
37. The purpose of limit up/limit down (LULD) is to prevent extraordinary volatility
    in National Market System (NMS) stocks.
38. For Limit-Up Limit-Down, price limits are 5% for S&P 500 and Russell 1,
    stocks and 10% for all other NMS stocks.
39. Under limit-up limit-down, a security is in a straddle state if the bid and offer
    are on either side of the price band. For example, a quote of 103-105 with
    an upper price band of 104 would be a straddle state. Under a straddle
    state, the exchange will monitor conditions and implement a pause for
    anything abnormal. Note that in this example 104-105 would be a limit state
    and there would be an automatic pause if the limit state persists for 15
    seconds.
40. If a security enters a limit up-limit down (LULD) trading halt within the last 5
    minutes of the trading day, the next opportunity to trade that security
    would be the closing cross. The closing cross will end the pause and set the
    closing price for the security.
41. What happens in a 15-second limit state?

```
a. No new reference prices or price bands are calculated.
b. Trading continues within the price bands.
c. The stock can exit a limit state when the entire size of all limit state
quotes is cancelled or executed during the 15 seconds.
d. If the quote remains at or outside the band for 15 seconds, a five-
minute pause is triggered by the primary listing exchange.
```
Chapter 4: Handling Customer Orders

1. Market orders are executed immediately upon receipt. Limit orders are
    executed only when the specified limit price is available and then in
    price/time priority. Marketable limit orders are limit orders than can be filled
    immediately given the current market price. For example, a buy limit at
    $10.50 when the best offer is $10.40 is marketable.
2. A client choosing to “hit the bid” is saying they want to place a market
    order to sell. Conversely, “lifting the offer” is a market order to buy


Series 57 Key Concepts

3. If an investor places a limit order that specifies that they want a certain
    price, including the commission, the broker-dealer most protect the order
    at a better price of its choosing so that the all-in price to the customer does
    not exceed the customer’s specifications. For example, if a customer says,
    “I want to pay no more than $30, including the commission,” the broker-
    dealer might choose to protect the order at $29, thereby allowing room for
    a $1 commission. This must be clearly explained to the customer.
4. Buy limit and sell stop orders are entered at or below the current market
    price. Sell limit and buy stop orders are entered at or above the current
    market price.
5. For cash dividends, orders entered at or below the market are reduced on
    the ex-dividend date – this includes buy limit and sell stop orders.
6. Dividends for fractional cents are rounded up to adjust orders. For example,
    a dividend for 37.25 cents would be treated as a 38-cent dividend and
    orders would be adjusted downward by 38 cents.
7. Nasdaq system hours are 4am – 8pm.
8. Customers wishing to engage in extended hours trading must receive a risk
    disclosure document which highlights the following after-hours trading risk
    factors: lack of liquidity, high volatility, unlinked markets, effect of news and
    wider spreads.
9. In a stock split both the number of shares and the share price are adjusted.

```
a. Example: A 3:2 split (you own 100 shares at $24)
```
```
The number of shares is multiple by 3, then divided by 2 (the new
share count is 100 x 3 / 2 = 150 shares)
```
```
The share price is multiplied by 2, then divided by 3 (the new price is
$24 x 2 / 3 = $16)
```
10. A marking-the-close violation occurs if trades are placed with the intent to
    artificially affect the closing price.
11. Collusion is a manipulative and prohibited practice where traders
    coordinate prices or the bid–ask spread. This goes well beyond negotiating
    trade prices (which is allowed).
12. Layering is a form of market manipulation where investors enter limit orders
    with the intended effect of moving the market to obtain a beneficial
    execution on the other side of the market.


Series 57 Key Concepts

13. Interpositioning is the prohibited practice of introducing additional parties
    to a securities transaction to generate additional commissions. If the
    introduction of the additional party results in a superior price (not equal, but
    better) then it is allowed.
14. Traders who act together to manipulate prices, often by creating an
    artificial appearance of supply or demand, are said to be “painting the
    tape” or participating in a stock pool.
15. Painting the tape can inflate trading volume, manipulate the stock price, or
    both.
16. Self-trades are transactions where both sides originate with the same firm.
    Broker-dealers must have procedures in place to review and prevent a
    pattern of self-trades. Assuming procedures are in place, a self-trade is not
    a violation if it was unintentional. For example, if the trade occurred
    between legitimately distinct trading desks and was not done merely to
    create the illusion of activity in a security, it would not be a violation.
17. Quote stuffing is a prohibited practice where algorithmic traders enter and
    then quickly withdraw large orders for the purpose of creating confusion in
    the market and taking advantage of trading opportunities.
18. A trader is allowed to split an order for a valid reason, such as faster
    execution, but trade shredding to generate additional commissions is
    prohibited.
19. Spoofing refers to entering orders to entice other participants to join on the
    same side of the market at a price at which they would not ordinarily trade,
    and then trading against the other market participants' orders.
20. Front running block transactions (generally a transaction involving 10,
    shares or more) is prohibited. The rule has several exceptions, including:

```
a. No-knowledge of the block pending block trade (i.e., information
barriers),
b. Transactions to fill prior customer orders,
c. Transactions to correct bona fide errors,
d. Transactions to offset odd-lot orders, or
e. Transactions in compliance with the marketplace rules of a national
securities exchange
```
21. It is a front running violation to trade based on advance knowledge of an
    imminent block transaction. Even if part of the block has already been


Series 57 Key Concepts

```
executed, the entire order must be filled and publicly reported to avoid
triggering a violation.
```
22. Tweeting newsworthy information as a means of public dissemination
    is not a violation as long as the information is accurate. However, if a CEO
    tweets newsworthy information about a company that is not factually
    accurate and which causes the stock to rise, this would be considered
    manipulative and deceptive.
23. Investors may face wide spreads (a large difference between the bid and
    the ask) if they 1) trade outside of normal market hours or 2) trade penny
    stocks.
24. An order ticket must specifically note whether an order was entered as a
    discretionary or an unsolicited order. It is a violation to inappropriately mark
    a solicited trade as unsolicited or discretionary.
25. The order ticket must include the time of execution, whereas the trade
    confirmation may, but is not required to.
26. Order receipt time is not required on a trade confirmation.
27. Trade confirmations must indicate whether the broker-dealer received
    payment for order flow for the transaction. The specific source and nature
    of the payment for order flow are furnished only upon the customer’s
    written request.
28. CUSIP numbers are found on a trade confirmation, but not on the order
    ticket.
29. The trade confirmation will include if the trade was executed as principal or
    agent.
30. The time of entry is defined as the time when the firm transmits the order or
    instruction for execution.
31. There are three types of pegged orders: primary peg, market peg, and
    midpoint peg. Any order with a limit price is not necessarily a pegged order.
    A pegged order is a special type of limit order that automatically adjusts as
    the market moves.
32. If a firm trades for its own account to execute a customer’s order as a
    riskless principal trade, this does not trigger a manning order obligation
    under the limit order protection rule. This is also referred to as executing a
    facilitated order.


Series 57 Key Concepts

33. A customer’s limit order is not required to be displayed under certain
    circumstances. Important exceptions include 1) if the customer requests
    their order not be displayed, 2) the customer’s size represents a de minimis
    change in the market maker’s size (defined as no more than 10% of the
    market maker’s displayed quote size), and 3) odd-lot orders.
34. A market maker is not required to display a customer all-or-none (AON) limit
    order.
35. When determining an equity mark-up or mark-down, a firm would not
    consider its own cost (or basis) in the security; instead, the firm should look
    to the current market price.
36. The 5% policy is different for debt securities. For debt securities, the mark-up
    or mark-down should first reflect the prevailing market price, which is
    established by the firm’s contemporaneous cost or proceeds.
37. The FINRA 5% policy is a guideline, NOT a rule. There are cases where a
    higher than 5% fee may be justified.
38. For NMS stocks trading for $1.00 or more, the minimum price improvement is
    one penny. For example, the smallest price improvement available to a bid
    of $12.30 is one cent, making the bid $12.31. A bid of $12.305 is not
    permissible. The smallest price improvement available for an offer of $12.
    is $12.34 (down one cent); a quote of $12.345 is not permitted.
39. For trade reporting purposes, a riskless principal transaction is treated as
    one trade. For example, if a broker-dealer purchases 50,000 shares of stock
    to fill an existing customer order for 50,000 shares, this would be reported as
    one transaction for 50,000 total shares. It would not be reported as two
    transactions for 100,000 total shares.
40. After a reverse stock split, all open orders are cancelled.
41. Securities, such as stocks and bonds, are typically deposited with a clearing
    house.
42. A firm dually registered as a broker-dealer and investment adviser is more
    likely to fill customer orders in an agency capacity rather than as a
    principal.
43. Displayed orders have priority over non-displayed orders at the same price.
44. Displayed shares have priority over reserve shares at the same price. For
    example: MM AA is displaying 4 round lots to buy at $10.00 and has a 2
    round lots of reserve at $10.00. MM BB is also displaying 2 round lots to buy


Series 57 Key Concepts

```
at $10.00. If a customer order is received to sell 6 round lots, the 4 round lots
being displayed by MM AA and the 2 round lots being displayed by MMBB
will be executed against, while the reserve quote would not be.
```
45. When a re-organized company emerges from bankruptcy with an IPO, the
    newly issued shares will generally trade when-issued with a “v” symbol at
    the end of the ticker. Once the shares a formally issued, the “v” symbol is
    removed.

Chapter 5: Trade Reporting

1. Stop stock orders (i.e., the customer is promised a price for a short period of
    time) are allowed only for customer orders. They do not require exchange
    or regulator permission.
2. If a broker-dealer receives a customer buy order for a security and
    simultaneously purchases that stock for its own account to fill the
    customer’s order from its own inventory, the trade report would be marked
    as “riskless principal”.
3. A trade report will identify whether a trade was a long sale or short sale.
    Note that there is not a specific trade modifier used to identify a short sale.
4. A trade report is marked as/of when the trade occurred earlier than the
    current day (e.g., yesterday) or when reporting the reversal of a trade from
    a previous day.
5. Important TRF modifiers:

```
a. “.T” indicates a timely report for a trade executed outside market
hours. Timely reports are due within 10 seconds of execution when
TRF is open; if TRF is closed, by 8:15 a.m. the next time TRF is open.
b. “.Z” indicates a late report for a trade executed during normal
market hours trade (9:30 a.m. – 4:00 p.m.). Late is defined as more
than 10 seconds after execution. Note: a trade executed during
market hours (e.g., 3:40 p.m.) but report late after the market closes
(e.g., 4:15 p.m.) should carry a .Z modifier because the execution
was during market hours.
c. “.P” indicates a Prior Reference Price trade. A trade report with a .P
modifier will include both the actual executed time and the
reference time. The price reported will be the actual executed
price.
i. Example: Client places an order to buy stock at 11:00 AM. At
11:30 AM the trader realizes that the order was not executed.
```

Series 57 Key Concepts

```
The trade can be executed at the 11:00 AM price with a .P
modifier indicating both times.
```
6. Unless there is an exemption from trade reporting requirements, an ATS must
    report trades to the TRF or ORF within 10 seconds of execution.
7. A “give-up” agreement allows one member to allow another member to
    report and lock-in trades on its behalf.
8. Certain transactions are exempt from trade reporting requirements:

```
a. Transactions that are part of a new issue.
b. Transactions where the buyer and seller have agreed to a price
unrelated to the current market price (e.g., a gift)
i. Note that these are reported for the purpose of regulatory
fee assessments but not for publication and dissemination.
c. Transactions related to the exercise of a derivative at a price
unrelated to the market value.
i. Note that these are reported for the purpose of regulatory
fee assessments but not for publication and dissemination.
d. Tender offer transactions
```
9. FINRA considers several factors for consequences for late trading
    reporting – including the trade complexity.
10. If a firm’s primary reporting facility is having an outage the firm may
    continue to trade provided that it can report to a secondary facility.
    Alternatively, firms may stop executing until the problem is resolved or can
    route orders to another exchange or FINRA facility that is able to
    effectively report trades.

Chapter 6: New-Issue Market

1. Insiders (e.g., CEO, CFO, and board members) will often agree to a post-
    IPO lock-up with their underwriter. Though not required, lock-ups typically
    last 180 days.
2. When selling IPOs, firms might choose to allocate shares to “friends and
    family” through a Directed Share Program.
3. Flipping is when an investor sells shares acquired in an IPO within 30 days of
    the offering date. The 30-day period is measured from the offering date
    regardless of when the purchaser was allocated or paid for the shares.
4. A green shoe clause in an underwriting agreement permits the underwriting
    investment bank to increase the size of the deal by up to 15% to meet
    investor demand.


Series 57 Key Concepts

5. A security that is the subject of an IPO must first open for trading on the
    primary exchange (e.g., NYSE), before it can begin trading elsewhere. Note
    that there is an exception where after the distribution of shares a stock can
    trade OTC until midnight the day prior to the IPO.
6. Prior to an IPO, orders to purchase the stock are permitted, but they must
    be limit orders. Not held and market (sometimes referred to as held) orders
    are not allowed. For example, a held sell order, a held limit buy order, and
    a held limit sell order would all be permitted pre-IPO (since they are either
    sell orders or buy orders that specify a price). A held buy order is not
    allowed, because there is no price.
7. In an IPO, a market maker can buy or sell stock in the secondary market
    after the first trade on the primary exchange. Once a new security is priced,
    the underwriters will sell the new issue at the public offering price (POP) to
    investors (e.g., at $11.00 per share). The initial transaction after the IPO
    (typically the next morning) will occur on Nasdaq or NYSE at the market
    price, which could be higher or lower than the IPO price.
8. A broker-dealer that is not part of an IPO can execute customer orders for
    the new shares on the effective date after the market opens. A market-
    making firm can register and immediately begin quoting an IPO after its
    opening IPO cross.
9. In a partial tender, exercised call options are included as part of an
    investor’s long position. If an investor exercises call options, those shares can
    be tendered, even if the tender closes that night.
10. A Dutch auction tender offer is an auction where all winning bidders pay
    the same price. In a Dutch auction, all orders are filled at the clearing price.
    The clearing price is determined based on the price at which all shares can
    be filled.
11. If a Dutch auction is oversubscribed, orders are filled pro rata – meaning
    everyone gets the same percentage of the shares they wanted to
    purchase.
12. Under Rule 10b-18, a company can repurchase up to 25% of its average
    daily trading volume (ADTV) in a particular day. Note that the ADTV is
    based on the average of the past four weeks.
13. Summary of Rule 144:

```
a. Control stock is subject to a volume restriction. This amount can be
calculated and then sold once every 90 days.
b. Control stock is not subject to a six-month holding period.
c. Restricted stock is subject to a six-month holding period, but not a
volume restriction.
```

Series 57 Key Concepts

14. Rule 144A permits Qualified Institutional Buyers (QIBs) to purchase
    unregistered securities. (Note: Rule 144 is different than Rule 144A).
15. Market makers may not collude to keep a stock’s price at a particular level.
    However, an underwriting syndicate may act together to support a new
    issue by having one firm, on behalf of the syndicate, place a stabilizing bid.
16. If an underwriter initiates stabilization when the market is closed, the
    maximum stabilization bid is the prior closing price. For example, an IPO
    opens at $40.00 per share and closes that day at $39.45. The maximum
    price a stabilizing bid may be entered for the next day is $39.45.
17. An underwriter can never stabilize above the IPO price.
18. Only one syndicate member may stabilize, but a stabilization bid can
    remain outstanding indefinitely and a stabilization agent is permitted to
    purchase an unlimited number of shares.
19. Make sure to review the restricted periods under Regulation M:

```
a. For the smallest companies (no criteria to meet), the restricted
period begins 5 business days before pricing.
b. For medium-sized companies, the restricted period begins 1
business day before pricing. These are defined as companies that
have an ADTV (average daily trading volume) of at least $100,
and a public float of at least $25 million.
c. Actively traded companies (large companies) have no restricted
period. Actively trades companies are those that have an ADTV of
at least $1 million and a public float of at least $150 million.
```
20. During the Regulation M restricted period, distribution participants (i.e.,
    underwriters) can choose to be passive market makers or can seek an
    excused withdrawal.
21. Under Regulation M Rule 103, the maximum bid for a passive market maker
    is the highest independent bid, which is the highest bid by a market maker
    that is not also an underwriter.
22. MMAA is a passive market maker. If MMBB has entered the highest
    independent bid, e.g., at $10.00, and then lowers its bid to $9.75, MMAA
    can purchase two times the minimum quotation size (typically 200 shares)
    at the $10.00 price and then must lower its price to $9.75.
23. An exception to Regulation M’s Rule 105 (short-sale rule) allows bona fide
    investors who meet certain conditions to short sell within the five-day
    restricted period and close their positions with newly offered shares. To use
    the exception, the latest a short sale trade can occur is 30 minutes prior to
    the close on the business day prior to the day of pricing. It is more important


Series 57 Key Concepts

```
to know the latest time the short sale can occur than the other conditions
required to use this rule.
```
24. Public companies are required to disclose quantitative and qualitative
    information on SEC filings. Regulation SK governs the release of non-
    financial information while Regulation SX governs the release of financial
    information.

Chapter 7: Equity Markets Securities Regulations

1. It is a violation of the suitability rules to email all of one’s clients with the
    same recommendation. This is not a know-your-customer (KYC) violation.
       a. Suitability focuses on whether there is a reasonable basis to believe
          that a recommended transaction or investment strategy is
          appropriate for the customer.
       b. KYC focuses on knowing the “essential facts” concerning each
          customer account, e.g., the customer’s identity, background,
          investment history, and sources of investable funds.
2. “Trading ahead” is the prohibited practice of trading securities based on
    non-public advance knowledge of the content of an upcoming research
    report. Traders that come into possession of such information may not trade
    on that information.
       a) Note, if the event causing a change in a pending research report is
          public (e.g., there is widely reported news that a company has lost
          a major client or gov’t contract) a trader could inform a client of
          the public news but must remain silent as to any pending change in
          the research coverage.
3. Regulation NMS Rules 605 and 606 require uniform information on where
    customer orders are being routed and the quality of execution being
    received. Candidates should know both the content of the rules and the
    rule numbers.
4. Reg NMS Rule 605 requires monthly reports by market centers.
5. Reg NMS Rule 606 reports do not include directed orders, since those orders
    are filled through the venue of a customer’s choosing.
6. Under Regulation BI, Form CRS must be presented to a customer at the time
    of, or prior to, making a recommendation, placing an order or opening an
    account.
7. Large traders must identify themselves using a Form 13H. However, “inactive
    status” is available for large traders who did not cross the large trader
    threshold at any time during the previous full calendar year. Once inactive,


Series 57 Key Concepts

```
a large trader need not file Form 13H unless and until its transactions are
equal to or greater than the threshold level.
```
8. If an institutional client suggests a trade which would take the client over
    their credit limit at that broker-dealer, the registered representative should
    talk to their supervisor about increasing the limit.
9. For NMS stocks under the ’34 Act, a Qualified Block positioner trades blocks
    of stock with a current market value of $200,000 or more in a single trade or
    several transactions at approximately the same time to facilitate a sale or
    purchase by a customer.
       a) A block is defined differently under FINRA’s OTC rules, where a block
          is defined as 10,000 shares and $100,000 in value.
       b) Qualified block positioners must maintain minimum net capital of $
          million.
10. A penny stock is an OTC equity worth less than $5.00 per share. Some rules
relating to penny stocks are below.

```
a) When a penny stock is trade is solicited, the registered rep must
disclose the current quote and compensation to be received by
the rep and the firm. Note that the number of market makers
making a market in the security is not required to be disclosed.
```
```
b) The client must sign and return a penny stock risk disclosure
document prior to their firm penny stock trade.
```
```
c) The client must sign a suitability statement before each penny stock
trade until they become an “established” customer (meaning they
have done at least three penny stock trades with that firm on three
separate days, or they have had an account for at least one year.
Exemptions from the suitability statement include:
```
```
i.Unsolicited orders
```
```
ii.Institutional accounts
```
```
iii.Firms who receive less than 5% of their commission revenue
from penny stock trades.
```
11. As noted above, penny stocks are generally defined as OTC equities
    worth less than $5 per share. However, companies with any of the
    following financial statistics are not penny stocks: net tangible assets of at
    least $2mm (or $5mm if in business less than three years) or average
    revenue of at least $6mm for the last three years.


Series 57 Key Concepts

12. Customers who own penny stocks must receive monthly account
    statements, which include the number of shares and estimated market
    value of each penny stock held in the account. The estimated market
    value is calculated as follows:

```
a) It is estimated as the highest bid on the last day of the statement
period multiplied by the number of shares owned by the customer.
```
```
b) If the stock is not currently being quoted, it is estimated as the
weighted average price per share paid by the broker-dealer during
the final five trading days of the statement period multiplied by the
number of shares owned by the customer.
```
```
c) If neither of the above options are available, then no estimated
market value is shown on the account statement.
```
13. Regulation FD requires firms to disclose sensitive information simultaneously
    with their intentional disclosure to research analysts. Accidental disclosure
    of sensitive information requires public disclosure by the later of 24 hours or
    the open of trading the next business day.

Chapter 8: Options Contracts and Strategies

1. OTC options are created individually between two counterparties. The key
    difference between OTC and exchange-listed options is that OTC options
    have counterparty risk.
2. CBOE floor brokers are individuals on the exchange floor who accept and
    execute orders from registered broker-dealers and Trading Permit Holders.
    They cannot accept orders from any other source.
3. To find the breakeven, use the strategy of “call up, put down.” For calls,
    add the net premium to the strike price of the dominant position—call up.
    For puts, subtract the net premium from the strike price of the dominant
    position—put down.
4. When asked to find the maximum gain (i.e., maximum revenue) or
    maximum loss, always include the premiums in the calculation. Note that
    premiums are still considered even if the question asks one to exclude fees.
    The premium is not a fee—it is the market price of the option.
5. Key items regarding covered calls:

```
a. The position is created by owning the stock and selling a call
against those shares.
b. Max Gain = Strike Price − Stock Purchase Price + Premium Received
```
6. The type of spread is determined by the contract feature that is different.


Series 57 Key Concepts

```
a. If the strike prices are different, but the expiration months are the
same, the spread is a “vertical” or “price” spread.
b. If the strike prices are the same, but the expiration months are
different, the spread is a “horizontal” or “calendar” spread.
c. If both the strike prices and the expiration months are different, the
spread is a “diagonal” spread.
```
7. An investor with a debit call spread will incur a loss of the aggregate
    premiums if both options expire.
8. Investors who establish debit call spreads are moderately bullish because
    they limit their potential upside to make the position less costly. They give up
    any profit above the strike price of the short call.
9. A bear call spread is established with two positions:

```
1) Selling a call with a low strike price, and
2) Buying a call with a higher strike price
```
```
It is also referred to as a “credit call spread.” The market view of this position
is bearish.
```
10. A put spread is 1) bearish and 2) a debit when the investor purchases a put
    contract with a higher strike price and sells a put contract with a lower strike
    price.
11. A trick to remember whether an investor hopes for a spread to widen or
    narrow is to look at the number of letters in the words:
       a. Debit spreads widen: “Debit” has five letters; “widen” has five
          letters.
       b. Credit spreads narrow: “Credit” has six letters; “narrow” has six
          letters.
12. In a spread, the dominant position is always the position with the higher
    premium. It indicates whether the spread is bullish or bearish and is also
    used to find the breakeven point.
13. A long straddle is created by simultaneously buying a call and buying a put
    on the same security with the same strike price. A short straddle would be
    created by selling a call and selling a put.
14. If an investor enters a straddle (long or short) with options that have
    different strike prices—e.g., a higher call strike and a lower put strike, or vice
    versa—the position is called a “strangle” or a “combination.” A long or short
    combination has the exact same attitude as a long or short straddle. For
    example, a long combination, like a long straddle, speculates that the
    stock will be volatile.


Series 57 Key Concepts

15. If an investor believes a stock will trade with volatility but is not sure of the
    direction, the investor should open a long straddle on the position.
16. An investor who expects little volatility (i.e., flat markets) should enter into a
    short straddle position (short call and short put). A short combination, similar
    to a straddle, would also achieve the same effect.
17. Index options are always settled for cash.
18. VIX index options allow investors to speculate on investor sentiment and
    market volatility. Importantly, the VIX index is inverse to the market; so, as
    the market rises, the VIX falls. When the market falls, the VIX rises. Described
    differently, a bearish investor would purchase VIX calls.
19. A butterfly spread is made of four options, all with the same expiration,
    three with different strike prices. A two-option position could not be a
    butterfly spread.
20. A butterfly spread has two contracts on the outside and two contracts in
    the middle – e.g., Buy 1 40 call, Sell 2 50 calls, Buy 1 60 call. Described
    differently, it is a 1-2-1 position, NOT a 2-1-2 position.
21. Review what options are American and European style:

```
a. American options: Most exchange-traded equity (stock and ETF)
options
b. European options: Most exchange-traded index options, such as
SPX (S&P 500 index) and VIX index options, as well as foreign
currency options.
```
22. The Employee Retirement Income Security Act (ERISA) is a federal law that
    protects private sector retirement plans such as 401(k) Plans. Importantly,
    an ERISA plan is permitted to trade options as long as it meets the
    investment criteria of the plan.
23. Options can be exercised up until 5:30pm et on the third Friday of the
    expiration month. An investor who owns an out-of-the-money option at this
    time will let it expire.
24. The CBOE’s position limits rule governs how many options contracts an
    investor may control. Exceptions to the standard position limits are available
    for 1) delta hedging, 2) firm facilitation, or 3) market-making.

```
Note: there is not an exception to position limits based on dividends. It is
more important to know the names of the exemptions – and what is not an
exemption - as opposed to their application or use.
```
25. Position limits on the same side of the market are aggregated. For example,
    5,000 long calls and 4,000 short puts are aggregated as a 9,000 position
    (since they are both bullish). On the other hand, 3,000 long calls and 3,000


Series 57 Key Concepts

```
long puts would be two separate 3,000 positions since one is bullish and one
is bearish.
```
26. OPRA (the Options Price Reporting Authority) collects, consolidates, and
    disseminates options market data (last sale and quotes) from options
    exchanges. Think of OPRA as the reporting facility for options transactions,
    similar to the consolidated tape or TRF.
27. To take advantage of a strong foreign economy, an investor can buy calls
    in that currency. For example, if the French economy looks strong and
    France has falling unemployment, an investor should buy EUR calls. If a
    foreign economy is weakening, an investor should buy puts on that
    currency.
28. Here are some key points regarding stock splits:

```
a. The value of an option contract remains the same if the underlying
stock splits. For example, the value of an option contract is $500; the
underlying equity has a 5:4 stock split, so the option’s value remains
the same at $500.
b. For an odd stock split, the contract size will be adjusted. For
example, in a 3:2 split, the options contracts on that underlying
equity will be adjusted. The number of shares per contract increases
by 3/2 (to 150 shares per contract) and the strike price is adjusted
downwards by 2/3. Note the premium on the option contract
doesn’t change.
```
29. Standard options contracts may not be purchased on margin. Therefore, a
    customer buying two options contracts at 14 would need to have at least
    $2,800 in her account ($14.00 per Share × 100 Shares × 2 Contracts =
    $2,800).

```
If the customer had more than $2,800 in cash in her account, no deposit
would be required to make the purchase. This funding could be obtained
by transfer from a cash account into the margin account.
```
30. Foreign currency options have a contract size of 10,000 units of currency
    (i.e., 10,000 pounds, Euros, or Canadian dollars).

```
The exception is Japanese yen. Options denominated in Japanese yen
have a contract size of 1,000,000 yen.
```
31. If a market maker holds a customer all-or-none (AON) buy order and
    receives a sell order that is not for enough shares, the market maker will not
    execute the customer’s AON order. For example, if a customer enters a buy
    600 shares AON order and, subsequently, a market order to sell 300 is


Series 57 Key Concepts

```
received, the AON order is not executed. The same concept applies to
options trades.
```
32. A facilitation cross is when a floor broker holds a customer order and a
    contra-side order, the broker can cross the two orders only after checking
    the market for a better price and allowing other market participants to
    execute the trade on the same price and terms. This is most common for
    options.
33. Not held orders permit floor brokers to decide the time and price at which
    to execute a customer’s order. All orders given to floor brokers are defined
    as not held orders unless otherwise specified. A not held order does not give
    discretion over the specific security or quantity.
34. When an option is exercised, the OCC assigns an exercise notice to a
    broker-dealer using random selection. A broker-dealer will then assign
    delivery to a customer who is short the equivalent position using random
    selection, first-in first-out or any other fair and equitable method.
35. Index options can be purchased in an ERISA sponsored plan provided they
    conform with the plan’s investment policy and that no margin is required
    (since ERISA accounts must be cash accounts). For example, selling
    uncovered calls requires a margin deposit and therefore would be
    prohibited.




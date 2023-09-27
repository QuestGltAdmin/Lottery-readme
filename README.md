# 🎟 NorthStar Lottery 

<!-- ![](../../.gitbook/assets/lottery-v2-header.png) -->

Playing the NorthStar Lottery gives you a chance to win huge BUSD prizes! It's easy, fair, and you can enter as often as you like as long as you have the Coins/Tokens to buy a ticket.

[View smart contract](https://testnet.bscscan.com/address/0x8e91f94ae01df2680bb30ab15d3216fb6a619407#code)

## **Specifics:**

* Lottery ticket cost for 1 ticket: \~$2 USD in any Coin or Token.
* User can purchase Lottery Tickets from any of the Token or coin He/She Holds.
* Individual user Lottery entry limit: No overall limit, but only 100 tickets can be bought at a time.
* Paying for one ticket will give users a random 6-digit combination with each digit being between 0-9, for e.g. “1-9-3-2-0-4”. Match numbers from the left to win prizes—the more numbers that match, the bigger the prize pool you'll share in.
* Lottery uses RandomNUmberGenerator along with Hashing for true, secure randomness.

## Ticket costs and bulk purchase discount

Lottery ticket prices are set at the start of the new lottery round, and target $2 USD (may vary slightly with sudden price fluctuations).

Buying multiple Lottery tickets at once gives a bulk discount on your purchase. You can buy as many as 100 tickets in one purchase, with the discount starting small at 2 tickets, and scaling up to 4.95% at 100 tickets.

<!-- ![](<../../.gitbook/assets/image (146).png>) -->

## **How to win**

Match numbers, **from the left side of your ticket**, to the winning numbers drawn at the end of a Lottery round.

* Matching even just the first number will win you a small prize.&#x20;
* Match more numbers to win a share of a larger prize pool.

## **‌**Prize eligibility

‌There are a total of six lottery balls, from 0 to 9, on each ticket. To win, your numbers need to match the drawn numbers in the same order as the lottery balls, starting from the left of the ticket. For example:



<!-- ![Drawn Numbers](<../assets/img/winning-criteria-img.png>) -->


![](<winning-criteria-img.png>)

In the example above, Ticket A, The first 4 digits match and the last 2 digits doesn’t match.

However, since the fifth and sixth digit does **not** match the drawn number, only the first Four digits count as matching in order. This would win a "Match first 4" prize.

<!-- ![Your Ticket B](<../../.gitbook/assets/image (149).png>) -->
Example Ticket B. Here's an lucky one. All the 6 digits match,so this ticket win a “Match first 6” prize.


You will only share in prizes from the highest prize bracket you are eligible for. A ticket matching the first three numbers will only be eligible for prizes from the match-three bracket, and not for the match-one or match-two brackets.

**Remember: The digits must match in order, starting from left to right.**

## Prize sharing across prize brackets

‌After a round is drawn, and tickets with matching numbers are determined, the prizes are awarded. The amount won by each ticket will depend on how many other tickets won in the same prize bracket.

‌For example, if you have the only ticket that matched three numbers in order, and the predetermined share of the prize pool for your bracket was 2000 BUSD, you'll receive the full 2000 BUSD.

‌If, however, you and three other people match three numbers in order, the 2000 BUSD would be split between the four winning tickets, meaning you would receive 500 BUSD.

<!-- See the [Lottery FAQ for a breakdown of prizes](lottery-faq.md#how-are-prizes-broken-down-between-brackets) across each bracket. -->

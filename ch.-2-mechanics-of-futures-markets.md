# Ch. 2 Mechanics of Futures Markets

## 2.1 BACKGROUND

* long position: agrees to buy
* short position: agrees to sell
* future price: the price on agreement of the asset ---> **determined by laws of supply and demand**



### Closing Out Position&#x20;

* vast majority of futures don't lead to delivery
  * traders close out their positions **prior to the delivery through** **entering into the opposite trade to the original one**.
  * <mark style="color:blue;">why does it mean?</mark>
    * <mark style="color:blue;">the exchange doesn't allow a trader holds both positions in one asset ---> it will take the trader's position as "flat".</mark>
* <mark style="color:blue;">Note: there is a difference between</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**closing a position and closing out a position**</mark>
  * <mark style="color:blue;">closing a position: selling the contract to other people before delivery</mark>





## 2.2 SPECIFICATION OF A FUTURES CONTRACT

* **exchange** **must specify the exact nature of the agreement between two parties**
  * asset type, contract size, the time of delivery, the place of delivery...
  * alternatives of assets ---> short position determines the steps
* when short positions are ready to delivery:
  * files a notice of intention to delivery with the exchange



### The Asset

* commodity:
  * variation in the quality of assets ---> prices determined by the grade
* financial assets:
  * unambiguous



### The Contract Size

* amount of assets to be delivered under **one contract**
* depends on **the users**



### Delivery Arrangements

* important for commodities with a **transaction cost ---> price received by the short positions will be adjusted**
* far from the main source of commodity ---> higher price



### Delivery Months

* **precise period ---> chosen by exchange to meet the needs of market participants**
* specify the beginning and the last day of the trade



### Price Quotes

* how prices are quoted ---> dollars or cents



### Price Limits and Position Limits

* there is a limit on the movement of daily price
  * **limit down: if the price in a day moves down by an amount from previous day's close equal to the daily price limit**
  * **limit up: if the price in a day moves up by an amount from previous day's close equal to the daily price limit**
  * in either case, the trade will be ceased.
* why:
  * prevent **speculative excess**
* controversial
* position limits: **the maximum of contracts that a speculator may hold**
  * prevent **speculators' undue influence**
  * the action of speculators is **leverage**



## 2.3 CONVERGENCE OF FUTURES PRICE TO SPOT PRICE

* Why?
  * futures price > spot price --->
    * traders will take this arbitrage
    * **traders will enter a short position in futures, buy the assets at the spot price, and make the delivery.**
    * the futures price go down as the sellers increase.
  * futures price < spot price --->
    * **companies who want to buy the asset will enter a long position and wait for the delivery**
    * the futures price go up as buyers increase.

![](<.gitbook/assets/Screen Shot 2022-07-28 at 2.55.28 PM.png>)

* <mark style="color:blue;">there is no reason to enter futures again as the two prices get closer ---> so they will only converge finally</mark>

## 2.4 THE OPERATION OF MARGIN ACCOUNTS

* **prevent default**



### Daily Settlement

* initial margin: the amount that must be deposited into the margin account at the time the contract is entered
* daily settlement / marking to market: **at the end of each trading day, the margin account is adjusted to reflect the trader's gains or losses**.
  * first settle: **settled at the close of the day it takes place**
  * loss ---> **the broker** has to pay it to the exchange clearing house
* **investors have the rights to withdraw any excess from its initial margin**
* maintenance margin:
  * make sure the **balance in the margin account is never negative**
  * **somewhat lower** than initial margin
  * if the balance in margin account < this limit:
    * **the investor will receive a margin call (the money he should pay in order to go back to initial margin) by the end of the next day**
    * **variation margins: the extra fund the investor deposits**
    * **if not pay the variation margin---> broker will close out the position**&#x20;



### Further Details

* <mark style="background-color:purple;">??? brokers pay investors interest on the balance in margin account ---> the rate is</mark> <mark style="background-color:purple;"></mark><mark style="background-color:purple;">**competitive**</mark> <mark style="background-color:purple;"></mark><mark style="background-color:purple;"></mark>&#x20;
* **investors can deposit securities to fulfill the requirement for margin account but don't need to pay subsequent margin calls**&#x20;
  * why: **the broker can sell the securities to refill the margin**
  * treasury bills: 90% of face value---> <mark style="color:blue;">less risker</mark>
  * stocks: 50% of market value
  * why? ---> there is **fluctuation in the value of securities**.
* **a future contract is settled daily**<mark style="color:blue;">,</mark> but a forward settled at the end of its life.
  * gain / loss are directly added to the margin account ---> **the contract's value goes to zero** and renew the other day
* the minimum level of margins is set by the exchange, but the brokers will require a little higher level ---> <mark style="color:blue;">risks</mark>
  * minimum margin levels are decided by **the variability of price** ---> more variable, higher minimum level
  * usually 75% for maintenance margin
* margins requirement also depends on **the objectives of the trader**.
  * **risk of default**
  * e.g. day trading ---> less margin, since closing out on the same day
* spread transaction: **two opposing positions in two different maturity months**
* margin requirement is the same for both **short futures positions and long futures positions**
  * **equally easy**
  * but not true for **spot market** --->
    * long: buy immediately
    * short: selling something you don't own it now



### The Clearing House and Its Members

* clearing house: intermediary
  * brokers who are not a member have to find a member to channel the business and post the margin with the member
  * <mark style="color:blue;">members example: J.P Morgan</mark>
  * main task: calculate the net position of the members each day
* **There is no maintenance margin applicable to the clearing house member.**
  * each day the clearing house member is settled
    * **in total transactions** lose money ---> provide variation margin
    * gain money ---> receives variation margin
* initial margins ---> **the number of contracts outstanding (have not been paid) on a net basis** is considered
  * **short positions ---> offset long positions**
* a guaranty fund ---> when one member doesn't provide variation margins
  * losses ---> when one member's positions are closed out.



### Credit Risk

* goal of margining systems: **funds can be payed to traders when there is a gain**



## 2.5 OTC MARKETS

* **credit risk**

### Central Counterparties

* CCP&#x20;
  * members: **provide initial margins + daily variation margins + contribute to a guaranty fund**
  * **it takes the credit risks of two parties**
    * e.g. A and B have a forward contract that A will buy B an asset at K one year later
    * CCP:&#x20;
      * buy an asset at K from B&#x20;
      * sell an asset at K to A
  * if an OTC participant is not a member of CCP ---> finds a member and provides margins to clear the trade



### Bilateral Clearing

* for the OTC transactions that are not cleared by the CCP
* enter an agreement (most common: **International Swaps and Derivatives Association (ISDA) Master Agreement**)
  * **both sides pay collateral** according to an annex (e.g. credit support annex. CSA）
* collateral agreements on CSA are valued each day
  * bilateral ---> one increases in value, and the other decreases in value
  * **the side with decreasing value will pay the increasing side a collateral equal to the amount of the decreasing value**
  * <mark style="color:blue;">why? ---> default risk</mark>
* CSA now: **both initial margin and variation margin**

![](<.gitbook/assets/Screen Shot 2022-07-28 at 4.23.50 PM.png>)



### Futures Trades vs. OTC Trades

* **initial margin earn interests in both situation**
  * **but variation margins only earn interest in OTC ---> futures: daily settlement**
* **securities: always fulfill for margin / collateral requirements**
  * haircut: the market value of the securities is decreased to some degree for margin purpose



## 2.6 MARKET QUOTES

*




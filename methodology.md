---
cover: .gitbook/assets/MEASURING THE CARBON COST OF CRYPTO TRANSACTION-2.png
coverY: 584.3292547274749
---

# METHODOLOGY

## TXN CARBON MVP

The dataset for Transactions was taken from the Polygonscan API.

#### TXN Carbon process of mapping a block to an emission.

![](<.gitbook/assets/Screenshot 2022-02-07 at 00.49.44.png>)

This solution is an MVP and a work in progress. The formula is:  &#x20;

&#x20;    (Sum of Gas Fee of all transaction of MINER Y/ Total number of transactions of Miner Y) X (Total transaction of Miners X Average CO2 cost per transaction) = XX kg CO2 &#x20;

The wallet’s footprint is the sum of Gas consumed for transactions leaving your wallet, multiplied by a best-guess estimated emissions factor. The emissions factor was derived from the average CO2 cost of transactions on Polygon.



The formula has its limits and is still a work in progress. There are theoretical researches on Ethereum emission that could potentially be used to build a better model. Since Polygon is a proof of Stake model, the architecture of the system enables us to use the average CO2 per transaction on Polygon because other variables will have negligible effects.



For more information, https-github.com-kliskyjakub-txn-carbon-impact-dashboard




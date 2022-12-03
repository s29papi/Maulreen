<div align="center">
  <br />
  <br />
  <br />
  <h3>Maulreen: is a low cost hub of token meta-transaction relayers.</h3>
  <br />
</div>

## Problem Statement ?

Currently gas fees on evmos are paid with (xxxx). For experienced users this may not be a problem, since they have learned to keep a reserve. For new users they  might not consider this requirment and therefore might get stuck on chain.

## Scenario ?

A new user recently bridged to EVMOS and does not have the gas fee to initially move out funds, he reached out to one of the relayers to fund the Gas Fees, and after the relayer executes the transaction, the relayer get paid in its specified token.

Another scenario, would be allowing the contrancts and the relay hub to be re-used by the public, this was dapp developer can have their users pay for gas with a token.

## Where does covalent come in ?
As this project is a prototype in the EVMOS X COVALENT X ENCODE Hackathon, 4 of covalents api's are used,

1. Token Balances Api, used to verify that a user has the funs to pay for this transaction
2. Events By Contract Address Api, used to monitor the relayer hub.
3. Events By Topic Hash Api, does same with Events By Contract Address.
4. Transactions Api

## What is Maulreen ?
 
 Maulreen is a low-cost hub of token meta-transaction relayers, **but it's also so much more than that**.

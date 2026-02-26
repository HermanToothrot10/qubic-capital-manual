# IPOP — IPO Participation Proposal

## Purpose

To decide whether QVAULT should **participate in an ongoing IPO** and define the **maximum amount to allocate**.
This proposal type can only be created when an IPO is active.

## Required inputs

- GitHub link
- Selection of the IPO to which the proposal applies

## Voting mechanism

- Voters choose Yes or No
- If voting Yes, voters enter the maximum amount (in Qu) they are willing to allocate

## Approval & allocation logic
- If No votes exceed Yes votes → allocation is 0
- If Yes votes exceed No votes → the allocated amount is the weighted average of the amounts entered in Yes votes

## Execution outcome

If approved and sufficient funds are available according to fund allocation priority, the proposal is executed immediately at epoch end.

QVAULT automatically bids in the IPO, maximizing the number of shares obtained.

Multiple approved proposals of this type may coexist and be effective at the same time, provided sufficient funds are available.


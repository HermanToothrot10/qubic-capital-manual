# AlloP — Allocation Percentage Proposal

## Purpose

To modify the **percentage allocation of weekly revenues** between:

- Distribution to QCAP holders
- Reinvestment fund
- Burn

## Constraints

- Allocation to QVAULT shareholders is permanently fixed at 3%
- Allocation to Burn is only possible from 1 January 2029
- The sum of configurable allocations must equal 97% (enforced by the UI)

## Required inputs

- GitHub link
- New allocation percentages

## Voting & approval

- Quorum required
- Yes votes must exceed No votes

## Execution outcome

If approved, the new allocation becomes effective after one full epoch and applies to future revenue distributions starting from the following epoch. For example, if approved at the end of epoch 200, it becomes effective at the start of epoch 202.

If multiple Allocation Percentage proposals are approved within the same epoch, only the last-created approved proposal is executed. Previously approved allocation proposals from the same epoch are superseded and have no effect.


# QCP — Quorum Requirement

## Purpose

To **modify the quorum percentage** required for proposals to be considered valid.

Default quorum: 67%

This parameter is critical: if participation falls below the quorum threshold, any proposal is automatically rejected.

## Required inputs

- GitHub link
- New quorum percentage

## Voting & approval

- Current quorum must be reached
- Yes votes must exceed No votes

## Execution outcome

If approved, the new allocation becomes effective after one full epoch and applies to future revenue distributions starting from the following epoch. For example, if approved at the end of epoch 200, it becomes effective at the start of epoch 202.

If multiple Quorum Requirement proposals are approved within the same epoch, only the last-created approved proposal is executed. Earlier approved quorum proposals from the same epoch are ignored and have no effect.


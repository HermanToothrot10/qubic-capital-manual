# Fund Allocation Priority

When multiple approved proposals compete for limited treasury funds in the same epoch, QVAULT enforces a strict priority order:

1. **IPOP — IPO Participation**
2. **MKTP — Marketplace**
3. **QEarnP — Qearn**

This logic is system-defined and automatically enforced.

## Example 1
Treasury: 100b<br><br>
IPO: 50b<br>
Marketplace: 20b<br>
Qearn: 10b<br><br>
→ All proposals are fully executed.

## Example 2
Treasury: 60b<br><br>
IPO: 40b<br>
Marketplace: 20b<br>
Qearn: 10b<br><br>
→ IPO and Marketplace are executed.<br>
→ Qearn is not executed.

## Example 3
Treasury: 50b<br><br>
IPO: 50b<br>
Marketplace: 10b<br>
Qearn: 5b<br><br>
→ IPO is executed.<br>
→ Marketplace and Qearn are not executed.

## Example 4
Treasury: 100b<br><br>
IPO A: 80b<br>
IPO B: 50b<br>
Total requested: 130b<br><br>
Allocation:<br>
IPO A → (80 / 130) × 100 = 61.54b<br>
IPO B → (50 / 130) × 100 = 38.46b<br><br>
→ Funds are prorated across IPOs.<br>
→ Lower-priority proposals receive no funds.

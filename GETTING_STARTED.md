# Learning Plan

## Schedule

Weekdays: one Ethernaut level per day.
Weekends: read and write up one audit finding per session.

Both run in parallel. Ethernaut builds exploitation intuition; reports show what that looks like in real production code.

## Weekend Phase 1: OpenZeppelin Reports (Start Now)

OZ reports explain the protocol before the findings, which makes the bugs actually make sense. Start here while still working through Ethernaut.

Full audit list: https://www.openzeppelin.com/research#security-audits
Start with Compound III: https://www.openzeppelin.com/news/compound-iii-audit

For each session:
1. Read the protocol summary
2. Find the Critical and High findings
3. Pick one to deep-dive
4. Write it up using the template in `audit-reports-studied/`
5. Commit and push

## Weekend Phase 2: Solodit (After Ethernaut Is Done)

Faster and less context per finding, which works once you have some background. Target 5 to 10 write-ups.

Solodit filtered to Critical + Code4rena: https://solodit.cyfrin.io/?i=HIGH%2CMEDIUM%2CLOW%2CGAS&maxf=&minf=&rf=alltime&sd=Desc&sf=Recency

## Phase 3: Code4rena Contests

https://code4rena.com/audits

Goal for the first contest: read the codebase and try. Finding a bug is a bonus, not the requirement.

## Committing Each Analysis

```bash
git add .
git commit -m "Add [Protocol] analysis - [vulnerability type]"
git push
```

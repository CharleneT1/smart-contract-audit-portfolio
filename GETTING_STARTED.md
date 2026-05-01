# Getting Started

## Schedule

**Weekdays:** One Ethernaut level per day — hands-on exploitation builds the intuition that makes reading reports actually stick.

**Weekends:** Audit report analysis — one finding written up per session.

---

## Weekend Work: Audit Report Analysis

### While Working Through Ethernaut (Weekends Now)
**OpenZeppelin reports** are the best starting point — they explain the protocol first, then the finding, so you have context for why something is a bug.

- Full list: https://www.openzeppelin.com/research#security-audits
- Start here: https://www.openzeppelin.com/news/compound-iii-audit (Compound III)

**Workflow:**
1. Read the protocol summary section
2. Find the Critical/High findings
3. Pick ONE to deep-dive
4. Fill out the template in `audit-reports-studied/`
5. Commit and push

---

### After Ethernaut Is Done (Weekends Later)
Move to Solodit for faster pattern-matching practice across more findings.

- https://solodit.cyfrin.io/?i=HIGH%2CMEDIUM%2CLOW%2CGAS&maxf=&minf=&rf=alltime&sd=Desc&sf=Recency
- Filter: Critical + Code4rena

---

### When Ready for Contests
- https://code4rena.com/audits
- Goal for first contest: read the code and try — finding a bug is a bonus, not the requirement.

---

## Commit After Each Analysis
```bash
git add .
git commit -m "Add [Protocol] analysis - [vulnerability type]"
git push
```

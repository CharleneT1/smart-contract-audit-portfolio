# Getting Started

## Phased Learning Path

### Phase 1: Hands-On Exploitation (Weeks 1-2)
**Ethernaut** — learn vulnerability patterns by exploiting them yourself, not just reading about them.

This builds the intuition that makes reading reports actually stick.

---

### Phase 2: Read Real Audit Reports (Weeks 3-4)
**OpenZeppelin reports** are the best starting point for beginners — they explain the protocol first, then the finding, so you have context for why something is a bug.

- Full list: https://www.openzeppelin.com/research#security-audits
- Start here: https://www.openzeppelin.com/news/compound-iii-audit (Compound III)

**Your workflow per report:**
1. Read the protocol summary section
2. Find the Critical/High findings
3. Pick ONE to deep-dive
4. Fill out the template in `audit-reports-studied/`

---

### Phase 3: Solodit Pattern Practice (Weeks 5-6)
Once you have context from real reports, Solodit findings are faster for pattern recognition.

- https://solodit.cyfrin.io/?i=HIGH%2CMEDIUM%2CLOW%2CGAS&maxf=&minf=&rf=alltime&sd=Desc&sf=Recency
- Filter: Critical + Code4rena
- Aim for 5-10 findings, one write-up per finding

---

### Phase 4: Code4rena Contests (Week 7+)
You don't need to find a bug in your first contest. The goal is to read unfamiliar protocol code and try — that practice is the skill you're building.

- https://code4rena.com/audits

---

## Commit After Each Analysis
```bash
git add .
git commit -m "Add [Protocol] analysis - [vulnerability type]"
git push
```

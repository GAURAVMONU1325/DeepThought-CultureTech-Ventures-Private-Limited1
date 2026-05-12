# Methodology Document — DeepThought Part A Research
## Pune | Specialty Biotech + Specialty Diagnostics & Life-science Tools

---

## 1. City & Segment Selection Rationale

**City chosen: Pune**

Pune was selected because:
- It is home to one of India's only Integrated Biotech Parks (TCG-IBP at Hinjewadi)
- Presence of national research institutions: National Chemical Laboratory (NCL), NCCS, NIV, IISER Pune — all of which create a dense talent pool that feeds into commercial biotech startups
- Strong CDMO and biopharma manufacturing belt forming in the Chakan-Talegaon-Bhosari corridor
- Maharashtra MIDC provides land and infrastructure for biotech manufacturing

**Segments chosen:**
1. **Specialty Biotech** — probiotics, enzymes, recombinant proteins, fermentation services
2. **Specialty Diagnostics & Life-science Tools** — diagnostic kits, antibodies, reagents, genomics tools

These two segments were chosen together because they share infrastructure, talent, and decision-makers in Pune's ecosystem. Many companies operate at the intersection (e.g., a recombinant protein company that also makes diagnostic antibody reagents).

---

## 2. Research Sources Used

### Primary sources (verified company data)
| Source | What it gave me |
|---|---|
| Company websites | Product descriptions, leadership bios, certifications, news |
| LinkedIn | Hiring data, leadership profiles, recent company posts |
| Tracxn / Crunchbase | Revenue estimates, funding history, founding year |
| Built In Pune (builtinpune.in) | Curated list of Pune biotech companies |
| Pharmchoices.com full Pune biotech list | Comprehensive directory of 40+ companies |
| LabioTech.eu | Narrative profiles of Pune biotech companies |
| Wikipedia | For specific companies with verified pages (Mylab) |
| DCVMN profile (Gennova) | Verified technical and product details |
| Ensun.io fermentation India list | Fermentation companies with Pune presence |

### Secondary verification sources
| Source | Purpose |
|---|---|
| MCA / Tofler / Screener | Revenue bands, legal registration status |
| Google News (company name + 2023/2024) | Recent press, new products, expansion announcements |
| DSIR recognition lists | Verifying R&D recognition claims |
| LinkedIn Jobs (company page) | Hiring signal verification (C6 criterion) |

---

## 3. Research Process — Step by Step

### Step 1: Generate a broad list (targeting 75-100 candidates)
Started with broad searches:
- "Pune biotech companies" — found builtinpune.in and pharmchoices.com lists
- "Pune specialty biotech manufacturer enzyme probiotic"
- "Pune diagnostic kit manufacturer reagent antibody"
- "Pune fermentation manufacturer DSIR PhD founder"

This gave an initial pool of ~60 company names.

### Step 2: First filter — segment and geography
Applied segment filter: kept only companies in the two chosen segments. Eliminated:
- Generic pharma (Emcure, Lupin Pune sites) → segment mismatch
- Pure CROs and testing labs (Prorelix, Vimta) → service company
- Large IT and software companies in the biotech space
- Companies where "Pune" was only a sales office

Remaining pool: ~35 companies

### Step 3: Auto-disqualifier screen
For each remaining company, checked:
- Is it a trader/distributor? → eliminated 3 companies
- Is it a service company (CRO, testing lab)? → eliminated Prorelix, GeneOmbio partially, Raygenome
- Is it generic pharma? → eliminated Serum Institute (also revenue >500Cr), Lupin
- Is it a subsidiary? → eliminated Praj HiPurity, Enzene (Alkem subsidiary), Roche Pune
- Revenue above Rs.500Cr? → eliminated Praj Industries, Serum Institute
- No website? → none found in this pool
- PE/VC controlled majority? → checked and found none in final list clearly PE-controlled

Remaining pool after auto-disqualifiers: ~28 companies

### Step 4: Federer Score each company
For each of the 28, scored C1-C6 using the criteria table. Used:
- Website content for C1 (do they have a plant? do they say "manufacturing"?)
- LinkedIn profiles for C4 (founder educational background)
- News/press for C5 and C6 growth signals
- Certification pages and DSIR listings for C3

### Step 5: Final 25 selection
Selected 25 companies scoring 45+ (C-band or better). Documented all fails with clear reasoning.

---

## 4. Key Learnings About the Segment

### What I learned about Pune's specialty biotech ecosystem
1. **The CDMO wave is real.** Pune's Chakan-Talegaon corridor is attracting biologics CDMO investment (Enzene expanding, Synergen growing) driven by the Biosecure Act pushing US clients to diversify away from Chinese CDMOs.

2. **Diagnostic kit manufacturing is concentrated around CDSCO licensing.** Only companies with ISO 13485 + CDSCO/DCGI approval can actually sell diagnostic kits in India. This is a meaningful barrier. Mylab crossed it first for COVID.

3. **The line between manufacturer and service company is blurry.** Many Pune companies (GeneOmbio, Shantani Proteome, AbGenics) do both — they manufacture kits/reagents AND offer contract services. The criterion is whether the manufactured product is the primary revenue source. I applied this conservatively and scored borderline cases as Moderate on C1.

4. **Founder/DM technical background is harder to verify for small private companies.** For companies like Ross Lifescience and Hi Tech BioSciences, founder information is not public. I scored these as Moderate on C4 with a note to verify.

5. **Revenue data is scarce for private companies.** Most specialty biotech companies in this range are private and do not publish financials publicly. I used Tracxn, Crunchbase, and RocketReach estimates where available, and marked "Unknown" where I could not verify.

### What makes Pune specifically good for this segment
- TCG-IBP provides shared infrastructure, reducing capex for early-stage manufacturers
- NCL and NCCS Pune are feeder institutions for scientific founders
- MIDC Hinjewadi and Bhosari MIDC provide industrial land
- Proximity to Mumbai provides access to export logistics and financial services

---

## 5. Key Fail Patterns Observed

| Fail Reason | Companies |
|---|---|
| Revenue >Rs.500Cr | Praj Industries, Serum Institute |
| Service company (CRO) | Prorelix Research, Raygenome (primarily clinical service) |
| Large-group subsidiary | Enzene (Alkem subsidiary), Praj HiPurity (Praj subsidiary) |
| Software / non-manufacturer | Vlife Sciences Technologies, QbD Purple |
| Wrong segment (generic pharma) | Serum Institute (vaccines generic) |
| Government institution | Agharkar Research Institute |

---

## 6. Code / AI Usage Note

Research was conducted using web search queries across multiple sources. No scraping scripts were written. Searches were structured to minimize AI hallucination by:

1. **Verifying every company name against its actual website** before including in the list
2. **Cross-checking revenue claims** across at least 2 sources (Tracxn + company website, or Crunchbase + news)
3. **Never including a company based solely on a list mention** — each company was individually verified via its own website
4. **Marking "Unknown"** for data I could not verify rather than estimating
5. **Flagging borderline cases** (C-band companies) explicitly rather than inflating scores

---

## 7. Confidence Levels

| Confidence Level | Companies |
|---|---|
| High — multiple source verification | Mylab, Gennova, Indus Biotech, KBCols, Serigen, Geneombio |
| Medium — website + 1 external source | GenePath, AbGenics, Shantani, Synergen, Innovassynth |
| Lower — website only | Ross Lifescience, Hi Tech BioSciences, Maple Biotech, GSL Biotech, Green Pyramid, Indo Bioactive, Linq Therapeutics, Kimya Biotech |

**Note:** Lower-confidence companies are scored conservatively (C-band) and flagged for further diligence before outreach.

---

*Submitted for DeepThought Part A — Business Analytics Target Company Research*
*City: Pune | Segments: Specialty Biotech + Specialty Diagnostics & Life-science Tools*

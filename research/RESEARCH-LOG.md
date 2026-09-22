# Research Log — 21 September 2026

## Milestone

The landing page is now treated as a stable public baseline.

A rollback copy was created before the latest performance work:

- `backups/index-stable-landing-2026-09-21-fast-experience.html`

The entrance was then optimized so the archive opens immediately on button press rather than waiting through a 300 ms JavaScript transition.

## Historical research restarted

The project has now moved back to the historical foundation.

### First archaeological expansion

A dedicated archaeology research pass identified an additional RAN record that was not present in the initial heritage JSON:

- **RAN 13631.02 — Biserica și necropola medievală de la Curtea de Argeș — Drujești**
- medieval church: late 16th century to second half of 18th century
- medieval necropolis: 16th–17th centuries
- systematic archaeological research: 1987, Muzeul Județean Argeș, Spiridon Cristocea

The pass also connected the existing Sân Nicoară record to the 2011 archaeological report and identified older specialist literature on the Domnească Court and Domnească Church.

## Principle

The archive will expand by **evidence layers**, not by filling the website with premature narrative.

Next: complete the archaeological site inventory, then expand documentary, architectural, institutional and everyday-life records.


## Archaeology autopilot pass — 21 September 2026

### Pass 03 completed

The archaeological layer was re-analyzed against:
- the municipal historical study's archaeological inventory;
- current RAN records;
- the *Cronica Cercetărilor Arheologice* database;
- the Digital Library of Romania.

Corrections made:
- removed an earlier unverified reference to a supposed 2022 Curtea de Argeș archaeological report because it could not be securely matched to the city during verification;
- replaced internal research citation tokens in the archaeology file with stable source-register references;
- added verified archaeological bibliography and research records S11–S16;
- linked the expanded source IDs into the heritage JSON.

The archaeological stage remains **OPEN**. The next threshold is a systematic reconstruction of the complete RAN inventory for the municipal administrative territory, followed by a campaign/publication matrix.

This is deliberate: the archive does not declare completeness merely because its best-known monuments have been documented.


## Archaeology autopilot pass — 04

Fresh cross-checks added:
- verified the previously suspected 2022 report ID 1263 belongs to Râmnicu Vâlcea, so it is excluded from Curtea de Argeș evidence;
- added the 1917–1923 anthropological study of human remains from the Domnească Church excavations;
- added the 2014 Grave 10 historiographical study;
- added the 2015 Constantinescu archaeological/historiographical review;
- linked these sources to the Domnească Church record.

Stage 1 remains OPEN. The next major objective is still the complete municipal RAN inventory and excavation/report matrix.


## Archaeology autopilot pass — 08

Built `research/RAN-INVENTORY-01.md` as a controlled provisional municipal archaeological inventory.

Cross-checks established:
- current RAN index: five Curtea de Argeș records currently returned;
- *Cronica* confirms Drujești and Sân Nicoară;
- report 1263 excluded as Râmnicu Vâlcea;
- report 6103 excluded as Câmpulung, while its Curtea de Argeș references are retained only as bibliography leads.

Stage 1 remains **OPEN**. Alternate names, older archaeological records, disappeared/reclassified sites and complete LMI reconciliation remain outstanding.


## Naming control — Pass 09

Canonical modern Romanian city form reaffirmed: **Curtea de Argeș**.

Historical/source spellings such as “Curtea de Argeş” may be retained only when reproducing or describing the original source record. The archive's own modern prose will use **Curtea de Argeș**.

A fresh RAN web cross-check confirms that current database records use source-era/unaccented variants in some fields, while the locality is the municipality of Curtea de Argeș. These variants are now treated as source metadata, not canonical project naming.


## Archaeology autopilot — Pass 15 · 22 September 2026

The project entered the next self-analysis cycle after the English-first public interface and social-preview work.

### What was checked
- current RAN source pages for Drujești and Sân Nicoară;
- current database maintenance/update information;
- the 2011 Sân Nicoară archaeological report;
- Constantinescu's 1984 archaeological synthesis and its scope;
- the existing RAN inventory, archaeology pass history and working chronology.

### What changed in the research method
The archive now explicitly separates **register chronology**, **excavation dating**, **historical interpretation**, and **current synthesis**. This is especially important where a current register gives one date while an archaeological report preserves another specialist hypothesis.

### New conclusion
The archaeological foundation remains **OPEN — NOT COMPLETE**. The current evidence is stronger, but the complete municipal archaeological inventory and campaign/publication/context matrix still need to be reconstructed before Stage 1 can be closed.

### Autopilot improvement
The project is no longer only accumulating sources. Each new pass must also test whether the **research architecture itself** is becoming more accurate. When a better distinction, source-control rule or record structure is discovered, it becomes part of the methodology and is then applied to subsequent research.

Next priority: continue archaeological inventory reconciliation and campaign/publication reconstruction before expanding into the next historical layer.


## Self-correction discovered during Pass 15

A targeted search uncovered a previously unresolved RAN-code lead for **Biserica Olari**: secondary-source material identifies the site as **RAN 13631.09**. The official RAN record was not independently retrieved in the same pass, so the project did not promote the code to verified status. The inventory now records it as a candidate pending official verification. citeturn5search0

This is an intentional autopilot behavior: when new evidence changes an earlier conclusion, the archive updates the earlier state rather than protecting an outdated assumption.
\n\n## Archaeology autopilot — Pass 16 · 22 September 2026\n\n### What was checked\n- current RAN Curtea de Argeș records and indexed result sets;\n- the 2011 Sân Nicoară archaeological report;\n- County Council Argeș institutional evidence for the Olari archaeological intervention;\n- the existing RAN inventory and chronology controls.\n\n### What changed\n- added S38 for the Sân Nicoară 2011 campaign report;\n- added S39 for the County Council Argeș Olari archaeological/restoration cross-check;\n- strengthened the Sân Nicoară campaign/context record;\n- kept Olari RAN 13631.09 explicitly at **CANDIDATE** status because official RAN verification remains incomplete.\n\n### Self-analysis\nThe research architecture continues to improve by separating **what was excavated**, **what a register records**, **what historical sources say**, and **what later researchers infer**. This prevents a useful source lead from silently becoming a fact.\n\n### Status\n**Archaeological Stage 1 remains OPEN — NOT COMPLETE.** The next target is still the municipal archaeological inventory plus campaign/publication matrix, with special attention to older excavations, disappeared/reclassified sites, and LMI entries that may have archaeological evidence without a currently verified RAN row.
## Archaeology autopilot — Pass 17 · 22 September 2026

### Fresh checks
- rechecked current RAN result pages for Curtea de Argeș;
- cross-checked RAN entries against the municipal planning report;
- added a current 2026 County Council administrative/spatial source;
- tested whether current register dates were being confused with database access dates.

### Research architecture improvement

The archive now distinguishes two dimensions that had previously been too easy to merge:

**Evidence type** — archaeological / documentary / register / scholarly / oral-tradition.

**Source function** — excavation evidence / inventory evidence / spatial-administrative evidence / interpretation.

This is a methodological upgrade rather than just another source addition.

### Findings

The current RAN pages display 26 April 2023 as the update/verification date on the checked records. The municipal planning report independently identifies several core archaeological records. The 2026 County Council statute provides current spatial/place-name context around Sân Nicoară, Olari and Drujești. None of these sources, alone, establishes a complete municipal archaeological inventory. citeturn0search1turn0search13turn0search12

**Stage 1 remains OPEN — NOT COMPLETE.**

Next: continue the municipal inventory reconstruction and build the campaign/publication matrix, prioritizing records and interventions that can reveal missing or reclassified sites.

## Archaeology autopilot — Pass 18 · 22 September 2026

The research target was expanded from “find missing RAN records” to “reconstruct the full archaeological intervention history.”

Fresh bibliographic research identified the 1967 Curtea Domnească publication, 1969 Basarab necropolis study, 1980 archaeological sondaje at the Neagoe Basarab foundation, and 1984 Constantinescu synthesis. citeturn0search8turn0search4

The Sân Nicoară trail reaches back to an 1886 architectural investigation and the 1920 Drăghiceanu campaign, with later specialist cross-checks. citeturn0search0turn0search12

Methodological correction: a complete archaeological archive cannot be defined only by today's RAN identifiers. The working completeness model is now RAN/LMI inventory + historical interventions + published research record + find/evidence record + spatial reconciliation.

Some findings are currently available only through bibliographic indexes or secondary accounts. They remain LEADS until the underlying primary publication/report is inspected.

Stage 1 remains OPEN — NOT COMPLETE.

## Archaeology autopilot — Pass 19 · 22 September 2026

Pass 19 added a new evidence class: **negative archaeological evidence**.

The 1982 Bătrîna & Bătrîna publication records research in additional Curtea de Argeș zones, including an investigated area west of Sân Nicoară hill where no material/complexes warranted expansion, apart from a medieval circular-plan oven. citeturn0search23

Drujești was strengthened through the 1990 Cristocea archaeological study and later specialist cross-reference. citeturn1search0turn1search50

Bătușari/Brad-Botușari entered the heritage reconciliation queue, but was deliberately not promoted into the archaeological inventory without stronger archaeological/register evidence. citeturn1search1

Methodology update: completeness now includes **tested-but-negative areas**, not only discoveries.

Stage 1 remains OPEN — NOT COMPLETE.

## Archaeology autopilot — Pass 20 · 22 September 2026

Pass 20 performed a targeted LMI ↔ RAN reconciliation.

Important correction: the Olari ensemble is independently confirmed in the LMI as AG-II-a-A-13639, with subcomponents 13639.01, 13639.02 and 13639.03. A secondary article claims RAN 13631.09, but current targeted RAN searches did not independently retrieve an official 13631.09 record. The project therefore keeps 13631.09 as CANDIDATE / DISCREPANCY rather than promoting it. citeturn1search4turn1search13turn2search0

The current RAN Sân Nicoară record also directly confirms an 1886 discovery entry and 2009–2011 preventive archaeological research. citeturn1search1turn1search7

Methodology strengthened: LMI identity, RAN identity, intervention identity and publication identity must be separately evidenced before being linked.

Stage 1 remains OPEN — NOT COMPLETE.

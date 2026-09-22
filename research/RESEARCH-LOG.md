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

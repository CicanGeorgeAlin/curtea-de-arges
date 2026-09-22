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

## Archaeology autopilot — Pass 21 · 22 September 2026

The historic urban site RAN 13631.11 was promoted to a **spatial master/reference layer**, because its current record defines a large protected perimeter including streets, cemeteries, the railway/station area and the central historic core. Its archaeological chronology is broadly 13th–19th century. citeturn0search2

New safeguard: the protected perimeter is not being interpreted as proof of archaeology on every parcel.

The RAN interface was also re-audited for completeness. Municipality-level results are filtered/paginated, so the current five-record working inventory remains provisional until an explicit municipality-scoped result set is captured and reconciled. citeturn0search7turn0search10

Stage 1 remains OPEN — NOT COMPLETE.

## Archaeology autopilot — Pass 22 · 22 September 2026

Pass 22 revealed a major scope distinction: the 2015 LMI heritage inventory for Curtea de Argeș is substantially broader than the current RAN archaeological subset. The official LMI includes numerous protected 19th–20th-century buildings and ensembles. citeturn0search20turn0search21

The archive therefore now separates heritage inventory from archaeology inventory instead of trying to force every monument into an archaeological category.

A separate memorial/public-art layer was also identified through CIMEC records for the WWI heroes' cemetery, a 1937 WWI memorial plaque and the Soviet soldiers' cemetery/monument. citeturn0search1turn0search4turn0search6

This expands the future archive architecture while preserving source discipline.

Stage 1 remains OPEN — NOT COMPLETE.

## Archaeology autopilot — Pass 23 · 22 September 2026

Pass 23 strengthened component-level modelling. The official LMI 2015 breaks the Princely Court ensemble AG-II-a-A-13647 into multiple protected structures and phases, so the archive will preserve ensemble/component relationships instead of treating the court as one object. citeturn0search16

A 2026 county territorial strategy provides an important methodological warning: many RAN sites nationally lack precise location and some are not represented in LMI. This is recorded as national heritage-management context, not as a Curtea de Argeș-specific statistic. citeturn0search18

New future-map field: location confidence = EXACT / PERIMETER / APPROXIMATE / HISTORICAL ONLY / UNRESOLVED.

Stage 1 remains OPEN — NOT COMPLETE.

## Archaeology autopilot — Pass 24 · 22 September 2026

Pass 24 formalized a municipality-scoped RAN extraction as the next research task. The current RAN interface is criterion-based and paginated, so generic search pages cannot establish completeness. citeturn0search7turn0search8

The municipal historical study provides an independent municipality-specific 2015 LMI table, creating a useful heritage baseline. citeturn0search33

Curtea Domnească was reconciled at component level: LMI AG-II-a-A-13647 / church AG-II-m-A-13647.01 versus RAN 13631.07. The differing source descriptions are preserved as parallel claims rather than silently merged. citeturn0search0turn0search2

Stage 1 remains OPEN — NOT COMPLETE.

## Archaeology / Heritage autopilot — Pass 25 · 22 September 2026

A major milestone was reached: the 2015 LMI Curtea de Argeș block was explicitly captured as a municipality-specific baseline, covering records 444–505. It includes the railway station, Argeș Monastery, Seminarul Teologic, historic houses, Olari, the historic urban site, hospital ensemble, Princely Court and components, Drujești, Sân Nicoară, further protected buildings/churches and Brad-Bătușari. citeturn0search6turn0search1

This changes the next phase from discovery-by-search to **systematic reconciliation**.

The project now has a concrete heritage baseline against which RAN, archaeological campaigns, publications, finds, spatial evidence and current status can be checked record-by-record.

Stage 1 remains OPEN — NOT COMPLETE.

## Archaeology / Heritage autopilot — Pass 26 · 22 September 2026

The current municipality-filtered RAN result set has now been captured: five Curtea de Argeș records — 13631.02 Drujești, 13631.05 Sân Nicoară, 13631.07 Curtea Domnească, 13631.10 Argeș Monastery and 13631.11 Historic Urban Site. citeturn0search3turn0search5

This resolves the earlier uncertainty about the current RAN municipality baseline, but not archaeological completeness beyond RAN.

A component discrepancy was identified at Argeș Monastery: LMI 13628 includes a park and relocated wooden church in addition to the church, chapel and episcopal palace represented on the current RAN page. citeturn0search4turn0search13

Next: systematic record-by-record reconciliation of the five RAN records against every relevant LMI component, intervention and publication.

Stage 1 remains OPEN — NOT COMPLETE.

## Archaeology / Heritage autopilot — Pass 27 · 22 September 2026

Deep record-by-record reconciliation began with Drujești and Sân Nicoară.

Drujești RAN 13631.02 directly records systematic archaeological research in 1987 by Spiridon Cristocea and separates church and necropolis chronologies. citeturn0search0

Sân Nicoară RAN 13631.05 was cross-checked against the primary 2011 campaign report, which adds spatial/contextual evidence. citeturn0search2turn0search20

The LMI reveals a further Sân Nicoară component, the Heroes' Cross 1916–1918, demonstrating that one place can contain archaeological, landscape and memorial layers. citeturn0search23

New modelling rule: PLACE → COMPONENT → PERIOD → FUNCTION → EVIDENCE.

Stage 1 remains OPEN — NOT COMPLETE.

## Archaeology / Heritage autopilot — Pass 28 · 22 September 2026

Deep audit continued with Curtea Domnească and Argeș Monastery.

RAN 13631.07 confirms a multi-component Princely Court site and contains an internal chronology nuance: narrative completion of the Domnească Church in 1352 versus component dating 1351–1370. Both are preserved as source claims. citeturn0search0turn0search8

RAN 13631.10 confirms Argeș Monastery components church 1512–1517, chapel 1885 and episcopal palace 1885. citeturn0search1turn0search2

Next: archaeological/restoration publication reconciliation for these two major complexes.

Stage 1 remains OPEN — NOT COMPLETE.

## Archaeology / Heritage autopilot — Pass 29 · 22 September 2026

Curtea Domnească research was deepened through a specialist 2016 reassessment of the 1920–1922 excavations and the 1967 restart. The 1920–1922 excavation journal records stove tiles from the princely-house basement, but their exact spatial grouping remains uncertain. The 1967 research identified earlier church foundations and clarified construction phases and plans. citeturn0search22

Constantinescu's 1984 monograph was rechecked for scope: it explicitly concerns the 1967–1973 archaeological research of the voivodal core within the modern city, not the whole modern city. citeturn0search4

Methodological result: Curtea Domnească now has a documented intervention chain beginning at least with 1920–1922, followed by 1967–1973 and later specialist reassessment.

Stage 1 remains OPEN — NOT COMPLETE.


## Archaeology / Heritage autopilot — Pass 30 · 22 September 2026

Pass 30 targeted the two major complexes whose intervention histories remained incomplete: **Curtea Domnească** and **Argeș Monastery**.

Fresh specialist/primary evidence established:

- a 1968 continuation of Curtea Domnească excavation with coin-supported chronology;
- a 13th-century occupation level preceding the first enclosure/14th-century princely-house phase in the 1968 campaign report;
- an early-16th-century north-side residence associated in the report with Neagoe Basarab;
- a discrete September 1965 archaeological intervention beside the Argeș Monastery church, limited to two small sections and affected by prior restoration disturbance.

The archive now treats these as **intervention-level evidence**, not merely as monument descriptions. The research architecture was strengthened to preserve the sequence:

**SITE REGISTER → INTERVENTION → CONTEXT → FIND → DATING → INTERPRETATION → LATER REASSESSMENT**

This pass also confirms that the current five-record RAN municipal baseline cannot stand in for the full intervention history.

### Gap analysis after Pass 30

**Curtea Domnească**
- intervention chain: materially stronger;
- 1968 coin evidence: newly controlled;
- excavation-plan/find-inventory reconstruction: still incomplete;
- 1920–1922 evidence: requires continued context-level reconciliation;
- later archaeological publications: still to be mapped systematically.

**Argeș Monastery**
- 1965 archaeological sondages: now verified;
- full precinct intervention history: incomplete;
- restoration archaeology and later investigations: incomplete;
- LMI component reconciliation: still open.

**Decision:** Archaeological Stage 1 remains **OPEN — NOT COMPLETE**.

Next research priority: reconstruct the **1967–1973 Curtea Domnească excavation plan + context/find matrix**, while simultaneously expanding the Argeș Monastery intervention chain beyond the 1965 sondages.


## Archaeology / Heritage autopilot — Pass 31 · 22 September 2026

Pass 31 moved from chronology toward **spatial archaeological reconstruction**.

A later specialist volume by Nicolae Constantinescu (2013) was located in the Digital Library of Romania and cross-checked against the earlier 1967 campaign publication. The volume contains a published plan of the 1967–1969 Curtea Domnească excavations, a 1969 excavation plan for the Domnească Church, and stratigraphic profiles from 1968 sections. citeturn1search23turn1search0

This adds an important bridge toward the future historical map: the archive can now distinguish archaeological campaign areas, sections, stratigraphic levels, structures and finds instead of treating the entire Princely Court as one undifferentiated archaeological object.

The same synthesis records later microzone evidence, including iron-working slag, a pottery kiln and pottery-making tools. These are retained as separate later research contexts and are not back-projected into the 1967–1969 campaign.

### Method upgrade

New archaeological spatial model:

**CAMPAIGN → SECTION / SURFACE → STRATIGRAPHIC LEVEL → STRUCTURE → FIND → INTERPRETATION**

### Gap analysis

Still missing:
- complete context-by-context excavation register;
- original field notebooks;
- complete find inventories;
- complete campaign drawings;
- systematic reconciliation of every published plan against the original 1967–1973 campaign chronology.

**Decision: Archaeological Stage 1 remains OPEN — NOT COMPLETE.**


## Archaeology / Heritage autopilot — Pass 32 · 22 September 2026

Pass 32 deliberately moved one step outside the monument itself.

A published archaeological profile from the 1983 EMV research was identified in Constantinescu's later synthesis. The excavated microzone included a 45 m × 2 m section and a second 25 m × 2 m section. The EMV-I profile records four successive habitation levels of the 13th–14th centuries up to about 1340, followed by later occupation beginning in the second half of the 14th century. It also records a 14th-century iron-working layer and a pottery kiln. citeturn0search0

### Research architecture correction

The project now explicitly separates:

**PRINCELY COURT CORE**  
from  
**SURROUNDING VOIVODAL MICROZONES**

This prevents the common historical-archaeological error of projecting one excavated monument's stratigraphy across an entire city.

New spatial rule:

**OBSERVATION → EXCAVATED LOCATION → STRATIGRAPHIC CONTEXT → LOCAL INTERPRETATION → POSSIBLE WIDER CORRELATION**

### Gap analysis

Still needed:
- identify all published EMV sections and their exact spatial relationship;
- reconcile the 1983 microzone with the historic urban RAN perimeter;
- identify other medieval habitation/craft zones;
- distinguish settlement evidence from princely-residence evidence;
- continue searching for original campaign documentation.

**Decision: Archaeological Stage 1 remains OPEN — NOT COMPLETE.**


## Archaeology / Heritage autopilot — Pass 33 · 22 September 2026

Pass 33 strengthened the EMV (extra muros-vest) microzone record.

A published 2003 account of the 1983–1984 rescue excavations places the work immediately west of the former Princely Court, along the former Râului/L. Catargiu street, and documents the archaeological-risk context created by a construction project. The authors report a 13th–14th-century habitation level, construction-related traces interpreted in relation to Basarab I's enclosure around c. 1340, and a pottery kiln (COL 1) attributed by them to the time of Mircea cel Bătrân. citeturn0search16turn0search17

### Methodological result

The archive now treats **EMV as its own archaeological microzone**, rather than as an undifferentiated extension of Curtea Domnească.

A second source lead was confirmed: Adrian and Lia Bătrîna's 1982 *Cercetări Arheologice* article on Curtea de Argeș. Because only bibliographic confirmation was obtained in this pass, its detailed contents remain **UNEXTRACTED / SOURCE LEAD** until directly inspected. citeturn0search2turn0search3

### Gap analysis

Next targets:
- extract the complete 1983–1984 EMV campaign sequence;
- locate the original/complete 1982 Bătrîna & Bătrîna article;
- map EMV sections and finds;
- reconcile EMV with the historic urban perimeter without assuming equivalence;
- identify additional medieval settlement/craft microzones.

**Decision: Archaeological Stage 1 remains OPEN — NOT COMPLETE.**


## Archaeology / Heritage autopilot — Pass 34 · 22 September 2026

Pass 34 completed an important source-control correction.

The Bătrîna & Bătrîna 1982 article is now treated as a **primary specialist archaeological publication**, rather than merely a bibliographic lead. It records continuation of investigations begun in 1979 and gives direct evidence for a tested area west of Sân Nicoară hill. citeturn0search31

The result is particularly valuable because it includes **negative archaeological evidence**: no material culture or complexes justified expanding research in the two investigated east–west sections, while a partially preserved circular-plan medieval oven was recorded.

The 1981 article is now linked as the preceding publication for the 1979 research programme. citeturn0search7

### Method upgrade

The archive now records settlement investigations using:

**CAMPAIGN → TEST AREA → RESULT → POSITIVE / NEGATIVE → INTERPRETATION**

Negative results are retained, but only within their tested spatial boundaries.

### Gap analysis

Next:
- extract the 1979 article;
- identify all 1979–1980 test areas;
- map their relationship to Sân Nicoară, Curtea Domnească and EMV;
- search for additional settlement archaeology publications;
- preserve all negative observations.

**Decision: Archaeological Stage 1 remains OPEN — NOT COMPLETE.**


## Archaeology / Heritage autopilot — Pass 35 · 22 September 2026

Pass 35 moved the 1979 Bătrîna & Bătrîna programme from “article exists” to **page-controlled archaeological evidence**, while preserving the remaining spatial uncertainty. The national archaeological journal index confirms the 1979 research article and its 144–171 pagination. citeturn0search0turn0search1

Later specialist synthesis cites the 1981 article, pp. 144–150, for a sunken habitation structure dated to the end of the 13th century, and pp. 151–153 for a mid-14th-century surface timber house supported above a stone socle. citeturn9search23 A specialist catalogue also cites pp. 166–167 for stove-tile evidence from a townspeople's dwelling. citeturn4search30

These are now controlled leads/evidence records, but the exact modern spatial positions are **not** promoted until the original 1979 plans and figures are inspected.

The 1980 campaign remains separate: the 1982 publication records a distinct area west of Sân Nicoară hill with two east–west sections, negative results for expansion, and one partially preserved medieval circular-plan oven. citeturn2search40

### Method upgrade

The settlement archaeology matrix now uses:

**CAMPAIGN → TEST AREA → PUBLISHED STRUCTURE/FIND → CHRONOLOGY → SOURCE PAGE → LOCATION CONFIDENCE**

This prevents a page-level archaeological discovery from being turned into a false map point.

### Gap analysis after Pass 35

Still required:
- original 1979 excavation plans/figures;
- exact sector-by-sector spatial reconstruction;
- reconciliation of 1979 structures with 1980 test areas;
- comparison with EMV and Sân Nicoară without assuming continuity;
- broader search for later publications reusing the 1979 domestic evidence.

**Decision: Archaeological Stage 1 remains OPEN — NOT COMPLETE.**


### Pass 35 addendum — find-level evidence

A specialist numismatic index was cross-checked and revealed that **dwelling 4**, excavated in Curtea de Argeș in 1979, produced a **double lead seal** bearing a fleur-de-lis emblem and the legend “+ DE TOURNAI”. The index directs the reader to the detailed publication in *Cercetări Numismatice* V. citeturn11search23

Methodological consequence: the 1979 campaign must eventually be reconstructed at **structure → find** level, not only as a settlement-chronology exercise. Attribution and interpretation of the seal remain open until the dedicated publication is inspected.


## Archaeology / Heritage autopilot — Pass 36 · 22 September 2026

Pass 36 formalized the campaign split between the 1979 and 1980 Bătrîna research programmes. The 1981 and 1982 publications are independently catalogued for Curtea de Argeș, and the 1982 article directly describes the 1980 work west of Sân Nicoară hill. citeturn2view0turn0search23

The archive now treats the evidence as separate spatial records rather than one excavation. A contemporary 1980 review confirms that the Bătrîna excavations contributed evidence for changes in urban dwelling forms from the end of the 13th century into the later 14th century, while the original publications remain the controlling sources for detailed claims. citeturn0search27

### Gap analysis after Pass 36

- 1979 original plan/figures: still required;
- dwelling-by-dwelling spatial reconstruction: still required;
- exact relationship between 1979 sectors and the 1980 west-Sân-Nicoară test area: unresolved;
- 1979 seal publication: identified, but detailed context still to be extracted;
- EMV remains a separate 1983–1984 microzone.

**Decision: Archaeological Stage 1 remains OPEN — NOT COMPLETE.**


## Archaeology / Heritage autopilot — Pass 37 · 22 September 2026

Pass 37 closed the bibliographic loop around the unusual dwelling-4 seal. ProEuropeana identifies the dedicated 1983 Bătrîna & Bătrîna study of a 15th-century trade seal discovered at Curtea de Argeș, *Cercetări Numismatice*, V, pp. 197–211. citeturn0search1

The archive now separates the find from the later interpretation: the seal is a 1979 dwelling-4 find; “15th-century trade seal” is the classification in the 1983 publication title; detailed dating, inscription and commercial interpretation remain to be extracted from that primary study.

### Gap analysis after Pass 37

- 1983 seal article identified: **YES**;
- 1983 article detailed extraction: **OPEN**;
- 1979 original excavation plan: **OPEN**;
- dwelling-by-dwelling spatial reconstruction: **OPEN**;
- exact relationship between 1979 sectors, 1980 tests and EMV: **OPEN**.

**Decision: Archaeological Stage 1 remains OPEN — NOT COMPLETE.**


## Archaeology / Heritage autopilot — Pass 38 · 22 September 2026

Pass 38 recovered a stronger primary-source description for the unusual 1979 Curtea de Argeș trade seal. The National Museum of Romanian History's *Cercetări Numismatice* record and the Digital Library of Romania both identify the dedicated Bătrîna & Bătrîna article in volume V (1983), pp. 197–211. citeturn0search0turn0search1

The accessible abstract adds controlled detail: the seal was found in a 1979 archaeological excavation, in an urban-type dwelling dated by the article to the end of the 14th/beginning of the 15th century; it is identified as a cloth trade seal from Tournai; and the heraldic signs are said to date it after 1426. The authors interpret the object as evidence of economic relations between Wallachia and major western European textile centres in the first half of the 15th century. citeturn0search0

### Self-correction

The archive will **not** collapse these statements into a single date. The dwelling's archaeological dating and the seal's post-1426 dating are now separate evidence fields. The difference is potentially meaningful and must be investigated through the full article and original excavation context.

The source register has been upgraded from “article identified” to **abstract-level extracted evidence**, while the full article remains **UNEXTRACTED**.

### Gap analysis after Pass 38

- 1983 seal article bibliographic control: **YES**
- 1983 seal article abstract-level extraction: **YES**
- full article text / dimensions / heraldic details / exact layer: **OPEN**
- 1979 original excavation plan: **OPEN**
- dwelling-by-dwelling spatial reconstruction: **OPEN**
- exact relationship between 1979 sectors, 1980 tests and EMV: **OPEN**

**Decision: Archaeological Stage 1 remains OPEN — NOT COMPLETE.**


## Archaeology / Heritage autopilot — Pass 39 · 22 September 2026

Pass 39 recovered the actual searchable PDF for the 1983 Curtea de Argeș trade-seal study and strengthened the evidence chain from bibliography to object-level description. citeturn2search28

The cumulative index confirms that the 1979 excavation of dwelling 4 produced a double lead seal: two round lead plates joined at two points, carrying a fleur-de-lis emblem and the legend “+ DE TOURNAI” on both faces. citeturn5search25

The article abstract separately identifies the object as a Tournai cloth trade seal and dates it after 1426 on heraldic grounds. citeturn2search0

A later 2010 Curtea de Argeș synthesis describes the associated structure as a burned merchant-type house and the seal as a luxury-cloth seal from Tournai. This is retained as later interpretation, not silently promoted to primary evidence. citeturn5search26

### Self-correction

The archive now distinguishes:
- **find description** — directly indexed;
- **object classification** — Tournai cloth trade seal;
- **object dating** — after 1426 according to the article;
- **building interpretation** — merchant-type house in a later synthesis;
- **spatial context** — still unresolved until the original 1979 plan is reconstructed.

**Decision: Archaeological Stage 1 remains OPEN — NOT COMPLETE.**


### Pass 40 · 22 September 2026 · figure-recovery control

Research located an authoritative journal index entry for the 1979 Curtea de Argeș settlement report and a later specialist bibliography that cites p.166, fig.14/3 of that report and p.103, pl.VII of the 1982 continuation. citeturn0search0turn0search25

The figures are now explicit retrieval targets. Because the underlying PDFs were not reliably exposed by the current web text interface, their contents are not inferred. This preserves the archive's rule: a bibliographic lead is not promoted to archaeological fact until the underlying figure/page is inspected.

**Stage 1 remains OPEN — exact dwelling-4 spatial context not yet established.**


### Pass 41 · 22 September 2026 · self-correction: figure 14

A new cross-check showed that later specialist literature cites the 1979 report's pp.166–167, fig.14 specifically in the context of ceramic stove/heating evidence in townspeople's dwellings. citeturn5search17turn5search0

The earlier Pass 40 assumption that this figure was a direct lead to dwelling 4 and the Tournai seal was therefore too broad and has been corrected. The archive now keeps the figure reference as a separate urban-dwelling/heating lead.

The Tournai seal's association with a 1979 urban-type dwelling remains supported by the 1983 specialist article, but its exact spatial relationship to the figure-14 material is **not established**. citeturn0search0

**Stage 1 remains OPEN.**


### Pass 42 · 22 September 2026 · direct primary-text extraction

The original 1983 trade-seal article yielded a stronger dating argument than its abstract alone: the authors connect the fleur-de-lis to Tournai's heraldic/sphragistic changes of 1426, date the Curtea de Argeș seal after 1426, and suggest an initial matrix series immediately after 1426, possibly in 1426. citeturn0search35

They also hypothesize that the opposing shield may be a corporate emblem of Tournai weavers/cloth-makers. This is recorded as hypothesis, not fact. citeturn0search35

**Stage 1 remains OPEN.**


### Pass 43 · 22 September 2026 · heraldic dating mechanism

The 1983 article's searchable text now provides the specific heraldic basis for the dating argument: a parted/counter-fasciated shield and a fleur-de-lis within a quatrefoil occur on the trade seals discussed; the fleur-de-lis is connected by the authors to Tournai's heraldic development, including the city's 1426 privilege to add a French royal chief. citeturn1search13

This is recorded as the authors' dating method. The archive does not merge the seal date with the archaeological date of the dwelling.

**Stage 1 remains OPEN.**


### Pass 44 · 22 September 2026 · independent dating cross-check

A 2018 specialist article independently calls the Curtea de Argeș object a Tournai lead cloth seal dated around 1426. citeturn1search25 The 1983 Bătrîna & Bătrîna article argues for post-1426 dating and suggests a first matrix series immediately after 1426, potentially in 1426. citeturn1search26

The 2008 cumulative index independently confirms the 1979 dwelling-4 association and physical description. citeturn2search32

The archive now preserves the dating formulations separately rather than forcing a false single-year consensus.

**Stage 1 remains OPEN.**


### Pass 45 · 22 September 2026 · publication-chain and chronology control

Cross-checking the official journal indexes confirms the sequence: 1979 fieldwork → 1981 publication; 1980 continuation → 1982 publication; dedicated seal study → 1983 publication. citeturn0search0turn0search5

The 1983 abstract explicitly says the seal was found in the 1979 excavations in an urban-type dwelling dated to the end of the 14th/beginning of the 15th century. citeturn0search1

The archive keeps this dwelling chronology separate from the seal's heraldic dating.

**Stage 1 remains OPEN.**


### Pass 46 · 22 September 2026 · L4 primary-context upgrade

Direct inspection of the 1983 article produced a stronger result: the authors explicitly identify **L4** when discussing the burned remains of the dwelling discovered in the 1979 excavations and argue that the cloth merchant associated with the seal was probably the owner of L4. citeturn0search20

The archive now separates this into three levels: burned L4 = primary textual evidence; merchant-owner identification = authorial interpretation; named merchant identity = not established.

This is the first controlled upgrade from generic “urban-type dwelling” to the publication's own dwelling identifier **L4**.

**Stage 1 remains OPEN.**


### Pass 47 · 22 September 2026 · L4 independent architectural cross-check

A later specialist synthesis provides a new controlled clue: Curtea de Argeș L4 is described as a semi-sunken dwelling with a gârlici-type entrance and is dated by ordinary pottery to the first half of the 15th century. citeturn0search32

The source cites the 1979 report p.166, fig.14/3 and 1982 p.103, pl.VII, but the archive does not yet claim that these figures have been directly inspected. The earlier Pass 41 correction remains in force: bibliographic citation alone does not establish the figure's exact content.

The dwelling chronology is now recorded as overlapping source formulations rather than a forced single date.

**Stage 1 remains OPEN.**


### Pass 48 · 22 September 2026 · L4 typology independent confirmation

A specialist archaeological catalogue independently confirms L4 as a semi-sunken dwelling with a gârlici entrance, dated by ordinary pottery to the first half of the 15th century; its stove-tile evidence is also placed in that period. citeturn0search24

A separate 2010 Curtea de Argeș synthesis describes the merchant-house type and the Tournai seal in calcined ruins, but the archive keeps this broader synthesis separate from the exact L4 identification until the original plan/context is directly controlled. citeturn0search25

**Stage 1 remains OPEN.**


### Pass 49 · 22 September 2026 · urban sampling strategy

The original 1979 report's opening methodology confirms that excavation sections were deliberately placed in vacant plots aligned with streets, under the hypothesis that portions of the modern street grid preserved the medieval one. Four dwellings were identified in the campaign, two completely and two partially. citeturn0search24

This is now recorded as contextual methodology for L4. A 1992 synthesis independently uses the 1979 publication in discussing the development of medieval urban housing at Curtea de Argeș. citeturn0search28

**Stage 1 remains OPEN.**


### Pass 50 · 22 September 2026 · source separation for L4 reconstruction

The official journal index confirms the dedicated 1979 excavation report and separate 1982 continuation. citeturn0search0turn0search6 The MNIR numismatic record independently confirms the Tournai seal's 1979 urban-dwelling context and the 1983 dating formulation. citeturn0search8

The archive now explicitly separates source roles before spatial reconstruction: excavation reports for L4 architecture/context; numismatic study for seal identification/dating/interpretation.

**Stage 1 remains OPEN.**


### Pass 51 · 22 September 2026 · tile evidence cross-check

A 2013 specialist article reproduces a Curtea de Argeș stove-tile fragment dated 14th–15th century and cites Bătrîna & Bătrîna 1982, plate I/2. citeturn0search28 A specialist catalogue separately cites the 1979 report's p.166 fig.14/3 and the 1982 report's p.103 pl.VII. citeturn0search26

These references strengthen the broader medieval urban-heating evidence but do not establish a direct L4/seal identification for the figures.

**Stage 1 remains OPEN.**


### Pass 52 · 22 September 2026 · primary-report recovery

The original 1979 report is directly accessible and confirms the campaign's settlement-scale design and dwelling-by-dwelling structure. citeturn0search19

The report's opening pages expose detailed evidence for L1, showing that the authors document individual dwellings stratigraphically. This reinforces the rule that L4 should be reconstructed from its own original pages rather than inferred from later summaries.

**Stage 1 remains OPEN.**


### Pass 53 · 22 September 2026 · seal function and ownership inference

The original 1983 text states that the Curtea de Argeș seal type was suited to sealing large bales/rolls of Tournai cloth and uses comparative evidence to distinguish it from seals for smaller cloth pieces. citeturn0search35

The authors then infer a high-value textile purchase by a major Argeș merchant and propose that this merchant was probably the owner of burned L4. This remains an authorial hypothesis, not a named historical identification. citeturn0search35

**Stage 1 remains OPEN.**


### Pass 54 · 22 September 2026 · primary-report access limitation

The 1979 excavation PDF was rechecked, but the current web text interface did not expose searchable page-level L4 text. citeturn0search21

No unsupported L4 plan/dimension/stratigraphy claims were added. This pass therefore strengthens the archive's evidence-control record rather than expanding the historical claim set.

**Stage 1 remains OPEN.**


### Pass 55 · 22 September 2026 · critical self-correction

A source audit discovered that the supposed independent confirmation of Curtea de Argeș L4 in Passes 47–48 was actually a passage about **Săbăoani L4**. The Curtea de Argeș material appears only in its bibliography/footnote as comparative stove-tile evidence. citeturn1search22

The archive therefore withdraws the earlier secondary claim that this catalogue independently described Curtea L4 as semi-sunken/gârlici and dated it to the first half of the 15th century.

The controlled evidence remains the 1983 primary seal study, which explicitly identifies the burned L4 at Curtea de Argeș. citeturn1search21

This correction is intentionally preserved in the research history rather than silently deleting the earlier mistake.

**Stage 1 remains OPEN.**


### Pass 56 · 22 September 2026 · page-level retrieval upgrade

The 1983 seal article's notes identify **1979 report p.144 and p.153** as direct references in the L4 discussion. citeturn0search35

The archive therefore promotes p.153 to the primary retrieval target for L4 context. The older p.166/fig.14 trail remains a comparative stove-tile lead and is not treated as an L4 plan reference. citeturn0search36

**Stage 1 remains OPEN.**


## Archaeology / Heritage autopilot — Pass 57 · 22 September 2026 · p.153 retrieval control

Pass 57 followed the strongest page-level lead from Pass 56. The 1983 Bătrîna & Bătrîna trade-seal article explicitly cites the 1979 settlement report at **pp.144 and 153** in its discussion of the burned dwelling L4. citeturn4search41

A fresh search recovered the official Digital Library copy of the 1979 article, *Cercetări Arheologice*, IV (1981), pp.144–171. The indexed record confirms the article and exposes its opening campaign description, but the current web interface did not expose the actual text of p.153. citeturn1search4turn1search1

### Self-correction / evidence control

No archaeological detail from p.153 has been invented or reconstructed from the 1983 footnote. In particular, the archive does **not** add L4 dimensions, plan, entrance type, stratigraphy, pottery inventory or exact spatial position.

The controlled L4 evidence remains:
- burned remains of L4 discovered in the 1979 research — stated in the 1983 primary study;
- Tournai cloth-trade seal associated with the 1979 urban dwelling/L4 discussion — stated in the 1983 primary study;
- proposed merchant ownership of L4 — authorial inference, not a named identification. citeturn5search33

### Gap analysis after Pass 57

Next retrieval target:
1. obtain an independently readable scan/OCR of **1979 report p.153**;
2. extract only the text actually present on that page;
3. compare it with the 1983 seal article's references;
4. only then promote any L4 architectural/stratigraphic details into the structured archaeological record.

**Decision: Archaeological Stage 1 remains OPEN — NOT COMPLETE.**


## Archaeology / Heritage autopilot — Pass 58 · 22 September 2026 · official journal retrieval route

Pass 58 found a new first-party retrieval route for the original 1979 excavation report. The current website of the journal *Cercetări Arheologice*, published by the Muzeul Național de Istorie a României, has a dedicated article record for Lia Bătrîna and Adrian Bătrîna, “Cercetări arheologice efectuate în anul 1979 în cuprinsul aşezării Curtea de Argeş, jud. Argeş,” *Cercetări Arheologice*, IV (1981), pp. 144–171. The article page provides a direct PDF link. citeturn11view0turn10view0

The journal's article page confirms that this is the original 1979 Curtea de Argeș report and not a secondary bibliography entry. citeturn11view0 The linked PDF is hosted by the journal itself, at a dedicated upload path. The current web interface, however, presents a verification page instead of exposing the PDF text, so **page 153 remains unresolved**. citeturn12view0

### Evidence-control decision

No new L4 archaeological facts are promoted from page 153.

The controlled chain therefore remains:
- 1979 report: primary excavation publication identified and directly routed, but p.153 text not yet readable;
- 1983 seal study: explicitly links the Tournai-seal discussion to burned dwelling **L4** and cites the 1979 report at pp.144 and 153;
- merchant ownership of L4: remains the 1983 authors' interpretation, not a demonstrated personal identification. citeturn7search41

### Retrieval target

**1979 report → p.153 → actual scan/OCR → L4 structure/context → cross-check with 1983 seal study.**

**Archaeological Stage 1 remains OPEN — NOT COMPLETE.**

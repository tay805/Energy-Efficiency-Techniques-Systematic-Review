# Supplementary Material S1: Protocol for a Systematic Literature Review of Energy Efficiency Techniques in IoT and Wireless Sensor Networks: Taxonomy, Trends and Research Gaps

## Registration

This protocol shall be registered with Zenodo.
The Zenodo DOI: 10.5281/zenodo.23194471 - Latest release

## Authors

Tawseef Ahmed Teli (corresponding author), Computer Applications, Higher Education Department, Srinagar, 190001, Jammu and Kashmir, India, tawseefahtel.8991@jk.gov.in. Aqib Javid Bhat, Mohd Numan Asgar, Danish Ellahi, Ubaid Mushtaq Mir, and Wasiq Tariq, Department of Computer Applications, Govt Degree College Anantnag, Khanabal, Anantnag, 192101, Jammu and Kashmir, India.

## Contributions

All six authors contribute equally to the conception and development of the review protocol and to the conduct and reporting of the systematic literature review. Tawseef Ahmed Teli, as corresponding author, is the guarantor of the review.

## Repository

https://github.com/tay805/Energy-Efficiency-Techniques-Systematic-Review

## Support

No financial or other support is received for this review. No sponsor or funder has any role in the design, conduct, or reporting of the review.

## Protocol Amendments

1. Updated search strings from 24 to 28 to include classic WSN energy-efficiency terms such as "network lifetime", "duty cycling", "MAC protocol", "routing protocol", "sleep scheduling", "energy harvesting WSN", "sensor node", "mote", "green WSN", "LPWAN", and "environmental monitoring".

2. The date window for the survey was expanded to January 2014 to July 2026 from 2014 to 2025.

3. Sensitivity analysis for composite ranking was updated to have an unbiased and proper methodology for ranking the works. 

4. Spearman Rank Correlations Between the Baseline and Alternative Weighing Scenarios to report the effect of various weighing scenarios on the final ranking.

## Rationale

Energy efficiency research for IoT and WSN edge devices spans hardware design, algorithmic scheduling, protocol adaptation, and energy harvesting, but no existing synthesis covers this full range while also identifying where the field's coverage remains structurally thin, for instance, security is treated as a separate concern from energy almost everywhere it appears, and work on hardware or energy-harvesting layers is comparatively rare relative to computation-layer offloading work. This review is designed to produce that synthesis and to make the resulting gaps explicit rather than incidental.

## Objectives

Standard PICO framing (population, intervention, comparator, outcome) does not map cleanly onto a technical/engineering literature of this kind, so this review adapts it as follows:

- Population: primary research studies addressing edge devices operating in IoT or WSN environments.

- Intervention/exposure: techniques, strategies, or mechanisms proposed for improving energy efficiency at the edge device level (routing protocols, offloading strategies, hardware/architectural design, energy harvesting).

- Comparator: not uniformly applicable across the corpus, given the methodological heterogeneity of included studies (simulation-based evaluation, hardware prototyping, analytical modelling); where reported, baseline or default-configuration comparisons within each study are captured in the extraction form rather than imposed as a review-wide comparator.

- Outcomes: reported energy consumption, network lifetime, or related efficiency metrics, alongside the eight research questions (RQ1–RQ8) listed below, which structure the review's synthesis beyond a single outcome metric.

## Research Questions

RQ1. How do reviewed studies characterize and classify edge devices within IoT and WSN architectures?

RQ2. What taxonomy of edge device types emerges from the reviewed literature?

RQ3. What types of data do edge devices generate, and how does data type shape transmission and compression requirements?

RQ4. What communication architectures, topologies, and routing strategies are reported for transmitting data from edge devices?

RQ5. Which communication protocols and packet/payload configurations are used, and how do these relate to transmission energy overhead?

RQ6. What parameters and metrics do reviewed studies use to characterize energy consumption?

RQ7. What strategies are proposed to reduce energy consumption, and how do they differ in mechanism and reported impact?

RQ8. How is security and privacy addressed in energy-efficient edge device designs?

## Eligibility Criteria

### Inclusion Criteria

- IC1. Include studies that address edge devices operating within IoT or WSN environments.

- IC2. Include studies that analyze or optimize energy consumption specifically at the edge device level.

- IC3. Include studies that propose, implement, or evaluate a technique or strategy for improving energy efficiency.

- IC4. Include studies that involve a routing protocol designed to enhance energy efficiency.

- IC5. Include studies that introduce a mechanism for extending network lifespan through energy-efficient operation.

### Exclusion Criteria

- EC1. Exclude studies published before January 2014 or after July 2026.

- EC2. Exclude studies published in sources that were not indexed in Scopus or Web of Science (SCIE).

- EC3. Exclude survey or review articles on IoT/WSN energy efficiency, as opposed to primary research contributions. (Excluded surveys or reviews shall be retained and examined separately to position the review’s novelty)

- EC4. Exclude books, book chapters, government reports, policy documents, newsletters, speeches, technical blog posts, letters, short communications, and other grey-literature or non-primary publication types that do not constitute eligible primary research publications.

- EC5. Exclude studies that do not explicitly address edge devices in IoT or WSN contexts.

- EC6. Exclude studies that do not analyze, model, or optimize energy consumption at the edge device level.

## Report Characteristics

- Publication window: January 2014 - July 2026.

- Venue quality: only studies published in SCIE-indexed (Web of Science Core Collection) or Scopus-indexed venues, verified against the Clarivate Master Journal List, the Scopus Source List, Scopus indexed conferences and SJR quartile data, were retained.

- Publication status: peer-reviewed journal and conference literature only; no grey literature.

- Scope boundary: consumer and environmental IoT applications; industrial IoT (IIoT) terminology shall be deliberately excluded from the search strategy as outside the review's defined scope.

- Language: English

## Information Sources

Google Scholar will be used as the sole primary search engine, selected for its cross-publisher coverage, with results subsequently filtered by venue-indexing status as above. Candidate records will be subsequently classified according to their digital library source: IEEE Xplore, ScienceDirect, SpringerLink, ACM Digital Library, MDPI, and other sources. Searches will cover publications from January 2014 through July 2026.

## Search Strategy

The following 28 search strings will be used:

### Search Strings

1. `("energy efficiency" OR "energy-efficient" OR "power consumption" OR "energy optimization" OR "energy conservation") AND ("Internet of Things" OR "IoT") AND ("edge computing" OR "edge device\*" OR "end device\*" OR "edge node\*") -IIoT -Industrial`

2. `"IoT energy" AND "devices"`

3. `(("sensor node" OR "mote") OR ("green WSN" OR "green wireless sensor network\*")) AND "energy" AND ("low power" OR "power conservation" OR "efficien\*")`

4. `("network lifetime" OR "duty cycling" OR "duty-cycle" OR "sleep scheduling") AND ("wireless sensor network\*" OR "WSN" OR "sensor node\*") AND "energy"`

5. `(("MAC protocol" OR "routing protocol") OR ("energy harvesting" OR "energy-harvesting")) AND "energy efficien\*" AND ("WSN" OR "sensor network\*" OR "sensor node\*")`

6. `"Energy harvesting" AND "IoT" AND "edge devices"`

7. `"IoT energy Based Research" AND "2020 onwards"`

8. `"power-saving strategies" AND "IoT devices"`

9. `("LPWAN" OR "WSN" OR "sensor network\*") AND ("energy efficient\*" OR "energy") AND ("environmental monitoring" OR "precision agriculture")`

10. `"IoT" AND "Energy"`

11. `("computation offloading" OR "task offloading" OR "fog computing") AND "sensor networks" AND "edge nodes" AND "energy optimization" NOT ("cloud computing" OR "cloudlet")`

12. `"Energy Efficiency" AND "Wireless Sensor Networks" AND "IoT"`

13. `"Energy consumption reduction" AND "IoT" AND "end devices"`

14. `"Energy efficiency" AND "edge devices"`

15. `"Energy efficient" AND "IoT" AND "end devices"`

16. `"Energy efficient Protocols" AND "IoT"`

17. `"battery life extension" AND "techniques for IoT"`

18. `"energy efficient" AND "IoT devices"`

19. `"low power" AND "IoT device design"`

20. `("energy efficient routing" OR "power-aware routing" OR "cluster head selection") AND "wireless sensor networks" AND "edge computing" NOT ("vehicular" OR "UAV")`

21. `"wsn" AND "edge" AND ("power conservation" OR "energy efficie\*")`

22. `("5G" OR "6G" OR "cellular IoT" OR "transmission power control") AND "WSN" AND "mobile edge computing" AND "power control" NOT ("healthcare" OR "satellite")`

23. `("lightweight security" OR "lightweight cryptography") AND "WSN" AND "edge computing" AND "energy cost" NOT "image processing"`

24. `"IoT devices" AND "energy"`

25. `"IoT" AND "energy conservation"`

26. `"energy efficiency" AND "IoT device"`

27. `"Internet of things" AND "energy"`

28. `"optimizing IoT device power" AND "consumption"`

## Study Records

### Data Management

Records will be tracked in a shared spreadsheet workbook covering identification, deduplication, screening, and extraction stages. The final summary table will be provided as supplementary material alongside this protocol.

### Selection Process

Screening will be conducted by four reviewers independently in two phases. In phase I, screening will be done based on title and abstract, and in phase II, screening will be done based on the full text. A study will be included only after going through both phases. When both reviewers in each phase reach a consensus and that decision will be retained as the final screening decision. In case of disagreement, Reviewer 3 will be consulted and his/her decision will be considered as the final decision. Only those manuscripts go through full-text screening which are included in phase I. The manuscripts excluded at phase I are dropped altogether.

### Data Collection Process

Data will be extracted into the structured form described below . Data extraction will be done by three teams each composing of two members following the same rules as screening. If an item is not reported or is unclear, it will be recorded as "NA/Not specified/Not reported/Not addressed" and will not be imputed.

### Data Items

The following fields will be extracted for each included study: Reference, Author, Year, Citation, Database, Focus Area, Technique, Category, Key Contribution, Findings, Limitations, Kinds of Edge Devices, Type of Data Provided, How the Data is Communicated, Protocol Used / Packet Size / Encryption, Security and Privacy, Energy Consumption Parameters, and How Energy Consumption is Reduced.

### Outcomes and Prioritization

No single outcome measure is prioritized across the corpus, given the methodological diversity of included studies. Instead, eight research questions (RQ1-RQ8, listed above) define the review's prioritized synthesis targets, in the order presented. Reported quantitative energy/lifetime metrics shall be captured per study in the Findings and Energy Consumption Parameters fields but shall not be pooled into a single review-wide outcome.

## Data Synthesis

- No quantitative meta-analysis will be planned or conducted; included studies report heterogeneous, non-poolable outcome metrics (energy savings expressed in different units, under different baselines and evaluation conditions), making statistical pooling inappropriate.

- A composite scoring rubric (citation score normalized by publication age, journal/venue ranking, contribution novelty, validation strength) will be used to rank the twenty highest-impact contributions, with a planned sensitivity analysis to test the ranking's stability under different criterion weighings.

- The primary synthesis is narrative and taxonomic: a two-axis taxonomy (seven system-perspective layers x five methodology families), descriptive quantitative analysis of publication trends, application domains, protocol adoption, and limitation-category frequency, and RQ-by-RQ thematic synthesis.

## Meta-Bias(es)

Reliance on a single primary search engine (Google Scholar) is a source of potential selection bias, partially mitigated by the six-source identification stage and the venue-quality filter, but not eliminated. No formal quantitative publication-bias assessment (e.g., funnel plot) will be conducted, consistent with the narrative (non-meta-analytic) synthesis approach.

## Confidence in Cumulative Evidence

GRADE will not be applied, as it is designed for intervention/outcome evidence in clinical and health research and does not have an established adaptation for algorithmic/technical computer science literature. Confidence in the reviewed evidence base is instead supported indirectly through the venue-quality filter and the composite impact-ranking exercise, both stated here as partial, not equivalent, substitutes for a formal evidence-grading framework.


# Replication Package

This repository contains the complete replication package for the paper. In addition to supporting transparency and reproducibility, the provided dataset can be used for benchmarking, comparative evaluation of communication technologies, cross-domain IoT requirement analysis, and early-stage IoT application design.

## Repository Contents

### data_extraction.xlsx
Contains the complete requirement extraction and synthesis pipeline used in this study. The workbook includes multiple worksheets covering the different processing stages, including raw extracted data, transposed data, requirement categorization and sorting, domain and application mapping, requirement normalization (with accompanying notes), requirement merging, and the final synthesized requirement sets. The workbook also contains supporting analysis and figures used during the study.

### snowballing_search.xlsx
Contains the complete recursive snowballing process used to identify the primary studies. The workbook documents the initial seed set and each forward and backward snowballing iteration until saturation was reached and no additional relevant studies could be identified.

For each iteration, studies are marked according to the applied inclusion and exclusion criteria. Included studies are highlighted in green and excluded studies in red. To avoid duplicate screening, each iteration also records whether a paper was already assessed in a previous iteration. The workbook additionally provides counts of unique papers screened during each stage of the process.

### primary_studies/
Contains PDF copies of the 22 primary studies included in the final dataset. File names correspond to the study identifiers used throughout `data_extraction.xlsx`, allowing traceability between extracted requirements and their original sources.

### studies.bib
BibTeX database containing the references for all primary studies included in the review.

---

**Article**: A Systematic Synthesis of IoT Communication Requirements Across Domains

**Written by**: Sebastian Leclerc, Alessio Bucaioni, Mohammad Ashjaei

**From**: Mälardalen University, Västerås, Sweden

# Nanopore-open-data
Nanopore data for Probe-free Multiplexed RPA Readout through Single-Molecule Nanopore Sensing and Deep Learning Classification


## Description
This repository provides an open dataset of solid-state nanopore measurements collected for diagnostic research. It includes raw current–time traces exported from the acquisition system, minimally processed event tables, and curated metadata that documents sample preparation, pore geometry, electrolyte, voltage, and acquisition settings. The goal is to enable reuse for benchmarking of event detection, classification, and downstream analytics, as well as transparent reporting and reproducibility.

### What is included
- **data/raw**: untouched instrument exports, one file per run or segment.  
- **data/raw**: instrument exports, one file per run or segment, derived tables such as per-event features and sample-level summaries.  
- **data/metadata**: data dictionary, sample sheet, and protocols.  
- **code**: Python Code.  


### Formats and conventions
- Raw traces as CSV columns for time and current in SI units.  
- Event tables as CSV with one row per event and columns
- Sampling rate, filter, pore diameter, electrolyte, temperature, and bias voltage recorded in metadata.  
- File names include run date, pore ID, and sample ID for deterministic joins.


## License
Data: CC BY 4.0. Code: MIT.
## How to cite
<final citation after DOI>

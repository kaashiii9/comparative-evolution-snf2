# comparative-evolution-snf2
Comparative evolutionary and domain analysis of human SMARCA4 and yeast SNF2.
# Comparative Evolutionary and Domain Analysis of SNF2 Family Proteins

## Project Overview
This project investigates the evolutionary conservation and domain architecture of the SNF2 family chromatin remodeler proteins by comparing:

- **Human SMARCA4 (BRG1)**
- **Yeast SNF2 (Saccharomyces cerevisiae)**

The goal is to identify conserved catalytic regions, evaluate sequence similarity, and analyze structural and functional domains using web-based bioinformatics tools.

---

## Objectives
- Identify orthologous relationship between SMARCA4 and SNF2
- Determine conserved and divergent regions
- Analyze domain architecture differences
- Interpret evolutionary constraints on catalytic regions

---

## Tools Used
- NCBI BLAST (blastp)
- Clustal Omega (Multiple Sequence Alignment)
- InterProScan (Domain Annotation)
- NCBI Protein Database
- (Planned) MEGA for phylogenetic analysis

---

## Methods

### 1️⃣ Sequence Retrieval
Protein sequences were retrieved from the NCBI Protein database:
- Human SMARCA4
- Yeast SNF2

### 2️⃣ BLAST Analysis
BLASTp was performed to identify conserved regions between the two proteins.
Parameters:
- Database: RefSeq protein
- Organism filter applied when necessary

### 3️⃣ Multiple Sequence Alignment
Clustal Omega was used to analyze conserved motifs and core catalytic regions.

### 4️⃣ Domain Architecture Analysis
InterProScan was used to identify functional domains and conserved structural motifs.

---

## Key Findings (Week 1 Results)

- Query coverage between human SMARCA4 and yeast SNF2: **~54%**
- Two significant alignment regions (HSPs) identified:
  - **Range 1:** ~751 amino acids, ~52% identity, E-value = 0.0  
  - **Range 2:** ~176 amino acids, ~30% identity, E-value = 4e-14  
- Strong conservation observed in the ATP-dependent helicase core
- Divergence observed in peripheral/regulatory regions

These findings suggest evolutionary conservation of the catalytic ATPase machinery with expansion of regulatory domains in humans.

---

## Project Structure

- data/ → Raw protein sequences
- results/ → BLAST outputs, alignment files
- figures/ → Screenshots and annotated images
- docs/ → Detailed report and notes
---

## Future Work
- Construct phylogenetic tree of SNF2 family members
- Map conserved regions onto AlphaFold structures
- Compare domain expansion across species
- Explore functional enrichment of interacting partners

---

## Skills Demonstrated
- Comparative genomics
- Sequence similarity analysis
- Domain annotation interpretation
- Evolutionary reasoning
- Bioinformatics workflow documentation

---

## Author
Kashi Kumar  
MSc Zoology | Bioinformatics & Molecular Biology Enthusiast  

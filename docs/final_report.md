# Comparative Evolutionary and Domain Analysis of Human SMARCA4 and Yeast SNF2  
## Report (Completed up to Multiple Sequence Alignment)

---

# 1. Chromatin and Chromatin Remodelling

In eukaryotic cells, DNA does not exist as a naked linear molecule. Instead, it is tightly packaged into a structured complex called chromatin. Chromatin consists of DNA wrapped around specialized proteins known as histones. These histone proteins act like spools, around which DNA winds to form repeating structural units called nucleosomes. Each nucleosome contains approximately 147 base pairs of DNA wrapped around a core of histone proteins. This packaging serves two important purposes. First, it allows extremely long DNA molecules to fit inside the limited space of the cell nucleus. Second, it regulates access to DNA, thereby controlling when and how genetic information is used by the cell.

Chromatin exists in different structural states depending on how tightly the DNA is packed. In tightly packed regions, called heterochromatin, DNA is less accessible to cellular machinery. In contrast, loosely packed regions, called euchromatin, allow easier access to DNA. This structural organization plays a crucial role in regulating gene expression, as DNA must be accessible for essential cellular processes such as transcription, replication, and repair.

Although chromatin packaging is necessary for DNA organization and protection, it can also restrict access to DNA when needed. For example, during transcription, RNA polymerase must access specific DNA sequences to synthesize RNA. If the DNA is tightly wrapped around histones, RNA polymerase cannot bind to the DNA, and gene expression cannot occur. Similarly, during DNA replication and repair, various enzymes require access to DNA to perform their functions. Therefore, the cell must have mechanisms to temporarily alter chromatin structure to allow access to DNA.

This process is carried out by chromatin remodelling proteins, which use energy derived from ATP hydrolysis to reposition, remove, or restructure nucleosomes. By doing so, these proteins can make DNA either more accessible or less accessible depending on cellular requirements. This ATP-dependent process is known as chromatin remodelling. Chromatin remodelling is essential for many critical cellular functions, including gene expression regulation, DNA replication, DNA repair, and cell differentiation. Without chromatin remodelling, cells would not be able to properly control access to their genetic information.

---

# 2. SMARCA4 and Its Role in Chromatin Remodelling

SMARCA4 (SWI/SNF-related matrix-associated actin-dependent regulator of chromatin subfamily A member 4), also known as BRG1, is a chromatin remodelling protein found in humans. It is encoded by the SMARCA4 gene and functions as the catalytic ATPase subunit of the SWI/SNF chromatin remodelling complex. This protein plays a central role in regulating gene expression by altering chromatin structure.

SMARCA4 helps overcome chromatin-mediated transcriptional repression by using energy derived from ATP hydrolysis to reposition nucleosomes. This allows transcription factors and RNA polymerase to access DNA and initiate transcription. Therefore, SMARCA4 does not directly synthesize RNA but enables transcription by modifying chromatin accessibility.

SMARCA4 belongs to the SNF2 helicase family of ATP-dependent chromatin remodelling proteins. Members of this family share conserved ATP-binding and helicase domains, which allow them to function as molecular motors that move along DNA. These domains are critical for ATP binding and hydrolysis, which provides energy for chromatin remodelling.

The protein sequence of SMARCA4 contains conserved functional domains, including the ATPase domain. Because protein function is determined by amino acid sequence and domain structure, analyzing the SMARCA4 protein sequence can provide insights into its functional regions and evolutionary conservation.

The objective of this study was to analyze the SMARCA4 protein sequence and identify evolutionarily conserved regions by comparing it with homologous proteins from other organisms.

---

# 3. Identification of Homologous Protein Using BLAST

To identify homologous proteins related to SMARCA4, BLASTp (Basic Local Alignment Search Tool for proteins) was used. BLASTp compares a protein sequence against a database of protein sequences and identifies regions of similarity.

The SMARCA4 protein sequence was used as the query sequence and searched against the RefSeq protein database. BLASTp identified SNF2 from *Saccharomyces cerevisiae* (yeast) as a homologous protein.

**Query Protein:**

NP_001122316.1  
SWI/SNF-related matrix-associated actin-dependent regulator of chromatin subfamily A member 4 isoform B  
Organism: *Homo sapiens*

**Subject Protein Identified:**

NP_014933.3  
SWI/SNF catalytic subunit SNF2  
Organism: *Saccharomyces cerevisiae S288C*

SNF2 is also an ATP-dependent chromatin remodelling protein and belongs to the same SNF2 helicase family. This indicates a shared evolutionary origin between human SMARCA4 and yeast SNF2.

---

# 4. Sequence Retrieval

Protein sequences were retrieved from the NCBI Protein database in FASTA format.

**SMARCA4 sequence length:** 1647 amino acids  
**SNF2 sequence length:** 1703 amino acids  

These sequences were used for further comparative analysis.

---

# 5. BLAST Analysis Procedure and Results

BLASTp was performed using the SMARCA4 protein sequence as the query.

## Procedure

1. SMARCA4 protein sequence was obtained in FASTA format from NCBI.
2. BLASTp tool was accessed from the NCBI BLAST interface.
3. SMARCA4 sequence was entered as the query.
4. RefSeq protein database was selected.
5. Default parameters were used.
6. BLAST was executed.

BLAST identified regions of similarity called High-scoring Segment Pairs (HSPs).

## Results

- Query coverage: 54%
- Range 1 identity: 52%
- Range 2 identity: 30%
- Range 1 E-value: 0.0
- Range 2 E-value: 4e-14

## Interpretation

The E-value represents the probability that similarity occurred by chance. An E-value of 0.0 indicates extremely strong evolutionary relationship.

The 54% query coverage indicates that more than half of the SMARCA4 protein aligns with SNF2.

The 52% identity in the main region indicates strong conservation of the ATPase catalytic core.

These results confirm that SMARCA4 and SNF2 are homologous proteins belonging to the same SNF2 helicase family.

---

# 6. Multiple Sequence Alignment Using Clustal Omega

Multiple sequence alignment was performed using Clustal Omega to examine amino acid conservation.

The FASTA sequences of SMARCA4 and SNF2 were aligned using default parameters.

## Alignment Symbols

- `*` → Identical amino acids  
- `:` → Strong similarity  
- `.` → Weak similarity  

## Observations

The alignment revealed a highly conserved central region between SMARCA4 and SNF2 corresponding to the ATPase helicase core.

This region contained long stretches of identical amino acids (`*`), indicating strong evolutionary conservation.

This conserved region corresponds to:

- ATPase domain
- Helicase domain

These domains are responsible for ATP binding and chromatin remodelling activity.

In contrast, the N-terminal and C-terminal regions showed lower conservation and more variation, suggesting regulatory divergence.

## Interpretation

The strong conservation of the ATPase catalytic core confirms that SMARCA4 and SNF2 share the same functional mechanism.

This demonstrates that ATP-dependent chromatin remodelling is evolutionarily conserved across species.

---

# Conclusion (Up to Clustal Omega)

The comparative analysis of SMARCA4 and SNF2 demonstrates strong evolutionary conservation, particularly in the ATPase helicase core. BLAST and multiple sequence alignment confirm that these proteins share a common ancestral origin and conserved chromatin remodelling function.

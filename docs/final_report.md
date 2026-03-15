# REPORT

---

## Chromatin and Chromatin Remodelling

In eukaryotic cells, DNA does not exist as a naked linear molecule. Instead, it is tightly packaged into a structured complex called chromatin. Chromatin consists of DNA wrapped around specialized proteins known as histones. These histone proteins act like spools, around which DNA winds to form repeating structural units called nucleosomes. Each nucleosome contains approximately 147 base pairs of DNA wrapped around a core of histone proteins. This packaging serves two important purposes. First, it allows the extremely long DNA molecules to fit inside the limited space of the cell nucleus. Second, it regulates access to DNA, thereby controlling when and how genetic information is used by the cell.  

Chromatin exists in different structural states depending on how tightly the DNA is packed. In tightly packed regions, called heterochromatin, DNA is less accessible to cellular machinery. In contrast, loosely packed regions, called euchromatin, allow easier access to DNA. This structural organization plays a crucial role in regulating gene expression, as DNA must be accessible for essential cellular processes such as transcription, replication, and repair.  

Although chromatin packaging is necessary for DNA organization and protection, it can also restrict access to DNA when needed. For example, during transcription, RNA polymerase must access specific DNA sequences to synthesize RNA. If the DNA is tightly wrapped around histones, RNA polymerase cannot bind to the DNA, and gene expression cannot occur. Similarly, during DNA replication and repair, various enzymes require access to DNA to perform their functions. Therefore, the cell must have mechanisms to temporarily alter chromatin structure to allow access to DNA.  

This process is carried out by chromatin remodelling proteins, which use energy derived from ATP hydrolysis to reposition, remove, or restructure nucleosomes. By doing so, these proteins can make DNA either more accessible or less accessible depending on cellular requirements. This ATP-dependent process is known as chromatin remodelling. Chromatin remodelling is essential for many critical cellular functions, including gene expression regulation, DNA replication, DNA repair, and cell differentiation. Without chromatin remodelling, cells would not be able to properly control access to their genetic information, which would disrupt normal cellular function.  

---

## SMARCA4 and Its Role in Chromatin Remodelling

SMARCA4 (SWI/SNF-related matrix-associated actin-dependent regulator of chromatin subfamily A member 4), also known as BRG1, is a chromatin remodelling protein found in humans. It is encoded by the SMARCA4 gene and functions as a catalytic ATPase subunit of the SWI/SNF chromatin remodelling complex. This protein plays a central role in regulating gene expression by altering chromatin structure.  

As discussed earlier, chromatin remodelling is essential because DNA is tightly wrapped around histones, which restricts access to transcriptional machinery. SMARCA4 helps overcome this barrier by using energy derived from ATP hydrolysis to reposition nucleosomes. This allows transcription factors and RNA polymerase to access DNA and initiate transcription. Therefore, SMARCA4 does not directly synthesize RNA but enables transcription to occur by making DNA accessible.  

SMARCA4 belongs to the SNF2 helicase family of ATP-dependent chromatin remodelling proteins. Members of this family share conserved ATP-binding and helicase domains, which allow them to function as molecular motors that move along DNA. These domains are critical for their function, and evolutionary conservation of these domains indicates preservation of chromatin remodelling activity across species.  

The protein sequence of SMARCA4 contains these conserved domains, including the ATPase domain responsible for ATP binding and hydrolysis. Because protein function is determined by amino acid sequence and domain structure, analysing the SMARCA4 protein sequence can provide insights into its functional regions and evolutionary conservation.  

The objective of this study was to analyse the SMARCA4 protein sequence and identify evolutionarily conserved regions by comparing it with proteins from other organisms. By doing so, we aimed to determine whether the ATP-dependent chromatin remodelling function of SMARCA4 is conserved across species.  

---

## Identification of Homologous Protein Using BLAST

To identify homologous proteins related to SMARCA4, BLASTp (Basic Local Alignment Search Tool for proteins) was used. BLASTp compares a protein sequence against a database of protein sequences and identifies similar sequences based on amino acid similarity.  

The SMARCA4 protein sequence was used as the query sequence and searched against the RefSeq protein database. BLASTp identified SNF2 from *Saccharomyces cerevisiae* (yeast) as a homologous protein. SNF2 is also a chromatin remodelling ATPase and is a member of the same SNF2 helicase family.  

This result indicates that human SMARCA4 and yeast SNF2 share a common evolutionary origin and likely perform similar biological functions. Because yeast is evolutionarily distant from humans, conservation between these proteins suggests that chromatin remodelling is an essential and ancient biological mechanism.  

---

## Sequence Retrieval

The protein sequence of human SMARCA4 was retrieved from the NCBI Protein database. The sequence was obtained in FASTA format, which represents the amino acid sequence using single-letter amino acid codes.  

The FASTA format begins with a header line containing the protein name and accession number, followed by the amino acid sequence.  

**Query Protein:**  
NP_001122316.1 SWI/SNF-related matrix-associated actin-dependent regulator of chromatin subfamily A member 4 isoform B [Homo sapiens]  

The sequence consisted of 1647 amino acids.  

Similarly, the protein sequence of yeast SNF2 was retrieved from the NCBI Protein database after it was identified through BLAST analysis.  

**Subject Protein:**  
NP_014933.3 SWI/SNF catalytic subunit SNF2 [Saccharomyces cerevisiae S288C]  

The SNF2 protein sequence contained 1703 amino acids.  

These sequences were used for subsequent comparative analysis.  

---

## BLAST Analysis Procedure and Results

BLASTp was performed using the SMARCA4 protein sequence as the query.  

### Steps performed:

1. The SMARCA4 protein sequence in FASTA format was copied from the NCBI Protein database.  
2. The BLASTp tool was accessed through the NCBI BLAST interface.  
3. The SMARCA4 FASTA sequence was pasted into the query sequence box.  
4. The RefSeq protein database was selected.  
5. The search was executed using default parameters.  

BLASTp compares the query sequence with sequences in the database and identifies regions of similarity called High-scoring Segment Pairs (HSPs). The protein sequence at the top was analysed as it showed highest compatibility.  

### Results obtained:

- Query coverage: 54%  
- Range 1 identity: 52%  
- Range 2 identity: 30%  
- Range 1 E-value: 0.0  
- Range 2 E-value: 4e-14  

### Interpretation:

The E-value represents the probability that the alignment occurred by chance. An E-value of 0.0 indicates extremely strong similarity and confirms that the proteins are evolutionarily related.  

The 54% query coverage indicates that more than half of the SMARCA4 protein aligns with the SNF2 protein.  

The 52% identity in the main alignment region indicates strong conservation of amino acid sequence. This suggests that the functional ATPase core region is conserved between yeast and humans.  

The smaller alignment region with 30% identity and E-value of 4e-14 also indicates significant similarity and may represent conserved functional or structural regions.  

These results confirm that SMARCA4 and SNF2 are homologous proteins belonging to the same protein family.  

---

## Multiple Sequence Alignment Using Clustal Omega

To examine conservation at the amino acid level, multiple sequence alignment was performed between human SMARCA4 and yeast SNF2 using Clustal Omega. The FASTA sequences of both proteins were uploaded to the Clustal Omega web server, and alignment was performed using default parameters. The output alignment displayed the amino acid sequences of both proteins along with conservation symbols indicating similarity between residues.  

In the Clustal Omega output:  

- `*` indicates identical amino acids  
- `:` indicates strongly similar amino acids  
- `.` indicates weak similarity  

Analysis of the alignment revealed a highly conserved central region between SMARCA4 and SNF2, particularly corresponding to the ATPase helicase core. This region showed long stretches of identical amino acids marked by `*`, indicating strong sequence conservation. Conserved motifs involved in ATP binding and hydrolysis, including glycine-rich and lysine-containing sequences characteristic of ATP-binding proteins, were present in both SMARCA4 and SNF2.  

This conserved region corresponds to the DEXHc ATPase domain and helicase domain, which are responsible for ATP hydrolysis and chromatin remodelling activity. The presence of identical and chemically similar residues in this region indicates that the structural and functional integrity of the ATPase motor has been preserved throughout evolution.  

In contrast, the N-terminal and C-terminal regions showed fewer identical residues and more mismatches, indicating greater sequence divergence. These regions likely correspond to regulatory domains that have evolved differently in yeast and humans to support species-specific functions.  

Overall, the Clustal Omega alignment confirms that the ATP-dependent helicase catalytic core is highly conserved between yeast SNF2 and human SMARCA4, supporting the conclusion that these proteins share a common evolutionary origin and retain the same fundamental chromatin remodelling function.
---

## Domain Architecture Analysis Using InterPro

To further investigate the functional significance of the conserved regions identified through multiple sequence alignment, domain architecture analysis was performed using InterPro. InterPro is a database that integrates predictive models from multiple sources to identify conserved protein domains and functional sites within a given sequence.

The protein sequences of human SMARCA4 and yeast SNF2 were individually submitted to the InterPro web server for domain annotation.

### Domains Identified in Human SMARCA4

InterPro analysis of SMARCA4 identified the following major domains:

- SNF2 helicase family domain  
- DEXHc ATPase domain  
- P-loop NTP-binding domain  
- BRK domain  
- Intrinsically disordered regions  

The DEXHc ATPase domain and P-loop NTP-binding domain are responsible for ATP binding and hydrolysis. These domains form the catalytic core of the protein and provide the energy required for chromatin remodelling activity. The helicase domain allows the protein to interact with and translocate along DNA.

The BRK domain is believed to contribute to regulatory or protein–protein interaction functions. Additionally, the presence of intrinsically disordered regions suggests regulatory flexibility in the human protein.

### Domains Identified in Yeast SNF2

InterPro analysis of SNF2 identified:

- SNF2 helicase domain  
- DEXHc ATPase domain  
- Helicase C-terminal domain  
- Bromodomain  
- HSA domain  

The ATPase and helicase domains correspond to the catalytic motor region of the protein. The bromodomain is known to recognize acetylated histones, which is important for chromatin targeting. The HSA domain contributes to interactions within the chromatin remodelling complex.

### Interpretation of Domain Conservation

The presence of conserved DEXHc ATPase and helicase domains in both SMARCA4 and SNF2 confirms that the ATP-dependent chromatin remodelling mechanism is evolutionarily conserved.

The conserved domains identified through InterPro correspond to the same central region that showed strong conservation in the Clustal Omega alignment. This correlation between sequence conservation and domain architecture strongly supports functional preservation of the catalytic core across species.

Differences observed in regulatory domains, such as the BRK domain in humans and bromodomain in yeast, suggest evolutionary divergence in regulatory mechanisms while maintaining the core ATPase function.

Overall, domain architecture analysis reinforces the conclusion that SMARCA4 and SNF2 share a conserved chromatin remodelling engine with species-specific regulatory adaptations.

### Phylogram Interpretation

The phylogenetic tree revealed evolutionary relationships that closely mirror the known history of the organisms included in this analysis. The mammalian SMARCA4 proteins from human, mouse, and rat clustered tightly together, which is expected given their relatively recent evolutionary divergence approximately 90-100 million years ago. The avian homologs from chicken and blue tit appeared within the broader vertebrate branch but diverged earlier, consistent with the separation of bird and mammalian lineages around 300 million years ago. Amphibian and fish homologs branched even further away, reflecting the earlier diversification of vertebrates roughly 400-500 million years ago.
In contrast, the invertebrate homologs from Drosophila melanogaster and Caenorhabditis elegans displayed greater evolutionary distance from the vertebrate proteins. This is consistent with the divergence between invertebrate and vertebrate lineages approximately 600-700 million years ago. The fungal SNF2 protein from Saccharomyces cerevisiae formed the most distant branch in the tree. Fungi separated from the lineage that eventually gave rise to animals more than one billion years ago, which explains the much larger degree of sequence divergence observed in the yeast SNF2 protein.
Despite these vast evolutionary distances and the incredible diversity of life forms represented from unicellular fungi to complex vertebrates, the core SNF2 ATPase domain remains strongly conserved. This conservation suggests that the SNF2 chromatin-remodelling ATPase likely originated in a very early eukaryotic ancestor, before the major diversification of modern eukaryotic lineages. As evolution proceeded and organisms became more complex, this ancestral protein was inherited and gradually modified, allowing different species to adapt the chromatin-remodelling machinery to their own regulatory needs.
The persistence of the SNF2 catalytic core across such diverse organisms reflects a key principle of molecular evolution: while biological systems evolve and diversify, essential molecular mechanisms tend to be preserved because they perform critical cellular functions. Chromatin remodelling is one such fundamental process. By regulating access to DNA, SNF2-family proteins play a central role in controlling transcription, replication, and DNA repair, processes that are indispensable for maintaining genome stability and proper cellular function.
Viewed in this way, the phylogram represents more than just a computational analysis of sequence similarity. It provides a glimpse into the deep evolutionary history of an essential molecular machine. Over the course of more than a billion years of evolution, from the earliest eukaryotic cells to modern multicellular organisms, the SNF2 chromatin-remodelling system has remained a constant presence. Evolution has shaped and diversified the organisms that carry it, yet the core molecular engine responsible for regulating chromatin structure has remained remarkably conserved, underscoring its fundamental importance to life itself.


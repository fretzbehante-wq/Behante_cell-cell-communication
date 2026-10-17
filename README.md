# Individual Cell-to-Cell Communication Laboratory

## Biological Question

How can FGF9 released by a potential sender cell activate FGFR3-associated signaling in a potential receiver cell, and what molecular interactions support this proposed cell-to-cell communication pathway?

The proposed signaling system for this activity is **FGF9–FGFR3**. FGF9 (fibroblast growth factor 9) is the candidate ligand, while FGFR3 (fibroblast growth factor receptor 3) is the candidate receptor. Human Protein Atlas (HPA), OmniPath, STRING, and IntAct were used to investigate gene and protein expression, ligand–receptor evidence, associated signaling proteins, and molecular interaction records.

The available evidence supports FGF9–FGFR3 as a candidate signaling relationship. However, the specific sender-to-receiver cell communication model remains a hypothesis because expression and database interaction evidence alone do not confirm that the proposed cells communicate directly in a particular biological context.

---

## PART A. Choose and Register the Sender Cell

### A.1. Selected Sender Cell

**Candidate sender cell:** Neuron

Neurons are considered a potential sender cell because the Human Protein Atlas describes FGF9 as a growth factor involved in nervous system development and indicates that it is produced mainly by neurons in this context. FGF9 may contribute to glial cell development and other processes involving cell proliferation, differentiation, and migration.

### A.2. Biological Context

The proposed biological context is **nervous system development and cell differentiation**. FGF9 may act as an extracellular signaling molecule that influences the behavior or development of nearby cells.

However, the available expression information does not establish that the selected neuron population releases FGF9 specifically toward astrocytes. Therefore, the neuron is treated as a candidate sender rather than a confirmed sender cell.

### A.3. Supporting Evidence

The Human Protein Atlas reports FGF9 expression in several tissues, including the brain, kidney, and retina. Its information also describes a role for FGF9 in nervous system development and glial cell development.

**Screenshot:** `figures/01_sender_cell_evidence.png`

![Sender cell evidence](figures/01_sender_cell_evidence.png)

---

## PART B. Discover a Candidate Signal Produced by the Sender Cell

### B.1. Candidate Signaling Molecule

**Ligand:** Fibroblast growth factor 9 (FGF9)  
**Gene:** `FGF9`  
**UniProt accession:** P31371

FGF9 is a member of the fibroblast growth factor family. According to the Human Protein Atlas, FGF9 has protein-level evidence and is associated with biological processes such as embryonic development, cell proliferation, differentiation, and migration.

### B.2. Expression and Localization Evidence

The Human Protein Atlas reports that FGF9 RNA expression is enhanced in the brain, kidney, and retina. Its cell-type expression information includes several cell populations, and the gene summary describes FGF9 production by neurons in the nervous system.

The reported localization information includes extracellular and intracellular locations, depending on the predicted localization or isoform. The extracellular localization is consistent with the possibility that FGF9 can function as a secreted signaling molecule.

Nevertheless, tissue-level expression does not independently confirm secretion by the exact sender cell selected for this model.

### B.3. Proposed Signaling Type

The proposed communication is **paracrine signaling**, in which a signaling molecule released by one cell acts on another cell nearby. This is a plausible interpretation for a locally secreted growth factor, but the specific neuron-to-astrocyte route has not been directly demonstrated by the available evidence.

### B.4. Interpretation

FGF9 is a reasonable candidate ligand because its expression and biological functions are consistent with a role in development and cell communication. Additional cell-specific evidence would be required to establish that the selected neurons produce and release FGF9 in the proposed context.

**Screenshot:** `figures/02_FGF9_expression.png`

![FGF9 expression evidence](figures/02_FGF9_expression.png)

---

## PART C. Identify the Receptor and Receiver Cell

### C.1. Candidate Receptor

**Receptor:** Fibroblast growth factor receptor 3 (FGFR3)  
**Gene:** `FGFR3`  
**UniProt accession:** P22607

FGFR3 is a cell-surface receptor with tyrosine-protein kinase activity. Binding of an appropriate fibroblast growth factor can activate intracellular signaling cascades involved in regulating cellular responses.

### C.2. Candidate Receiver Cell

**Candidate receiver cell:** Astrocyte

Astrocytes are considered a possible receiver cell because the Human Protein Atlas lists astrocytes among the cell types associated with enhanced FGFR3 expression. FGFR3 expression in astrocytes makes this cell type a candidate for further investigation.

However, receptor expression alone does not demonstrate that astrocytes receive FGF9 from the selected neurons. The proposed receiver cell should therefore be interpreted as a candidate supported by expression evidence, rather than as a confirmed recipient.

### C.3. OmniPath Ligand–Receptor Evidence

OmniPath Explorer was used to investigate the possible relationship between FGF9 and FGFR3. The interaction table displayed FGF9 (P31371) and FGFR3 (P22607), with annotations from CellCall, CellChatDB, and CellPhoneDB.

These database annotations support the selection of FGF9–FGFR3 as a candidate ligand–receptor pair. However, the records do not independently demonstrate that this interaction occurs between the exact neuron and astrocyte populations proposed in this model.

### C.4. Proposed Communication Statement

The proposed model is that a neuron may release FGF9, which could activate FGFR3 on a potential receiver cell such as an astrocyte and initiate intracellular signaling associated with cellular development or differentiation.

This statement represents a **candidate communication model**. Further cell-specific and experimental evidence would be needed to confirm the sender, receiver, and biological response.

**Screenshot:** `figures/03_FGFR3_receiver_evidence.png`

![FGFR3 receiver evidence](figures/03_FGFR3_receiver_evidence.png)

**Screenshot:** `figures/04_omnipath_evidence.png`

![OmniPath evidence](figures/04_omnipath_evidence.png)

---

## PART D. Explore the Receptor-Centered Network in STRING

### D.1. STRING Network

STRING was used to examine the functional association network centered on FGFR3 in *Homo sapiens*. The network provides information about proteins that are known or predicted to be functionally associated with FGFR3.

Proteins relevant to the proposed signaling pathway include:

| Protein | Proposed role |
|---|---|
| FGFR3 | Receptor tyrosine kinase that initiates signaling following ligand binding |
| FRS2 | Adaptor protein involved in transmitting signals from FGFRs |
| GRB2 | Signaling adaptor that helps connect receptor-associated proteins to downstream pathways |
| SOS1 | Guanine nucleotide exchange factor involved in RAS activation |
| HRAS | Small GTPase involved in downstream signal transduction |

These proteins provide a useful overview of signaling components associated with FGFR3. Their presence in the network supports a plausible signaling context but does not, by itself, establish the exact order of events in the proposed cell-to-cell communication model.

### D.2. Functional Enrichment

The STRING enrichment results included the **fibroblast growth factor receptor signaling pathway (GO:0008543)**.

| Enriched term | Reported result | Interpretation |
|---|---|---|
| Fibroblast growth factor receptor signaling pathway (GO:0008543) | 9 of 59; strength = 2.44; FDR = 6.89 × 10⁻¹⁸ | Supports the association of the network with FGF receptor signaling |
| Cell surface receptor protein tyrosine kinase signaling pathway | Displayed in the enrichment results | Consistent with signaling initiated by receptor tyrosine kinases |
| Positive regulation of organ growth | Displayed in the enrichment results | Consistent with developmental and growth-related functions |
| Fibroblast growth factor receptor activity | Displayed in the enrichment results | Relevant to the function of FGFR3 |

The enrichment of the fibroblast growth factor receptor signaling pathway is consistent with the proposed role of FGFR3 in signal transduction. The reported FDR indicates that the enrichment is statistically significant within the STRING analysis.

### D.3. Interpretation and Limitations

The STRING network supports functional relationships between FGFR3 and proteins associated with intracellular signaling. FRS2, GRB2, SOS1, and HRAS provide a plausible connection to downstream pathways, including RAS–MAPK signaling.

However, STRING associations may represent functional relationships rather than direct physical interactions. The network also does not establish that all displayed proteins act in a single linear pathway or that the pathway is activated in the specific proposed receiver cell.

**Screenshot:** `figures/05_string_network.png`

![STRING network](figures/05_string_network.png)

**Screenshot:** `figures/06_string_enrichment.png`

![STRING functional enrichment](figures/06_string_enrichment.png)

---

## PART E. Validate a Molecular Interaction Using IntAct

### E.1. Selected Molecular Interaction

IntAct was used to examine an interaction record involving FGFR3 and FRS2. This pair was selected because FRS2 is an adaptor protein associated with signaling from fibroblast growth factor receptors.

### E.2. Recorded Interaction Evidence

| Item | Record |
|---|---|
| Molecule A | FGFR3 |
| Molecule B | FRS2 |
| Organism | *Homo sapiens* |
| Detection method | Proximity-dependent biotin identification (BioID) |
| Publication PMID | 35384245 |
| IntAct accession | EBI-32721979 |
| Interaction type | Proximity |
| MI score | 0.27 |

### E.3. Interpretation and Limitations

The IntAct record provides experimental evidence that FGFR3 and FRS2 were detected in a proximity-based interaction context. This finding is consistent with the proposed involvement of FRS2 in FGFR3-associated signaling.

However, proximity-dependent biotin identification detects proteins located near one another and does not, by itself, prove direct physical binding. The MI score is a database interaction score and should not be interpreted as a percentage probability.

The result supports the relevance of FGFR3–FRS2 for investigating receptor-associated signaling, but it does not directly confirm the proposed neuron-to-astrocyte communication event.

**Screenshot:** `figures/07_intact_network.png`

![IntAct interaction evidence](figures/07_intact_network.png)

**Screenshot:** `figures/08_intact_interaction_table.png`

![IntAct interaction table](figures/08_intact_interaction_table.png)

---

## PART F. Build the Final Cell-to-Cell Communication Model

### F.1. Proposed Signaling Model

The proposed model begins with a neuron as the candidate sender cell and FGF9 as the candidate extracellular signal. FGF9 may interact with FGFR3 on a potential receiver cell, represented here by an astrocyte. Following receptor activation, FGFR3-associated signaling may involve adaptor proteins such as FRS2 and GRB2, followed by downstream components such as SOS1 and HRAS.

The STRING network supports functional associations between FGFR3 and signaling-related proteins, while the IntAct record provides proximity-based evidence involving FGFR3 and FRS2. Together with the OmniPath ligand–receptor annotations, these findings support the biological plausibility of the proposed pathway.

### F.2. Final Model Summary

**Candidate sender cell → Candidate ligand → Candidate receptor → Candidate receiver cell → Intracellular signaling network**

**Neuron → FGF9 → FGFR3 → Astrocyte (candidate) → FRS2/GRB2-associated signaling and downstream RAS–MAPK-related components**

This model integrates the available expression, ligand–receptor, network, and molecular interaction evidence. It should be interpreted as a proposed model rather than a confirmed cell-to-cell communication pathway.

### F.3. Limitations

The evidence comes from database annotations, expression information, functional association networks, and a proximity-based interaction record. These resources provide different types of support and do not independently demonstrate that neurons release FGF9 to activate FGFR3 in astrocytes.

Further cell-specific expression data and experimental validation would be needed to confirm the exact sender and receiver cells, demonstrate ligand release and receptor activation, and establish the downstream cellular response.

**Screenshot:** `figures/09_final_model.png`

![Final cell-to-cell communication model](figures/09_final_model.png)

---

## References and Database Resources

1. Human Protein Atlas. (n.d.). *FGF9—Fibroblast growth factor 9*. https://www.proteinatlas.org/
2. Human Protein Atlas. (n.d.). *FGFR3—Fibroblast growth factor receptor 3*. https://www.proteinatlas.org/
3. OmniPath. (n.d.). *Om

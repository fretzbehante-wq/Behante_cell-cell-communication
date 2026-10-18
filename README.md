# Cell-to-Cell Communication Laboratory 

**Assigned cell:** Sertoli cell

## Biological Question

How can FGF9 released by a neuron activate FGFR3-associated signaling in an astrocyte, and what molecular interactions support this proposed cell-to-cell communication pathway?

This activity investigates a possible neuron-to-astrocyte communication pathway involving fibroblast growth factor 9 (FGF9) and fibroblast growth factor receptor 3 (FGFR3). Evidence was gathered from the Human Protein Atlas (HPA), OmniPath, STRING, and IntAct databases and compared with published research.

Published research by Brandebura et al. (2022) supports neuron-to-astrocyte FGF9 signaling during mouse brainstem development. Their study found that *Fgf9* was enriched in neurons, while *Fgfr3* was enriched in astrocytes in the medial nucleus of the trapezoid body (MNTB). However, the evidence collected from the databases in this activity does not independently establish every step of the complete signaling pathway.

---

## PART A. Identify the Potential Sender Cell

The selected sender cell for this model is the **neuron**.

Neurons are specialized cells that communicate with other cells through electrical and chemical signals. In the proposed model, neurons are considered the potential source of FGF9, a signaling protein that can act on cells expressing compatible fibroblast growth factor receptors.

The Human Protein Atlas (HPA) provides information about FGF9 expression in different tissues and cell types. In addition, Brandebura et al. (2022) reported that *Fgf9* was enriched in neurons in the mouse MNTB. Their findings provide published evidence supporting neurons as a source of FGF9 in this specific biological context.

Therefore, the neuron is a literature-supported sender for the proposed model, particularly in the context of mouse brainstem development.


---

## PART B. Identify the Signaling Ligand: FGF9

The selected signaling ligand is **fibroblast growth factor 9 (FGF9)**.

- **Gene symbol:** *FGF9*
- **UniProt accession:** P31371
- **Protein type:** Secreted signaling protein

FGF9 belongs to the fibroblast growth factor family. It participates in several biological processes, including development and cellular signaling. As a signaling ligand, FGF9 can interact with compatible fibroblast growth factor receptors on target cells.

The Human Protein Atlas provides information about FGF9 expression and its association with the nervous system. Its protein localization information also supports its extracellular signaling role.

Furthermore, Hecht et al. (1995/1996) reported that FGF9 binds with high affinity to FGFR2 and FGFR3 in a heparin-dependent manner. This supports the biological plausibility of FGF9 acting as a ligand for FGFR3.

However, FGF9 is not exclusive to neurons, and its expression alone does not prove that a particular neuron releases it directly to a particular astrocyte. The proposed sender–receiver relationship should therefore be interpreted within the biological context supported by the available evidence.

<img width="623" height="438" alt="01_HPA_FGF9_Expression png" src="https://github.com/user-attachments/assets/b1b1754d-4fa2-479e-ada3-bea6c44eb2bc" />
<img width="618" height="434" alt="01_HPA_FGF9_Expression png2" src="https://github.com/user-attachments/assets/13a48044-85db-4405-ba6b-5a14eeb0cde7" />
<img width="616" height="188" alt="01_HPA_FGF9_Expression png3" src="https://github.com/user-attachments/assets/5922643c-cf17-4dbd-80de-ac911edbba78" />


---

## PART C. Identify the Receptor and Potential Receiver Cell

The selected receptor is **fibroblast growth factor receptor 3 (FGFR3)**.

- **Gene symbol:** *FGFR3*
- **UniProt accession:** P22607
- **Protein type:** Receptor tyrosine kinase
- **Potential receiver cell:** Astrocyte

FGFR3 is a receptor tyrosine kinase that can initiate intracellular signaling when activated by an appropriate ligand. The Human Protein Atlas reports FGFR3 expression in different tissues and cell types, including astrocytes.

The OmniPath database also lists the FGF9–FGFR3 ligand–receptor interaction. This supports the known molecular relationship between FGF9 and FGFR3, although the database annotation alone does not establish that this interaction occurs between the exact sender and receiver cells in the proposed model.

Additional evidence comes from Brandebura et al. (2022), who found that *Fgfr3* was enriched in astrocytes in the mouse MNTB. Together with their findings on neuronal *Fgf9*, this supports the biological basis of neuron-to-astrocyte FGF9 signaling during mouse brainstem development.

Thus, astrocytes are a literature-supported potential receiver in this model. However, the database evidence collected for this activity should not be interpreted as direct proof of ligand binding and receptor activation in a specific neuron–astrocyte pair.

## Receptor FGFR3 evidence:
<img width="621" height="483" alt="fgfr31" src="https://github.com/user-attachments/assets/eb8e6870-e6da-4594-b708-9a0b779e5cf6" />
<img width="620" height="443" alt="fgfr32" src="https://github.com/user-attachments/assets/937f9c82-1183-4256-98b4-d3742166a7d3" />
<img width="621" height="320" alt="fgfr33" src="https://github.com/user-attachments/assets/c4ed1b55-1e68-429a-91ab-520ff8c7fb48" />

## OmniPath findings:
<img width="951" height="628" alt="02FGF9-FGFR3 intercell" src="https://github.com/user-attachments/assets/fbd6eea5-578e-4ccc-8274-1544bf887de9" />
<img width="951" height="628" alt="02FGF9-FGFR3 interactions" src="https://github.com/user-attachments/assets/ccc07edd-6822-4210-90b8-92ae221a82bd" />

---


## PART D. STRING Network Interpretation

- **Query protein:** FGFR3
- **Organism:** *Homo sapiens*
- **Network size:** 11 nodes and 54 edges
- **Expected number of edges:** 14
- **PPI enrichment p-value:** 1.09 × 10⁻¹⁵
<img width="514" height="621" alt="string2" src="https://github.com/user-attachments/assets/20d9641d-6996-4a0a-8a6f-7db36a5d2cf9" />


### Network proteins and their relevance to the proposed model

| **Protein** | **Relevance to the Proposed Model** |
|---|---|
| FGFR3 | Receptor tyrosine kinase that can receive FGF9 signaling. |
| FRS2 | Adaptor protein associated with fibroblast growth factor receptor signaling. |
| GRB2 | Adaptor protein that links receptor-associated signaling components to downstream pathways. |
| SOS1 | Guanine nucleotide exchange factor involved in RAS activation. |
| HRAS | Small GTPase involved in downstream intracellular signaling. |


### Network statistics interpretation

The STRING network contains 11 nodes and 54 edges, compared with 14 expected edges. The PPI enrichment p-value of 1.09 × 10⁻¹⁵ indicates that the proteins in the network have significantly more associations than expected for a random set of proteins under STRING's model. This supports the functional relatedness of the selected proteins.

However, STRING associations may be based on different evidence sources and do not necessarily demonstrate direct physical binding. The network also does not prove that all the interactions occur in the same cell or during the specific neuron-to-astrocyte communication process.

### Relevant functional enrichment

| **Enriched term** | **Reported result** | **Relevance to the Proposed Model** |
|---|---|---|
| Fibroblast growth factor receptor signaling pathway (GO:0008543) | 9 of 59; enrichment strength = 2.44; FDR = 6.89 × 10⁻¹⁸ | Supports the association of the selected proteins with FGFR-related signaling. |
<img width="686" height="627" alt="string pathway enrichment evidence" src="https://github.com/user-attachments/assets/85d8c26a-f913-46ed-b111-6568f5539306" />

### Interpretation and limitations

The STRING results support the relevance of the selected proteins to fibroblast growth factor receptor signaling. The association network and significant functional enrichment are consistent with a possible intracellular pathway involving FGFR3 and downstream signaling components.

Nevertheless, these results do not independently confirm the complete FGFR3–FRS2–GRB2–SOS1–HRAS sequence in astrocytes responding to neuronal FGF9. STRING functional associations should not be interpreted as proof that every protein directly interacts with the next protein in the proposed sequence.

Therefore, STRING provides supporting evidence for the molecular plausibility of the proposed pathway, while the exact sequence of events in neuron-to-astrocyte communication remains to be established in the specific biological context.


---

## PART E. Examine the FGFR3–FRS2 Interaction Using IntAct

The IntAct database was used to examine the reported interaction between FGFR3 and FRS2. The retrieved record provides experimental evidence from proximity-dependent biotin identification (BioID), which detects proteins located near a protein of interest. The results are summarized below.

### Table 1. Summary of the FGFR3–FRS2 Interaction Evidence from IntAct

| **Parameter** | **Result** | **Relevance to the Proposed Model** |
|---|---|---|
| Interacting proteins | FGFR3–FRS2 | Supports an association between the receptor and an adaptor protein involved in FGF receptor signaling. |
| Experimental method | Proximity-dependent biotin identification (BioID) | Provides evidence that the proteins may be in close proximity within the experimental system. |
| Interaction accession | EBI-32721979 | Identifies the retrieved interaction record in IntAct. |
| PubMed ID | PMID: 35384245 | Links the interaction record to its associated publication. |
| MI score | 0.27 | A database-reported interaction score; it should not be interpreted as proof of direct binding. |
| Experimental context | HEK293 cells | Indicates the reported experimental context and does not establish that the same interaction was demonstrated in astrocytes. |

The IntAct result supports the possible association of FGFR3 with FRS2, which is relevant to fibroblast growth factor receptor signaling. However, BioID detects proximity rather than necessarily demonstrating direct physical binding. In addition, the reported experiment was conducted in HEK293 cells, so it does not independently confirm that the same interaction occurs during neuron-to-astrocyte communication.

Therefore, this result provides supporting molecular evidence for the proposed pathway, but further context-specific evidence would be needed to establish the FGFR3–FRS2 interaction in the exact cell-to-cell communication model.
<img width="1354" height="648" alt="intact figure sa e" src="https://github.com/user-attachments/assets/1c548d66-6d96-450c-8c40-d7156d1db80d" />

---

## PART F. Proposed Cell-to-Cell Communication Model

Based on the database findings and published literature, the proposed communication model is:

**Neuron → FGF9 → FGFR3 on astrocyte → Intracellular signaling**

In this model, the neuron serves as the source of the FGF9 ligand. FGF9 may interact with FGFR3 expressed by an astrocyte, potentially initiating receptor-associated intracellular signaling involving adaptor proteins such as FRS2 and downstream components such as GRB2, SOS1, and HRAS.

The model is supported by several complementary sources of evidence. Brandebura et al. (2022) provided published evidence for neuron-to-astrocyte FGF9 signaling during mouse brainstem development. Hecht et al. (1995/1996) demonstrated the ligand-binding relationship between FGF9 and FGFR3. The HPA provides expression information, OmniPath supplies ligand–receptor annotations, STRING provides a broader protein association network, and IntAct supplies experimental evidence concerning the FGFR3–FRS2 association.

Nevertheless, these sources provide different kinds of evidence and should not be treated as interchangeable. The published study supports neuron-to-astrocyte FGF9 signaling in a specific biological context, while the database results help evaluate the molecular plausibility of the proposed pathway. They do not collectively prove that every step of the complete FGFR3-associated signaling cascade occurs in the same neuron–astrocyte system.


## Required Evidence Recorded

| **Item** | **Records** |
|---|---|
| Sender cell | Neuron; published research supports neuronal FGF9 expression in the mouse medial nucleus of the trapezoid body (MNTB). |
| Signal/ligand | FGF9, UniProt P31371; HPA provides expression and protein localization information, while published research supports neuronal *Fgf9* expression in the mouse MNTB. |
| Receptor | FGFR3, UniProt P22607; a receptor tyrosine kinase that can bind FGF9. |
| Receiver cell | Astrocyte; HPA reports FGFR3 expression in astrocytes, and published research found *Fgfr3* enrichment in astrocytes in the mouse MNTB. |
| Signaling type | Proposed paracrine signaling between neighboring cells through a secreted ligand. The published study supports neuron-to-astrocyte FGF9 signaling during mouse brainstem development. |
| HPA | Provides expression, cell-type, and protein localization information for FGF9 and FGFR3. |
| OmniPath | Lists the FGF9–FGFR3 ligand–receptor interaction with 19 references in the recorded results. This supports the annotated molecular relationship but does not independently establish signaling between the selected cells. |
| STRING | 11 nodes, 54 edges, 14 expected edges, PPI enrichment p = 1.09 × 10⁻¹⁵. |
| STRING functional association | The network includes FGFR3 and related signaling proteins, including FRS2, GRB2, SOS1, and HRAS. Individual association scores should only be reported if confirmed in the recorded results. |
| STRING enrichment | Fibroblast growth factor receptor signaling pathway (GO:0008543); 9 of 59, enrichment strength = 2.44, FDR = 6.89 × 10⁻¹⁸. |
| IntAct | FGFR3–FRS2 association; PMID 35384245; proximity-dependent biotin identification (BioID); MI score = 0.27 in the recorded result. This supports proximity in the reported experimental context, not necessarily direct binding. |
| Published literature | Brandebura et al. (2022) reported neuronal *Fgf9* enrichment and astrocytic *Fgfr3* enrichment in the mouse MNTB, providing biological evidence for neuron-to-astrocyte FGF9 signaling. |
| Final model | Neuron → FGF9 → FGFR3 on astrocyte → FGFR-associated intracellular signaling → potential changes in astrocyte function. The complete downstream sequence remains a proposed mechanism in this activity. |

## Laboratory Activity Questions

### 1. What sender cell did you choose, and in what tissue or biological context does it act?

I chose the neuron as the potential sender cell. Brandebura et al. (2022) found that *Fgf9* was enriched in neurons in the mouse medial nucleus of the trapezoid body (MNTB), a region of the brainstem. This provides published evidence supporting neurons as a source of FGF9 in this specific biological context.

### 2. What signaling molecule did you identify, and what evidence supports its production or presentation by the sender cell?

The selected ligand is fibroblast growth factor 9 (FGF9; UniProt P31371). The Human Protein Atlas provides information about its expression and protein localization. In addition, Brandebura et al. (2022) reported neuronal *Fgf9* enrichment in the mouse MNTB, supporting its role as a potential neuronal signaling molecule.

### 3. What receptor receives the signal, and which receiver cell did you select?

The selected receptor is fibroblast growth factor receptor 3 (FGFR3; UniProt P22607), a receptor tyrosine kinase. The receiver cell is an astrocyte because the Human Protein Atlas reports FGFR3 expression in astrocytes. Brandebura et al. (2022) also found *Fgfr3* enrichment in astrocytes in the mouse MNTB, supporting this proposed receiver cell.

### 4. What type of cell-to-cell signaling is represented: paracrine, endocrine, autocrine, or contact-dependent?

The proposed model represents paracrine signaling because FGF9 is a secreted signaling protein that can act on a nearby cell expressing a compatible receptor. Published research supports neuron-to-astrocyte FGF9 signaling during mouse brainstem development. However, the database records in this activity do not independently demonstrate the exact distance or direct communication between an individual neuron and astrocyte.

### 5. Which proteins in your STRING network appear most relevant to the receptor-associated response? Explain briefly.

FGFR3, FRS2, GRB2, SOS1, and HRAS are relevant to the proposed receptor-associated signaling network. FGFR3 is the receptor, FRS2 is an adaptor protein associated with FGF receptor signaling, GRB2 helps connect signaling components, SOS1 participates in RAS activation, and HRAS is involved in downstream intracellular signaling. STRING supports functional associations among proteins, but these associations do not necessarily demonstrate direct physical binding or confirm that the entire sequence occurs in astrocytes responding to neuronal FGF9.

### 6. What enriched pathway or biological process is consistent with your proposed mechanism?

The STRING results included the fibroblast growth factor receptor signaling pathway (GO:0008543), with 9 of 59, an enrichment strength of 2.44, and an FDR of 6.89 × 10⁻¹⁸. This enrichment supports the relevance of the selected proteins to FGFR-associated signaling. However, pathway enrichment does not independently establish that every protein in the proposed sequence participates in the same cell-specific response.

### 7. What did IntAct show for the molecular interaction you examined? What type of evidence was reported?

IntAct listed an FGFR3–FRS2 association supported by proximity-dependent biotin identification (BioID), with PMID 35384245 and an MI score of 0.27 in the recorded result. BioID identifies proteins located near a protein of interest, so the result supports their proximity in the reported experimental context rather than necessarily demonstrating direct binding. Because the recorded experiment involved HEK293 cells, it does not independently establish the same interaction in astrocytes.

### 8. Which parts of your final model are strongly supported, and which parts remain an inference?

The FGF9–FGFR3 molecular relationship is supported by receptor-binding literature and the OmniPath annotation. Published research by Brandebura et al. (2022) also supports neuronal FGF9 signaling in relation to astrocyte maturation during mouse brainstem development. The HPA, STRING, and IntAct results provide additional expression and molecular association evidence. However, the complete sequence from neuronal FGF9 release through FGFR3 and every downstream signaling component has not been established by the database results alone.

### 9. What cellular response is expected in the receiver cell, and why?

A potential response is a change in astrocyte function, including astrocyte maturation. Brandebura et al. (2022) found that deleting *Fgf9* from principal neurons affected astrocyte maturation and other features of the developing mouse brainstem. These findings support a functional role for neuronal FGF9 signaling. However, they do not establish that every observed effect is mediated exclusively through FGFR3 or through the complete downstream sequence proposed in this activity.

## References

Brandebura, A. N., Kolson, D. R., Amick, E. M., Ramadan, J., Kersting, M. C., Nichol, R. H., Holcomb, P. S., Mathers, P. H., Stoilov, P., & Spirou, G. A. (2022). Transcriptional profiling reveals roles of intercellular Fgf9 signaling in astrocyte maturation and synaptic refinement during brainstem development. *Journal of Biological Chemistry, 298*(8), 102176. https://doi.org/10.1016/j.jbc.2022.102176

Hecht, D., Zimmerman, N., Bedford, M., Avivi, A., & Yayon, A. (1995). Identification of fibroblast growth factor 9 (FGF9) as a high affinity, heparin dependent ligand for FGF receptors 3 and 2 but not for FGF receptors 1 and 4. *Growth Factors, 12*(3), 223–233. https://pubmed.ncbi.nlm.nih.gov/8619928/

IntAct. (n.d.). *Molecular interaction database*. https://www.ebi.ac.uk/intact/

OmniPath. (n.d.). *OmniPath: A comprehensive collection of molecular biology prior knowledge*. https://omnipathdb.org/

STRING. (n.d.). *STRING: Functional protein association networks*. https://string-db.org/

The Human Protein Atlas. (n.d.). *The Human Protein Atlas*. https://www.proteinatlas.org/

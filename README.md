## Biopython Lab — Sequence Analysis

### Overview

This repository contains my Biopython lab work on retrieving and analyzing nucleotide sequences from the **NCBI Nucleotide database**.

The lab demonstrates sequence searching, retrieval, GC content calculation, and FASTA file creation using Python and Biopython.

### Part 1: TP53

The human **TP53** gene was used to demonstrate the complete workflow:

- Search NCBI for a gene sequence
- Retrieve a nucleotide sequence
- Determine sequence length
- Calculate GC content
- Save the sequence in FASTA format

Search term:

```text
TP53[Gene] AND Homo sapiens[Organism]
```

### Part 2: COX-2 (PTGS2)

The **PTGS2** gene, commonly known as COX-2, was analyzed in:

- *Homo sapiens* (human)
- *Danio rerio* (zebrafish)

Search terms:

```text
PTGS2[Gene] AND Homo sapiens[Organism]
```

```text
PTGS2[Gene] AND Danio rerio[Organism]
```

For both species, the sequence ID, sequence length, first 100 bases, and GC content were analyzed.

The two sequences were then combined into a single multi-FASTA file:

```text
COX2_human_zebrafish.fasta
```

### Repository Contents

| File | Description |
|---|---|
| `Biopython_Lab.ipynb` | Completed Colab notebook |
| `COX2_human_zebrafish.fasta` | Human and zebrafish PTGS2 sequences |
| `README.md` | Project documentation |

### Tools

- Python
- Biopython
- Google Colab
- NCBI Nucleotide Database
- FASTA

### Author

***Paul Obonyo***

```text
This repository contains coursework completed as part of a Biopython sequence-analysis lab.
```

---

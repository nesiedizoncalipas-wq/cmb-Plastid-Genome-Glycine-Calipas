# Characterization of a Plastid Genome: *Glycine*

## 1. Student and Course Information

- **Student Name:** Nesiedizon Calipas
- **Course:** Cell and Molecular Biology
- **Section:** B
- **Chosen Genus:** *Glycine*
- **Selected Species:** *Glycine soja*

## 2. Genome Information

- **Organism:** *Glycine soja* isolate HAAS216
- **NCBI Accession/Version:** PX591265.1
- **Genome Type:** Complete chloroplast genome
- **Genome Length:** 152,222 base pairs (bp)
- **Family:** Fabaceae
- **Topology:** Circular, as reported in the GenBank record
- **NCBI Source:** [Glycine soja chloroplast genome — PX591265.1](https://www.ncbi.nlm.nih.gov/nuccore/PX591265.1)
- **Date Retrieved:** 10/05/26
  
## 3. Genome Summary

The genome used in this activity is the complete chloroplast genome of *Glycine soja* isolate HAAS216. The sequence is 152,222 bp long and belongs to the plant family Fabaceae. Chloroplast genomes contain genes involved in photosynthesis, transcription, translation, and other functions needed for chloroplast activity.

The Galaxy sequence statistics showed one sequence record, a GC content of 35.37%, and no ambiguous N bases. The sequence contains more adenine (A) and thymine (T) than guanine (G) and cytosine (C), indicating an AT-rich nucleotide composition.

## 4. Genome Download and Galaxy Workflow

The genome was obtained from the NCBI Nucleotide database using accession PX591265.1. The sequence was downloaded in FASTA format for sequence statistics, while the annotated GenBank record was used as a reference for identifying genome features and genes.

The FASTA sequence was uploaded to Galaxy at [usegalaxy.org](https://usegalaxy.org/). The FASTA sequence statistics tool was used to examine the sequence length, number of records, nucleotide composition, and GC content.

- **Galaxy History Name:** `Plastid_Glycine_Calipas`
- **Input Dataset:** *Glycine soja* isolate HAAS216 chloroplast FASTA sequence
- **Tool Used:** FASTA sequence statistics tool in Galaxy
- **Main Results:** 152,222 bp; 1 sequence record; 35.37% GC content

## 5. Gene Content and Important Observations

The annotated chloroplast genome contains genes associated with photosynthesis, gene expression, and protein synthesis. Examples include:

| Gene | General function |
|---|---|
| `psbA` | Encodes the D1 protein of photosystem II |
| `psaA` | Encodes a core protein of photosystem I |
| `rbcL` | Encodes the large subunit of RuBisCO, involved in carbon fixation |
| `atpB` | Encodes a subunit of ATP synthase |
| `petB` | Encodes a component of the cytochrome b6f complex |
| `rpoB` | Encodes a subunit of the plastid RNA polymerase |
| `rps16` | Encodes a ribosomal protein |
| `matK` | Encodes a maturase associated with intron splicing |

The Galaxy results indicate that the genome is AT-rich, with a GC content of 35.37%. The FASTA file contained one sequence record and no ambiguous N bases. Exact gene totals, duplicated gene copies, intron locations, and genome-region boundaries should be based on the complete annotated GenBank record.

## 6. Data Sources and References

1. **NCBI Nucleotide / GenBank.** *Glycine soja* isolate HAAS216 chloroplast, complete genome. Accession PX591265.1. [https://www.ncbi.nlm.nih.gov/nuccore/PX591265.1](https://www.ncbi.nlm.nih.gov/nuccore/PX591265.1)
2. **Galaxy Project.** Galaxy platform for accessible, reproducible, and collaborative data analysis. [https://usegalaxy.org/](https://usegalaxy.org/)
3. **Wang, S. and Bi, Y.** *The complete chloroplast genome of wild soybean (Glycine soja) isolate HAAS216.* GenBank direct submission, 2025, as listed in the NCBI record.

## 7. Reproducibility

Another student can repeat this analysis by opening the NCBI record for PX591265.1, downloading the FASTA sequence, and uploading it to Galaxy. They can then run the FASTA sequence statistics tool and compare the sequence length, number of records, and GC content with the results reported here. The annotated GenBank record can be used to check gene features and genome organization. The accession number and software information are provided so the workflow can be repeated.


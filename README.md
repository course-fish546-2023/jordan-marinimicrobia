# jordan-marinimicrobia

Rpubs: https://rpubs.com/jwinter2/ssu16s

Zenodo DOI: https://doi.org/10.5281/zenodo.7967443

Slides: https://rpubs.com/jwinter2/qslides05

For this project, I'll be working with MAGs (metagenome-assembled genomes). Specifically, I'll be looking at *Sulfitobacter pontiacus*, a sulfur oxidizing species of marine bacteria. I created a heatmap of the different genes in my MAGs and complete genomes from NCBI. I want to know if my MAGs from the ODZ are different than genomes in culture.

*End goal: heatmap. This entails the following workflow:*
- Verify my MAGs are *Sulfitobacter pontiacus*
- Annotate bins (which are Sulfitobacter, which bins to use, Busco statistics, which bin is which clade)
- Visualization in anvio (refine bins, make pangenome)
- Kegg orthologs and heatmap (get genes in each bin, which genes are different)

*The data is located here, last updated 4/4/23:* https://drive.google.com/drive/folders/1OXxGidW8jpFo5yJQGMCA6CkAvpEsdor-?usp=share_link

This metagenome is from the Eastern Tropical North Pacific oxygen deficient zone at 585 m.

*Types of data I have to work with in folders in Google Drive:*

Annotations:

- Kegg orthologs for each gene (KO_best_only file)
- Annotated amino acid and nucleotide sequences for the metagenome

Assembly:

- Contig lengths
- Assembly depth
- Fasta file of entire metagenome (assembled contigs and individual reads)
- Coverage information
- Bam file
- Output from hifiasm, which was used to generate contigs

Bins:

- list of contigs and reads in each bin for each binning method

CAT-BAT:
- information on the organism ID of each contig and read, as well as each gene in each contig and read
- mar ref db used for CAT

*Hash:* 1efa55285fd040142179f15a0538a2053609b0b6
Generated using shasum on the Google Drive folder containing my raw data

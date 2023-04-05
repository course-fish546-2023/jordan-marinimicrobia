# jordan-marinimicrobia

For this project, I'll be working with MAGs (metagenome-assembled genomes). Specifically, I'll be looking at Marinimicrobia, an uncultured phylum of marine bacteria involved in global biogeochemical cycling. I plan to do a pangenomic analysis of the phylum.

The data is located here, last updated 4/4/23: https://drive.google.com/drive/folders/1OXxGidW8jpFo5yJQGMCA6CkAvpEsdor-?usp=share_link

This metagenome is from the Eastern Tropical North Pacific oxygen deficient zone at 585 m.

Types of data I have to work with in folders:

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

Hash: acc9c03889fc92438025a01f126d510721ecca77

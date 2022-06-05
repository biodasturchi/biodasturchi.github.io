---
layout: default
---

### 1.7 NCBI Genomes & NCBI Assembly

**Prerequisite Terminologies:**

In order to have a better understanding of the main topic, you should get yourself familiar with the following term:

- Introduction to NCBI.
- Genome.
- FTP format.
- RefSeq database.
- Genome annotations.
- Genome Assembly.
- Scaffold.

**Introduction**

**Genome** is a sub-database of NCBI which allows us to retrieve an entire genome of an organism/species, which can be sequences, genomic maps, genomic assemblies, or annotations. It is a comprehensive database that has a huge number of genome assemblies that can be retrieved or downloaded from this database. It is an open platform for your researchsubmission, hence you can submit your research findings on a particular genome and it’ll be available for other researchers as well. 

**Assembly** is also a sub-database of NCBI, which contains the information from assembled genomes. It means the genomes that are available within this database are completely sequenced and are available for metadata statistical reports with assembly names and other information of this sort.

**Steps:**

- Click on the link below to visit the homepage of NCBI: https://www.ncbi.nlm.nih.gov/
- On the right hand side of the page, from the ‘Popular Resources’ list, click on the ‘Genome’ hyperlink. OR
- Or select the ‘Genome’ option from the databases list and in thesearch box enter the organism or species name, you’d like. OR
- Click on the link below to visit the homepage of ‘Genome’ database:https://www.ncbi.nlm.nih.gov/genome/
- On the homepage of Genome database, it provides the hyperlinks to:
    
    | Name | Resource |
    | --- | --- |
    | Other Resources | Assembly, BioProject, BioSample, Genome Data Viewer, NCBI Datasets. |
    | Custom Resources: | Human Genome, Microbes, Organelles, Viruses, Prokaryotic reference genome. |
    | Using Genome: | Help, Browse by Organism, Download/FTP, Download FAQ, Submit a genome. |
    | Genome Tools: | BLAST the human genome, Microbial nucleotide BLAST. |
    | Genome Annotation and Analysis: | Eukaryotic Genome Annotation, Prokaryotic Genome Annotation, Pairwise sequence analysis (PASC). |
    | External Resources: | GOLD-Genomes Online Database, Bacterial Genomes at Sanger, Ensembl. |

**Note**: The BLAST available on this database works only with Human Genome/Microbial nucleotides Genome and is quite different from the BLAST available on public domain.

- Click on the hyperlink of ‘Browse by Organism’, it’ll open a separate webpage where you can search any particular genome by entering the name of the organism.
    - In the ‘Overview’, it provides the total number of entries present on this database.
    - Then it also provides the hyperlinks to separate kingdoms with their names and entries present within these kingdoms, e.g., Eukaryotes (12094), Prokaryotes (252264), etc.
        - By clicking on one of these hyperlinks, you can filter your results to that kingdom/species only.
    - Below the ‘Overview’ button, it provides the information to all the entries present within the database and also the respective hyperlinks to the entries.
        - The first column contains the ‘Sr. #’ of the entries in the table, then in the next column is the ‘Organism’s Name’, then in the next column it provides the ‘Organism Groups’ (lineage of the organisms), then it provides the ‘Size’ of the genome and then ‘Chromosomes’, ‘Organelles’, ‘Plasmid’, and ‘Assembles’ in the next columns respectively.
- Enter the name of a particular organism (e.g., Aves) in the search box, to get the list of all the species/organism related to that particular organism you’ve searched for.
- You can filter your results in a more meaningful way by clicking on the ‘Filter’ button present on the top right corner of the webpage.
    - For example, you can filter the results by applying filters to a particular group, subgroup, assembly level, partial, anomalous, etc.
    - After filtering the results, it’ll provide you the filtered results in a tabular form, where you can click on a particular entry and it’ll directly take you to the respective organism’s genome page.
    - By clicking on a particular hyperlink in the table, it’ll take you directly to the respective webpage to provide you more information.
        - For example, when you click on the ‘Proteins’ of a particular entry, it’ll provide you the results in the tabular form, where all the proteins present in that organism are listed.
        - You can filter the results by clicking on the ‘Chromosome 1’ to get the information about the proteins encoded by the genes located on chromosome number 1.
        - There you can find the Non-redundant chromosome accession of the entries listed in the table as well as other information including ‘GeneID’, ‘Strand’, ‘Starting point’ and ‘Ending point’, ‘Protein Product’ (contains the protein accessions), etc.
    - You can download a particular genome from RefSeq or Genome databases, by clicking on the respective FTP link present in the last column of the table.

**➢ Retrieving a genome of interest from the Genome database:**

- Click on the link below and then enter the name of the organism (e.g., Aves) in the search box and press ENTER. https://www.ncbi.nlm.nih.gov/genome/browse#!/overview/
- Click on a particular entry (e.g., Gallus gallus) and it’ll open the homepage of that organism’s genome.
- It’ll provide the basic information on top of the webpage, for example the download hyperlinks for that particular entry is provided on the top of the page, and by clicking that links, you can download the whole genome of the organism, its transcripts or proteins in FASTA format.
    - Similarly you can download the genome annotation files in GFF, GenBank or tabular formats by clicking on the respective link.
    - You can also perform BLAST analysis on the genome, transcripts, or proteins of the particular organism by clicking on the respective link.
    - Then it provides the list of genomes for the particular species you’ve searched for, and to browse the list, click on the respective link.
    - Then you can also download the whole genome of the particular organism you are looking for, by clicking on the GenBank or RefSeq hyperlinks provided there, which will download the genome file in FTP format.
- Then below this area, it provides the name of the organism, its ‘Genome assembly and Annotation Report’, the ‘Lineage’ of the organism and its ‘Summary’ as well.
- Then it provides the ‘Replicon Info’ in the tabular form, which provides you the comprehensive chromosome-wise information of the genome, where it provides the information about the:
    - ‘RefSeq’ accession of the entries,
    - INSDC (International Nucleotide sequence Database collaboration) accession,
    - the ‘Size (Mb)’ only for the particular chromosome,
    - the ‘GC%’ of the particular chromosome,
    - the ‘Proteins’ encoded by the genes,
    - The RNAs (rRNA, tRNA and others) information each chromosome entry.
    - The ‘Gene count’ and the ‘Pseudogenes’ as well.
    - Then at the end of the table (row-wise), it also provides the information about the Mitochondrial (mt) genome present in that particular organism you are working on.
- Then it provides the graphical representation of the chromosomes, i.e., higher the length of the bar, the lengthier the chromosome will be, and vice versa.● Then it provides the graphical view of the ‘Genome Region’, where you can find a particular region from the genome you are working on, and you can also download the genome of that particular region.
    - You can zoom-in and zoom-out from a particular region of the genome.

**➢ FTP format analysis:**

- Click on the RefSeq or GenBank from the Download options to go to the FTP page of the genome, which provides all the information and on a single page, so you don’t need to visit different pages to retrieve that information.
- Clicking on any particular link on this page, it’ll download the respective information in GFF or FASTA format based on the information you want to retrieve. [You should use this page to download a particular file from the genome you are working on, rather than visiting different pages to retrieve the information.]
- Click on the link below to visit the RefSeq page of all the genomes available on the homepage of the Genome database: https://ftp.ncbi.nlm.nih.gov/genomes/refseq/
- Click on any genome (e.g., Plants) and choose a particular entry (e.g., Arabidopsis thaliana) to get all the assemblies that are available in the genome of that particular organism.
    - Then go to the latest assembly version of the genome and it’ll provide you the same FTP information for the Arabidopsis thaliana, as it displayed before.
- You can visit this FTP page by entering the organism’s name (e.g., Arabidopsis thaliana) in the search box of the Genome homepage.
    - Click on the genome of interest and then click on G or R hyperlinks given in the last column of the table of the genome.
    - It’ll take you to the FTP representation of the genome assemblies of the particular genome.
    - Clicking on a particular link on this page, it’ll either start downloading the file or will send the request to the database servers for downloading the specific information, and after the acceptance of the request, it’ll download the file.

**➢ Retrieval of an assembled genome from NCBI:**

- Click on the link below to visit the Assembly Database of NCBI: https://www.ncbi.nlm.nih.gov/assembly/organism/
- Alternatively, you can select the ‘Assembly’ from the database list and enter the name of the genome of interest on the homepage of NCBI.
- It’ll provide the ‘Assembly information by Organisms’ in a tabular form, where it provides information about the genomes of different organisms, their names, date of publishing the genome as fully sequenced genome, assembly level (Scaffold or chromosome), etc.
- Click on a particular hyperlink (name of the entry), to open the assembly page of the particular species.
- To download a particular assembly, click on the ‘Download Assembly’ button and then select the required database (RefSeq or GenBank), then select the information files of your choice or select all types of information to download all the files and press the ‘Download’ button.
- Then on the assembly page of a particular organism, it provides the basic information on the top of the page like the ‘Organism’s name’, its ‘Description’, ‘BioSample’ and ‘BioProject’ accessions, etc.

**Note:** You should always use the RefSeq database to retrieve the genomic information.

- Then it provides the ‘Global Statistic’ which provides different statistical information about the total number of regions with alternative loci or patches, Total sequence length, No. of Scaffolds, Gaps between the Scaffolds, etc.
- Then it provides the ‘Assembly Definition’ and ‘Assembly Statistics’ in a tabular form.
- The ‘Assembly Statistics’ is more likely to be used by data scientists, since it provides huge statistical datasets for statistical analysis of the genome.
- The ‘Assembly Definition’ table provides chromosome-wise information about the particular genome. By clicking on the accession of a particular chromosome, you’ll be able to download the information about that particular chromosome.

**Note:** If you’ve downloaded the GFF files of any particular genome, or the genome annotation files, you should never open that files on you Windows OS, since it takes a lot of storage on real time on your RAM, so it can be harmful for your PC. If you’re working with Linux OS or MacOS, then you should follow the specific procedure to open the files on the respective operating systems.

**Summary:**

In this video tutorial of NCBI, we came to know about the two sub-databases of NCBI to retrieve and analyze the genomes of an organism. We got to know how to retrieve and analyze an entire genome of an organism using the “Genomes” database of NCBI and also came to know about the FTP format to download the genomic information from RefSeq or GenBank databases. And from the “Assembly” database of NCBI, we got to know the procedure to download and retrieve the fully sequenced genomes provided by NCBI and other integrated databases.

[Back](../../)
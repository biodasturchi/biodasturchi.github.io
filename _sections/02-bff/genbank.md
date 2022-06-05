---
layout: default
---

### 2.1 GenBank (Sequence Annotation Format)

**Prerequisite Terminologies**
Before proceeding to the topic, it is important to be aware of the
followings to have the better understanding:
- Accession Number
- Sequence Retrieval using NCBI
- Flat File format

**GenBank**
GenBank format is a flat file format (also referred as *GenBank Flat File
Format*) that organizes and stores the sequence and its annotation
together. It is divided into two sections:
1. Annotation or Feature section
2. Sequence section
The purpose of this highly organized way of providing additional data is
to make it possible for this information to be standardized for human
interpretation, and to be handled by many different computer programs.

**Annotation or Feature Section**
The first or annotation section contains the entry’s *LOCUS*, *DEFINITION*,
*ACCESSION* and *VERSION* and denoted by *ORIGIN*. The final detail is the
actual sequence. These five elements are the essential parts of the
GenBank format.
The non-essential parts of the entry contain what is commonly known as
*metadata*, and can include more detailed information about the
organism, cross-references to other databases, and even a list of
publications in which this entry is featured in. The *FEATURES* part of the
entry describes important characteristics of the entry’s sequence such as
presence of *coding sequences, proteins*, etc. The rest of this part is
intended for the computer program to read it.

**Sequence Section**
This section contains the actual sequence that we want to study. The
sequence might be in the form of nucleotides or amino acids just as the
FASTA format. The sequence is distributed in 6 columns and each
column consists of 10 residues either nucleotides or amino acids which
tells us that each row has 60 residues. At the end of the sequence ‘//’ in
order to indicate the end of the entry.

**Syntax**
The syntax for the GenBank is designed as:
```genbank
LOCUS         AB000000      000 bp    mRNA    linear    PRI 01.01.1970
DEFINITION    Homo sapiens mRNA................................
ACCESSION     AB000000
ORIGIN    1 acaagatgcc attgtccccc ggcctcctgc tgctgctgct ctccggggcc acggccaccg
         61 ctgccctgcc cctggagggt ggccccaccg gccgagacag cgagcatatg caggaagcgg
        121 caggaataag gaaaagcagc ctcctgactt tcctcgcttg gtggtttgag tggacctccc
        181 aggccagtgc cgggcccctc ataggagagg aagctcggga ggtggccagg cggcaggaag
        241 gcgcaccccc ccagcaatcc gcgcgccggg acagaatgcc ctgcaggaac ttcttctgga
        301 agaccttctc ctcctgcaaa taaaacctca cccatgaatg ctcacgcaag tttaattaca
        361 gacctgaa
//
```

**LOCUS**
The LOCUS field contains a number of different data elements, including
locus name, sequence length, molecule type, GenBank division, and
modification date.

**DEFINITION**
Brief description of sequence; includes information such as source
organism, gene name/protein name, or some description of the
sequence's function.

**ACCESSION**
The unique identifier for a sequence record.
The above example briefly describes the syntax. Originally, the GenBank
format contains the huge amount of information about the sequence.

**Summary**
In this tutorial, we’ve learnt about the GenBank format which stores the
sequence as well as annotates it. And it has two sections that consists
Annotation or feature section and Sequence section. We have taken the
example of Homo sapiens Lactase. You can choose the sequence that
you may require.

[Back](../../)
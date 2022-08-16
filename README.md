# LOBSTERS
League Of Backbone plasmid vector Series To Expand the Range of Selection markers  (LOBSTERS) for genome editing in budding yeast

# A series of genome-editing plasmid vectors for <I>Saccharomyces cerevisiae</I>.
Features of the plasmid series are:
- Three Cas systems (SpCas9, SaCas9, and enAsCas12a) are available.
- A Cas gene and the cognate sgRNA/crRNA gene are encoded on a single centromeric plasmid.
- The target sequence can be inserted by the Golden Gate Assembly.
- The expression of the Cas gene and/or the sgRNA/crRNA gene are under the control of the <I>GAL1</I> promoter.
- Six marker genes (<I>KanMX</I>, <I>HphMX</I>, <I>NatMX</I>, <I>HIS3</I>, <I>LEU2</I>, and <I>URA3</I>) are available.

## Available plasmids
|  Number  |  Cas type    |  Marker gene  |  Promoter for Cas gene  |  Promoter for sgRNA/crRNA  |  Terminator for sgRNA/crRNA  |  Plasmid type  |
| -------- | ------------ | ------------- | ----------------------- | -------------------------- | ---------------------------- | -------------- |
|  25-27   |  SpCas9      | <I>KanMX </I> |  <I> pGAL1 </I>         | <I> pGAL1 </I>             | <I> tCYC1 </I>               | Centromeric    |
|  25-28   |  SpCas9      | <I>HphMX </I> |  <I> pGAL1 </I>         | <I> pGAL1 </I>             | <I> tCYC1 </I>               | Centromeric    |
|  25-29   |  SpCas9      | <I>NatMX </I> |  <I> pGAL1 </I>         | <I> pGAL1 </I>             | <I> tCYC1 </I>               | Centromeric    |
|  25-30   |  SpCas9      | <I> HIS3 </I> |  <I> pGAL1 </I>         | <I> pGAL1 </I>             | <I> tCYC1 </I>               | Centromeric    |
|  25-31   |  SpCas9      | <I> LEU2 </I> |  <I> pGAL1 </I>         | <I> pGAL1 </I>             | <I> tCYC1 </I>               | Centromeric    |
|  16-15   |  SpCas9      | <I> URA3 </I> |  <I> pGAL1 </I>         | <I> pGAL1 </I>             | <I> tCYC1 </I>               | Centromeric    |
|  25-32   |  SaCas9      | <I>KanMX </I> |  <I> pGAL1 </I>         | <I> pGAL1 </I>             | <I> tCYC1 </I>               | Centromeric    |
|  25-33   |  SaCas9      | <I>HphMX </I> |  <I> pGAL1 </I>         | <I> pGAL1 </I>             | <I> tCYC1 </I>               | Centromeric    |
|  25-34   |  SaCas9      | <I>NatMX </I> |  <I> pGAL1 </I>         | <I> pGAL1 </I>             | <I> tCYC1 </I>               | Centromeric    |
|  25-35   |  SaCas9      | <I> HIS3 </I> |  <I> pGAL1 </I>         | <I> pGAL1 </I>             | <I> tCYC1 </I>               | Centromeric    |
|  25-36   |  SaCas9      | <I> LEU2 </I> |  <I> pGAL1 </I>         | <I> pGAL1 </I>             | <I> tCYC1 </I>               | Centromeric    |
|  17-31   |  SaCas9      | <I> URA3 </I> |  <I> pGAL1 </I>         | <I> pGAL1 </I>             | <I> tCYC1 </I>               | Centromeric    |
|  25-37   |  enAsCas12a  | <I>KanMX </I> |  <I> pGAL1 </I>         | <I> pGAL1 </I>             | <I> tCYC1 </I>               | Centromeric    |
|  25-38   |  enAsCas12a  | <I>HphMX </I> |  <I> pGAL1 </I>         | <I> pGAL1 </I>             | <I> tCYC1 </I>               | Centromeric    |
|  25-39   |  enAsCas12a  | <I>NatMX </I> |  <I> pGAL1 </I>         | <I> pGAL1 </I>             | <I> tCYC1 </I>               | Centromeric    |
|  25-40   |  enAsCas12a  | <I> HIS3 </I> |  <I> pGAL1 </I>         | <I> pGAL1 </I>             | <I> tCYC1 </I>               | Centromeric    |
|  25-41   |  enAsCas12a  | <I> LEU2 </I> |  <I> pGAL1 </I>         | <I> pGAL1 </I>             | <I> tCYC1 </I>               | Centromeric    |
|  16-16   |  enAsCas12a  | <I> URA3 </I> |  <I> pGAL1 </I>         | <I> pGAL1 </I>             | <I> tCYC1 </I>               | Centromeric    |

Plasmid sequence data are available from the links below:

![Plasmid sequences in SnapGene format](https://github.com/poccopen/Genome_editing_plasmid_for_budding_yeast/tree/master/Plasmid_sequence_files%20(SnapGene))

![Plasmid sequences in GenBank format](https://github.com/poccopen/Genome_editing_plasmid_for_budding_yeast/tree/master/Plasmid_sequence_files%20(GenBank))

![Plasmid sequences in plain text format](https://github.com/poccopen/Genome_editing_plasmid_for_budding_yeast/tree/master/Plasmid_sequence_files%20(Plain%20text))

## GUI application for oligo DNA design
Oligo DNA sequences for the Golden Gate Assembly can be designed by a python script (graphical user interface version).
- sgRNA_crRNA_oligo_designer_GUI.py

PySimpleGUI is required to run the script.

https://pysimplegui.readthedocs.io/en/latest/


```
python sgRNA_crRNA_oligo_designer_GUI.py
```

![GUI](https://github.com/poccopen/Genome_editing_plasmid_for_budding_yeast/blob/master/images/sgRNA_crRNA_designer_GUI.png)

A binary version is available (only for Windows users).
- sgRNA_crRNA_oligo_designer_GUI.exe


## Scripts to identify "editable" nucleotides and "editable" ORFs at the 5' end in the budding yeast reference genome
- Editable_fraction_of_yeast_genome.py
- ORFs_editable_at_the_5_ends.py

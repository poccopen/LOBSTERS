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
|  Number  | Plasmid name                 | Cas type     |  Marker gene  |
| -------- | ---------------------------- | ------------ | ------------- |
|  25-27   | pLOBSTER-SpCas9-Kan(empty)   |  SpCas9      | <I>KanMX </I> |
|  25-28   | pLOBSTER-SpCas9-Hyg(empty)   |  SpCas9      | <I>HphMX </I> |
|  25-29   | pLOBSTER-SpCas9-Nat(empty)   |  SpCas9      | <I>NatMX </I> |
|  25-30   | pLOBSTER-SpCas9-His(empty)   |  SpCas9      | <I> HIS3 </I> |
|  25-31   | pLOBSTER-SpCas9-Leu(empty)   |  SpCas9      | <I> LEU2 </I> |
|  16-15   | pLOBSTER-SpCas9-Ura(empty)   |  SpCas9      | <I> URA3 </I> |
|  25-32   | pLOBSTER-SaCas9-Kan(empty)   |  SaCas9      | <I>KanMX </I> |
|  25-33   | pLOBSTER-SaCas9-Hyg(empty)   |  SaCas9      | <I>HphMX </I> |
|  25-34   | pLOBSTER-SaCas9-Nat(empty)   |  SaCas9      | <I>NatMX </I> |
|  25-35   | pLOBSTER-SaCas9-HIS(empty)   |  SaCas9      | <I> HIS3 </I> |
|  25-36   | pLOBSTER-SaCas9-Leu(empty)   |  SaCas9      | <I> LEU2 </I> |
|  17-31   | pLOBSTER-SaCas9-Ura(empty)   |  SaCas9      | <I> URA3 </I> |
|  25-37   |pLOBSTER-enAsCas12a-Kan(empty)|  enAsCas12a  | <I>KanMX </I> |
|  25-38   |pLOBSTER-enAsCas12a-Hyg(empty)|  enAsCas12a  | <I>HphMX </I> |
|  25-39   |pLOBSTER-enAsCas12a-Nat(empty)|  enAsCas12a  | <I>NatMX </I> |
|  25-40   |pLOBSTER-enAsCas12a-HIS(empty)|  enAsCas12a  | <I> HIS3 </I> |
|  25-41   |pLOBSTER-enAsCas12a-Leu(empty)|  enAsCas12a  | <I> LEU2 </I> |
|  16-16   |pLOBSTER-enAsCas12a-Ura(empty)|  enAsCas12a  | <I> URA3 </I> |

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

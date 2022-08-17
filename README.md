## LOBSTERS
**L**eague **O**f **B**ackbone plasmid vector **S**eries **T**o **E**xpand the **R**ange of **S**election markers for genome editing in <I>Saccharomyces cerevisiae</I>

## An expanded series of genome-editing plasmid vectors for budding yeast.
Features of the plasmid series are:
- Three Cas systems (SpCas9, SaCas9, and enAsCas12a) are available.
- A Cas gene and the cognate sgRNA/crRNA gene are encoded on a single centromeric plasmid.
- The target sequence can be inserted by the Golden Gate Assembly.
- The expression of the Cas gene and/or the sgRNA/crRNA gene are under the control of the <I>GAL1</I> promoter.
- Six marker genes (<I>KanMX</I>, <I>HphMX</I>, <I>NatMX</I>, <I>HIS3</I>, <I>LEU2</I>, and <I>URA3</I>) are available.

![Schematic](https://github.com/poccopen/LOBSTERS/blob/main/pLOBSTERs_schematic.png)

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
|  25-35   | pLOBSTER-SaCas9-His(empty)   |  SaCas9      | <I> HIS3 </I> |
|  25-36   | pLOBSTER-SaCas9-Leu(empty)   |  SaCas9      | <I> LEU2 </I> |
|  17-31   | pLOBSTER-SaCas9-Ura(empty)   |  SaCas9      | <I> URA3 </I> |
|  25-37   |pLOBSTER-enAsCas12a-Kan(empty)|  enAsCas12a  | <I>KanMX </I> |
|  25-38   |pLOBSTER-enAsCas12a-Hyg(empty)|  enAsCas12a  | <I>HphMX </I> |
|  25-39   |pLOBSTER-enAsCas12a-Nat(empty)|  enAsCas12a  | <I>NatMX </I> |
|  25-40   |pLOBSTER-enAsCas12a-His(empty)|  enAsCas12a  | <I> HIS3 </I> |
|  25-41   |pLOBSTER-enAsCas12a-Leu(empty)|  enAsCas12a  | <I> LEU2 </I> |
|  16-16   |pLOBSTER-enAsCas12a-Ura(empty)|  enAsCas12a  | <I> URA3 </I> |

Plasmid sequence data are available from the links below:

![Plasmid sequences in SnapGene format](https://github.com/poccopen/LOBSTERS/tree/main/pLOBSTERs_SnapGene)

## An application for oligo DNA design
### For python users (on Windows, MacOS, Linux, etc.)
Oligo DNA sequences for the Golden Gate Assembly can be designed by a python script. [gRNA_oligo_designer_for_pLOBSTERs.py](https://github.com/poccopen/LOBSTERS/tree/main/gRNA_oligo_designer_for_pLOBSTERs.py)

PySimpleGUI is required to run the script. https://pysimplegui.readthedocs.io/en/latest/

[Usage] `python gRNA_oligo_designer_for_pLOBSTERs.py`

### For Windows users
A binary version of the python script is available only for Windows. [gRNA_oligo_designer_for_pLOBSTERs.exe](https://www.dropbox.com/s/k9lh0sh21y4bi90/gRNA_oligo_designer_for_pLOBSTERs.exe?dl=0)

[Usage] Simply double-click the .exe file.

![Screen shot](https://github.com/poccopen/LOBSTERS/blob/main/gRNA_oligo_designer_for_pLOBSTERs.png)

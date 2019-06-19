# Centre for Trophoblast Research: Placental Bioinformatics Course

<sup>Version 0.3: 20180705</sup>

Russell S. Hamilton (rsh46@cam.ac.uk), Xiaohui Zhao (xz289@cam.ac.uk) & Malwina Prater (mn367@cam.ac.uk)


## An introduction to RNA-Seq ##


### Objective for the practical ###

- To learn about how to process, analyse and interpret RNA-Seq data


### Learning goals ###

- Experience using the Linux operating system (Ubuntu)
- Learn how to run bioinformatics tools on the command line
-	Learn how to use R and R-studio
-	Visualise sequencing alignments in a genome browser


### Materials ###

#### Publication ####

The data are from

Stumpo, D.J., Trempus, C.S., Tucker, C.J., Huang, W., Li, L., Kluckman, K., Bortner, D.M. and Blackshear, P.J. (2016) Deficiency of the placenta and yolk sac specific tristetraprolin family member ZFP36L3 identifies likely mRNA targets and an unexpected link to placental iron metabolism. Development, 143, 1424-1433 [doi:10.1242/dev.130369](https://dx.doi.org/10.1242/dev.130369)

And downloaded via EBI European Nucleotide Archive (ENA) from

- [Yolk Sac](https://www.ebi.ac.uk/ena/data/view/PRJNA275943)
- [Placenta](https://www.ebi.ac.uk/ena/data/view/PRJNA275944)

#### Presentation / Notes ####
- [2018_PlacentalBiologyCourse_Presentation.pdf](2018_PlacentalBiologyCourse_Presentation.pdf)
- [2018_PlacentalBiologyCourse_Presentation.pptx](2018_PlacentalBiologyCourse_Presentation.pptx)

#### Commands / Code ####

- [2018_PlacentalBiologyCourse_Commands.txt](2018_PlacentalBiologyCourse_Commands.txt)
- [2018_PlacentalBiologyCourse_Sleuth.Rmd](2018_PlacentalBiologyCourse_Sleuth.Rmd)

#### Reference Genome / Transcriptome ####

Gene to transcript table
- [ENST_ENSG_GeneName.GRCm38.kallisto.table](ENST_ENSG_GeneName.GRCm38.kallisto.table)
- A Kallisto index for GRCm38 is required e.g. Mus_musculus.GRCm38.cdna.all.idx. See [https://pachterlab.github.io/kallisto/starting.html](https://pachterlab.github.io/kallisto/starting.html) for details how to create/download.


#### Sample Files with pre-made QC and alignments ####
- SRR1811706_ES610_WT_Yolk_Sac
- SRR1811707_ES611_WT_Yolk_Sac
- SRR1811708_ES612_WT_Yolk_Sac
- SRR1811709_ES613_WT_Yolk_Sac
- SRR1823638_ES51_WT_Placenta
- SRR1823639_ES51_WT_Placenta
- SRR1823640_ES52_WT_Placenta
- SRR1823641_ES52_WT_Placenta
- SRR1823642_ES53_WT_Placenta
- SRR1823643_ES54_WT_Placenta
- SRR1823644_ES55_WT_Placenta

#### Files Excluded from this distribution ####

A directory containing pre-made kallisto pseudoalignment files for samples `SRR1823638_ES51_WT_Placenta` and `SRR1811706_ES610_WT_Yolk_Sac` as they are too large to store here.
- IGV_Alignments/


### License ### 	

    Attribution-Non Commercial-Share Alike CC BY-NC-SA ( https://creativecommons.org/licenses/by-nc-sa/ )

		Attribution:	You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.

		NonCommercial:	You may not use the material for commercial purposes.

		ShareAlike:	If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.

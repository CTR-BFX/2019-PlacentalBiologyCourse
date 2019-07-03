# Centre for Trophoblast Research: Placental Bioinformatics Course

<sup>Version 0.2: 20190702</sup>

Russell S. Hamilton (rsh46@cam.ac.uk), Xiaohui Zhao (xz289@cam.ac.uk) & Malwina Prater (mn367@cam.ac.uk)


## An introduction to RNA-Seq ##

What is RNA sequencing? From Sequencer to gene counts
 - Lecture 1: [[2019_PlacentalBiologyCourse_Lecture_1](2019_PlacentalBiologyCourse_Lecture_1.pptx)]
 - Practical 1: [[2019_PlacentalBiologyCourse_Commands_Rversion.Rmd](2019_PlacentalBiologyCourse_Commands_Rversion.Rmd)]

From Gene counts to differential expression analysis
 - Lecture 2: [[2019_PlacentalBiologyCourse_Lecture_2](2019_PlacentalBiologyCourse_Lecture_2.pptx)]
 - Practical 2: [[2019_PlacentalBiologyCourse_DESeq2.Rmd](2019_PlacentalBiologyCourse_DESeq2.Rmd)] and a PDF summary
 [[2019_PlacentalBiologyCourse_DESeq2.pdf](2019_PlacentalBiologyCourse_DESeq2.pdf)]

### Objective for the practical ###

- To learn about how to process, analyse and interpret RNA-Seq data

### Learning goals ###

- Experience using the Linux operating system (Using Ubuntu via R-Studio)
- Learn how to run bioinformatics tools on the command line
-	Learn how to use R and R-studio
-	Visualise sequencing alignments in a genome browser (not part of 2019 course)


### Materials ###

#### Publication ####

The data are from

Stumpo, D.J., Trempus, C.S., Tucker, C.J., Huang, W., Li, L., Kluckman, K., Bortner, D.M. and Blackshear, P.J. (2016) Deficiency of the placenta and yolk sac specific tristetraprolin family member ZFP36L3 identifies likely mRNA targets and an unexpected link to placental iron metabolism. Development, 143, 1424-1433 [doi:10.1242/dev.130369](https://dx.doi.org/10.1242/dev.130369)

And downloaded via EBI European Nucleotide Archive (ENA) from

- [Yolk Sac](https://www.ebi.ac.uk/ena/data/view/PRJNA275943)
- [Placenta](https://www.ebi.ac.uk/ena/data/view/PRJNA275944)

#### Reference Genome / Transcriptome ####

Gene to transcript table and entrezid (these would normally be downloaded during the analysis, but this is not robust enough for a practical with muultiple people downloading at the same time)
- [ENST_ENSG_GeneName.GRCm38.kallisto.table](ENST_ENSG_GeneName.GRCm38.kallisto.table)
- [ensEMBL2id.csv](ensEMBL2id.csv)
- A Kallisto index for GRCm38 is required e.g. Mus_musculus.GRCm38.cdna.all.idx. See [https://pachterlab.github.io/kallisto/starting.html](https://pachterlab.github.io/kallisto/starting.html) for details how to create/download.

#### Sample Files with pre-made QC and alignments ####
- [SRR1811706_ES610_WT_Yolk_Sac](SRR1811706_ES610_WT_Yolk_Sac)
- [SRR1811707_ES611_WT_Yolk_Sac](SRR1811707_ES611_WT_Yolk_Sac)
- [SRR1811708_ES612_WT_Yolk_Sac](SRR1811708_ES612_WT_Yolk_Sac)
- [SRR1811709_ES613_WT_Yolk_Sac](SRR1811709_ES613_WT_Yolk_Sac)
- [SRR1823638_ES51_WT_Placenta](SRR1823638_ES51_WT_Placenta)
- [SRR1823639_ES51_WT_Placenta](SRR1823639_ES51_WT_Placenta)
- [SRR1823640_ES52_WT_Placenta](SRR1823640_ES52_WT_Placenta)
- [SRR1823641_ES52_WT_Placenta](SRR1823641_ES52_WT_Placenta)
- [SRR1823642_ES53_WT_Placenta](SRR1823642_ES53_WT_Placenta)
- [SRR1823643_ES54_WT_Placenta](SRR1823643_ES54_WT_Placenta)
- [SRR1823644_ES55_WT_Placenta](SRR1823644_ES55_WT_Placenta)

Subsampled FASTQ files for running fastQC, trim_galore and kallisto on the teaching computers
- [SRR1823638_sub_1.fastq.gz](SRR1823638_sub_1.fastq.gz)
- [SRR1823638_sub_2.fastq.gz](SRR1823638_sub_2.fastq.gz)

#### Files Excluded from this distribution ####

A directory containing pre-made kallisto pseudoalignment files for samples `SRR1823638_ES51_WT_Placenta` and `SRR1811706_ES610_WT_Yolk_Sac` as they are too large to store here.

>IGV_Alignments/ contains BAM alignment files for a selection of samples (not part of 2019 course)

### License ### 	

    Attribution-Non Commercial-Share Alike CC BY-NC-SA ( https://creativecommons.org/licenses/by-nc-sa/ )

		Attribution:	You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.

		NonCommercial:	You may not use the material for commercial purposes.

		ShareAlike:	If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.

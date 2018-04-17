# 3DAROC

<p>

<img align="right" src=/Documents/Logo/Foto-DNA_MMarti_0.jpg?raw=True>

## Course description

3C-based methods, such as Hi-C, produce a huge amount of raw data as pairs of DNA reads that are spatially close in the cell nucleus. Overall, these interaction matrices have been used to study how the genome folds within the nucleus, that is one of the most fascinating problems in modern biology. The rigorous analysis of the paired-reads using computational tools has been essential to fully exploit the experimental technique, and to study how the genome is folded in the space. Currently, there is a huge expansion on the wealth of data on genome structure with the availability of many datasets of Hi-C experiments down to 1 kb resolution (see for example: http://hic.umassmed.edu/welcome/welcome.php ; http://promoter.bx.psu.edu/hi-c/view.php or http://www.aidenlab.org/data.html ). In this course, participants will learn to use TADbit, a software designed and developed to manage all the dimensionalities of the Hi-C data:
</p>

 - 1D - Map paired-end sequences to generate Hi-C interaction matrices
 - 2D - Normalize matrices and identify constitutive domains (compartments, TADs)
 - 3D - Generate populations of model structures which reproduce the Hi-C interaction matrices
 - 4D - Compare samples at different time points

Participants can bring specific biological questions and/or their own 3C data to analyze during the course. At the end of the course, participants will be familiar with the TADbit software, and will be able to fully analyze Hi-C data. *Note: Although the TADbit software is central in this course, alternative software will be discussed for each part of the analysis.*

## Instructors

<p>
<img align="left" src=http://gtpb.igc.gulbenkian.pt/bicourses/images/Marc_Marti-Renom.jpeg?raw=True width="100">

**Marc A. Marti-Renom** obtained a Ph.D. in Biophysics from the Universidad Autonoma de Barcelona where he worked on protein folding under the supervision of B. Oliva, F.X. Aviles and M. Karplus. After that, he went to the US for a postdoctoral training on protein structure modeling at the Sali Lab (Rockefeller University) as the recipient of the Burroughs Wellcome Fund fellowship. Later on, Marc was appointed Assistant Adjunct Professor at UCSF. Between 2006 and 2011, he headed of the Structural Genomics Group at the CIPF in Valencia (Spain). Currently, Marc is an ICREA research professor and leads the Structural Genomics Group at the National Center for Genomic Analysis - Centre for Genomic Regulation (CNAG-CRG) in Barcelona. His group is broadly interested on how RNA, proteins and genomes organize and regulate cell fate. Finally, Marc is an Associate Editor of the PLoS Computational Biology journal and has published over 90 articles in international peer-reviewed journals.

*Affiliation: Centro Nacional de Análisis Genómico (CNAG) and Center for Genomic Regulation (CRG), Barcelona, ES*
</p>

<p>
<img align="left" src=http://gtpb.igc.gulbenkian.pt/bicourses/images/Francois_Serra.jpg?raw=True width="100">

**François Serra** obtained his Degree in Biology, specialized in Physiology and Neurophysiology, his Master's Degree in Structural genomics and bioinformatics (Strasbourg I University, France) and it's PhD in Evolutionary Genomics in the Department of Bioinformatics at the CIPF (Valencia). He is now part of the Structural Genomic team of Marc Marti-Renom at CNAG and at CRG (Barcelona). His main research interests are grounded on comparative genomics and evolution with a special focus on the effect of evolution in the structural arrangement of genomes. He has taught MEPA and 3DMOG for GTPB, and also in similar courses at CIPF (Valencia, ES) and the Department of Genetics of the University of Cambridge (UK).

*Affiliation: Centro Nacional de Análisis Genómico (CNAG) and Center for Genomic Regulation (CRG), Barcelona, ES*
</p>

<p>
<img align="left" src=http://gtpb.igc.gulbenkian.pt/bicourses/images/Marco_di_Stefano.jpg?raw=True width="100">

**Marco Di Stefano** obtained his Ph.D. in Biophysics from SISSA in Trieste (Italy) working on Physics-based structural models of chromosomes to study the relationship between gene co-expression and gene co-localization. He currently works as a post-doctoral researcher in the structural genomics group of Marc Marti-Renom at CNAG-CRG (Barcelona). His main research interest is to integrate biopolymer physics and experimental techniques, such as imaging and 3C, to characterize constitutive mechanisms of chromosome folding. He is involved in the YRM initiative (http://www.yrmr.it/drupal/) for young Physicists. He has taught 3DAROC16 for GTPB.

*Affiliation: Centro Nacional de Análisis Genómico (CNAG) and Center for Genomic Regulation (CRG), Barcelona, ES*
</p>

## Target Audience

The course is designed for experimental researchers and bioinformaticians at the graduate and post-graduate levels which are interested in studying the genome spatial organization. 

It is likely that the participants to this course aim at getting involved in generating Hi-C data for  chromosome structure determination, or that they just want to be able to correctly interpret and analyse publicly available data.

## Course Pre-requisites

Recommended Linux and basic Python programming skills, graduate level in Life Sciences. All hands-on will be given at 3 levels of computational expertise (web platform, command-line tool and python scripting).


## Content

|                  | Lectures (pdf)                          | Core pipeline (notebooks)               | Annex (notebooks)                 | Feedback (1: not clear; 5: very clear) |
|-------------------|----------------|-------------------------|------------|------|
| Day1 | <ul><li>[Welcome](/Presentations/Day1/01_20161010_Welcome.pdf)</li><li>[Intro structure determination](/Presentations/Day1/02_20161010_introduction_to_structure_determination.pdf)</li><li>[3D Genomes overview](/Presentations/Day1/03_20161010_3D-genomes_overview.pdf)</li><li>[Intro TADbit](/Presentations/Day1/04_20161010_Intro_TADbit.pdf)</li><li>[NGS for HiC](/Presentations/Day1/05_20161010_NGS_for_HiC.pdf)</li><li>[Intro UNIX](/Presentations/Day1/06_20161010_linux.pdf)</li><li>[Intro Python](/Presentations/Day1/07_20161010_python.pdf)</ul></li> |<ul><li>[Hi-C Quality check](/Notebooks/00-Hi-C quality check.ipynb)</li><li>[Mapping](/Notebooks/01-Mapping.ipynb)</li><li>[Parsing mapped reads](/Notebooks/02-Parsing mapped reads.ipynb)</li></ul> | <ul><li>[Software installation](/Notebooks/A0-Preparing your computer for HiC data analysis.ipynb)</li><li>[Prepare reference genome](/Notebooks/A1-Preparation reference genome.ipynb)</li><li>[Download Hi-C experiment](/Notebooks/A2-Download published Hi-C experiments.ipynb)</li></ul> | <li>Integrative modeling: 4.7</li><li>FASTQ/Hi-C quality check: 4.8</li><li>Mapping: 4.9</li>|
| Day2 | <ul><li>[Morning wrap up](/Presentations/Day2/01_20161011_Summary_of_day_1.pdf)</li><li>[Chromatin and 3Cs](/Presentations/Day2/02_20161011_Chromatin_and_3Cs.pdf)</li><li>[Integrative modeling](/Presentations/Day2/03_20161011_IntegrativeModeling.pdf)</li><li>[Applications(I): Alpha globin](/Presentations/Day2/04_20161011_Applications(I)_alpha_globin.pdf)</li></ul>| <ul><li>[Filterind reads](/Notebooks/03-Filtering mapped reads.ipynb)</li><li>[Normalization](Notebooks/04-Bin-filtering and normalization.ipynb)</li></ul> | <ul><li>[Compare/merge experiments](/Notebooks/A3-Compare and merge Hi-C experiments.ipynb)</li></ul> | <li>Genome organization: 4.9</li><li>3D modeling: 3.7</li><li>Filtering/normalization: 4.2</li>|
| Day3 | <ul><li>[Morning wrap up](/Presentations/Day2/01_20161012_Summary_of_day_2.pdf)</li><li>[Applications(II): Caulobacter](/Presentations/Day2/02_20161012_Applications(II)_Caulobacter.pdf)</li><li>[Applications(III): TAD hormone](/Presentations/Day2/02_20161012_Applications(III)_TAD_hormone.pdf)</li><li>[Normalization & comparison](/Presentations/Day2/02_20161012_NormalizationComparison.pdf)</li></ul>| <ul><li>[Compartments and TADs](/Notebooks/05-Compartments and TADs.ipynb)</li></ul> | <ul><li>[Align and compare TADs](/Notebooks/A4-Align and compare TADs.ipynb)</li></ul> | <li>Validation 3D models: 0.0</li><li>Compartment/TAD calling: 4.5</li><li>TADbit usage: 4.2</li>|
| Day4 | <ul><li>[Morning wrap up](/Presentations/Day4/01_20161013_Summary_of_day_3.pdf)</li><li>[Applications(IV): Fly colors](/Presentations/Day4/02_20161013_Applications(IV)_FlyColors.pdf)</li></ul>| <ul><li>[Parameter optimization](/Notebooks/06a-Modeling - parameter optimization.ipynb)</li><li>[Model optimization](/Notebooks/06b-Modeling - model optimization.ipynb)</li></ul> | <ul><li>[Analysis of 3D models](/Notebooks/A5-Modeling - analysis of 3D models.ipynb)</li></ul> |
| Day5 | <ul><li>[Nucleosome dynamics](/Presentations/Day5/nucleosome_dynamics.pdf)</li><li>[DNA and chromatin dynamics](/Presentations/Day5/nucleosome_dynamics.pdf)</li></ul>|  |  |

## TADbit tools

Most of the tasks of the "core pipeline" can be tunned directly from command line (without any python), using [TADbit tool](/TADbit_tools). Have a look to the commands, and the metadata of the results. 

_For now TADbit tool is not incuded in the general documetation, as it is still "under construction". Use it carefully, and don't hesitate to repport any weird behaviour you observe._

<p>
 
 
<img align="left" src=http://www.multiscalegenomics.eu/MuGVRE/wp-content/uploads/2016/06/main_logo_VRE3.png?raw=True width="100">


## Virtual research environment

With small datasets TADbit core pipeline can be runned through a new Virtual Research Environment ([VRE](https://vre.multiscalegenomics.eu/workspace/)), hosted by the [MuG project](https://www.multiscalegenomics.eu/). 

This might also be the best place to try TADkit for visualizing genomes in 3D.

</p>


## TADbit version

This tutorial is associated with a __specific version of TADbit__, if you wish to reproduce exactly the results in the notebooks you should use the version of TADbit tagged `3DAROC_2016`.

To install this version do:

    git clone https://github.com/3dgenomes/tadbit
    cd tadbit
    git checkout tags/3DAROC_2018
    sudo python setup.py install

Course Timetable (provisional)

### Mon, May 21st

|  Day #1  |
|------------|
|  09:30 - 10:00	Welcome and introductions  |
|  10:00 - 11:00	Overview on structure determination  |
|  11:00 - 11:30	Coffee Break  |
|  11:30 - 12:30	3D modeling of genomes and genomic domains  |
|  12:30 - 14:00	Lunch Break  |
|  14:00 - 15:00	Introduction to Linux and Python: the Jupyter notebook  |
|  15:00 - 16:00	Next Generation Sequencing (NGS) and data handling  |
|  16:00 - 16:30	Tea Break  |
|  16:30 - 18:00	From raw data to Hi-C contact matrices  |

### Tue, May 22nd

|  Day #2  |
|-------------|
|  09:30 - 11:00	Morning wrap-up: what have we done so far?
|        		Multiscale Genomics: From genomes to structures
|  11:00 - 11:30	Coffee Break
|  11:30 - 12:30	Coarse-Grained DNA and Chromatin Dynamics
|  12:30 - 14:00	Lunch Break
|  14:00 - 16:00	Nucleosome positioning 
|  16:00 - 16:30	Tea Break
|  16:30 - 18:00   Nucleosome Dynamics

### Wed, May 23rd

|  Day #3  |
|-------------|
|  09:30 - 11:00	Morning wrap-up: what have we done so far?  |
|        		Chromatin structure and Hi-C data  |
|  11:00 - 11:30	Coffee Break  |
|  11:30 - 12:30	Integrative modeling applied to chromatin  |
|  12:30 - 14:00	Lunch Break  |
|  14:00 - 16:00	Biological applications (I)  |
|  16:00 - 16:30	Tea Break  |
|  16:30 - 18:00	Hi-C contact matrices: filtering and normalization  |

### Thu, May 24th

|  Day #4  |
|-------------|
|  09:30 - 11:00	Morning wrap-up: what have we done so far?  |
|        		Biological applications (II)  |
|  11:00 - 11:30	Coffee Break  |
|  11:30 - 12:30	Compartment detection and analysis  |
|  12:30 - 14:00	Lunch Break  |
|  14:00 - 16:00	Topologically Associated Domains detection and analysis  |
|  16:00 - 16:30	Tea Break  |
|  16:30 - 18:00	Comparison between experiments  |

### Fri, May 25th

|  Day #5  |
|-------------|
|  09:30 - 11:00	Morning wrap-up: what have we done so far?  |
|        		Biological applications (III)  |
|  11:00 - 11:30	Coffee Break  |
|  11:30 - 12:30	3D Modeling of real Hi-C data with TADbit (I)  |
|  12:30 - 14:00	Lunch Break  |
|  14:00 - 16:00	3D Modeling of real Hi-C data with TADbit (II)  |
|  16:00 - 16:30	Tea Break  |
|  16:30 - 18:00	Final wrap-up session  |

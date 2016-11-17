
# EMOS

This repo hosts some materials (mainly links) related to the data management
course for the [European Masters of Official Statistics](http://www.uu.nl/masters/en/methodology-and-statistics-behavioural-biomedical-and-social-sciences/tracks) track.

### Reproducibility

Some materials to get acquinted with the topic

#### The reproducibility crisis

- [Ten famous psychology findings that are difficult to  replicate](https://digest.bps.org.uk/2016/09/16/ten-famous-psychology-findings-that-its-been-difficult-to-replicate/) Or better: to _reproduce_.
- [The hocky stick controversy](https://web.archive.org/web/20031211211711/http://www.climate2003.com/file.issues.htm) Critics of the climate reconstruction by [Mann, Bradly and Hughes (1999)](http://www.meteo.psu.edu/holocene/public_html/shared/research/ONLINE-PREPRINTS/Millennium/mbh99.pdf), made clear mistakes (in Excel) when trying to reproduce MBH's analyses.
- [Washington Post (2015)](https://www.washingtonpost.com/news/speaking-of-science/wp/2015/08/27/trouble-in-science-massive-effort-to-reproduce-100-experimental-results-succeeds-only-36-times/) Many scientific studies can't be replicated. That's a problem.
- [Challenges in irreproducible research](http://www.nature.com/news/reproducibility-1.17552#) Collection of online _Nature_ articles devoted to reproducibility.

#### Definitions


- [Scientific objectivity](http://plato.stanford.edu/entries/scientific-objectivity/) In the stanford encyclopedia of philosophy.
- [Kennet & Shmueli (2015)](http://www.nature.com/nmeth/journal/v12/n8/full/nmeth.3489.html) Clarifying the terminology that describes scientific reproducibility. _Nature Methods_ **12** 699.
- [Reproducibility and Repeatibility](http://www.astm.org/SNEWS/MA_2009/datapoints_ma09.html) According to [ASTM International](www.astm.org)



#### Reproducibility of computation

- [Literate programming](http://www.literateprogramming.com/knuthweb.pdf) Donald Knuth (1992)
- [A short movie](https://www.youtube.com/watch?v=s3JldKoA0zw) summarizing the problem.
- [Peng (2011)](http://www.ncbi.nlm.nih.gov/pmc/articles/PMC3383002/) [preprint] Reproducible Research in Computational Science. _Science_ **334** 1226-1227.
- [Kennet and Shmueli (2014)](https://www.researchgate.net/profile/Ron_Kenett/publication/228169566_On_Information_Quality/links/5422d44c0cf238c6ea6d6af5.pdf) On Information Quality.
  _J. R. Stat. Soc. Ser. A Stat. Soc_ **177** 3-38
- [Arabas _et al._ (2014)](https://arxiv.org/abs/1408.2123) Case Studies in Reproducibility in the Computational Sciences. [arXiv:1408.2123](https://arxiv.org/abs/1408.2123)
- [Horn and Leisch (2011)](http://bib.oxfordjournals.org/content/12/3/288.full.pdf+html)
    Case studies in reproducibility. _Briefings in Bioinformatics_ **12** 288-300.
- [Gentleman and Temple Lang (2004)](http://www.math.usu.edu/~corcoran/classes/14spring6550/handouts/reproducible_research.pdf) Statistical Analyses and Reproducible Research. _Bioconductor Project Working Papers_,
Paper 2, 2004.
- [Donald Knuth's talk on literate programming](https://channel9.msdn.com/Events/useR-international-R-User-conference/useR2016/Literate-Programming) at [_useR!2016_](https://useR2016.org)


#### In official statistics

- [Principles Governing International Statistical Activities](http://unstats.un.org/unsd/methods/statorg/Principles_stat_activities/principles_stat_activities.asp) (United Nations)
- [European Statistics Code of Practice](http://ec.europa.eu/eurostat/documents/3859598/5921861/KS-32-11-955-EN.PDF)
- Statistics Netherlands [code of conduct](https://www.cbs.nl/nl-nl/over-ons/organisatie/jaarverslag/gedragscode) (in Dutch)
- United States [BLS Guidelines for Informing Users of Information on Quality and Methodology](http://www.bls.gov/bls/quality.htm)
- [Stodden (2013)](https://web.stanford.edu/~vcs/talks/ISI-Aug302013-STODDEN.pdf) The reproducible research movement in statistics. _59th ISI World Statistics Congress_ Hong Kong (Aug 13, 2013).


#### Dynamic documents with R

- [rmarkdown.rstudio.com](http://rmarkdown.rstudio.com/lesson-1.html) getting started
- [JJ Allaire's talk on Notebooks](https://channel9.msdn.com/Events/useR-international-R-User-conference/useR2016/Notebooks-with-R-Markdown) at useR2016 (video).
- [Sweave user manual](https://stat.ethz.ch/R-manual/R-devel/library/utils/doc/Sweave.pdf) Leisch and R-core (2015)

#### Building a compendium with R

- [Rtools](https://cran.r-project.org/bin/windows/Rtools/) Needed if you're not on a unix-like OS. 
- [R package development](http://r-pkgs.had.co.nz/) Wickham (2015)
- [Writing R Extensions](https://cran.r-project.org/doc/manuals/r-release/R-exts.html) The only official reference.


### Data validation

#### Value chains

- The [wikipedia article](https://en.wikipedia.org/wiki/Value_chain) has good basic references.

#### The Statistical Value Chain in Official Statistics

There seems to be no general definition of the concept of statistical value
chain (SVD) accross statistical institutes although the use of the term is wide
spread. Some examples of documents using the subject:

- The UK Office of National Statistics  [guidelines for measuring statistical quality](http://unstats.un.org/unsd/dnss/docs-nqaf/UK-Guidelines_Subject.pdf) rely on the concept of a SVC
- Eurostat published a [summary of good practices](http://ec.europa.eu/eurostat/documents/64157/4377619/Summary-of-good-practises.pdf/3be1a60d-2263-4daa-8d20-2b1479c70b1e), organized according to the SVC.

It is likely that statistical value chains are going to be more integrated
accross the European Statistical System in some way or another in the future.
The driving ideas behind this are described in the [ESS Vision
2020](http://ec.europa.eu/eurostat/web/ess/about-us/ess-vision-2020). A
description of how the ESS works can be found
[here](http://ec.europa.eu/eurostat/cros/system/files/General%20Observations-05-T-European%20Statistical%20System%20v1.0_0.pdf).




#### Foundations of data validation

- A formal typology of data validation functions. [slide deck](https://www.unece.org/fileadmin/DAM/stats/documents/ece/ces/ge.44/2015/mtg1/PPT_5_new_Netherlands_vanderLoo2015.pdf) and [full paper](http://www.unece.org/fileadmin/DAM/stats/documents/ece/ces/ge.44/2015/mtg1/WP_5_Netherlands_A_formal_typology_of_data_validation_functions.pdf) of the UNECE work session on statistical data editing in Budepest (2015).
- [Methodology for data validation](https://ec.europa.eu/eurostat/cros/system/files/methodology_for_data_validation_v1.0_rev-2016-06_final.pdf) Handbook of the ESS.

#### The `validate` package

- [getting started](https://cran.r-project.org/web/packages/validate/vignettes/intro.html) manual
- [talk](https://www.youtube.com/watch?v=RMCc2Iu0UIQ) given at the [satRdays](https://budapest.satRdays.org) conference



### Representation of data

#### Tables and data bases

- [wikipedia](https://en.wikipedia.org/wiki/Relational_database) on relational databases
- [WWWSQLDESIGNER](https://ondras.zarovi.cz/sql/demo/) an online schema designer
- [wikipedia](https://en.wikipedia.org/wiki/Logical_data_model) on data models
- [SQLite tutorial](http://www.sqlitetutorial.net/) with exercise database

#### XML, JSON

- [wc3schools](http://www.w3schools.com/xml/) XML tutorial
- [wc3schools](http://www.w3schools.com/js/js_json_intro.asp) JSON introduction


#### Representation of numbers

- [Convert a number to single precision](https://www.youtube.com/watch?v=C3NcYd2hl9s) Video
- [wikipedia](https://en.wikipedia.org/wiki/IEEE_floating_point) on the IEEE 745 standard
- [microsoft's deviation](https://support.microsoft.com/en-us/kb/78113) from the IEEE 745 standard


#### Representation of text

- [a blogpost](http://kunststube.net/encoding/) describing encoding problems
- [Unicode table](http://unicode-table.com/en/)
- [wikipedia](https://en.wikipedia.org/wiki/Character_encoding) on character encoding



# EMOS

This page covers some materials discussed in the data management course 2016-2018.





### Value chains

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


### Data validation

#### Foundations 

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
- [Normal forms](https://beginnersbook.com/2015/05/normalization-in-dbms/) explained nicely

#### The CAP theorem

- [wikipedia article](https://en.wikipedia.org/wiki/CAP_theorem)
- Proof by [Gilbert and Lynch (2002)](https://courses.e-ce.uth.gr/CE623/CAP_theorem_proof.pdf) ACM SIGACT News **33** 51-55 



#### Architectural approaches

- Data Warehouse
    - [wikipedia](https://en.wikipedia.org/wiki/Data_warehouse)
- Data Mart
    - [wikipedia](https://en.wikipedia.org/wiki/Data_mart)
- Data Lake
    - [Stein and Morrison (2014)](http://www.smallake.kr/wp-content/uploads/2017/03/20170313_074222.pdf) PWC Technology forecast **1** 1--8
    - [wikipedia](https://en.wikipedia.org/wiki/Data_lake)
- Data virtualisation
    - [wikipedia](https://en.wikipedia.org/wiki/Data_virtualization)

### Information modeling

There are many tutorials on UML, both free and payed. Here are some resources:

- [free online tutorial](https://www.tutorialspoint.com/uml/index.htm) by tutorialpoint.com
- The book [Hamilton and Miles (2006)](https://flatis.moe/uploads/uploads/uml.pdf) is oriented towards IT development.
- The book by [Grassle, Baumann and Baumann (2005)](http://elearning.utm.my/18191/pluginfile.php/762857/mod_resource/content/1/UML%202%20in%20Action%20-%20Patrik%20Graslse.pdf) also includes business processes.


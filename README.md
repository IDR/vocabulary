
## IDR Controlled Vocabularies and Ontology Annotation

We are using a number of controlled vocabularies and ontologies in the BBSRC-funded [Image Data Repository](http://idr-demo.openmicroscopy.org/webclient/userdata/?experimenter=-1) (IDR) project.  Our approaches to annotation are being modified and expanded as we gather more imaging datasets, expand the functionality we are providing within OMERO for the IDR,  and as a result of discussions with others in the imaging community about the best approaches to take.


We have a spreadsheet outlining the [controlled vocabulary and ontology sources](https://docs.google.com/spreadsheets/d/1S9of23dD8vY1QUv90RV_-Ugu0h6yTeNobuj92-OoSl8/edit?usp=sharing) for terms we are currently using for High Content Screens (HCS).


### Dataset Descriptors

For high level information describing the type of dataset, e.g. "this is a primary RNAi High Content Screen imaging dataset",  we have put together some terms to describe aspects of the High Content Screens and the protocols describing the steps in the screen.  We have submitted these terms to the [Experimental Factor Ontology](http://www.ebi.ac.uk/efo) (EFO).


For example the following terms (and child terms below them) have been added:

 * [High Content Screen](http://www.ebi.ac.uk/ols/beta/ontologies/efo/terms?iri=http%3A%2F%2Fwww.ebi.ac.uk%2Fefo%2FEFO_0007550)
 * [High Content Screening stage](http://www.ebi.ac.uk/ols/beta/ontologies/efo/terms?iri=http%3A%2F%2Fwww.ebi.ac.uk%2Fefo%2FEFO_0007555)
 * [screening library](http://www.ebi.ac.uk/ols/beta/ontologies/efo/terms?iri=http%3A%2F%2Fwww.ebi.ac.uk%2Fefo%2FEFO_0007559)
 * [HCS protocols](http://www.ebi.ac.uk/ols/beta/ontologies/efo/terms?iri=http%3A%2F%2Fwww.ebi.ac.uk%2Fefo%2FEFO_0007570)

We are also looking at using terms from the [Biological imaging methods](http://www.ebi.ac.uk/ols/beta/ontologies/fbbi) ontology or importing them into EFO.


### Samples, Experimental Variables and Library Annotation

For sample annotation we are using [NCBITaxon](http://www.ebi.ac.uk/ols/beta/ontologies/ncbitaxon) for organisms, and EFO for cell lines.  EFO should also cover most sample characteristics when we move to other types of imaging data with perhaps more detailed sample information.  It also provides a description of the experimental variables or conditions we have seen such as environmental stress, compound treatment, media and genotype.


We are using a few controlled vocabulary terms when describing control wells in High Content Screens e.g. positive control, negative control, empty well etc. These can be found in the [controlled vocabulary and ontology sources](https://docs.google.com/spreadsheets/d/1S9of23dD8vY1QUv90RV_-Ugu0h6yTeNobuj92-OoSl8/edit?usp=sharing) spreadsheet.


### Processed Data Annotation

Cellular phenotypes identified in studies are annotated with [Cellular Microscopy Phenotype Ontology](http://www.ebi.ac.uk/cmpo) (CMPO) terms where possible.  We are adding to this ontology as required, with nearly 40 new terms added since May 2015. For example, we have created a series of phenotypes describing [protein localization within nuclear sub compartments](http://www.ebi.ac.uk/ols/beta/ontologies/cmpo/terms?iri=http%3A%2F%2Fwww.ebi.ac.uk%2Fcmpo%2FCMPO_0000403).  We are also recording whether phenotypes were manually or automatically assigned ("Phenotype Score Type" in  the [controlled vocabulary and ontology sources](https://docs.google.com/spreadsheets/d/1S9of23dD8vY1QUv90RV_-Ugu0h6yTeNobuj92-OoSl8/edit?usp=sharing) spreadsheet).


Data provided in processed/results files are described using both a free text description and by using a controlled vocabulary term to record the type of information in each column of the file.  The controlled vocabulary terms are given in the "Processed Data Column Type" row in the [controlled vocabulary and ontology sources](https://docs.google.com/spreadsheets/d/1S9of23dD8vY1QUv90RV_-Ugu0h6yTeNobuj92-OoSl8/edit?usp=sharing) spreadsheet.

For columns that contain "Data" or "Phenotype" results, we are also trying to capture the analysis level the results refer to  e.g. is the measurement or phenotype at the level of a single replicate of an siRNA, or is it derived from results from several siRNAs targeting the same gene? The controlled vocabulary terms we are currently using are listed in the "Processed Data Column Annotation Level" row in the [controlled vocabulary and ontology sources](https://docs.google.com/spreadsheets/d/1S9of23dD8vY1QUv90RV_-Ugu0h6yTeNobuj92-OoSl8/edit?usp=sharing) spreadsheet.

This is a work in progress and we welcome comments and suggestions for improvement.

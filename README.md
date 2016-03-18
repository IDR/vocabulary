
# IDR Controlled Vocabularies and Ontology Annotation

We are using a number of controlled vocabularies and ontologies in the BBSRC-funded [Image Data Repository](http://idr-demo.openmicroscopy.org/webclient/userdata/?experimenter=-1) (IDR) project.  Our approaches to annotation are being modified and expanded as we gather more types of imaging datasets, expand the functionality we are providing within OMERO for the IDR,  and as a result of discussions with others about the best approaches to take.


We have a spreadsheet outlining the [controlled vocabulary and ontology sources](https://docs.google.com/spreadsheets/d/1S9of23dD8vY1QUv90RV_-Ugu0h6yTeNobuj92-OoSl8/edit?usp=sharing) for terms we are currently using for High Content Screens.

This document does not cover how we are storing the information as this is still being developed.


## Dataset descriptors

For high level information describing the type of dataset, e.g. "this is a primary RNAi High Content Screen imaging dataset",  we have put together some terms to describe apects of the High Content Screens and the protocols describing the steps in the screen.  These are now in the [Experimental Factor Ontology](http://www.ebi.ac.uk/efo) (EFO).


For example the following terms (and child terms below them) have been added: 

 * [high content screen](http://www.ebi.ac.uk/ols/beta/ontologies/efo/terms?iri=http%3A%2F%2Fwww.ebi.ac.uk%2Fefo%2FEFO_0007550)
 * [high content screening stage](http://www.ebi.ac.uk/ols/beta/ontologies/efo/terms?iri=http%3A%2F%2Fwww.ebi.ac.uk%2Fefo%2FEFO_0007555)
 * [screening library](http://www.ebi.ac.uk/ols/beta/ontologies/efo/terms?iri=http%3A%2F%2Fwww.ebi.ac.uk%2Fefo%2FEFO_0007559)
 * [HCS protocols](http://www.ebi.ac.uk/ols/beta/ontologies/efo/terms?iri=http%3A%2F%2Fwww.ebi.ac.uk%2Fefo%2FEFO_0007570)

We are looking at using terms from the [Biological imaging methods](http://www.ebi.ac.uk/ols/beta/ontologies/fbbi) ontology or getting some terms from this ontology imported into EFO.


## Samples and Library Annotation

For sample annotation we are using [NCBITaxon](http://www.ebi.ac.uk/ols/beta/ontologies/ncbitaxon) for organisms, and EFO so far for cell lines.  EFO should also cover most sample characteristics when we move to other types of imaging data with perhaps more detailed sample information.


We are using a few controlled vocabulary terms when describing control wells in HCS e.g. positive control, negative control, empty well etc. These can be found in the [controlled vocabulary and ontology sources](https://docs.google.com/spreadsheets/d/1S9of23dD8vY1QUv90RV_-Ugu0h6yTeNobuj92-OoSl8/edit?usp=sharing) spreadsheet.


## Processed Data Annotation

Cellular phenotypes that are identified are annotated with e [Cellular Microscopy Phenotype Ontology](http://www.ebi.ac.uk/cmpo) terms.  We are adding to this ontology as required. We are also recording whether the phenotypes were manually or automatically assigned ("Phenotype Score Type" in  the [controlled vocabulary and ontology sources](https://docs.google.com/spreadsheets/d/1S9of23dD8vY1QUv90RV_-Ugu0h6yTeNobuj92-OoSl8/edit?usp=sharing) spreadsheet ).


Information provided in processed/results files provided is described using both a free text description and by using a controlled vocabulary term to record the type of information in each column.  The controlled vocabulary terms are given in the "Processed Data Column Type" row in the [controlled vocabulary and ontology sources](https://docs.google.com/spreadsheets/d/1S9of23dD8vY1QUv90RV_-Ugu0h6yTeNobuj92-OoSl8/edit?usp=sharing) spreadsheet.

For columns that contain "Data" or "Phenotype" results, we are also trying to capture the analysis level the results refer to  e.g. is the measurement or phenotype at the level of a single replicate of an siRNA, or is it derived from results from several siRNAs targetting the same gene? The controlled vocabulary terms we are currently using are listed in the "Processed Data Column Annotation Level" row in the [controlled vocabulary and ontology sources](https://docs.google.com/spreadsheets/d/1S9of23dD8vY1QUv90RV_-Ugu0h6yTeNobuj92-OoSl8/edit?usp=sharing) spreadsheet.






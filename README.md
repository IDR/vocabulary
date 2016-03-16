
# IDR Controlled Vocabularies and Ontology Annotation

We are using a number of controlled vocabularies and ontologies in the BBSRC-funded [Image Data Repository](http://idr-demo.openmicroscopy.org/webclient/userdata/?experimenter=-1) (IDR) project.  Our approaches to annotation are being modified and expanded as we gather more types of imaging datasets, expand the functionality we are providing within OMERO for the IDR,  and as a result of discussions with others about the best approaches to take.  We have a spreadsheet outlining the [controlled vocabulary and ontology sources](https://docs.google.com/spreadsheets/d/1S9of23dD8vY1QUv90RV_-Ugu0h6yTeNobuj92-OoSl8/edit?usp=sharing) for terms we are currently using.


## Dataset descriptors

For high level information describing the type of dataset, e.g. this is a primary RNAi high content screen imaging dataset,  we have put together some terms to describe apects of the High Content Screens and these are now in the [Experimental Factor Ontology](http://www.ebi.ac.uk/efo) (EFO).  For example the following terms (and child terms below them) have been added: 

 * [high content screen](http://www.ebi.ac.uk/ols/beta/ontologies/efo/terms?iri=http%3A%2F%2Fwww.ebi.ac.uk%2Fefo%2FEFO_0007550)
 * [high content screening stage](http://www.ebi.ac.uk/ols/beta/ontologies/efo/terms?iri=http%3A%2F%2Fwww.ebi.ac.uk%2Fefo%2FEFO_0007555)
 * [screening library](http://www.ebi.ac.uk/ols/beta/ontologies/efo/terms?iri=http%3A%2F%2Fwww.ebi.ac.uk%2Fefo%2FEFO_0007559)
 * [HCS protocols](http://www.ebi.ac.uk/ols/beta/ontologies/efo/terms?iri=http%3A%2F%2Fwww.ebi.ac.uk%2Fefo%2FEFO_0007570)

We are also looking at using terms from the [Biological imaging methods](http://purl.obolibrary.org/obo/fbbi) ontology or getting some terms from this ontology imported into EFO.

## Sample annotation

We are using [NCBITaxon](http://purl.obolibrary.org/obo/ncbitaxon) for organisms, and EFO so far for cell lines.  EFO should also cover most sample characteristics when we move to other types of imaging data with perhaps more detailed sample information.

##  Control types

We are using a few controlled vocabulary terms when describing control wells in HCS e.g. positive control, negative control, empty well etc.
These can be found in the [controlled vocabulary and ontology sources](https://docs.google.com/spreadsheets/d/1S9of23dD8vY1QUv90RV_-Ugu0h6yTeNobuj92-OoSl8/edit?usp=sharing) spreadsheet.

## Cellular phenotypes

We are using the [Cellular Microscopy Phenotype Ontology](http://www.ebi.ac.uk/cmpo) to annotate cellular phenotypes and have been adding terms to this ontology as required. 





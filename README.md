# Clinical Tripleizer
A KNIME workflow using Python and shell scripts to convert CSV and FHIR data to RDF.

**What's this for?**

Clinical data in Fast Healthcare Interoperability Resources (FHIR) format is particularly conducive for use and analysis in an RDF triplestore. If you have clinical data in FHIR format and want to load it into a triplestore, this pipeline will help walk you through the steps. More than that, if you want to combine your clinical data with other datasets in CSV format, this pipeline will also help convert your CSV data to RDF. In fact, this pipeline can be used solely for that purpose (CSV converstion to RDF), skipping the clinical data entirely.

**How's it work?**

The entire pipeline is contained in the KNIME file in this repo. All documentation for its use is in the KNIME file as well. Just make sure you have the following prerequisites installed before starting:

_Prerequisites:_

* KNIME
* Python 3.X
* [Blazegraph](https://blazegraph.com/), if you want to load your RDF files into a triplestore
* [FHIRToRDF](https://github.com/BD2KOnFHIR/fhirtordf), if you want to use the clinical data capabilities of the pipeline

**Acknowledgements**

This pipeline relies heavily on [FHIRToRDF](https://github.com/BD2KOnFHIR/fhirtordf) and the [Blazegraph](https://blazegraph.com/) triplestore. Thanks to the developers!

#### CIDOC CRM
* Conceptual Reference Model of the International Committee for Documentation
* ISO standard for the controlled exchange of cultural heritage information
* The CRM is a document defining classes in scope notes rather than an
implementation (in eg RDF)
* two main implementations:
	- the RDFS implementation created by Forth in Crete and published on the
	  CIDOC CRM website
	- ERLANGEN CRM. Implementation in OWL, used in WissKI
* event centered high level ontology

+++

#### Shortcomings of CIDOC CRM
* No versioning for the "official versions" published on the CIDOC CRM website
\>\> every class resolves to version 5.0.4
* Not all extensions compatible with ERLANGEN CRM
* no native possibility to add simple attributes >> BioCRM unary role
* fairly complex RDFs (eg 5 nodes + edges for modelling a birth event)

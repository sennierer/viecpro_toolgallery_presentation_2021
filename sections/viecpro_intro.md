#### TOC

<span style="font-size: 0.7em">

* VieCPro project requirements <!-- .element: class="fragment" -->
* ACDH-CH infrastructure and tools <!-- .element: class="fragment" -->
* APIS & apps built on APIS <!-- .element: class="fragment" -->
* VieCPro workflow <!-- .element: class="fragment" -->
* VieCPro NLP pipeline <!-- .element: class="fragment" -->

</span>
    
https://sennierer.github.io/viecpro_kickoff_2021/ <!-- .element: class="fragment" -->

+++

<img class="r-stretch" style="margin-bottom:60px" src="images/acdh_tools_prosopography.svg">

+++

#### Several interoperable tools

* [APIS](https://apis.acdh.oeaw.ac.at): entity store with several plugins (annotation, references etc.)
	- Plugins for: Atom (TEI editing), GDoc and Word
	- accessible for other tools via API
* [ApisHUB](https://apis-hub.acdh-dev.oeaw.ac.at/): Central hub for network visualization on all APIS instances
* [HistoGIS](https://histogis.acdh.oeaw.ac.at/): GIS service that provides Shapefile from 19th and early 20th century (focus on Austrian-Hungarian Empire)
	- API to retrieve shapefiles needed on the fly

+++

#### Several interoperable tools II

* [Omnipot](https://omnipot.acdh-dev.oeaw.ac.at/): Researchspace based knowledgebase that combines data from different sources
* [Nerdpool](https://nerdpool.acdh-dev.oeaw.ac.at/): Service to spawn prodigy instances for training NLP models
* [SpacyApp](https://spacyapp.acdh-dev.oeaw.ac.at/): service to run large chunks of texts (eg TEIs) through spacy NLP models

+++

#### VieCPro project requirements

* Prosopographical Database <!-- .element: class="fragment" -->
* extendable for more datasets to come <!-- .element: class="fragment" -->
* frontend to curate the data <!-- .element: class="fragment" -->
* API to automatically ingest the data <!-- .element: class="fragment" -->
* pipeline for data ingestion <!-- .element: class="fragment" style="font-size: 1.5em; color: #a1261d" -->

+++


<img class="r-stretch" src="images/hzab_xlsx_sc.png">
<img style="margin-bottom:60px" src="images/hzab_apis_sc.png">
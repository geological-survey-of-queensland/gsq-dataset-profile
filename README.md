# GSQ Dataset Profile
This is a model of a general *dataset*.

<img src="model/dataset.ong" style="width:800px;" alt="Dataset model" />  

**Fig. 1**: The general model of a dataset (after [DCAT (rev)](https://www.w3.org/TR/vocab-dcat-2/)).  

It is a profile of the [DCAT (rev)](https://www.w3.org/TR/vocab-dcat-2/) Dataset Catalogue Vocabulary model of dataset's metadata. It is used for describing the [Geological Survey of Queensland (GSQ)](https://www.business.qld.gov.au/industries/mining-energy-water/resources/geoscience-information/gsq)'s datasets which are listed in a dataset catalogue, currently under test at <http://gsq/cat>.

In addition to profiling DCAT (rev), this profile, through published alignments of DCAT (rev) is mapped to [ISO 19115-1:2014 Geographic information -- Metadata](https://www.iso.org/standard/53798.html) which is the model used for much spatial dataset's metadata transfer in Australia.


## Profile Resources
This profile is presented as a series of files that perform different roles:

* [Guidance document](Guidance.pdf) - a written document explaining how to use this profile
* [model](model/) - the *model* folder contains the model specification itself. This is given as both images and also as a formal [RDF]() model file (ontology).
* [profile.ttl](profile.ttl) - the profile declaration. A description of all of the items in this profile (the formal model, validating resources, documentation etc.) according to the W3C's [Profiles Ontology](https://www.w3.org/TR/dx-prof/) which describes how all the parts related to one another, the roles they play (to give *guidance* for use, to *validate* data etc.) and how this profile *profiles* the various standards listed above.


## License
The content of this repository is licensed for use with the [Creative Commons 4.0 License](https://creativecommons.org/licenses/by/4.0/). See the [license deed](LICENSE) for details.


## Contacts
*author*:  
**Nicholas Car**  
*Senior Experimental Scientist*  
CSIRO Land & Water, Environmental Informatics Group  
<nicholas.car@csiro.au>

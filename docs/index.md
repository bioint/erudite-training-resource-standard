## ERuDIte is the Educational Resource Discovery Index, which is a collection of online learning resources focused on data science.
### It is a part of the BD2K Training Coordinating Center (TCC), and it powers the Web Portal at [BigDataU.org](https://bigdatau.ini.usc.edu/).
#### This webpage documents the unified schema (which is primarily based on Schema.org classes and properties) we use to model the learning resources in ERuDIte. 

Examples of our schema in context can be found as:
1. embedded JSON-LD snippets in the source of each [resource webpage](https://bigdatau.ini.usc.edu/resource/14783120385630643790)
2. exported files on Zenodo - https://doi.org/10.5281/zenodo.1214375 

## Background 
Originally, the ERuDIte Training Resource Metadata Standard was a composite of many standards (See Methodology for more details). 
However, in our collaboration with [ELIXIR TeSS](https://tess.elixir-europe.org/) and [Bioschemas.org](http://bioschemas.org/), we adapted Schema.org classes and properties to model our metadata, 
using a similar approach to Bioschemas.org Training Material specification where Schema.org properties are used with range restrictions
specific to the organization's domain. 

With the ERuDIte Training Resource Metadata Standard, we use 
- schema:CreativeWork to represent learning resources/training materials
- schema:Person to represent instructors and creators of the learning resources
- schema:Organization to represent the learning resource providers and the instructors' affiliations 

While the predominance of our properties are from Schema.org, we do have a few ERuDIte specific properties in our vocabulary. See Specification Notes for more. 

## Vocabulary Definition Files
In our main repository, we currently provide two file types that contain the definition of ERuDIte's schema. 
1. Turtle 
2. CSV 

### More About ERuDIte
To learn more about ERuDIte and its aims to support continuous online learning for data science: http://bigdatau.org/about_erudite

## Contact
We'd love to hear from you! File a bug, new feature idea, or question on our 
[Github repository]().

## References
- [Bioschemas.org Training Material Specification](http://bioschemas.org/specifications/TrainingMaterial/specification/) 
- [Schema.org](https://schema.org/)

**This work is supported by the National Institutes of Health under Grant 1U24ES026465-01.**


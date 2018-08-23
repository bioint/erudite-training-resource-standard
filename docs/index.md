## ERuDIte is the Educational Resource Discovery Index, which is a collection of online training resources focused on data science.
### It is a part of the BD2K Training Coordinating Center (TCC), and it powers the Web Portal at [BigDataU.org](https://bigdatau.ini.usc.edu/). 
### This site documents the metadata standard we use to model the training resources in ERuDIte. 

## Background 
Originally, the ERuDIte Training Resource Metadata Standard was a composite of many standards (See [Methodology]({{ "methodology.html" | absolute_url }}) for more details). 
However, in our collaboration with [ELIXIR TeSS](https://tess.elixir-europe.org/) and [Bioschemas.org](http://bioschemas.org/), we adapted [Schema.org](https://schema.org/) classes and properties to model our metadata, 
using a similar approach to Bioschemas.org Training Material specification where Schema.org properties are used with range restrictions
specific to the TeSS's domain. 

With the ERuDIte Training Resource Metadata Standard, we use 
- schema:CreativeWork to represent learning and training resources
- schema:Person to represent instructors and creators of the training resources
- schema:Organization to represent the training resources' providers and the instructors' affiliations 

While the predominance of our properties are from Schema.org, we do have a few ERuDIte specific properties in our vocabulary. See [Specifications]({{ "specifications.html" | absolute_url }}) for more. 

## Vocabulary Definition Files
In our main repository at [https://github.com/bioint/erudite-training-resource-standard](https://github.com/bioint/erudite-training-resource-standard), 
we currently provide two file types that contain the definition of ERuDIte's standard. 
1. Turtle 
2. CSV

## Examples
Examples of our metadata standard in action can be found as:
1. embedded JSON-LD snippets in the source of each resource webpage. See source of [example resource page](https://bigdatau.ini.usc.edu/resource/14783120385630643790).
2. data exports on Zenodo - [https://doi.org/10.5281/zenodo.1214375](https://doi.org/10.5281/zenodo.1214375)

## Contact
We'd love to hear from you! File a bug, new feature idea, or question on our 
[Github repository](https://github.com/bioint/erudite-training-resource-standard).

### More About ERuDIte
To learn more about ERuDIte and its aims to support continuous online learning for data science, visit [http://bigdatau.org/about_erudite](http://bigdatau.org/about_erudite).

##### This work is supported by the National Institutes of Health under Grant 1U24ES026465-01.


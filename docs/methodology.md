## Methodology

Early in the creation of the ERuDIte Training Resource Metadata Standard, we used classes
and properties from multiple standards, specifically: 
- [Dublin Core](http://dublincore.org)
- [Learning Resource Metadata Initiative](http://lrmi.dublincore.net)
- [IEEE's Learning Object Metadata](https://standards.ieee.org/findstds/standard/1484.12.1-2002.html)
- [eXchanging Course Related Information](http://shop.bsigroup.com/ProductDetail/?pid=000000000030259242)
- [Metadata for Learning Opportunities](https://joinup.ec.europa.eu/solution/metadata-learning-opportunities-mlo-advertising/about)
- [Schema.org](https://schema.org/)

However, in beginning our collaboration with [ELIXIR TeSS](https://tess.elixir-europe.org/), an
online training registry for life-sciences in Europe, we wanted to exchange our metadata, which 
precipitated the need for harmonious standards between ELIXIR TeSS and TCC ERuDIte.

To model its training materials, ELIXIR TeSS uses [Bioschemas.org](http://bioschemas.org/)
[training materials specification](http://bioschemas.org/specifications/TrainingMaterial/specification/), 
which uses primarily Schema.org CreativeWork properties and adds restrictions based on TeSS's
specific needs. 

Consequently, with ERuDIte, we transformed our metadata standard to consist predominantly
of Schema.org classes and properties. This not only eased the data exchange between TeSS
and ERuDIte, but also allowed us to use a standard that is supported and developed by [major search engines](https://schema.org/docs/faq.html#1),
thus increasing the discovery of ERuDIte's contents overall.

As expected, there are properties in our metadata standard that are ERuDIte specific. 
Please see Specifications]({{ "specifications.html" | absolute_url }}) for more details. 

## References
- [Bioschemas.org Training Material Specification](http://bioschemas.org/specifications/TrainingMaterial/specification/) 
- [Schema.org](https://schema.org/)
 
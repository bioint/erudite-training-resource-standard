## Specifications

### Creating Vocabulary Definition Files
Using the Schema.org Vocabulary Definition files at [https://schema.org/docs/developers.html](https://schema.org/docs/developers.html)
as templates, we define the ERuDIte Training Resource Metadata Standard with three major classes:
1. **CreativeWork** - used to model training resources
2. **Person** - used to model instructors and resource creators
3. **Organization** - used to model resources' providers and instructors' affiliations

The ERuDIte Training Resource Metadata Standard is available for download as Turtle and CSV files
on [GitHub](https://github.com/bioint/erudite-training-resource-standard).

### ERuDIte Specific Properties 

In the ERuDIte Training Resource Metadata Standard, there are 4 ERuDIte specific properties,
and we use the prefix "erudite" to define them in our definition files. 

The properties are:
1. **erudite:enables** - property of CreativeWork to capture that a resource is a prerequisite of another.
2. **erudite:provides** - property of Organization and is the inverse of schema:provider
3. **erudite:syllabus** - property of Course (subclass of CreativeWork) and used to capture syllabus text
4. **erudite:dateIndexed** - property of CreativeWork to capture the date when a resource in ERuDIte is available on bigdatau.org

### ERuDIte Range Restrictions

#### schema:genre
We use the **schema:genre** property to provide tags to our training resources. The tags used
as the Range for the property come from a fixed ontology, the Data Science Education Ontology,
which was also defined as part of our work in ERuDIte. To learn more about the Data Science Education
Ontology, see [https://bioint.github.io/DSEO/](https://bioint.github.io/DSEO/).

### Visualization
Below is the ERuDIte Training Resource Metadata Standard as a UML diagram for a visual representation of our standard definition. 
[![schemauml]({{ "/assets/schema-uml/SchemaOrg-2018-10-15-final-300dpi.png" | absolute_url }})]({{ "/assets/schema-uml/SchemaOrg-06-06-17-1525-300dpi.png" | absolute_url }})

# glossary-catalogue-dictionary

![image](https://user-images.githubusercontent.com/92937667/139904234-176b257c-055e-4d28-826c-a824271b6059.png)

## Definitions

### Business Glossary
> A business glossary is business language-focused and easily understood in any business setting from boardrooms to technology standups. 

Business terms aren’t meant to define data, metadata, transforms, or locations, but rather to _define what each term means in a business_ sense. What do we mean by a conversion? A sale? A prospect? These types of questions can be answered with a business glossary. Having a business glossary brings common understanding of the vocabulary used throughout an organization. The scope of a business glossary should be enterprise-wide or at least divisional-wide in cases where different divisions have significantly different business terminology. Because of the scope and the expertise needed, responsibility for the business glossary is owned by the business rather than by technology. Often a data steward or business analyst will have this as a sole responsibility.

#### Examples
* census
* ward
* occupancy

### Data Dictionary
> A data dictionary should be focused on the descriptions and details involved in storing data. There should be one data dictionary for each database in the enterprise. 

The data dictionary includes _details about the data such as data type_, permissible length, lineage, transformations, and so on (like a database schema). This metadata helps data architects, engineers, and data scientists understand how to join, query, and report on the data, and explains the granularity as well. Because of the need for technical and metadata expertise, the ownership responsibility for a data dictionary lies within technology, frequently with roles such as database administrators, data engineers, data architects and/or data stewards.

### Example
* `LSOA: code (type: string), unique`
* `Ward: geometry (type: polygon), name (type: string)`
* `Household: accomodation (type: string), bedrooms: (type: integer)`

### Data Catalog
>The data catalog serves as a single-point directory to locate information and it further provides the mapping between the business glossary and data dictionaries. 

The data catalog is an enterprise-wide asset providing a _single reference source for location of any data set_ required for varying needs such as Operational, BI, Analytics, Data Science, etc.. Just as with the business glossary, if one division of an enterprise is significantly different than others, it would be reasonable for the data catalog to be exclusive to the division rather than to the enterprise. The data catalog would most reasonably be developed after the successful creation of both the business glossary and data dictionaries, but it can also be assembled incrementally as the other two assets evolve over time. A data catalog may be presented in a variety of ways such as enterprise data marketplace. The marketplace would serve as the distribution or access point for all, or most, enterprise certified data sets for a variety of purposes. Because of the mapping work requiring involvement from both business and technical expertise, assembling the data catalog is a collaborative effort.

#### Example
* census
* wards
* council tax

### Exemplar differences for a given record type

![image](https://user-images.githubusercontent.com/92937667/139896091-e00d1ff4-291d-4c24-b899-76fce2503160.png)

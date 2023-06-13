![Exabeam](https://user-images.githubusercontent.com/57500390/233129963-f6395c81-5c85-458c-b526-368de7b82aae.svg)

Common Information Model
========================
Welcome to the Exabeam common information model.

The Information model defines the structure of security content across Exabeam products. The hierarchical framework informs every aspect of security content usage throughout the flow of Exabeam processes.

The common information model includes a set of layered interfaces that each inherit the configuration of the previous layer. Together they create a complete picture of an event, according to the information model. Note that, with this layered approach, if an element is shown with an empty field array, it is by design because the element's field structure is defined in another interface. For more information, see [Common Information Model Interface](https://docs.exabeam.com/en/content/all/exabeam-security-content/182296-security-content-in-the-common-information-model-structure.html#UUID-0a6f25e0-a3cf-c844-0ac8-7c9ff7b0e2ee)

You can follow the links below to explore individual interfaces or view the entire [Information model in a JSON format](cim.json).

### [Universal Interface](Universal/Universal_Interface.md)
### [Subject Interface](Subjects/Subject_Interface.md)
### [Activity Type Interface](ActivityTypes/ActivityType_Interface.md)
### [Extension Interface](Extensions/Extension_Interface.md)

## Additional Elements 

In addition to the elements represented in the Common Information Model interfaces, the model also preserves other types of information with event data. You can follow the links below to explore these elements. 

[Platforms and Landscapes](https://github.com/ExabeamLabs/CIMLibrary/blob/main/Platforms_Landscapes.md) – A list of platforms listed by landscape

[Field Descriptions](Fields_Descriptions.md) – A list of available fields and their descriptions 

[Product Categories](https://github.com/ExabeamLabs/Content-Library-CIM2/blob/master/Exabeam%20Product%20Categories.md) – A list of supported product categories with descriptions (redirects to the New-Scale Content Library) 

[Vendors and Products](https://github.com/ExabeamLabs/Content-Library-CIM2/blob/master/Exabeam%20Data%20Sources.md) – A list of products listed by vendors (redirects to the New-Scale Content Library) 

## Migration Resources

To upgrade from earlier Exabeam products to the New-Scale Security Operations Platform, existing content must be migrated so that it complies with Common Information Model standards. The following resources provide the mapping information necessary to migrate the content.

[Field Mapping by Events](FieldsMappings.md) - A table that maps old events and fields to the corresponding Common Information Model activity types and fields

[Parser Names Matrix](https://github.com/ExabeamLabs/Content-Library-CIM2/blob/master/ParserNamesMatrix.md) - A set of alphabaetical tables that map old parser names to New-Scale parser names that comply with the Common Information Model (redirects to the New-Scale Content Library)

[Metadata Field Mapping](MetaFieldsMappings.md) - A table that maps old metadata field names to field names that comply with the Common Information Model.

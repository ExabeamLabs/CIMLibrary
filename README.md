![Exabeam](banner.png)

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

[Platforms and Landscapes](https://github.com/ExabeamLabs/CIMLibrary/blob/master/Platforms_Landscapes.md) – A list of platforms listed by landscape 

[Field Descriptions](Fields_Descriptions.md) – A list of available fields and their descriptions 

[Product Categories](https://github.com/ExabeamLabs/CIMLibrary/blob/master/Exabeam%20Product%20Categories.md) – A list of supported product categories with descriptions (redirects to the Content Library) 

[Vendors and Products](https://github.com/ExabeamLabs/CIMLibrary/blob/master/Exabeam%20Data%20Sources.md) – A list of products listed by vendors (redirects to the Content Library) 

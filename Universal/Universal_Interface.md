 Universal Interface
====================

###  Description

The universal interface defines a set of global fields. These are fields that are required for every event, regardless the type of event. The following list represents the minimum fields required to define an event. The list includes the CDI (core/detection/informational) values for each field. For more information about CDI values, see [Information Model Interface](https://docs.exabeam.com/en/content/all/exabeam-security-content/182296-security-content-in-the-common-information-model-structure.html#UUID-6a60b174-21d7-7d57-4a23-9a3f7a663f29).


###  Universal fields

| Field            | Core     | Detection | Informational |
| ---------------- | -------- | --------- | ------------- |
| activity_type    | &#10003; |           |               |
| host             |          |           | &#10003;      |
| landscape        |          | &#10003;  |               |
| outcome          | &#10003; |           |               |
| platform         |          | &#10003;  |               |
| product          | &#10003; |           |               |
| product_category |          | &#10003;  |               |
| subject          | &#10003; |           |               |
| time             | &#10003; |           |               |
| vendor           | &#10003; |           |               |
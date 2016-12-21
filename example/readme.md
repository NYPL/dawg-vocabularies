##Example vocabulary directory

Include the following files in a directory named for the vocabulary you want to serialize. This directory name should sit inside the directory for your domain. Both of these will be used in the base URI for your terms, ex. "http://data.nypl.org/discovery/locations/"  

- [vocabulary]_scheme.csv : This is a list of the properties you want to include for each term along with definitions, cardinality, and some other information.
- [vocabulary]_void.csv : This is key/value list of the properties describing your vocabulary itself
- [vocabulary]_terms.csv : This is the list of terms along with their properties and values

Templates are here. Talk to @saverkamp if you have any questions! 
##Example vocabulary directory

Include the following files in a directory named for the vocabulary you want to serialize. This directory name should sit inside the directory for your domain. Both of these will be used in the base URI for your terms, ex. "http://data.nypl.org/discovery/locations/"  

- [vocabulary]_scheme.csv : This is a list of the properties you want to include for each term along with definitions, cardinality, and some other information.
- [vocabulary]_void.csv : This is key/value list of the properties describing your vocabulary itself, using VoID
- [vocabulary]_terms.csv : This is the list of terms along with their properties and values

Templates are [here](https://docs.google.com/spreadsheets/d/18bw7aKrqPUqHFoXha9vu8z1zOIfV8zQaR5xyD7Eq5GU/edit). 

More info on SKOS [here](https://www.w3.org/TR/skos-primer/).  

More on VoID [here](https://www.w3.org/TR/void/).  

Talk to [@saverkamp](https://github.com/saverkamp) if you have any questions! 
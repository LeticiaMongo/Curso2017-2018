#Hands-on assignment 3 – Self assessment#

##Checklist##

**Every RDF file:**

- [X] Uses the .ttl extension
- [X] Is serialized in the Turtle format
- [X] Follows the resource naming strategy
- [X] Uses class and property URIs that are the same as those used in the ontology

**Every URI in the RDF files:**

- [X] Is "readable" and has some meaning (e.g., it is not an auto-increased integer) 
- [X] Is not encoded as a string
- [X] Does not contain a double slash (i.e., "//")

**Every individual in the RDF files:**

- [X] Has a label with the name of the individual
- [X] Has a type
- [X] Every value in the RDF files:
- [X] Is not empty (i.e., “”)
- [X] Is trimmed
- [X] Is properly encoded (e.g., dates, booleans)
- [X] Includes its datatype
- [X] Uses the correct datatype (e.g., values of 0-1 may be booleans and not integers, not every string made of numbers is a number) 

##Comments on the self-assessment##
In some entities of the rdf the value of isFree is not displayed although all entities have a value on their respective cell. We dont know the reason. Also, although all datatypes are properly encoded in their own format, the encoding of the text is not entirely correct and some characters are not shown properly.
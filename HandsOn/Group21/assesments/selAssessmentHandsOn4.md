# Hands-on assignment 4 – Self assessment

## Checklist

**Every RDF file:**

- [X] Uses the .nt extension
- [X] Is serialized in the NTriples format
- [X] Follows the resource naming strategy
- [ ] Uses class and property URIs that are the same as those used in the ontology

**Every URI in the RDF files:**

- [X] Is "readable" and has some meaning (e.g., it is not an auto-increased integer) 
- [X] Is not encoded as a string
- [X] Does not contain a double slash (i.e., “//”)

**Every individual in the RDF files:**

- [X] Has a label with the name of the individual
- [X] Has a type

**Every value in the RDF files:**

- [ ] Is trimmed
- [ ] Is properly encoded (e.g., dates, booleans)
- [X] Includes its datatype
- [ ] Uses the correct datatype (e.g., values of 0-1 may be booleans and not integers, not every string made of numbers is a number)

## Comments on the self-assessment
Could not find out how to transform "SI" and "NO" values in ACCESIBILIDAD column
into a proper boolean with YARRRML.
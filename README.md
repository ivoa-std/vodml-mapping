# Syntax proposal to map VOTable data on VO Model

This proposal has been designed in parallel with the development of MANGO, the model for source data.  
 
The objective is to provide a standard that allows to map VOTable data on any VO-DML compliant model. 

The mapping syntax can be used with any other model serialized in VO-DML

### Doc Preview

An PDF [Preview](https://github.com/ivoa-std/ModelInstanceInVot/releases/download/auto-pdf-preview/vodml-instance-vot-draft.pdf "preview")
 of the standard is automatically generated by the CI (also available in the Release tab).

### Syntax Guide Lines

- Facilitate as much as possible the annotation of archival data
- Faith to the model structure
- As compact as possible

### Main Features

- The mapping is gathered in one block global for the VOTable
- The structure of the block is as follow
    - A reference to the mapped VODML
    - A set of globals instances that can be referenced by any other components
    - A Set of table mapping blocks: one per table 

### Resources

- `doc` : standard document
- `schema`: XML schema for the mapping syntax (XSD1.1)
- `python_workflow`: code sample for exercising the mapping syntax
    - Mapping component builder 
    - Example of automatic annotation processor
    - Annotation validation
    - Annotated table processing

# Licence

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">
  <img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a>
  <br />
  This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">
  Creative Commons Attribution-ShareAlike 4.0 International License</a>.
  

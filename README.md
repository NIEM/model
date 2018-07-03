# NIEM release model

This repo contains a rendering of the content of the NIEM 4.0RC2 release.

The content can currently be viewed on <https://niem.github.io/model>

The structure of the content.

* `/` : An index listing all the namespaces ([example](https://niem.github.io/model))
* `/${namespace}` : An index listing all components in a namespace ([example](https://niem.github.io/model/nc))
* `/${namespace}/${component}`: A description of a component ([example](https://niem.github.io/model/nc/PersonType)). Each component description contains: 
  * The name of the component
  * The human-readable definition/description of the component
  * A diagram of the component and its relationships to other components ([example](https://niem.github.io/model/nc/PersonType#diagram))
  * The XML Schema definition of the component ([example](https://niem.github.io/model/nc/PersonType#xml-schema))
  * A JSON Schema definition for the component. The JSON Schema is under development, and should not be considered normative. ([example](https://niem.github.io/model/nc/PersonType#json-schema))

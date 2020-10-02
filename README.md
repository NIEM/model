# The NIEM release model viewer website

This Git repository contains a browsable rendering of the content of NIEM releases.

View NIEM releases at <https://niem.github.io/model>.

The structure of the content:

- <https://niem.github.io/model/>: A listing of NIEM release versions available .
- <https://niem.github.io/model/4.2>: A listing of the namespaces in the 4.2 release.
- <https://niem.github.io/model/4.2/nc>: A listing of all the components in the NIEM Core namespace.
- <https://niem.github.io/model/4.2/nc/PersonType>: A landing page for the `nc:PersonType` schema component from NIEM. This includes:
    - Name of the component
    - Its namespace prefix and namespace URI
    - Its definition
    - A diagram showing the relationships this component has to other components in NIEM. Click on names in the diagram to see details about other components.
    - An XML Schema fragment for the component.
    
For recent versions of NIEM, you can see full details of any component by browsing to:

`https://niem.github.io/model/${niem version}/${namespace prefix}/${component local name}`

This website was built with the [XML Schema documentation generator at https://github.com/webb/xml-schema-documentation-generator](https://github.com/webb/xml-schema-documentation-generator).


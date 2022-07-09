# NGSI-LD @context-File Generator

Code Generator for `@context`-Files (NGSI-LD and JSON-LD) used in the [official FIWARE tutorial](https://github.com/FIWARE/tutorials.Understanding-At-Context/tree/NGSI-LD/context-file-generator): 

> Note: The Data Models used here for `@context` generation are defined using OpenAPI 3.0 Swagger format. To help with the generation of IRIs the specification has been extended with additional annotations as necessary. The `x-ngsi` attribute, as the name suggests is just a simple Specification Extension - usually it is not relevant to Swagger, and indeed you could generate a simple `@context` file without it, but the data held within in has been used to help generate a rich `@graph` and more comprehensive documentation.
> 
> The simple NGSI-LD `@context` generator in the tutorial defaults to using `uri.fiware.org` namespaces and updates with corrected URIs based on the `x-ngsi.uri` and `x-ngsi.uri-prefix` attributes.
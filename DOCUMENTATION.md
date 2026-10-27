# Description provenance

Provenance of the schema descriptions in `openapi/ogcapi-dggs-1.yaml`: every description was authored from the standard's own requirements classes and prose — none imported.

| Schema | Source | Description (first sentence) |
|---|---|---|
| `FeatureCollection` | OGC 21-038 (DGGS) concepts and ogcapi-common building blocks | A collection of DGGS features: zones with their data, serialized as GeoJSON. |
| `all-collections` | OGC 21-038 (DGGS) concepts and ogcapi-common building blocks | A list of all collections available on this API, across all collection types. |
| `all-dggrs` | OGC 21-038 (DGGS) concepts and ogcapi-common building blocks | A list of all Discrete Global Grid Reference Systems (DGGRS) supported by this API. |
| `collectionDesc` | OGC 21-038 (DGGS) concepts and ogcapi-common building blocks | A description of a collection hosting DGGS data. |
| `collections` | OGC 21-038 (DGGS) concepts and ogcapi-common building blocks | A list of the collections available on this API, with their titles, descriptions and links. |
| `confClasses` | OGC 21-038 (DGGS) concepts and ogcapi-common building blocks | The conformance classes the deployment implements, per the OGC API conformance declaration. |
| `crs` | OGC 21-038 (DGGS) concepts and ogcapi-common building blocks | The coordinate reference systems supported for spatial inputs and outputs. |
| `dataType` | OGC 21-038 (DGGS) concepts and ogcapi-common building blocks | A data type declaration for an input or output value. |
| `dggrs` | OGC 21-038 (DGGS) concepts and ogcapi-common building blocks | A Discrete Global Grid Reference System: the hierarchical grid used to organize and query the data. |
| `dggrs-definition` | OGC 21-038 (DGGS) concepts and ogcapi-common building blocks | The full definition of a DGGRS: its geometry, level counts, cell shapes and parent-child relations. |
| `dggrs-item` | OGC 21-038 (DGGS) concepts and ogcapi-common building blocks | A subset of a DGGRS definition: identifier and URI. |
| `dggs-json` | OGC 21-038 (DGGS) concepts and ogcapi-common building blocks | A DGGS data container: zones with their values serialized in the DGGS-JSON encoding. |
| `enumeration` | OGC 21-038 (DGGS) concepts and ogcapi-common building blocks | An input whose value must be one of an enumerated set of literals. |
| `exception` | OGC 21-038 (DGGS) concepts and ogcapi-common building blocks | An exception report describing why a request failed, per the OGC API exception convention. |
| `extent` | OGC 21-038 (DGGS) concepts and ogcapi-common building blocks | The spatial and temporal extent of a collection or deployment. |
| `grid` | OGC 21-038 (DGGS) concepts and ogcapi-common building blocks | A grid refinement of a DGGRS: the set of zones at a given refinement level intersecting the query area. |
| `irregularGrid` | OGC 21-038 (DGGS) concepts and ogcapi-common building blocks | An irregular DGGS grid whose zones vary in shape or area at a given level. |
| `landingPage` | OGC 21-038 (DGGS) concepts and ogcapi-common building blocks | The landing page of the API: links to the conformance declaration, collections and other resources. |
| `link` | OGC 21-038 (DGGS) concepts and ogcapi-common building blocks | A hyperlink with its relation type, per the OGC API link conventions. |
| `numberMatched` | OGC 21-038 (DGGS) concepts and ogcapi-common building blocks | The number of items matching the selection criteria, if the server can determine it. |
| `numberReturned` | OGC 21-038 (DGGS) concepts and ogcapi-common building blocks | The number of items returned in this response. |
| `regularGrid` | OGC 21-038 (DGGS) concepts and ogcapi-common building blocks | A regular DGGS grid whose zones are uniform in shape and area at a given level. |
| `role` | OGC 21-038 (DGGS) concepts and ogcapi-common building blocks | The role performed by a contact in relation to the DGGS dataset. |
| `timeStamp` | OGC 21-038 (DGGS) concepts and ogcapi-common building blocks | The timestamp of the response, per RFC 3339. |
| `zone-info` | OGC 21-038 (DGGS) concepts and ogcapi-common building blocks | Information about a DGGS zone: its identifier, geometry, refinement level and data values. |

These descriptions are offered upstream as part of the model-based publication program (metanorma-ogc#153); corrections by the editors are welcome and will be tracked here.

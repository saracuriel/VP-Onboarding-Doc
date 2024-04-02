Level 2: Content-based Discovery
===================================

Requirements to achieve level 2
------------

Level 2 enables the discovery of resources by remote querying of aggregated descriptive information, and/or a limited amount of anonymous record information. This latter is provided either as safe/obfuscated record level data or (when using the Fair-in-a-Box (FiaB) software) aggregating/counting queries over record-level data. When querying at this level, the response can provide yes/no answers, metadata, or record counts (which can be thresholded or windowed) and will not expose the underlying data. For example, for the query ‘How many patients are defined with a certain Human Phenotype Ontology (HPO) code in the dataset?’, the answer would just be an approximate count of patients. This information can be valuable for researchers to assess whether a resource is likely to have relevant data for their research question based on their respective study design and methodology. This requires that the Level 1 connection is already established.

In Level 2, the focus shifts from merely publishing organisational metadata of a resource to uncovering valuable insights about the resource based on aggregated exploration of its contents, enabling researchers to gauge resource suitability without revealing sensitive data. This is enabled by the Beacon v2 API that was adapted for the EJP RD context. The **EJP RD Beacon v2 API** [`link <https://github.com/ejp-rd-vp/vp-api-specs>`_], operates at two levels depending on the resource type:

#. **/catalogs endpoint level:** Involves answering queries based on summary metadata about a resource, and this is most suitable for the querying of catalogues (I.e., resources whose content comprises of lists of other resources).
#. **/individuals endpoint level:** Entails answering queries based on safe exploration of records within a resource, and this is most suitable for querying of individual registries, biobanks and knowledge bases (i.e., resources with data about entities such as patients, biosamples, cell lines, etc).

To be queryable at this level, the resource must follow the **EJP RD Beacon v2 framework** [`link <https://github.com/ejp-rd-vp/vp-api-specs>`_], allowing querying at an aggregated level while preserving data privacy. The data elements queried at this level are based on the Common Data Elements (CDEs) for rare disease registration [`link <https://eu-rd-platform.jrc.ec.europa.eu/sites/default/files/CDS/EU_RD_Platform_CDS_Final.pdf>`_].

Beacon v2 itself consists of two components: the Framework and the Models. The Framework contains the format for the requests and responses, whereas the Models define the structure of the data response. In the context of EJP RD VP Level 2 querying, the queried summary metadata (catalog level) and safe data (record level) can be provided in any convenient format, including the EJP RD metadata schema (catalog level) and the CARE-SM (record level). 

The overall function of these components is to expose an interface through which users can query a resource. Beacon v2 interfaces have formal, machine-readable definitions that follow the OpenAPI Specification, that defines the capabilities of the API. Content-based discovery queries can be initiated from any query point in the VP network (e.g., the EJP RD VP portal) by a Beacon-based API as long as the resource has exposed its data following the EJP RD Beacon v2 framework with the filters and models described in the EJP RD VP API specification [`link <https://github.com/ejp-rd-vp/vp-api-specs>`_]. These filters are briefly described below.

Level 2 endpoint types: Catalogs and Individuals
------------

The /catalogs endpoint and the /individuals endpoint have different filters to query the exposed data. Results of queries from both endpoints will only be aggregated data and will not reveal sensitive information.



.. toctree::
   :maxdepth: 1
   :caption: Contents:

   catalogs_level
   individuals_level
   vp_api
   post_onboard
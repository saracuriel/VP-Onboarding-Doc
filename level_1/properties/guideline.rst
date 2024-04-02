Guideline
~~~~~~~~~~~~

**Mandatory Properties**

.. list-table:: 
	:widths: 20 60 20
	:header-rows: 1

	* - Property
	  - Definition and usage note
	  - URI
	* - **Title**
	  - The name of the guideline. This is a required field and needs to be unique.
	  - | dcterms:title
	* - **Description**
	  - A description of the patient registry.
	  - | dcterms:description
	* - **License**
	  - This should contain a URL that provides details regarding the license that is applicable to this resource. If no suitable license can be provided, then the default license should be used: https://w3id.org/ejp-rd/resources/licenses/v1.0/. Other licenses are:   https://creativecommons.org/licenses/, e.g. http://creativecommons.org/licenses/by-nc-nd/4.0
	  - | dcterms:license
	* - **Theme**
	  - Points to an URL that specifies relevant ontology concepts that classify the patient registry. Typically, these can be looked up using the `Ontology Lookup Service (OLS) <https://www.ebi.ac.uk/ols/index>`_ or Bioportal.
	  - | dcterms:theme
	* - **Publisher**
	  - Pointer to the Organisation that published the resource. The range is foaf:Organisation
	  - | dcterms:publisher
	* - **Personal Data**
	  - Set to "true" if the resource onboarded to the Virtual Platform contains personal data, personal data meaning data related to identified or identifiable persons (as per GDPR definition), otherwise "false".
	  - | ejprd:personalData
	* - **Contact Point**
	  - Pointer to a Contact Point, Range is vCard
	  - | dcat:contactPoint 
	* - **Language**
	  - An ISO 639-1 two-letter code for the languages this patient registry is provided in. Example: en indicates that this patient registry is available in English. The range is an xsd:string. The ISO language codes can be found at:  https://id.loc.gov/vocabulary/iso639-1.html  and an example:  http://id.loc.gov/vocabulary/iso639-1/en 
	  - | dcterms:language 
	* - **issued**
	  - This resource publication date. The range is xsd:date
	  - | dcterms:issued
	* - **modified**
	  - This resource last revision date. The range is xsd:date
	  - | dcterms:modified


**Recommended Properties**

.. list-table::
	:widths: 20 60 20
	:header-rows: 1

	* - Property
	  - Definition and usage note
	  - URI
	* - **Access Rights**
	  - Information about who can access the resource or an indication of its security status. This should point to a URL where this information can be found. We strongly recommend that access rights are described as DUC CCE profile.
	  - | dcterms:accessRights





	* - **Endpoint Description**
	  - A machine-readable document defining the API of the service (e.g., in openAPI). **This field is required for services that have an API.** This field is optional for services that are attached to Catalogue, or serve via a Web page.
	  - | dcat:endpointDescription
	* - **Endpoint URL**
	  - The URL to which API requests are sent. **This field is required for services that have an API.** This field is optional for services that are attached to Catalogue, or serve via a Web page
	  - | dcat:endpointURL
	* - **Landing Page**
	  - This a URL to a web page with more information regarding the Data Service. **This field is required for services that have an API.**
	  - | dcat:landingPage


**Optional Properties**

.. list-table::
	:widths: 20 60 20
	:header-rows: 1

	* - Property
	  - Definition and usage note
	  - URI
	* - **Logo**
	  - A link to the graphic representation of this resource.
	  - | foaf:logo
	* - **ODRL Policy**
	  - An ODRL conformant policy document (`https://www.w3.org/TR/odrl-model/ <https://www.w3.org/TR/odrl-model/>`_) expressing the rights and/or responsibilities associated with access to and/or use of the resource. This should point to a URL where this conformant document has been published.
	  - | odrl:hasPolicy
	* - **version**
	  - The version indicator (name or identifier) of a resource. The range is a rdfs:literal
	  - | dcat:version
	* - **Conforms to**
	  - If applicable, it should point to the URL, an established standard to which the data within the described resource conforms (e.g. MAGE-ML for Microarray data).
	  - | dcterms:conformsTo
	* - **Keyword**
	  - Keywords applicable to this patient registry
	  - | dcat:keyword
	* - **VP Connection**
	  - This property is attached to every portion of your Metadata record that you wish the VP to explore (e.g. Dataset X, Data Service Y, but NOT Dataset Z). **If you do not add this tag to at least the description of your resource, you will not be onboarded.** The range is http://purl.org/ejp-rd/vocabulary/VPDiscoverable
	  - | ejprd:vpConnection
	* - **identifier**
	  - Identifier of this resource. It can be a link.  Range is an xsd:string
	  - | dcterms:identifier


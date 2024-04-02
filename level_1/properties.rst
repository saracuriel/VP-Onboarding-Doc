EJP RD Metadata Schema Properties
------------

Organization (Mandatory Properties)
~~~~~~~~~~~~

.. list-table:: Mandatory Properties for Organization
	:widths: 20 60 20
	:header-rows: 1

	* - Property
	  - Definition and usage note
	  - URI
	* - **Title**
	  - The name of the Organisation. This is a required field and needs to be unique.
	  - | dcterms:title
	* - **Landing page**
	  - This a URL to a web page with more information regarding the Patient Registry. Any URL must start with http:// or https://
	  - | dcat:landingPage
	* - **Description**
	  - A description of the organisation. Example: hPSCreg® offers the research community, legislators, regulators, and the public at large an in-depth overview on the status of human pluripotent stem cell (hPSC) research.
	  - | dcterms:description


Organization (Optional Properties)
~~~~~~~~~~~~

.. list-table:: Level 1 - Optional Properties for Organization
	:widths: 20 60 20
	:header-rows: 1

	* - Property
	  - Definition and usage note
	  - URI
	* - **Logo URL**
	  - A link to the graphic representation of this resource.
	  - | foaf:logo
	* - **Location**
	  - The name of the location of the organisation. Example: Germany
	  - | dcterms:location
	* - **Identifier**
	  - Range is a string. We recommend using the ROR standard to identify your organisation.
	  - | dcterms:identifier


Patient Registries (Mandatory Properties)
~~~~~~~~~~~~

.. list-table:: Mandatory Properties for Patient Registries
	:widths: 20 60 20
	:header-rows: 1

	* - Property
	  - Definition and usage note
	  - URI
	* - **License**
	  - This should contain a URL that provides details regarding the license that is applicable to this resource. If no suitable license can be provided, then the default license should be used: https://w3id.org/ejp-rd/resources/licenses/v1.0/. Other licenses are:   https://creativecommons.org/licenses/, e.g. http://creativecommons.org/licenses/by-nc-nd/4.0
	  - | dcterms:license
	* - **Title**
	  - The name of the patient registry. This is a required field and needs to be unique.
	  - | dcterms:title
	* - **Description**
	  - A description of the patient registry.
	  - | dcterms:description
	* - **Theme**
	  - Points to an URL that specifies relevant ontology concepts that classify the patient registry. Typically, these can be looked up using the `Ontology Lookup Service (OLS) <https://www.ebi.ac.uk/ols/index>`_ or Bioportal.
	  - | dcterms:theme
	* - **Publisher**
	  - Pointer to the Organisation that published the resource. The range is foaf:Organisation
	  - | dcterms:publisher
* - **Publisher**
	  - Pointer to the Organisation that published the resource. The range is foaf:Organisation
	  - | dcterms:publisher

Patient Registries (Recommended Properties)
~~~~~~~~~~~~

.. list-table:: Level 1 - Recommended Properties for Patient Registries
	:widths: 20 60 20
	:header-rows: 1

	* - Property
	  - Definition and usage note
	  - URI
	* - **Logo URL**
	  - A link to the graphic representation of this resource.
	  - | foaf:logo
	* - **Location**
	  - The name of the location of the organisation. Example: Germany
	  - | dcterms:location
	* - **Identifier**
	  - Range is a string. We recommend using the ROR standard to identify your organisation.
	  - | dcterms:identifier


Patient Registries (Optional Properties)
~~~~~~~~~~~~

.. list-table:: Level 1 - Optional Properties for Patient Registries
	:widths: 20 60 20
	:header-rows: 1

	* - Property
	  - Definition and usage note
	  - URI
	* - **Logo URL**
	  - A link to the graphic representation of this resource.
	  - | foaf:logo
	* - **Location**
	  - The name of the location of the organisation. Example: Germany
	  - | dcterms:location
	* - **Identifier**
	  - Range is a string. We recommend using the ROR standard to identify your organisation.
	  - | dcterms:identifier

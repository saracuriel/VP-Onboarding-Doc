Distribution
~~~~~~~~~~~~

A distribution is a representation of your data. You can have as many distributions as needed of a dataset. For example, one distribution in .csv, another one in .json, etc.


**Mandatory Properties**

.. list-table:: 
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
	* - **Publisher**
	  - Pointer to the Organisation that published the resource. The range is foaf:Organisation
	  - | dcterms:publisher
	* - **Version**
	  - The version indicator (name or identifier) of a resource. The range is a rdfs:literal
	  - | dcat:version


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


**Optional Properties**

.. list-table::
	:widths: 20 60 20
	:header-rows: 1

	* - Property
	  - Definition and usage note
	  - URI
	* - **ODRL Policy**
	  - An ODRL conformant policy document (`https://www.w3.org/TR/odrl-model/ <https://www.w3.org/TR/odrl-model/>`_) expressing the rights and/or responsibilities associated with access to and/or use of the resource. This should point to a URL where this conformant document has been published.
	  - | odrl:hasPolicy
	* - **Media type**
	  - If you have more than one media type available for your resource and you wish to make them all accessible, you need to add another “Distribution”. Example: json.
	  - | dcat:mediaType
	* - **Access URL or Download URL**
	  - The URL from where the data can be accessed or downloaded.
	  - dcat:accessURL (to point to a web page from which the data can be downloaded) OR dcat:downloadURL (to point directly to the data file itself)
	* - **Access service**
	  - Pointer to the dcat:DataService if available
	  - | dcat:accessService
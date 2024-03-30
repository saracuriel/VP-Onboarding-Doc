What is the EJP RD Virtual Platform?
===================================

The EJP RD Virtual Platform network is an ecosystem of data resources and services related to rare diseases, that allows researchers and other stakeholders to easily find, access, and use data for different purposes, such as discovering and analysing it. To be part of this ecosystem, resources need to implement specifications [`link <https://www.ejprarediseases.org/wp-content/uploads/2023/05/EJPRD_P2_AD49_PU_Virtual-Platform-Specification-V2.0.pdf>`_] that make them 'Findable, Accessible, Interoperable, and Reusable (FAIR) for humans and machines'. We call those resources 'VP compliant'. This compliance varies depending on the features that the resources' controllers wish to provide. The more specifications a resource implements, the larger the contribution and empowerment to the functionality of the VP, and to research benefiting the rare disease community.

The VP network is designed so that a user, or an algorithm on behalf of a user, does not need previous knowledge of where data is. This means that data can be automatically found by machines, without the need to include explicit references to data in the algorithm code. Additionally, the user or the algorithm does not need to know the resource content beforehand, because FAIR data should be inherently interpretable by machines. Moreover, users and algorithms should not have to worry about incompatibilities between the resources or accidentally using data without permission. This is made possible by the interoperability of both data and metadata within the VP network, with metadata containing explicit access conditions.


For whom is the EJP RD Virtual Platform intended? 
------------

Onboarding resources to the VP benefits data resource managers by making their data reusable for rare disease research as well as data users like rare diseases researchers, clinicians, etc, who will have more data available for their analyses. The VP is designed to meet the needs of diverse stakeholders, each with specific objectives related to accessing and processing (meta)data.

Common users of the VP include:

#. **Clinicians** conducting research projects (e.g., European Research Network (ERN) researchers) whose main objectives include accessing the rare disease (meta)data available through the VP to conduct large-scale transversal studies, and building cohorts (e.g., for clinical trials). They can use the user-friendly interface with safeguards to prevent illegal or unethical data use. ERN patient registry developers can also create specialized interfaces for clinical researchers by incorporating VP functions in its user interface.  
#. **Application developers** whose main objectives are to develop new functionalities and applications for their organizations, e.g., adding functions to a clinical data platform in a hospital or creating user-friendly interfaces for given target users or for given tasks. These new functionalities could consist of (but are not limited to) various forms of analysis over multiple resources, such as queries for basic information, performing various forms of statistics, or running computational workflows. To fulfil these objectives, application developers will need a standardized API, like that of the VP, which in turn accesses standardized information from the resources. 
#. **Data scientists** whose objectives are to develop analysis methods across any number of resources with relevant data, e.g., by computational workflows, artificial intelligence or statistical methods, knowledge discovery, etc. To fulfil these objectives, the data scientists require that data in resources are standardized and machine actionable. In other words, spending months to make data compatible for each analysis will be outdated in the VP. 
#. **Patient representatives** whose main objectives are to foster optimal use of healthcare data derived from rare disease patients. Their primary objective is to ensure that relevant resources pertaining to rare diseases are easily accessible and usable by all those working towards patient priorities, such as improving quality of life, facilitating earlier access to care, and advancing the understanding of rare diseases, new drugs, and therapies. In addition, patients would benefit from a simple way to access their own data, see how their data is used in the VP, and be provided with statistics on their disease.


Why connect to the EJP RD VP
------------

By connecting to the EJP RD Virtual Platform, a resource joins a network of data sources that enables them to be semantically interoperable and to be accessible as detailed in the previous section.  It additionally allows the resource to interact and cross-query their metadata and/or data with other resources of relevance within the network. 

Through the process of connecting to the Virtual Platform, the resource is offered guidance by the EJP RD team of FAIRification Stewards. The onboarding process can be a valuable opportunity to build the resource’s strategy for data reusability and to identify the technical path for enabling it. Milestones can be set according to the desired `level of connection <https://ejprd.sharepoint.com/:w:/r/sites/pillar2-central9/Shared Documents/General/3.3_WF_FAIRification/OnboardingTasks/Onboarding document 2.0.docx?d=wf386b4e9247b47b3bdc049bb9cff57e5&csf=1&web=1&e=mXSv1s&nav=eyJoIjoiMzgzODg1ODk2In0>`_.



How to connect to the EJP RD VP?
------------

Resources can connect to the VP at different levels. Depending on the level of connection chosen, the VP enables rare disease resources to have their metadata and/or data Findable, Accessible, Interoperable and Reusable (FAIR). Regardless of the level of connection, resources retain full control of their metadata/data by specifying who can access their resources and under which conditions. 

It is important to note that a resource can start at one level and later choose to upgrade or downgrade to a higher or lower level, respectively, depending on how it wishes to contribute functionally to the rare disease community.

The various levels are illustrated and described by Figure 1 and Table 1. Figure 1 illustrates the different levels to which a resource can connect to the VP. Table 1 provides a summary of the different connection levels to the VP, including a definition of each level, the technical requirements for onboarding, options of access conditions, and an example query that each connection level permits.

    ..  figure:: /figures/f1.png
        :alt:  Illustration of the different levels and their interaction with the Virtual Platform.
        :width: 100px

        Figure 1 - Illustration of the different levels and their interaction with the Virtual Platform.

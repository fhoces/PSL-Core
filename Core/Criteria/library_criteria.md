
Policy Simulation Library Project Criteria
============================================

Summary
-------

1. Models must be transparant.   
1. Interface recommendations fascilitate interoperability. 
1. Organizational recommendations fascilitate community.  

Introduction
-------------

Open-source modeling ensures that model results are reproducible, that experts around the world can collaborate to make models better, and that users can explore the parameter space for themselves. These outcomes systematically improve public policy decisionmaking. 

We have developed the criteria in this document to fascilitate the growth of an open source public policy modeling ecosystem.

Acceptance Criteria for Transparancy and Quality 
--------------------------------------------
--------------------------------------------

1. Models MUST be released under an OSI-approved opens source license.   
1. Data MUST be publicly available, unless release is restricted by a third party. 
1. For any data that SHOULD not be disclosed, provided MUST be:
	- A complete descriptive list of all data variables; 
	- Descriptive statistics for all data variables for such data (including averages, standard deviations, number of observations, and correlations to other variables), to the extent that the descriptive statistics do not violate the rule against disclosure;
	- Contact information for the individual or entity who has unrestricted access to the data. 
1. At least one test MUST generate key outputs from source materials, the test MUST be run with every new version, and the outputs of the test MUST be checked into the repository.  
1. Test coverage MUST be reported. 
1. Projects MUST use [semantic versioning][1]. 
1. Projects MUST report names and contact information for at least one maintainer. 
1. Projects MUST have a suggested citation. 
1. Projects MUST have a project overview. 
1. Projects MUST have installation directions. 
1. Project MUST be mirrored in the same GitHub organization as PSL-Core.

Community Criteria
-------------------

1. Projects SHOULD have a public roadmap.
1. Projects SHOULD have contributor documentation and guidelines. 
1. Projects SHOULD have regular office hours, webinars, or standing meetings. 
1. Projects SHOULD list technical contributors. 
1. Projects SHOULD list funders. 
1. Projects SHOULD list user citations and case studies. 
1. Projects SHOULD include subject matter tags, chosing from ...  
1. Projects SHOULD include a disclaimer. 
1. Projects SHOULD have a public issues tracker.
1. Projects SHOULD have a changelog. 
1. Projects MAY have a Stack Overflow channel. 
1. Projects MAY include a "News" translation of the changelog for users. 
1. Projects MAY include criteria for participating in cross-model PSL initiatives. 
1. Projects MAY include a link to a webapp verison. 
1. Projects MAY include a list of consultants. 


Interoperability Criteria
--------------------------

1. The source code SHOULD be written in an open source language. 
1. All input and output variables SHOULD be documented like...
1. All policy parameters and assumptions SHOULD be documented like...
1. Meta information about your project SHOULD be documenteded like... 
1. A configuration file, like...SHOULD identify the location of these materials in your repository. 




[1]: https://semver.org/
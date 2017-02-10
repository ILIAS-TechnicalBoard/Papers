#Members of the Technical Board

* Timon Amstutz, University of Bern, Switzerland
* Michael Jansen, Databay AG, Würselen, Germany
* Alexander Killing, Leifos GmbH, Cologne, Germany
* Richard Klees, CaT Concepts and Training GmbH, Cologne, Germany
* Fabian Schmid, studer + raimann ag, Burgdorf, Switzerland

###Contact
Do you have any security related questions? Would you like to discuss the development process? Are there suggestions that do not fit into the feature wiki you want to be heard? The Technical Board has its own mailing list, just send us your input, we promise to get back to you: tb@lists.ilias.de

###Function and Guidelines
Within the process of ILIAS software development, the Technical Board was established in 2016 in the ILIAS society to push improvements and further development of ILIAS in an effective and useful way.
 
Main task is to develop strategies for ILIAS Software-Engineering within the general vision of ILIAS.
 
Aware that many areas cannot be considered separate but rather holistic, the Technical Board is split in the following five fields of activity.
 
* Software Architecture
* Performance
* Security
* Usability
* Quality Assurance and Development Process
 
This text describes the specific tasks in the different fields of work and sets possible guidelines to adapt optimally to the needs of the growing ILIAS community.
 
We know that many of you already operate within the different thematic fields. We want to invite you to continue your work and cooperate with us.

###Software Architecture
The field "Software Architecture" is responsible for the underlying
rules and definitions of used pattern in ILIAS core code. It will determine the functionality of programming languages that developers should use and provides rules for how code will be documented.
 
It also takes care of questions like:
 
* How can the ILIAS software be structured and built to minimize the error potential?
* How can functionality be encapsulated in a way, that one failing component cannot affect other components?
* How can code be structured in a modular way to be expandable and to make individual components replaceable?
* How can software be structured to support current maintenance principles?

###Performance
The field “Performance” is about gaining and maintaining a sustainable system efficiency, regarding the dimensions
 
* CPU usage,
* RAM usage and
* Response time.
 
The aim of the field of activity is to assess the dimensions in an objective manner. For this aim, metrics about the dimensions have to be measured to quantify the impact of various decisions like using libraries, patterns or the implementation of feature requests.
 
It is possible to use the metrics to define performance requirements for some special features or features in general.
 
Dealing with performance measurements will also have a performance impact in optimizing ILIAS default settings and give suggestions for hard- and software that leads administrators to a well-performing ILIAS installation.
 
The results of performance measurements will be documented and communicated to the broader community to raise the awareness of critical questions regarding performance.

###Security
The field “Security” is split in two fields of work. One is to protect information and data in ILIAS from unauthorized access, the other is to define policies how the ILIAS community should deal with security and privacy related issues.
 
Part of the first field is to define the processes and policies about storing and defending information and data against common threats and attacks. Among other things this includes:
 
* Preventing: Unauthorized Access or Disclosure, Use, Modification, Inspection
* Addressing: OWASP Top 10 Application Risks, Top 10 Security Risks (https://www.owasp.org/index.php/Category:OWASP_Top_Ten_Project)
* Ensuring: Confidentiality, Integrity, Authenticity, Non Repudiation

 
Questions are: How and in which intervals will security of ILIAS be assessed? Or: How can possible scenarios be described to achieve relevant coverage in periodic penetration tests?
 
A further task of the first field is to create developer guidelines and to define rules for dos and don'ts, regarding:
 
* Form Processing/URL
* Database/SQL
* Session/Cookies
* File Uploads
* (Dynamic) Includes
* Secure Authentication (Methods)/Authorization/Password Storage
 
The guidelines and rules also include recommendations for secure default settings of ILIAS and the environment like web server or runtime.
 
The second field of work deals with the case of emergency. What happens for example, when a bug is found? What will be published, when, and for whom? Issue tracker or commit messages for example shouldn’t be used as they are to public, but what can be used? The field defines policies how the ILIAS community should act under the circumstances of security-related topics.

###Usability
In the field “Usability” everything revolves around the user of the system. The field of activity examines and optimizes the efficiency, learnability, memorability, fault tolerance and the level of satisfaction that ILIAS delivers for its users.
 
How can for example a user reach a specific target in a specific context by the fastest possible means? How can we ensure, that the ILIAS system is simple to use and that it is self-explanatory in the best possible way?
 
To reach these goals it is necessary to learn more about the target user groups of ILIAS and their main objectives and to find a way of integrating these main objectives in the basic application concept of ILIAS and its main purpose.
 
The field of work operates according to the following principles:
 
* consistency (internal and external)
* visibility (mapping and affordance of objects, system status and feedback)
* simplicity (memory load, minimalist design)
* design for error (diagnose and recover, reversal of actions)
* effectiveness (locus of control)
 
These principles will be the basis to define concrete guidelines, concepts, tools and components that directly support software development and general improvement in usability of ILIAS.
 
The field will work out metrics (for example user tests) that allow to measure the different usability aspects and to monitor their progress over time.

###Development Process and Quality Assurance
The two fields of work “Development Process” and “Quality Assurance” are combined in one field of activity.
 
Development Process coordinates the creation of output of the development process, the ILIAS OSS (Open Source Software). This includes a comprehensive communication to the stakeholder and also defining and documenting the complete workflow around the annual releases of ILIAS. Specific aspects of these topics are:
 
* define the timeline for release of ILIAS OSS
* define the responsibilities and limitations of maintainerships
* define the workflows for the development guide
* propose recommendations on which tools can be used for developing
* define requirements for contributions to the core code
* define requirements for entries in the feature wiki
* structure and regulate the conditions of the jour fixe
* define the workflow of the jour fixe
 
The second field of work is Quality Assurance (QA). The field of activity will propose measures for the quality assurance and for necessary actions and it will predefine processes depending on the output of those measures. The field of activity w uses amongst others the following evaluations for QA:
 
* output of the CI server (Unit Tests, Dicto Rules, Continious Performance)
* results from Testrail
* statistics and facts from Mantis
* statistics and facts from the feature wiki
* statistics and facts from Github
* compliance of release dates with the timeline defined in the software process
* output of measures collected by other fields

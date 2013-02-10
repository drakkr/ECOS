% Method of Evaluation of Costs linked to Open Source (ECOS)
% ![Logo](Images/ECOS.png)
% Version 1.0 - 21/11/2012

This document describes the ECOS method, designed to evaluate the costs linked to Open Source in an objective manner, traceable and argued.
It is distributed under the terms of the GNU Free Documentation License.

# License

Copyright © 2012-2013 Atos.

Permission is granted to copy, distribute and/or modify this document under the terms the GNU Free Documentation License v1.2 published by the Free Software Foundation ; the Invariant section being "ECOS Manifesto", the Front-Cover Text being "This document describes the ECOS method, designed to evaluate the costs linked to Open Source in an objective manner, traceable and argued. It is distributed under the GNU Free Documentation License.", and no Back-Cover Texts.

A copy of the license is available on this page <http://www.gnu.org/copyleft/fdl.html>.

# ECOS Manifesto

##  Of the need of a method

The cost of free and open source software comes with a lot a of stereotypes. Indeed, free means both "for zero price" (gratis) and "with little or no restriction" (libre). To avoid this ambiguity, the distinction is made with this phrase: « Think free as in free speech, not free beer ».

Cost reduction often leads to consider open source. But to avoid surprises, possible benefits and economies have to be checked from the very beginning. Every single deployment project, even without license fees, comes with related costs.

A clear distinction between cost reduction and cost reallocation is very important. Financial aspects must be taken into consideration for any reflections on Open Source.

Having a method of evaluation of costs linked to the deployment and use of free and open source software is therefore necessary.

* What is the cost of this software support compared to the one already installed?

* What is the cost of change?

* What are the estimated productivity gains?

* What are the licenses acquisition and management related economies?

* What are the hardware related economies?

* What is the cost of vendor lock-in?

To serenely answer these questions and make an educated decision while managing the risks, it is required to have a method that allows to :

* compare the cost of ownership of proprietary software to the cost of ownership of free and open source software ;

* assess the cost of change ;

* assess the return on investment.

Those different points led Atos to design and formalize the method of Evaluation of Costs linked to Open Source (ECOS).

##  Of the need of a free method

In our opinion, such a method must be distributed to anyone under a free license. Only such a license is indeed able to guarantee the promotion of the free and Open Source movement, through :

* the possibility of the reuse of the evaluations by anyone ;

* the quality and objectivity of the generated documents, that can always be improved through transparency and peer review.

Hence, Atos decided to distribute the ECOS method under the GNU Free Documentation License.

# History of modifications

--------------------------------------------------------------------------------------
 Version   Date       Authors                  Comments
--------- ----------  --------------------     ---------------------------------------
  1.0      21/11/2012 Thomas Moreau (Atos)     Design and first draft.
                      Raphaël Semeteys (Atos)  
--------------------------------------------------------------------------------------

# Introduction

##  Purpose

This document deals with the method, named "ECOS" (Evaluation of the Costs linked to Open Source), designed by Atos to evaluate the costs linked to Open Source within the framework of consulting and software migration.
This method can be used as part of a more general approach of IT governance that is not discussed here, describes a process of evaluation of the cost of ownership of software and return on investment.

##  Target audience

The target audience is :

* people inquiring on the method either as professionals or as non-professionals ;

* free and open source communities ;

* IT experts wanting to know and apply this method in day-to-day activities of evaluation and selection of components in order to build software solutions meeting their or their customers needs while minimizing costs ;

* companies and organizations willing to evaluate the costs linked to Open Source in their information systems.

# General approach

The ECOS approach, composed of four interdependent steps, start at the first stage before making a decision, goes on during the installation or migration of a part of the information system and keeps going after the change-over, in operational conditions.

![General approach of ECOS](Images/processus-en.png)

##  Continuous application

The ECOS method can be used before, during and after the installation of a free and open source solution.

###  Before

The ECOS method can be used before making a decision. It allows to highlight important elements to make an educated decision regarding the adoption, the migration or the rejection of a free and open source solution. The method allows to spot several targets and several relevant ways of migration and also to discover interesting opportunities.

###  During

The ECOS method can be used during the installation of a free and open source solution. It allows to provide financial reports, to track variance, to sharpen or review initial hypothesis and to spot interesting economic blueprints.

###  After

The ECOS method can be used after the installation of a free and open source solution. It allows to validate hypothesis, to provide a balance sheet of the project and to communicate the results.

##  Interdependent steps

The general approach of ECOS is composed of several interdependent steps that may be followed with different granularities in order to be more or less detailed:

+------------------+---------------------------------------------------------------------------------+
| Step             | Description                                                                     |
+==================+=================================================================================+
| Define           | Definition with the IT teams of the domains and sectors that will be studied and|
|                  | the time frame of the study.                                                    |
+------------------+---------------------------------------------------------------------------------+
| Collect          | Collection of the data regarding the information system, the governance, its use|
|                  | and its costs. IT teams involvement is required through interviews and access to|
|                  | financial figures.                                                              |           |
+------------------+---------------------------------------------------------------------------------+
| Evaluate         | Evaluation of the opportunity of migration and relevant free and open source    |
|                  | alternatives.                                                                   |
+------------------+---------------------------------------------------------------------------------+
| Compare          | Qualitative and quantitative comparison of relevant scenarios with advantages,  |
|                  | disadvantages, costs, benefits and return on investments.                       |
+------------------+---------------------------------------------------------------------------------+

###  Define

####  Scope

The first step of the process of evaluation of the costs linked to Open Source is to define the scope of the study. It means choosing the different domains and sectors of the information system that are in better position to benefit from a substantial cost reduction, according to the extremely high price of existing solutions or because of the difficulty to maintain or improve a solution based on a obsolete and closed source component for example.

####  Time Frame

The return on investment is usually calculated on a 3 to 8 years term. This time frame must be fixed according to the context and strategic plan of the organization.

###  Collect

The second step of the process of evaluation of the costs linked to Open Source is to collect the all data regarding the use (like the criticality for example) and the costs (licenses fees, support...) of the solutions in the domains and sectors of the information system chosen in the previous step.

In addition to financial figures, it may be useful to interview the IT teams in order to clearly understand the needs and expectations.

###  Evaluation

The third step of the process of evaluation of the costs linked to Open Source is to evaluate different solutions.

####  Two modes of evaluations

The criteria may be evaluated within two modes :

* quantitatively, usually in currency or monetary unit, to measure the economic efficiency, the profitability ;

* qualitatively, usually a score from -1 to 1, because a purely monetary method would overshadow important qualitative criteria. The qualitative criteria are represented in graphs.
In order to have a clear view of the costs linked to Open Source, it is recommended to evaluate only 5 qualitative criteria maximum.

####  Calculation

The cost difference between the installed solution and the free and open source alternatives is used to measure the economic efficiency, the profitability of change.
In order to have a single score to compare two scenarios, it is possible to mix qualitative and quantitative results. This score, named ECOS score, is calculated with this formula:
ECOS score      = sum of quantitative criteria's value
                  x ( 1 + sum [qualitative score x weight])
where :
Qualitative scores may be -1, 0 or 1.
Weight assigned to qualitative criteria may be 5%, 10% or 15% depending of how important the criterion is, 5% being assigned to an unimportant criterion while 15% is assigned to important criterion.  
Example:  
Note ECOS	= 30 000 x (1 + -1x5% + 0x5% + 1x10% + -1x15% + 0x10%)  
		= 30 000 x (1 + -10%)  
		= 27 000 €C0$  

####  OPerational Expenditures (OPEX)

#####  Hardware

Keeping old hardware instead of buying new one, reducing energy consumption and reducing used space in datacenters may reduce costs.

__Example__

The online travel company Orbitz has moved major portions of its infrastructure off Oracle's Coherence to noSQL Couchbase. So the number of nodes has been reduced from 400 to 70 and the in-memory cache size reduced from 620GB to 55GB.

__Type of criterion__

The hardware cost can be measured in terms of money if financial figures are provided by the IT teams.
Should the opposite occur, a score from -1 to 1 may be assigned to this criterion :

* 1 : free and open source alternatives require more hardware ;

* 0 : free and open source alternatives hardware requirements are virtually identical ;

* -1 : free and open source alternatives require less hardware.

#####  Security

Security is a key aspect of any information system. It can be measured in terms of money or qualitatively through security flaws discovery and fix time.

__Example__

According to French National Information Security Agency (ANSSI) :
"The use of proprietary technologies, stewarded by Extra-European interest, is a major disadvantage for the national sovereignty and security. As most other European countries, France has important technological vulnerabilities in that matter and the sole possible parry is the use of free software."

__Type of criterion__

The security cost is difficult to measure. IT security vendors report figures without disclosing the methodology nor the data.

Unless the IT teams are able to provide financial data regarding IT security, this criterion is assigned a score from -1 to 1 :

* 1 : free and open source alternatives are less secure ;

* 0 : free and open source alternatives security is virtually identical ;

* -1 : free and open source alternatives are more secure ;

#####  Lock-in avoidance and interoperability
Lock-in avoidance is possible thanks to the use of interoperable solutions.

__Example__

The Open Document format is an open standard and can be used by many applications such as OpenOffice.org, LibreOffice, AbiWord, Google Drive, Koffice, MS Office 2007 and 2010, NeoOffice or Sun Microsystems StarOffice.
Choosing a solution might impose Operating System restrictions. For example, MS Office is not available on Linux platforms.
Choosing an Operating System might impose processor architecture restrictions. For example, AIX is bound to PowerPC, Solaris is bound to SPARC and MS Windows is bound to x86.

__Type of criterion__

The cost of vendor lock-in or interoperability is difficult to measure.
Unless the IT teams are able to provide financial data regarding vendor lock-in, this criterion is assigned a score from -1 to 1 :

* 1 : free and open source alternatives increase vendor lock-in ;

* 0 : free and open source alternatives interoperability is virtually identical ;

* -1 : free and open source alternatives decrease vendor lock-in.

#####  Productivity

Productivity can be increased by switching to alternative solutions.

__Example__

PDF conversion is a native feature in OpenOffice and LibreOffice while it is not available in Microsoft Office.

__Type of criterion__

Productivity can be measured in terms of money if financial figures are provided by the IT teams.
Should the opposite occur, a score from -1 to 1 may be assigned to this criterion :

* 1 : free and open source alternatives decrease productivity ;

* 0 : free and open source alternatives maintain productivity ;

* -1 : free and open source alternatives increase productivity ;

#####  Availability

Switching to alternative solutions may increase application availability.

__Example__

Since it moved off Oracle's Coherence into noSQL Couchbase, Orbitz can now roll out changes to its web application without downtime.

__Type of criterion__

Availability related cost is difficult to measure.
Unless the IT teams are able to provide financial data regarding downtime, this criterion is assigned a score from -1 to 1 :

* 1 : free and open source alternatives increase downtime ;

* 0 : free and open source alternatives maintain downtime ;

* -1 : free and open source alternatives decrease downtime.

#####  Image improvement

Communicating about the switch to Open Source can improve the company's image. It may reinforce corporate values, like expertise, transparency, collaborative work, team spirit or sustainable development.

__Example__

Companies such as Google and Twitter are well known for their involvement in free and open source projects and cultivate their image.

__Type of criterion__

Image improvement is measured qualitatively. A score from -1 to 1 is assigned to this criterion :

* 1 : free and open source alternatives damage the department or the company's image ;

* 0 : free and open source alternatives maintain the department or the company's image ;

* -1 : free and open source alternatives improve the department or the company's image.

#####  Support

Because a solution is open source, many companies can offer support. The competition decrease prices while maintaining a good quality of support.

__Example__

Using free software allowed a French ministry to cut 90% of its applications operating expenses. This huge cost reduction has been allowed by issuing a public tender regarding the maintenance of more than a hundred pieces of software with very strict SLAs (Time to recover of 48 hours...)

__Type of criteria__

The cost of support can be measured in terms of money if financial figures are provided by the IT teams.
Should the opposite occur, a score from -1 to 1 may be assigned to this criterion :

* 1 : free and open source alternatives support is more expensive ;

* 0 : free and open source alternatives support is as expensive ;

* -1 : free and open source alternatives support is less expensive ;

#####  Licenses

Free and open source solutions don't come with license fees nor license management costs.

__Example__

Oracle's licenses fees are well known for its expensiveness while there is an alternative without license fees : PostgresSQL.

__Type of criterion__

The cost of license fees and license management can be measured in terms of money if financial figures are provided by the IT teams.

#####  Innovation

Using free and open source solutions can allow to create new goods and services and to innovate. Indeed, access to the source allows to start specific software development more easily.

__Example__

The hadoop ecosystem and the noSQL movement are open source solutions leading big data.

__Type of criterion__

The cost of innovation is difficult to measure.
Unless the IT teams are able to provide financial data regarding innovation, this criterion is assigned a score from -1 to 1 :

* 1 : free and open source alternatives are less innovative or stifle innovation ;

* 0 : free and open source alternatives are as innovative ;

* -1 : free and open source alternatives are more innovative or accelerate innovation.

#####  Quality of service

Free and open source solution can deliver a better quality of service.

__Example__

Orbitz has significantly improved the latency of its applications while ending weekly failures by switching from Oracle's Coherence to Couchbase.

__Type of criterion__

The cost of the quality of service is difficult to measure.
Unless the IT teams are able to provide financial data regarding the quality of service, this criterion is assigned a score from -1 to 1 :

* 1 : free and open source alternatives decrease the quality of service ;

* 0 : free and open source alternatives maintain the quality of service ;

* -1 : free and open source alternatives increase the quality of service.

#####  Continuity
The continuity of a solution and its data is essential. It is even more crucial under mandatory data retention policies.

__Example__

Using an open standard offers better guarantees of data reusability, even years after.

__Type of criterion__

The cost of continuity is difficult to measure.
Unless the IT teams are able to provide financial data regarding continuity, this criterion is assigned a score from -1 to 1 :

* 1 : free and open source alternatives offer worse continuity ;

* 0 : free and open source alternatives offer the same continuity ;

* -1 : free and open source alternatives offer better continuity ;

####  CAPital EXpenditures (CAPEX)

#####  Urgency

Switching to open source comes from either an altruist or an opportunist attitude. The need of change can come from legal or regulatory obligations or from the obsolescence of the installed solution, that has reached EoL (End of Life) or EoS (End of Support).

__Example__

With the huge changes brought by Microsoft Office 2007 came the opportunity to switch to the OpenOffice.org suite.

__Type of criterion__

The need of change is measured qualitatively. A score from -1 to 1 is assigned to this criterion :

* 1 : change is not necessary or not urgent ;

* 0 : change is necessary but not very urgent ;

* -1 : change is necessary and urgent.

#####  Training

Switching software might require staff training.

__Example__

Database management system PostgreSQL training.

__Type of criterion__

The cost of staff training is measured in terms of money.

#####  Communication

Good communication is key to any project.

__Example__

posters, brochures.

__Type of criterion__

The cost of communication is measured in terms of money.

#####  Emphasis

Emphasizing on knowledge, through a wiki or a forum for example, helps a lot in making the transition to the new solution.

__Example__

Maintaining a wiki or a forum.

__Type of criterion__

The cost of emphasis is measured in terms of money.

#####  Additional work

Additional work has to be anticipated during the period of transition between the two solutions.

__Example__

Maintaining the two solutions at the same time.

__Type of criterion__

The cost of additional work is measured in terms of money.

#####  Expertise

The change might require expert consultancy.

__Example__

Expert consultancy on PostgreSQL data migration.

__Type of criterion__

The cost of expert consultancy is measured in terms of money.

#####  Hardware

Additional hardware might be required during the period of transition between the two solutions.

__Example__

Server rental.

__Type of criterion__

The cost of additional hardware is measured in terms of money.

#####  Data conversion and specific software development

Switching solutions might require data conversion or specific software development.

__Example__

Microsoft Excel macros to Apache OpenOffice conversion.

__Type of criterion__

The cost of data conversion and specific software development is evaluated in money terms.

#####  Verification and validation

In order to make sure the solution is working properly, it is necessary to go through a verification and validation process.

__Example__

Proof of Concept development.

__Type of criterion__

The cost of the verification and validation process is measured in terms of money.

###  Compare

The first step of the process of evaluation of the costs linked to Open Source is to compare in quantitative, qualitative and mixed ways (with the ECOS score) the different relevant scenarios with their advantages, disadvantages, costs, benefits and return on investment.

#  Tools

A tool is being developed by Atos to apply this method.
A spreadsheet is available enclosed.

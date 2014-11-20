[![Stories in Ready](https://badge.waffle.io/modelwriter/product-backlog.png?label=ready&title=Ready)](https://waffle.io/modelwriter/product-backlog)
[Product-Backlog](https://waffle.io/modelwriter/product-backlog)
===============
**Product backlog of the ModelWriter project** 

Product Backlog: [https://waffle.io/modelwriter/product-backlog](https://waffle.io/modelwriter/product-backlog)

The product backlog itself is implemented in the [issue tracker](https://github.com/modelwriter/product-backlog/issues) of this repository.

For details on the scrum of scrum process see [this wiki page](https://github.com/modelwriter/product-backlog/wiki/Scrum-of-scrum-process).

[![Throughput Graph](https://graphs.waffle.io/modelwriter/product-backlog/throughput.svg)](https://waffle.io/modelwriter/product-backlog/metrics)  

Conventions for WP start date and end date:
* M\<i\> always means start of the month \<i\>.
* Q\<i\> always means start of quarter \<i\>
* Y\<1\> always means start of year \<1\>
* First month is M1, first quarter is Q1, first year is Y1.

Therefore:
* First day of project is M1.
* End of a 3-year project is expressed as M37

Work Packages, Tasks and Deliverables
===========

The exhaustive list of deliverables **D\<x\>.\<y\>.\<z\>** associated to each Task **T\<x\>.\<y\>** of each **WP\<x\>**.


**WP1 Industrial Use Cases and Requirements (EADS)**
* T1.1 – Evaluation Methods & Tools [UNIT + KS + Industrial Use Cases partners]
  * D1.1.1 Report: Evaluation Methods & Tools
* T1.2 – Industrial Use Cases for Belgian Consortium (EADS)
  * D1.2.1 Report: Industrial Use Cases for Belgian Consortium
   * D1.2.2 Data: Corpus for D1.1.1 (public part)
   * D1.2.3 Data: Corpus for D1.1.1 (confidential part)
* T1.3 – Industrial Use Cases for French Consortium (Obeo + EADS Fr IW)
  * D1.3.1 Report: Industrial Use Cases for French Consortium
  * D1.3.2 Data: Corpus for D1.2.1 (public part)
  * D1.3.3 Data: Corpus for D1.2.1 (confidential part)
* T1.4 – Industrial Use Cases for Turkish Consortium (Mantis + UNIT + KS + HISBIM)
  * D1.4.1 Report: Industrial Use Cases for Turkish Consortium
  * D1.4.2 Data: Corpus for D1.4.1 (public part)
  * D1.4.3 Data: Corpus for D1.4.1 (confidential part)
* T1.5 – Consolidated User Requirements (EADS + Country Coordinators)
  * D1.5.1 Report: User Requirements Document (URD) for ModelWriter
* T1.6 – User Requirements Review (EADS + UNIT+ KS + KUL + ALL)
  * D1.6.1 Report: Minutes of the User Requirements Review meeting
* T1.7 – Software Requirements (EADS + WP2 to WP7 leaders)
  * D1.7.1 Report: Software Requirements Document (SRD) for ModelWriter
* T1.8 – Software Requirements Review (EADS + UNIT + KS + KUL + ALL)
  * D1.8.1 Report: Minutes of the Software Requirements Review meeting
* T1.9 – Annual Product Review (EADS + Country Coordinators)
  * D1.9.1 Report: Annual Product Owner Review
* T1.10 – Technical Risk Assessment and Management (Obeo + UNIT + KS+ ALL)
  * D1.10.1 Technical Risk Assessment Document

**WP2 - Semantic Parsing and Generation of Documents and Documents Components (LORIA)**
* T2.1 – Data Collection (LORIA+KUL+SA)
  * D2.1.1 Report: Software Requirements - Evaluation of the natural language processing requirements set by the use cases [LORIA,KUL]
* T2.2 – Hybrid approaches to semantic parsing (KUL+LORIA)
  * D2.2.1 Report: Overview and comparison of existing deep semantic parsers
* T2.3 – Hybrid approaches to Natural Language Generation (LORIA+VUB+KUL) 
  * D2.3.1 Report: Overview and comparison of existing generators
* T2.4 – Definition of the target semantic representation language (FUB+LORIA+FZI+EADS)
  * D2.4.1 Data: Corpora (Text, Knowledge, Bi-Texts) [LORIA,KUL,SA]. Report: Documentation of the corpora
* T2.5 – Development of the semantic parser and of the generator (LORIA + KUL)
  * [M8] D2.5.1	Report: Specification of the Knowledge Representation Language(s) output by the parser and input to the generator [VUB,KUL,LORIA]
  * [ M8, M20, M28] D2.5.2-x (release x=1,2,3) Software: Semantic Parser [KUL,LORIA]. Report: Software Documentation
  * [ M8, M20, M28] D2.5.3-x (release x=1,2,3)	Software: Natural Language Generator [LORIA,KUL]. Report: Software Documentation
  * [ M10, M22, M30] D2.8.x (release x=1,2,3) 	Software: Integration in ModelWriter [SA]. Report: Software Documentation

**WP3 Model to/from Knowledge Base (UNIT)**
* T3.1 - Review of M2M transformation approaches  (UNIT + KS)
  * D3.1.1 Review of model-to-model transformation approaches and technologies.
* T3.2 - Specification and design of the M2M Transformation Framework (UNIT + KS)
  * D3.2.1 M2M Transformation Framework architectural design document.
* T3.3 – Development of the Transformation Manager component (UNIT)
  * D3.3.1 Transformation Manager architectural design document.
  * D3.3.2-x (release x=1,2,3) Software: Transformation Manager component
* T3.4 – Development of the Configuration Manager component (UNIT)
  * D3.4.1 Configuration Manager architectural design document.
  * D3.4.2-x (release x=1,2,3)  Software: Configuration Manager component
* T3.5 – Development of the Traceability Manager component (UNIT)
  * D3.5.1 Traceability Manager architectural design document.
  * D3.5.2-x (release x=1,2,3)  Software: Traceability Manager component
* T3.6 – Development of the Synchronization Manager component (UNIT)
  * D3.6.1 Synchronization Manager architectural design document.
  * D3.6.2-x (release x=1,2,3)  Software: Synchronization Manager component
* T3.7 – Design of the model-to-model transformations (UNIT + Mantis + VUB)
  * D3.7.1 Model-to-model transformations (from user-visible models to KB-stored models) design document.
* T3.8 – Implementation of the model-to-model transformations (UNIT + VUB)
  * D3.8.1-x (release x=1,2,3)  Software: Source and binary code of each model-to-model transformation
* T3.9 – Validation of the M2M Transformation Framework (UNIT + Mantis + VUB + KS)
  * D3.9.1 Test-plan for the M2M Transformation Framework.
  * D3.9.2 Field experiment concerning ModelWriter model transformations

**WP4 - Knowledge Base Design and Implementation (Mantis)**
* T4.1 - Design of the Knowledge Base (VUB + SA + Obeo + Mantis + UNIT + KS)
  * D4.1.1 Report: Knowledge Base Design document
* T4.2 - API of the Knowledge Base (VUB + KS + Obeo + UNIT)
  * D4.2.1 Report: Interface Control Document (ICD)
* T4.3 - Implementation of the Knowledge Base (VUB)
  * D4.3.1-x (release x=1,2,3) Software: Knowledge Base
* T4.4 – Plug-in #1: ModelWriter-assisted requirements review (VUB + SA)
  * D4.4.1 Report: Technical Note for ModelWriter-assisted Quality Review of Requirements
  * D4.4.2 Software: Proof-of-concept model checker
* T4.5 – Knowledge Base serialization and reuse plug-in (Mantis)
  * D4.5.1 Report: Technical Note for KB serialization and reuse
* T4.6 – Plug-in #3: ModelWriter-assisted semantic comparison of 2 documents (Obeo + Mantis)
  * D4.6.1 Report: Technical Note for ModelWriter-assisted Comparison of 2 Documents
  * D4.6.2-x (release x=1,2,3) Software: Proof-of-concept semantic comparison engine
* T4.7 – Plug-in #2: ModelWriter-assisted compliance review (SA)
  * D4.7.1 Report: Future ModelWriter-Enabled Use Cases
* T4.9 – Internal bi-directional synchronization mechanism (Obeo + UNIT)
* T4.10 – External synchronization mechanism for collaborating ModelWriters (SA)

**WP5 Project Management (UNIT)**
* T5.1 – Project and Stage Plans (UNIT + WP Leaders)
  * D5.1.1-x (release x=1,2,3) Management reports and cost statements (confidential)
* T5.2 – Project Controls (UNIT + WP Leaders)
  * D5.2.1 Project Controls
  * D5.2.1-x (release x=1,2,3) Project and Next Management Stage Plan
* T5.3 – Project Monitoring (UNIT+ WP Leaders)
* T5.4 – Communication Management and Infrastructure (UNIT+ WP7 leader)
  * D5.4.1 Communication Management Strategy
* T5.5 – Risk Management and Infrastructure (UNIT+ WP Leaders)
  * D5.5.1 Risk Management Strategy (A24)
* T5.6 – Configuration Management and Infrastructure (UNIT+ WP Leaders)
  * D5.6.1 Configuration Management Strategy (A6)
* T5.7 – Quality Management and Infrastructure (UNIT+ WP Leaders)
  * D5.7.1 Quality Management Strategy (A22)
* T5.8 – Closing Project (UNIT+ WP Leaders)
  * D5.8.1 Final project report (Public Deliverable)
  * D5.8.2 Updated State-of-the-art (Public Deliverable)

**WP6 - ModelWriter Architecture, Integration and Evaluation (Obeo)**
* T6.1 - Experimental Prototyping (Obeo + SA +  VUB)
  * D6.1.1 Software: Prototype Core ModelWriter (Obeo, SA, VUB)
* T6.2 - Architectural Design (Obeo + SA + VUB + Mantis + UNIT + technological WP Leaders)
  * D6.2.1 Report: Architectural Design Document (ADD) (Obeo, SA, VUB, Mantis)
* T6.3 - Writer Part enhancements (SA)
  * D6.3.1-x (release x=1,2,3) Software: Writer enhancements (SA)
* T6.4 User Interfaces Implementation (SA + Obeo)
  * D6.4.1 Report: Ergonomics Guidelines document for the Writer Part (SA)
  * D6.4.2-x (release x=1,2,3) Software: User Interface for the Writer part (SA)
  * D6.4.3-x (release x=1,2,3) Software: IDE-integrated User Interface to handle Synchronization issues major release (Obeo)
* T6.5 - Acceptance Test Plan (SA + UNIT + KS + ALL)
  * D6.5.1-x (release x=1,2,3) Report: Acceptance Test Plan (SA + all)
  * D6.5.2-x (release x=1,2,3) Software: Automated Acceptance Tests (SA + all)
* T6.6 - Acceptance Test Procedures (SA + UNIT + KS + ALL)
  * D6.6.1-x (release x=1,2,3) Report: Acceptance Test Procedures (SA + all)
* T6.7 - ModelWriter Integration (Obeo + UNIT + ALL)
  * D6.7.1-x (release x=1,2,3) Software: ModelWriter major release (Obeo)
* T6.8 - Cyclic Evaluation of Analysis Performance (SA + Obeo + LORIA + UNIT + KS + ALL)
  * D6.8.1-x (release x=1,2,3) Report: Evaluation report (All)

**WP7 Dissemination and Exploitation**
* T7.1 - Dissemination Plan (Obeo + UNIT + SA + LORIA + KS + ALL)
  * D7.1.1 Dissemination Plan                                                                                                
* T7.2 – Business Model & Exploitation Plan (EADS Fr IW + SA + Obeo + all industrial partners)
  * D7.2.1 Exploitation Plan                                                                                                 
  * D7.2.1-1 Exploitation Plan Y1
  * D7.2.1-2 Exploitation Plan Updated Y2                                                                                   
  * D7.2.1-3 Exploitation Plan Updated Y3                                                                                  
  * D7.2.2 Marketing Plan                                                                                                    
  * D7.2.3 Roadmap for future exploitation and pre-competition survey                                                        
* T7.3 – Workshops & Events (VUB + UNIT + Obeo + KS + EADS Fr IW + ALL)
  * D7.3.1 Newsletter - International Conference Announcement
* T7.4 – ModelWriter-ITEA Consortium Website (SA)
  * D7.4.1 ModelWriter-ITEA website including secured intranet                                                                      
* T7.5 - Community Forum & Open Source Campaign (VUB + Obeo)
  * D7.5.1 Technical-oriented talk about the principles and benefits of the ModelWriter-ITEA approach and tooling                   
  * D7.5.2 Research-oriented talk about the principles and benefits of the ModelWriter-ITEA approach and tooling                    
* T7.6 – Social Networks (UNIT + KS)
  * D7.6.1 ModelWriter-ITEA's Facebook Group                                                                                        
  * D7.6.2 ModelWriter-ITEA's LinkedIn Group                                                                                        
  * D7.6.3 ModelWriter-ITEA's Twitter Group                                                                                         
  * D7.6.4 ModelWriter-ITEA's Yammer Group                                                                                          
* T7.7 – Standardization (LORIA + UNIT + KS)
  * D7.7.1 ModelWriter and standardization activities.

Common FAIR Vocabulary
======================
The common FAIR vocabulary is a set of consolidated terms pertaining to FAIR Principles based on Peng et al. (2024). Capitalized "Principles" denotes the FAIR Principles framework, while the lower case of "principles" refers to the descriptions of individual FAIR principles.

---------------------------------------------------
 Class, representing the FAIR Principles Framework
---------------------------------------------------
  * FAIR Principles, a framework providing high-level data management and stewardship guidelines defined by Wilkinson et al. (2016) for sharing digital resources, especially in a computer-friendly environment.

------------------------------------------------------------------------------------------
 Dimensions, representing the four key non-functional requirements of the FAIR Principles
------------------------------------------------------------------------------------------
  * ***Findability (F)***
  * ***Accessibility (A)***
  * ***Interoperability (I)***
  * ***Reusability (R)*** 

----------------------------------------------------------
 Sub-Classes, representing 15 individual FAIR principles
---------------------------------------------------------- 
  * {F1, F2, F3, F4, A1, A1.1, A1.2, A2, I1, I2, I3, R1, R1.1, R1.2, R1.3}
    * Sub-class in F: {F1, F2, F3, F4}
    * Sub-class in A: {A1, A1.1, A1.2, A2}
      * Sub-subclass in A1: {A1.1, A1.2}
    * Sub-class in I: {I1, I2, I3}
    * Sub-class in R: {R1, R1.1, R1.2, R1.3}
      * Sub-subclass in R1: {R1.1, R1.2, R1.3}

------------------------------------------------------------------------------
 Categories, representing unique core entities covered in the FAIR principles
------------------------------------------------------------------------------
  * ***Data (D)***
  * ***Metadata (M)***
  * ***Infrastructure (IS)***

---------------------------------------------------------------------------- 
 Quality Measures, representing unique core concepts in the FAIR principles
---------------------------------------------------------------------------- 
  *  ${\color{rgb(12,123,220)}Identifier}$, refers to a unique and persistent identifier for data and/or metadata.
    
  *  ${\color{rgb(12,123,220)}{\textsf{\textit{Rich Metadata}}}}$, refers to a set of descriptors of data including those minimally required for search and discovery, as well as those needed for understanding and reuse. This entity is closely related to “Attribute” in the context of (re)use.
    
  *  ${\color{rgb(12,123,220)}Resource}$, refers to infrastructure such as search engines like Google that users can perform searches to find relevant data.
    
  *  ${\color{rgb(12,123,220)}Protocol}$, refers to a computational agent such as HTTPs (Secure Hypertext Transfer Protocol) or FTP (File Transfer Protocol) that facilitates efficient information retrieval.
    
  *  ${\color{rgb(12,123,220)}Procedure}$, refers to a set of defined and implemented specified rules and roles in the data search and retrieval infrastructure for user authentication (e.g., Single Sign-on with Two-Factor-Authentication) and access control (user permission/profile).
    
  *  ${\color{rgb(12,123,220)}Language}$, refers to a formal system used to express the context of data and/or metadata in a format such as XML (eXtensible Markup Language) and RDF (Resource Description Framework) that can be utilized by machines.
    
  *  ${\color{rgb(12,123,220)}Vocabulary}$, refers to a standardized set of terms and their meanings or definitions; A data vocabulary may consist of terms and definitions that describe the types of data, their characteristics, and the relationships between different data elements. A metadata vocabulary includes terms and definitions used to describe metadata attributes, properties, and relationships.
    
  *  ${\color{rgb(12,123,220)}Reference}$, refers to a reference to another resource that provides additional relevant and useful information, including references to published documents (journal articles, reports, conference proceeding papers, etc.) on data product algorithms and validation, (meta)data standard specifications, as well as that to previous metadata records, if appropriate.
    
  *  ${\color{rgb(12,123,220)}Attribute}$, closely related to Rich Metadata, refers to a set of attributes that focus on providing information for use suitability and conditions of the discovered data.
    
  *  ${\color{rgb(12,123,220)}License}$, refers to a license that describes under which conditions the discovered data can be used; To facilitate reuse, the license chosen should be as open as possible and unambiguous to both humans and machines.
    
  *  ${\color{rgb(12,123,220)}Provenance}$, refers to information on when and how the data or metadata was created and modified, and by whom, its sources and ownership throughout its lifecycle.
     
  *  ${\color{rgb(12,123,220)}Standard}$, refers to an established or agreed-upon set of guidelines, rules, specifications, or criteria used as a reference or norms.

-----------
References
==========
Peng, G., G. Berg-Cross, M. Wu, R.R. Downs, S.R. Shrestha, L. Wyborn, N. Ritchey, H.K. Ramapriyan, S.J. Clark, J. Wood, Z. Liu, and A. Marouane, 2024: Harmonizing Quality Measures of FAIRness Assessment Towards Machine-Actionable Quality Information. *Intern. J. Digital Earth*. Under review.

Wilkinson, M. D.,  M. Dumontier, I. J. Aalbersberg, G. Appleton, M. Axton, A. Baak, and others, 2016: The FAIR Guiding Principles for scientific data management and stewardship. *Sci. Data*,  3,  https://doi.org/10.1038/sdata.2016.18  

==========================================================================

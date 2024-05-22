Common FAIR Vocabulary
======================
Consolidated terms pertaining to FAIR Principles based on Peng et al. (2024)

-------
 Class
-------
  * FAIR Principles, a framework providing high-level data management and stewardship guidelines for sharing digital resources, defined by Wilkinson et al. (2016).

------------------------------------------------------------------------------------------
 Dimensions, representing the four key non-functional requirements of the FAIR Principles
------------------------------------------------------------------------------------------
  * Findability (F) 
  * Accessibility (A)
  * Interoperability (I)
  * Reusability (R) 

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

------------------------------------------------------------------
 Categories, representing unique entities in the FAIR Principles
------------------------------------------------------------------
  * Data (D)
  * Metadata (M)
  * Infrastructure (IS)

---------------------------------------------------------------------------- 
 Quality Measures, representing unique core concepts in the FAIR principles
---------------------------------------------------------------------------- 
  * _Identifier_, a unique and persistent identifier for data and/or metadata;
  * _Rich Metadata_, a set of descriptors of data including those minimally required for search and discovery, as well as those needed for understanding and reuse. This core concept is closely related to “Attribute” in the context of (re)use.
  * _Resource_, infrastructure such as search engines like Google that users can perform searches to find relevant data;
  * _Protocol_, a computational agent such as HTTPs (Secure Hypertext Transfer Protocol) or FTP (File Transfer Protocol) that facilitates efficient information retrieval;
  * _Procedure_, a set of defined and implemented specified rules and roles in the data search and retrieval infrastructure for user authentication (e.g., Single Sign-on with Two-Factor-Authentication) and access control (user permission/profile);
  * _Language_, a formal system used to express the context of data and/or metadata in a format such as XML (eXtensible Markup Language) and RDF (Resource Description Framework) that can be utilized by machines;
  * _Vocabulary_, a standardized set of terms and their meanings or definitions; A data vocabulary may consist of terms and definitions that describe the types of data, their characteristics, and the relationships between different data elements. A metadata vocabulary includes terms and definitions used to describe metadata attributes, properties, and relationships.
  * _Reference_, a reference to another resource that provides additional relevant and useful information, including references to published documents (journal articles, reports, conference proceeding papers, etc.) on data product algorithms and validation, (meta)data standard specifications, as well as that to previous metadata records, if appropriate.
  * _Attribute_, closely related to Rich Metadata, a set of attributes that focus on providing information for use suitability and conditions of the discovered data;
  * _License_, a license that describes under which conditions the discovered data can be used; To facilitate reuse, the license chosen should be as open as possible and unambiguous to both humans and machines.
  * _Provenance_, information on when and how the data or metadata was created and modified, and by whom, its sources and ownership throughout its lifecycle; 
  * _Standard_, an established or agreed-upon set of guidelines, rules, specifications, or criteria used as a reference or norms.

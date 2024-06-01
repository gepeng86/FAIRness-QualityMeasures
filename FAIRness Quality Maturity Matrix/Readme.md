**FAIRness Quality Maturity Matrix (FAIR-QMM)**
-----------------------------------------------

This folder contains the FAIR-QMM for digital scientific data products as defined in Peng et al. (2024; Appendix A). The FAIR-QMM builds on a set of [FAIRness quality measures](https://github.com/gepeng86/FAIR-QualityMeasures/tree/main/FAIR%20Quality%20Measures) and informed by a wide array of community practices in the management and stewardship of digital scientific data (e.g., Wilkinson et al. 2016; 2019; Peng et al. 2015; Fenner et al. 2019; RDA FAIR Data Maturity Model Working Group 2020; Devaraju and Huber 2021; Jacobsen et al. 2020; Wu et al. 2023; Hutchison et al. 2024; Schultes 2023) as well as the online resources captured in Table A1. 

**Table A1.** A list of online resources that are beneficial in formulating the FAIRness Quality Maturity Matrix (FAIR-QMM)
| **Resource** | **URL** | **Commments** |
|    :---:     |  :---:  |  :---         |
| ARDC FAIR Data Self-Assessment Tool | https://ardc.edu.au/resource/fair-data-self-assessment-tool/ | Questionnaire with a drop-down menu for each question; a total of 12 questions. |
| GO-FAIR FAIR Implementation Questionnaires | https://www.go-fair.org/how-to-go-fair/fair-implementation-profile/ | 21 questions with associated FAIR enabling resource types. |
| GO-FAIR Foundation FAIR Interpretations | https://www.gofair.foundation/interpretation | Interpretations are primarily based on Jacobsen et al. (2020). |
| FAIRsFAIR F-UJI Tool | https://www.f-uji.net/index.php?action=home | Automatic tool with rules and automatic checks based on 17 of 41 RDA FAIR Data Maturity Indicators (Devaraju et al. 2022). |
| FAIRsharing FAIR Metrics | https://github.com/FAIRMetrics/Metrics/tree/master/MaturityIndicators | A set of 14 universal metric (Wilkinson et al. 2018). |


The full description of the FAIR-QMM for digital scientific data is provided in Tables A2.1-15, accompanied by explanations, examples, and corresponding harmonized FAIRness indicators from Peng (2023). The examples provided serve as references and do not indicate any endorsement or preference by the authors regarding their implementation. Additional references can be found in Peng et al. (2024).

**A2.1.** FAIR ID, quality measure (non-bolded entity denotes just core concept), definitions of Level 1, 2, and 3 maturity stages, along with explanations, examples, and associated harmonized indicators for the F1 principle.

｜**FAIR ID** ｜**Quality Measure** ｜**Level 1 Minimal Stage** ｜**Level 2 Intermediate Stage** | **Level 3Optimal Stage** |
| :---:       | :---:               | :---                      |  :---                         | :---                     |
| **F1** | **Identifier** | Data and metadata are assigned identifiers | L1 + identifiers are either: i) eternally persistent but not globally unique; ii) globally unique but not always persistent; iii) unique within a particular scientific discipline |L1 + identifiers are globally unique and eternally persistent |
| **Explanations** | Any identifier, usually just locally unique within an internal database or (meta)data management system |
Identifiers that are unique within a particular domain/group; many are valid only for the duration of a project; may or may not be resolvable |
Identifiers that are globally unique and permanently persistent - they should also be resolvable which implies “the persistence of the binding between identifier and object and the persistence of the service to resolve from the identifier to the object” (Treloar n.d.) but it is explicitly addressed in A1. |
| **Examples** |Identifiers for individual NASA CMR dataset-level and granule-level metadata records, e.g., C1996881146-POCLOUD; G2743390617-POCLOUD 
| Universally Unique Identifier (UUID) or Uniform Resource Locator (URL), which is globally unique but not necessarily persistent. 
International Virtual Observatory Identifier (VOID) - which is VO-specific - but can actually be globally unique.
| Digital Object Identifiers (DOIs) - also resolvable and citable.

Other widely used globally unique and persistent identifiers that are resolvable, include Handle, Persistent uniform resource locator (PURL), w3id, Archival Resource Keys (ARK). 

Utilizing a Globally UNique Persistent Resolvable Identifier (GUPRI) ensures the compliance to both F1 and A1. |
| **Harmonized Indicators** | F1-01D; F1-01DM 
| Meeting some, but not all, of the following indicators: F1-02D; F1-02M; F1-03D; F1-03M
| F1-02D; F1-02M; F1-03D; F1-03M |



**References**

Devaraju, A., R. Huber, M. Mokrane, P. Herterich, L. Cepinskas, J. de Vries, H. L'Hours, J. Davidson, and W. Angus. 2022. “FAIRsFAIR Data Object Assessment Metrics (0.5).” _Zenodo_. https://doi.org/10.5281/zenodo.6461229 

Fenner, M., M. Crosas, J.S. Grethe, D. Kennedy, H. Hermjakob, and others. 2019. “A data citation roadmap for scholarly data repositories.” _Sci. Data_ 6. https://doi.org/10.1038/s41597-019-0031-8

Hutchison, V.B., T. Norkin, L.S. Zolly, and L. Hsu. 2024. “State of the Data: Assessing the FAIRness of US Geological Survey Data.” _Data Science Journal_. https://doi.org/10.5334/dsj-2024-022 

Jacobsen, A, R.M. de Azevedo, N. Juty, D. Batista, S. Coles, and others. 2020. “FAIR principles: Interpretations and implementation considerations.” _Data Intelligence_ 2. https://doi.org/10.1162/dint_r_00024 

Peng, G., G. Berg-Cross, M. Wu, R.R. Downs, S.R. Shrestha, L. Wyborn, N. Ritchey, H.K. Ramapriyan, S.J. Clark, J. Wood, Z. Liu, and A. Marouane, 2024. "Harmonizing Quality Measures of FAIRness Assessment Towards Machine-Actionable Quality Information." _Int. J. Digit. Earth_. Under review.

Peng, G. 2023. “Dissecting the FAIR Guiding Principles - Key Categories, Core Concepts, Focus Elements, and Harmonized Indicators (v01r00-20230225).” Updated 2024. _Zenodo_. https://doi.org/10.5281/zenodo.7896947 

Peng, G., J.L. Privette, E.J. Kearns, N.A. Ritchey, and S. Ansari. 2015. “A unified framework for measuring stewardship practices applied to digital environmental datasets.” _Data Science Journal_ 13. http://dx.doi.org/10.2481/dsj.14-049

RDA FAIR Data Maturity Model Working Group. 2020. “FAIR Data Maturity Model: specification and guidelines.” _Research Data Alliance_. https://doi.org/10.15497/RDA00050

Schultes, E. 2023. “The FAIR hourglass: A framework for FAIR implementation.” _FAIR Connect_ 1. https://doi.org/10.3233/FC-221514 

Wilkinson, M.D.,  M. Dumontier, I. J. Aalbersberg, G. Appleton, M. Axton, A. Baak, and others, 2016: The FAIR Guiding Principles for scientific data management and stewardship. _Sci. Data_ 3,  https://doi.org/10.1038/sdata.2016.18

Wilkinson, M.D., S.A. Sansone, E. Schultes, P. Doorn, and others. 2018. “A design framework and exemplar metrics for FAIRness.” _Sci. Data_ 5. https://doi.org/10.1038/sdata.2018.118 

Wilkinson, M.D., M. Dumontier, S.A. Sansone, L.O.B. da Silva Santos, and others. 2019. “Evaluating FAIR maturity through a scalable, automated, community-governed framework.” _Sci. Data_ 6. https://doi.org/10.1038/s41597-019-0184-5; FAIR Evaluation Services http://w3id.org/AmIFAIR

Wu, M., S.M. Richard, C. Verhey, L.J. Castro, B. Cecconi, and N. Juty. 2023. “An Analysis of Crosswalks from Research Data Schemas to Schema.org.” _Data Intelligence_ 2023:100–121. https://doi.org/10.1162/dint_a_00186


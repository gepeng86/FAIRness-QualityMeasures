**FAIRness Quality Maturity Matrix (FAIR-QMM)**
-----------------------------------------------

This folder contains the description of the FAIR-QMM for digital scientific data products as defined in Peng et al. (2024; Appendix A). The FAIR-QMM builds on a set of [FAIRness quality measures](https://github.com/gepeng86/FAIR-QualityMeasures/tree/main/FAIR%20Quality%20Measures) and informed by a wide array of community practices in the management and stewardship of digital scientific data (e.g., [Wilkinson et al. 2016](https://doi.org/10.1038/sdata.2016.18); [Wilkinson et al. 2019](https://doi.org/10.1038/s41597-019-0184-5); [Peng et al. 2015](http://dx.doi.org/10.2481/dsj.14-049); [Fenner et al. 2019](https://doi.org/10.1038/s41597-019-0031-8); [RDA FAIR Data Maturity Model Working Group 2020](https://doi.org/10.15497/RDA00050); [Devaraju and Huber 2021](https://doi.org/10.5281/zenodo.6461229); [Jacobsen et al. 2020](https://doi.org/10.1162/dint_r_00024); [Schultes 2023]( https://doi.org/10.3233/FC-221514); [Wu et al. 2023]( https://doi.org/10.1162/dint_a_00186); [Hutchison et al. 2024](https://doi.org/10.5334/dsj-2024-022)) as well as the online resources captured in Table A1. 

**Table A1**. A list of online resources that are beneficial in formulating the FAIRness Quality Maturity Matrix (FAIR-QMM)
| **Resource** | **URL** | **Commments** |
|    :---:     |  :---:  |  :---         |
| ARDC FAIR Data Self-Assessment Tool | https://ardc.edu.au/resource/fair-data-self-assessment-tool/ | Questionnaire with a drop-down menu for each question; a total of 12 questions. |
| GO-FAIR FAIR Implementation Questionnaires | https://www.go-fair.org/how-to-go-fair/fair-implementation-profile/ | 21 questions with associated FAIR enabling resource types. |
| GO-FAIR Foundation FAIR Interpretations | https://www.gofair.foundation/interpretation | Interpretations are primarily based on Jacobsen et al. (2020). |
| FAIRsFAIR F-UJI Tool | https://www.f-uji.net/index.php?action=home | Automatic tool with rules and automatic checks based on 17 of 41 RDA FAIR Data Maturity Indicators (Devaraju et al. 2022). |
| FAIRsharing FAIR Metrics | https://github.com/FAIRMetrics/Metrics/tree/master/MaturityIndicators | A set of 14 universal metric (Wilkinson et al. 2018). |

---------------------

The full description of the FAIR-QMM for digital scientific data is provided in Tables A2-5 for the Findability, Accessibility, Interperability, and Reusability dimension, respectively. Additional information inclduing explanations, examples, and corresponding harmonized FAIRness indicators can be found in Peng et al. (2024). 


**Table A2.** FAIR ID, quality measure (non-bolded entity denotes just core concept), and the definitions of Level 1, 2, and 3 maturity stages for the _Findability_ dimension of the FAIR Principles
<table>
<thead>
<tr class="header" >
<th><p><strong> </strong></p>
<p><strong>FAIR ID</strong></p></th>
<th><p><strong> </strong></p>
<p><strong>Quality Measure</strong></p></th>
<th><p><strong>Level 1</strong></p>
<p><strong>Minimal Stage</strong></p></th>
<th><p><strong>Level 2</strong></p>
<p><strong>Intermediate Stage</strong></p></th>
<th><p><strong>Level 3</strong></p>
<p><strong>Optimal Stage</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>F1</strong></td>
<td><strong>Identifier</strong></td>
<td><p> Data and metadata are assigned identifiers </p></td>
<td><p> L1 + identifiers are either: i) eternally persistent but not globally unique, ii) globally unique but not always persistent, or iii) unique and persistent within a particular scientific discipline </p></td>
<td><p> L1 + identifiers are globally unique and eternally persistent </p></td>
</tr>
<tr class="even">
<td><strong>F2</strong></td>
<td><strong>Rich Metadata</strong></td>
<td><p> Data are described by basic/minimal metadata </p></td>
<td><p> L1 + core metadata elements for data discovery </p></td>
<td><p> L2 + comprehensive metadata elements for enhanced data discovery </p></td>
</tr>
<tr class="odd">
<td><strong>F3</strong></td>
<td>Linked ID</td>
<td><p> Metadata includes data identifier </p></td>
<td><p> L1 + data identifier is clearly and explicitly included in collection-level metadata record  </p></td>
<td><p> L2 + data identifier is explicitly included in machine-readable  collection- and file-level metadata  </p></td>
</tr>
<tr class="even">
<td><strong>F4</strong></td>
<td><strong>Resource</strong></td>
<td><p> Data and metadata are indexed in resources </p></td>
<td><p> L1 + resources for data and metadata are searchable with basic search capability </p></td>
<td><p> L2 + searchable resources are standard-based with advanced search capability </p></td>
</tr>
</tbody>
</table>

-----------

**Table A3.** FAIR ID, quality measure (non-bolded entity denotes just core concept), and the definitions of Level 1, 2, and 3 maturity stages for the _Accessibility_ dimension of the FAIR Principles
<table>
<thead>
<tr class="header" >
<th><p><strong> </strong></p>
<p><strong>FAIR ID</strong></p></th>
<th><p><strong> </strong></p>
<p><strong>Quality Measure</strong></p></th>
<th><p><strong>Level 1</strong></p>
<p><strong>Minimal Stage</strong></p></th>
<th><p><strong>Level 2</strong></p>
<p><strong>Intermediate Stage</strong></p></th>
<th><p><strong>Level 3</strong></p>
<p><strong>Optimal Stage</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>A1</strong></td>
<td><p><strong>Communication Protocol</strong> - Retrievable </p></td>
<td><p> Data and metadata identifiers resolve to the digital data and metadata objects, respectively </p></td>
<td><p> L1 + using i) non-standard-based web services; ii) standardized within a particular domain </p></td>
<td><p> L2 + protocols are: i) standard-based; ii) based on community standards  </p></td>
</tr>
<tr class="even">
<td><strong>A1.1</strong></td>
<td><strong>Communication Protocol</strong></td>
<td><p> The communication protocols for retrieving data and metadata are open </p></td>
<td><p> L1 + protocols are free </p></td>
<td><p> L2 + protocols are universally implementable  </p></td>
</tr>
<tr class="odd">
<td><strong>A1.2</strong></td>
<td><p><strong>Procedure</strong></p></td>
<td><p> The communication protocols allow for procedures </p></td>
<td><p> L1 + procedures include that for authentication </p></td>
<td><p> L2 + procedures include that for authorization </p></td>
</tr>
<tr class="even">
<td><strong>A2</strong></td>
<td><p>Metadata Longevity</p></td>
<td><p> Metadata associated with the latest version of data are accessible online </p></td>
<td><p> L1 + Metadata associated with the last previous version of data are accessible online  </p></td>
<td><p> Metadata associated with all versions of data are accessible online permanently  </p></td>
</tr>
</tbody>
</table>

--------------

**Table A4.** FAIR ID, quality measure (non-bolded entity denotes just core concept), and the definitions of Level 1, 2, and 3 maturity stages for the _Interoperability_ dimension of the FAIR Principles
<table>
<thead>
<tr class="header" >
<th><p><strong> </strong></p>
<p><strong>FAIR ID</strong></p></th>
<th><p><strong> </strong></p>
<p><strong>Quality Measure</strong></p></th>
<th><p><strong>Level 1</strong></p>
<p><strong>Minimal Stage</strong></p></th>
<th><p><strong>Level 2</strong></p>
<p><strong>Intermediate Stage</strong></p></th>
<th><p><strong>Level 3</strong></p>
<p><strong>Optimal Stage</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>I1</strong></td>
<td><p><strong>Language</strong> (knowledge Representation) </p> </td>
<td><p> Data and metadata use languages for knowledge representation </p></td>
<td><p> L1 + languages are formal and accessible </p></td>
<td><p> L2 + languages are shared and broadly applicable </p></td>
</tr>
<tr class="even">
<td><strong>I2</strong></td>
<td><strong>Vocabulary</strong></td>
<td><p> Data and metadata use vocabularies </p></td>
<td><p> L1 + vocabulary is managed, findable and accessible; assigned a GUPRI to the vocabulary itself </p></td>
<td><p> L2 + vocabulary is governed, version-controlled, interoperable and reusable; with a GUPRI assigned to each term within the vocabulary </p></td>
</tr>
<tr class="odd">
<td><strong>I3</strong></td>
<td><strong>Reference</strong></td>
<td><p> Data and metadata include references </p></td>
<td><p> L1 + references can be to other data and/or metadata that are machine-readable in non-proprietary format  </p></td>
<td><p> L2 + references are qualified and following linked data standards </p></td>
</tr>
</tbody>
</table>

--------------------------

**Table A5.** FAIR ID, quality measure (non-bolded entity denotes just core concept), and the definitions of Level 1, 2, and 3 maturity stages for the _Reusability_ dimension of the FAIR Principles
<table>
<thead>
<tr class="header" >
<th><p><strong> </strong></p>
<p><strong>FAIR ID</strong></p></th>
<th><p><strong> </strong></p>
<p><strong>Quality Measure</strong></p></th>
<th><p><strong>Level 1</strong></p>
<p><strong>Minimal Stage</strong></p></th>
<th><p><strong>Level 2</strong></p>
<p><strong>Intermediate Stage</strong></p></th>
<th><p><strong>Level 3</strong></p>
<p><strong>Optimal Stage</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>R1</strong></td>
<td><strong>Attribute</strong></td>
<td><p> Data and metadata are described with attributes </p></td>
<td><p> L1 + attributes are plural and relevant </p></td>
<td><p> L2 + attributes are accurate and comprehensive for (re)use </p></td>
</tr>
<tr class="even">
<td><strong>R1.1</strong></td>
<td><strong>License</strong></td>
<td><p> Data and metadata are released with a usage license </p></td>
<td><p> L1 + licenses are accessible </p></td>
<td><p> L2 + licenses are clear and machine-readable </p></td>
</tr>
<tr class="odd">
<td><strong>R1.2</strong></td>
<td><strong>Provenance</strong></td>
<td><p> Data and metadata are associated with basic provenance </p></td>
<td><p> L1 + limited provenance information based on domain standards </p></td>
<td><p> L2 + comprehensive provenance based on community standards </p></td>
</tr>
<tr class="even">
<td><strong>R1.3</strong></td>
<td><strong>Standard</strong></td>
<td><p> Data and metadata meet standards </p></td>
<td><p> L1 + standards are domain relevant </p></td>
<td><p> L2 + standards are community standards established by authorized standard bodies </p></td>
</tr>
</tbody>
</table>

-------------

**References**
----------------
Devaraju, A., R. Huber, M. Mokrane, P. Herterich, L. Cepinskas, J. de Vries, H. L'Hours, J. Davidson, and W. Angus. 2022. “FAIRsFAIR Data Object Assessment Metrics (0.5).” _Zenodo_. https://doi.org/10.5281/zenodo.6461229 

Fenner, M., M. Crosas, J.S. Grethe, D. Kennedy, H. Hermjakob, and others. 2019. “A data citation roadmap for scholarly data repositories.” _Sci. Data_ 6. https://doi.org/10.1038/s41597-019-0031-8

Hutchison, V.B., T. Norkin, L.S. Zolly, and L. Hsu. 2024. “State of the Data: Assessing the FAIRness of US Geological Survey Data.” _Data Science Journal_. https://doi.org/10.5334/dsj-2024-022 

Jacobsen, A, R.M. de Azevedo, N. Juty, D. Batista, S. Coles, and others. 2020. “FAIR principles: Interpretations and implementation considerations.” _Data Intelligence_ 2. https://doi.org/10.1162/dint_r_00024 

Peng, G., G. Berg-Cross, M. Wu, R.R. Downs, S.R. Shrestha, L. Wyborn, N. Ritchey, H.K. Ramapriyan, S.J. Clark, J. Wood, Z. Liu, and A. Marouane, 2024. "Harmonizing Quality Measures of FAIRness Assessment Towards Machine-Actionable Quality Information." _Int. J. Digit. Earth_. Under review.

Peng, G., J.L. Privette, E.J. Kearns, N.A. Ritchey, and S. Ansari. 2015. “A unified framework for measuring stewardship practices applied to digital environmental datasets.” _Data Science Journal_ 13. http://dx.doi.org/10.2481/dsj.14-049

RDA FAIR Data Maturity Model Working Group. 2020. “FAIR Data Maturity Model: specification and guidelines.” _Research Data Alliance_. https://doi.org/10.15497/RDA00050

Schultes, E. 2023. “The FAIR hourglass: A framework for FAIR implementation.” _FAIR Connect_ 1. https://doi.org/10.3233/FC-221514 

Wilkinson, M.D.,  M. Dumontier, I. J. Aalbersberg, G. Appleton, M. Axton, A. Baak, and others, 2016: The FAIR Guiding Principles for scientific data management and stewardship. _Sci. Data_ 3,  https://doi.org/10.1038/sdata.2016.18

Wilkinson, M.D., S.A. Sansone, E. Schultes, P. Doorn, and others. 2018. “A design framework and exemplar metrics for FAIRness.” _Sci. Data_ 5. https://doi.org/10.1038/sdata.2018.118 

Wilkinson, M.D., M. Dumontier, S.A. Sansone, L.O.B. da Silva Santos, and others. 2019. “Evaluating FAIR maturity through a scalable, automated, community-governed framework.” _Sci. Data_ 6. https://doi.org/10.1038/s41597-019-0184-5; FAIR Evaluation Services http://w3id.org/AmIFAIR

Wu, M., S.M. Richard, C. Verhey, L.J. Castro, B. Cecconi, and N. Juty. 2023. “An Analysis of Crosswalks from Research Data Schemas to Schema.org.” _Data Intelligence_ 2023:100–121. https://doi.org/10.1162/dint_a_00186


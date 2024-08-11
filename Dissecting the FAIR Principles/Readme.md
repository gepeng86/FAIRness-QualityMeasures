Dissecting the FAIR Principles 
===============================

[<span class="underline" style="color:blue">Wilkinson et al. (2016)</span>](https://doi.org/10.1038/sdata.2016.18) designed high-level guiding principles under four nonfunctional requirements - Findability, Accessibility, Interoperability, and Reusability. We refer to these four nonfunctional requirements as ***four FAIR quality dimensions***.

Wilkinson et al. (2016) also developed 15 FAIR principles to establish specific functional requirements for digital objects along the four FAIR quality dimensions in a computational environment. These 15 FAIR principles cover three high-level unique categories: data, metadata, and infrastructure. refered to as ***three FAIR categories***. 

The principles also entail essential properties or specific functional requirements for each of the three categories. For example, F1 requires that data and metadata should each be assigned a property: identifier; the identifier is further qualified to be globally unique and eternally persistent. After mapping the 15 principles onto the three categories, ***28 category-specific requirements*** are identified for data, metadata, and infrastructure. Additional details in [this folder](https://github.com/gepeng86/FAIRness-QualityMeasures/tree/main/Category-Specific%20Requirements).

In contrast to its simple acronym, the FAIR Principles are highly complex even before accounting for domain and application dependencies. The FAIR principles are inherently multi-dimensional. They are also multi-layered and multi-faceted, revolving around key concepts with multiple elements, as depicted in the first figure below. The figure utilizes the results from a FAIR graph representation tool developed by Abdelhak Marouane and Ge Peng. (A filled circle indicates an additional layer in the current branch while an open circle signifies the end of the branch.) The tool offers an interactive and systematic approach to explore individual FAIR principles without the need for implementing a graph database, while still maintaining a holistic framework of the individual FAIR Guiding Principles. The development of the tool is open source, and we welcome community contribution. The latest version can be found at: https://bit.ly/FAIR-GR)


By decomposing the definitions of the FAIR principles through a systematic concept mapping approach, [<span class="underline" style="color:blue">Peng (2023)</span>](https://doi.org/10.5281/zenodo.7896948) deduced ***21 unique category-specific core concepts*** and ***48 category-specific focus elements***, and formulated ***85 harmonized indicators*** for FAIR data. The second figure below ties all these together. Detailed information on the common FAIR vocabulary can be found in [this folder](https://github.com/gepeng86/FAIRness-QualityMeasures/tree/main/Common%20FAIR%20Vocabulary).

The 21 unique category-specific core concepts lead to ***12 unique core concepts***, which are defined as ***FAIRness Quality Measures***. Detailed information can be found in [this folder](https://github.com/gepeng86/FAIRness-QualityMeasures/tree/main/FAIR%20Quality%20Measures).


<img src="https://github.com/gepeng86/FAIRness-QualityMeasures/blob/main/_images/Peng_etal_2024_FAIR-QM_Figure2_Citation.jpg" width="850" />

<img src="https://github.com/gepeng86/FAIRness-QualityMeasures/blob/main/_images/Peng_DissectingFAIR-Principles_v00r08.jpg" width="600" />


References
----------

Peng, G. 2023. Dissecting the FAIR Guiding Principles - Key Categories, Core Concepts, Focus Elements, and Harmonized Indicators. Updated 2024. _Zenodo_. https://doi.org/10.5281/zenodo.7896947 

Peng, G., G. Berg-Cross, M. Wu, R.R. Downs, S.R. Shrestha, L. Wyborn, N. Ritchey, H.K. Ramapriyan, S.J. Clark, J. Wood, Z. Liu, and A. Marouane. (2024). Harmonizing Quality Measures of FAIRness Assessment Towards Machine-Actionable Quality Information. _Int. J. Digit. Earth._ https://doi.org/10.1080/17538947.2024.2390431

Wilkinson, M. D.,  M. Dumontier, I. J. Aalbersberg, G. Appleton, M. Axton, A. Baak, and others. 2016. The FAIR Guiding Principles for scientific data management and stewardship. _Sci. Data_, 3,  https://doi.org/10.1038/sdata.2016.18

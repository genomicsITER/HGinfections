<a name="HGinfections"></a>

<!-- Created: February 28, 2025 -->
<!-- Last updated: February 28, 2025 -->

# Collaborative studies of host genetics of infections and outcomes
Host genetic factors have been increasingly recognized as affecting the severity of responses to infections. Such influence is clear in patients with inborn errors of immunity. To date, most genomic studies have been conducted in families or isolated cases while studies in population cohorts (besides those in COVID-19), leveraging the power of genome-wide association studies (GWAS), are scarce in the literature.

One main complication of severe infections in the ICU is the acute respiratory distress syndrome (ARDS), a pulmonary inflammatory disease caused by an insult to the alveolar–capillary barrier that results in increased vascular permeability and subsequent formation of pulmonary edema. ARDS is a major cause of mortality in adult ICUs and has no specific treatment options.

<br>

<!-- --------------------------------- SECTION -------------------------------- -->

# Publicly available datasets

<ul>
  <li><a href="#study1">3-way meta-GWAS sepsis-associated ARDS</a></li>
  <li><a href="#study2">GWAS of VEGFR1 levels in sepsis</a></li>
  <li><a href="#study3">GWAS in hospitalized patients with CAP</a></li>
  <li><a href="#study4">Rare variant risks in sepsis-associated ARDS</a></li>
 </ul>

<br>

<!-- --------------------------------- SECTION -------------------------------- -->

<a name="study1"></a>
# 3-way meta-GWAS sepsis-associated ARDS
We have previously performed the first GWAS of sepsis-associated ARDS susceptibility (1) to identify novel genes and further advance the understanding of ARDS pathogenesis and risk (2). That study revealed the importance of the VEGF signaling axis and a significant association at <i>FLT1</i> gene, encoding the vascular endothelial growth factor receptor 1 (VEGFR1).

To further identify novel genetic risk factors involved in sepsis-associated ARDS, we have now performed a GWAS meta-analysis across three independent studies: the GENetics of SEPsis-induced ARDS Network (GEN-SEP), The Critical Care Trials Group of the German Sepsis Competence Network (SepNet), and UK Biobank (UKBB). We tested the association of >8 million genetic variants from 4,399 at-risk sepsis controls and 716 patients with sepsis-associated ARDS.  

<p align="center">
  <img src="https://github.com/genomicsITER/HGinfections/blob/main/images/Figure1_metaGWAS_workflow.jpg" width="auto"/>
</p>
<p align="center"><b>Figure 1</b>: Flowchart of 3-way meta-GWAS sepsis-associated ARDS.</p>

## Access to the results of this study
To help advance ARDS research and allow the wider research community to access to the most accurate effect sizes for genetic variants on a genome-wide scale, the variant summary data resulting from this 3-way meta-GWAS of susceptibility to sepsis-associated ARDS (3; <a href="https://doi.org/10.1101/2025.02.11.25322045">https://doi.org/10.1101/2025.02.11.25322045</a>) (approximately 600 MB) can be accessed after an internal assessment of formal requests received.

## What type of results would be made available?
No individual level data will be made available. Granted requests will have access to a file with the GWAS meta-analysis variant summary data with the following descriptors:

   •	**rsid**
   
   •	**chr**: chromosome [build37]

   •	**pos**: position [build37]
      
   •	**marker_ID**: marker name [(chromosome:position) build37]
   
   •	**effect_allele**

   •	**non_effect_allele**
   
   •	**eaf**: effect allele frequency average from across three studies included in the meta-analysis
      
   •	**n_studies**: the number of studies the variant was analysed in the meta-analysis
    
   •	**beta**: this is the beta from the meta-analysis
      
   •	**standard_error**: this is the standard error from the meta-analysis
      
   •	**p**: this is the p value from the meta-analysis

<p align="right">
  <a href="#HGinfections" title="Up">
    <img src="https://github.com/genomicsITER/HGinfections/blob/main/images/home-icon.png" style="float: right; margin: 10px; padding: 2px;" />
  </a>
</p>

<br>
<br>

<!-- --------------------------------- SECTION -------------------------------- -->

<a name="study2"></a>
# GWAS of VEGFR1 levels in sepsis
Based on the importance of the VEGF signaling axis in sepsis-associated ARDS, we performed a GWAS based on soluble VEGFR1 protein levels to identify protein quantitative trait loci (pQTLs) in patients with sepsis from the GEN-SEP cohort to prioritize genes of interest. We evaluated the associations of approximately 7.5 million variants at three time points: T1 (n=225) within 24 hours after sepsis diagnosis, T2 (n=169) at 48–72 hours, and T7 (n=108) at 7 days.  

<p align="center">
  <img src="https://github.com/genomicsITER/HGinfections/blob/main/images/Figure2_GWAS-VEGFR1_workflow.jpg" width="auto"/>
</p>
<p align="center"><b>Figure 2</b>: Flowchart of the GWAS of soluble VEGFR1 levels in sepsis patients.</p>

## Access to the results of this study
To contribute with this proteogenomic study to the advancement of research on host genetics of sepsis outcomes on a genome-wide scale, the variant summary data results from the GWAS of the three time points (4; [https://doi.org/10.1101/2025.01.30.25321087](https://doi.org/10.1101/2025.01.30.25321087)) (approximately 550 MB each file) can be accessed after an internal assessment of formal requests received.

## What type of results would be made available?
No individual level data will be made available. Granted applications will have access to the three GWAS variant summary data files with the following descriptors:

   •	**rsid**
   
   •	**chr**: chromosome [build37]

   •	**pos**: position [build37]
      
   •	**marker_ID**: marker name [(chromosome:position) build37]
   
   •	**effect_allele**

   •	**non_effect_allele**
   
   •	**eaf**: effect allele frequency
    
   •	**beta**
      
   •	**standard_error**
      
   •	**p**

<p align="right">
  <a href="#HGinfections" title="Up">
    <img src="https://github.com/genomicsITER/HGinfections/blob/main/images/home-icon.png" style="float: right; margin: 10px; padding: 2px;" />
  </a>
</p>

<br>
<br>

<!-- --------------------------------- SECTION -------------------------------- -->

<a name="study3"></a>
# GWAS in hospitalized patients with CAP
Community acquired pneumonia (CAP) is a major public health problem due to its high morbidity and mortality. To identify genetic risk loci associated with CAP, we conducted a case-control GWAS including 259 hospitalized CAP patients recruited between March 2001 and 2016, and 3,526 population controls. This study only included patients with confirmed pneumococcal infection or those in whom no identified causative microorganism was identified. A total of 7.6 million variants were analyzed.

<p align="center">
  <img src="https://github.com/genomicsITER/HGinfections/blob/main/images/Figure3_GWAS-CAP_workflow.jpg" width="auto"/>
</p>
<p align="center"><b>Figure 3</b>: Flowchart of the GWAS of community-acquired pneumonia.</p>

## Access to the results of this study
To contribute to the advancement of research on infectious respiratory diseases and allow the wider research community to access the results on a genome-wide scale, the variant summary data resulting from this GWAS on CAP (5; [https://doi.org/10.1186/s12931-024-03009-4](https://doi.org/10.1186/s12931-024-03009-4))  (approximately 550 MB) can be accessed after an internal assessment of formal requests received.

## What type of results would be made available?
No individual level data will be made available. Granted requests will have access to a file with the GWAS summary data with the following descriptors:

   •	**rsid**
   
   •	**chr**: chromosome [build37]

   •	**pos**: position [build37]
      
   •	**marker_ID**: marker name [(chromosome:position) build37]
   
   •	**effect_allele**

   •	**non_effect_allele**
   
   •	**eaf**: effect allele frequency
    
   •	**beta**
      
   •	**standard_error**
      
   •	**p**

<p align="right">
  <a href="#HGinfections" title="Up">
    <img src="https://github.com/genomicsITER/HGinfections/blob/main/images/home-icon.png" style="float: right; margin: 10px; padding: 2px;" />
  </a>
</p>

<br>
<br>

<!-- --------------------------------- SECTION -------------------------------- -->

<a name="study4"></a>
# Rare variant risks in sepsis-associated ARDS 
So far, sequencing-based studies to assess the role of rare variants in the population (<1%) have focused on small cohorts or on familial cases linked to inborn defects. To investigate the role of rare genetic variants in sepsis-associated ARDS, we analyzed exome sequencing data from the GEN-SEP cohort, including 272 ARDS patients as cases, and 550 at-risk sepsis controls. To enable capturing the underlying genetic heterogeneity, we relied on a network-based clustering analysis to identify biological pathways and genes of interest.

<p align="center">
  <img src="https://github.com/genomicsITER/HGinfections/blob/main/images/Figure4_Flowchart-exomes-GEN-SEP.jpg" width="auto"/>
</p>
<p align="center"><b>Figure 4</b>: Flowchart of the whole-exome study in sepsis-associated ARDS.</p>

## Access to the results of this study
All analysis results related to this study have been included in the manuscript (6; Tosco-Herrera et al. 2025). Variant calls from whole-exome sequencing have been deposited in EGA (accession identifier pending final release).

## What type of results would be made available?
No individual level data will be made available.

<p align="right">
  <a href="#HGinfections" title="Up">
    <img src="https://github.com/genomicsITER/HGinfections/blob/main/images/home-icon.png" style="float: right; margin: 10px; padding: 2px;" />
  </a>
</p>

<br>
<br>

<!-- --------------------------------- SECTION -------------------------------- -->

## Who should I contact for requesting access to the data?
Requesters should contact GWASARDS.adm [at] gmail [dot] com to request access to the data. Within a few days, an email with the instructions for data downloading will be obtained in response.

Please, be aware that **delays in obtaining a response** with the instructions for downloading are expected during particular periods of the year.

## Which information should I submit to access the variant summary data?
Requesters should provide a signed document including the following information: <b>full name and title of the PI, affiliation, and a brief description of the project and the aims where the data is to be used<b>.

The document should explicitly state that the data requester also agrees to:
<ul>
  <li>>use the data only as part of that indicated research,</li>
  <li>not redistribute the data outside the project without permission, and</li>
  <li>acknowledge the provenance of the data in any dissemination of results</li>.
</ul>

A template document for the request is [here](https://github.com/genomicsITER/HGinfections/blob/main/Request_template.txt)).

<p align="right">
  <a href="#HGinfections" title="Up">
    <img src="https://github.com/genomicsITER/HGinfections/blob/main/images/home-icon.png" style="float: right; margin: 10px; padding: 2px;" />
  </a>
</p>

<br>
<br>

<!-- --------------------------------- SECTION -------------------------------- -->

## Contact
Dr. Carlos Flores, Research Unit - Hospital Universitario N.S. de Candelaria -Instituto de Investigación Sanitaria de Canarias (IISC), Genomics Division - Instituto Tecnológico y de Energías Renovables (ITER), & CIBER de Enfermedades Respiratorias (CIBERES), Instituto de Salud Carlos III,  Spain.
e-mail: GWASARDS.adm [at] gmail [dot] com

<br>
<br>

<!-- --------------------------------- SECTION -------------------------------- -->

## References
1: Guillen-Guio B, Lorenzo-Salazar JM, Ma SF, Hou PC, Hernandez-Beeftink T, Corrales A, García-Laorden MI, Jou J, Espinosa E, Muriel A, Domínguez D, Lorente L, Martín MM, Rodríguez-Gallego C, Solé-Violán J, Ambrós A, Carriedo D, Blanco J, Añón JM, Reilly JP, Jones TK, Ittner CA, Feng R, Schöneweck F, Kiehntopf M, Noth I, Scholz M, Brunkhorst FM, Scherag A, Meyer NJ, Villar J, Flores C. Sepsis-associated acute respiratory distress syndrome in individuals of European ancestry: a genome-wide association study. Lancet Respir Med 2020, 8: 258-266. Doi: [https://doi.org/10.1016/S2213-2600(19)30368-6](https://doi.org/10.1016/S2213-2600(19)30368-6). PubMed PMID: 319820411. 

2: Hernández-Beeftink T, Guillen-Guio B, Villar J, Flores C. Genomics and the Acute Respiratory Distress Syndrome: Current and Future Directions. Int J Mol Sci. 2019, 20:4004. Doi: https://doi.org/10.3390/ijms20164004. PubMed PMID: 31426444.

3: Guillen-Guio, B, Suarez-Pajes, E, Tosco-Herrera, E, Hernandez-Beeftink, T, Lorenzo-Salazar, J M, Chang, D, González-Montelongo, R, Rubio-Rodríguez, L A, Leavy, O C, Allen, R J, Corrales, A, Cruz, R, Bardají-Carrillo, M, Carracedo, A, Tamayo, E, Kerchberger, V E, Ware, L B, Yaspan, B L, Scholz, M, Scherag, A, Villar, J, Wain L V, Flores, C. Genome-wide association study of susceptibility to acute respiratory distress syndrome. MedRxiv 2025. [https://doi.org/10.1101/2025.02.11.25322045 ](https://doi.org/10.1101/2025.02.11.25322045 )

4: Suarez-Pajes, E, Shrine, N, Tosco-Herrera, E, Hernandez-Beeftink, T, Rubio-Rodríguez, L A, García-Laorden, M I, Corrales, A, Prieto-González, M, Rodríguez-Pérez, A, Carriedo, D, Blanco, J, Ambrós, A, González-Higueras, E, Espinosa, E, Muriel-Bombin, A, Domínguez, D, García de Lorenzo, A, Añon, J M, Soro, M, Villar, J, Tobin, M  D,  Wain, L V, Leavy, O C, Guillen-Guio, B, Flores, C. Genetic regulation of the vascular endothelial growth factor receptor 1 during sepsis and association with ARDS susceptibility. Medrxiv 2025. [https://doi.org/10.1101/2025.01.30.25321087](https://doi.org/10.1101/2025.01.30.25321087) 

5: Suarez-Pajes, E, Marcelino-Rodriguez, I, Hernández Brito, E, Gonzalez-Barbuzano, S, Ramirez-Falcon, M, Tosco-Herrera, E, Rubio-Rodríguez, L A, Briones, M L, Rajas, O, Borderías, L, Ferreres, J, Payeras, A, Lorente, L, Aspa, J, Lorenzo Salazar, J M, Valencia-Gallardo, J M, Carbonell, N, Freixinet, J L, Rodríguez de Castro, F, … Rodríguez-Gallego, C,  Solé Violán, J, Flores, C, Rodríguez-Gallego, C. A genome-wide association study of adults with community-acquired pneumonia. Respiratory Research 2024. , 25(1), 374. doi: [https://doi.org/10.1186/s12931-024-03009-4](https://doi.org/10.1186/s12931-024-03009-4). PubMed PMID: 39415140

6: Tosco-Herrera E, Rubio-Rodríguez LA, Muñoz-Barrera A, Jáspez D, Suárez-Pajes E, Corrales A, Alonso-González A, Prieto-González M, Rodríguez-Pérez A, Carriedo D, Blanco J, Ambrós A, Lorente L, Martín MM, Solé-Violán J, Rodríguez-Gallego C, González-Higueras E, Espinosa E, Muriel-Bombin A, Domínguez D, Soro M, Hernández-Beeftink T, Añón JM, Villar J, Guillén-Guio B, Marcelino-Rodríguez I, Lorenzo-Salazar JM, González-Montelongo R, Flores C. Rare genetic variant risks in patients with sepsis-associated acute respiratory distress syndrome. In preparation, 2025.

<p align="right">
  <a href="#HGinfections" title="Up">
    <img src="https://github.com/genomicsITER/HGinfections/blob/main/images/home-icon.png" style="float: right; margin: 10px; padding: 2px;" />
  </a>
</p>

<br>
<br>

<!-- --------------------------------- SECTION -------------------------------- -->

<a name="Update logs"></a>
## Update logs

> [1] February 28, 2025. Public release of this repository. 

<p align="right">
  <a href="#HGinfections" title="Up">
    <img src="https://github.com/genomicsITER/HGinfections/blob/main/images/home-icon.png" style="float: right; margin: 10px; padding: 2px;" />
  </a>
</p>

<br>
<br>




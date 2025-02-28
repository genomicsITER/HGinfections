<a name="HGinfections"></a>

<!-- Created: February 28, 2025 -->
<!-- Last updated: February 28, 2025 -->

# Collaborative studies of host genetics of infections and outcomes
Host genetic factors have been increasingly recognized as affecting the severity of responses to infections. Such influence is clear in patients with inborn errors of immunity. To date, most genomic studies have been conducted in families or isolated cases while studies in population cohorts (besides those in COVID-19), leveraging the power of genome-wide association studies (GWAS), are scarce in the literature.

One main complication of severe infections in the ICU is the acute respiratory distress syndrome (ARDS), a pulmonary inflammatory disease caused by an insult to the alveolar–capillary barrier that results in increased vascular permeability and subsequent formation of pulmonary edema. ARDS is a major cause of mortality in adult ICUs and has no specific treatment options.

<!-- --------------------------------- SECTION -------------------------------- -->

# Publicly available datasets

<ul>
  <li><a href="#study1">3-way meta-GWAS sepsis-associated ARDS</a></li>
  <li><a href="#study2">GWAS of VEGFR1 levels in sepsis</a></li>
  <li><a href="#study3">GWAS in hospitalized patients with CAP</a></li>
  <li><a href="#study4">Rare variant risks in sepsis-associated ARDS</a></li>
 </ul>


<!-- --------------------------------- SECTION -------------------------------- -->

<a name="study1"></a>
# 3-way meta-GWAS sepsis-associated ARDS
We have previously performed the first GWAS of sepsis-associated ARDS susceptibility (1) to identify novel genes and further advance the understanding of ARDS pathogenesis and risk (2). That study revealed the importance of the VEGF signaling axis and a significant association at <i>FLT1</i> gene, encoding the vascular endothelial growth factor receptor 1 (VEGFR1).

To further identify novel genetic risk factors involved in sepsis-associated ARDS, we have now performed a GWAS meta-analysis across three independent studies: the GENetics of SEPsis-induced ARDS Network (GEN-SEP), The Critical Care Trials Group of the German Sepsis Competence Network (SepNet), and UK Biobank (UKBB). We tested the association of >8 million genetic variants from 4,399 at-risk sepsis controls and 716 patients with sepsis-associated ARDS.  


<p align="center">
  <img src="https://github.com/genomicsITER/HGinfections/blob/main/images/Figure1_metaGWAS_workflow.jpg" width="auto"/>
</p>
<p><br></p>
<!-- ![What is this](Figure_susceptibility_GWASIPF.png) -->

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






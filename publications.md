---
layout: page
title: "Publications"
description: "CINVESTAV Sede Sur, Mexico"
feature_image: /assets/images/publications_banner.png
order: 5
---

<style>
  .feature-image-container {
    margin-top: 20px !important;
  }

  /* Search bar styling */
  #pubSearch {
    width: 100%;
    padding: 12px;
    margin: 20px 0;
    border: 1px solid #ddd;
    border-radius: 4px;
    font-size: 16px;
  }

  /* The Table Fix */
  .table-responsive {
    width: 100vw;
    position: relative;
    left: 50%;
    right: 50%;
    margin-left: -50vw;
    margin-right: -50vw;
    overflow-x: auto;
    display: block;
    clear: both;
    background-color: #fff;
  }

  .pub-table {
    width: 94% !important;
    max-width: 1600px; 
    margin: 0 auto;
    min-width: 1100px; 
    border-collapse: collapse;
    font-size: 0.88em;
    line-height: 1.6;
    table-layout: fixed;
  }

  /* --- ZEBRA STRIPING & COLORS --- */
  /* Base row color */
  .pub-table tbody tr {
    background-color: #ffffff;
  }

  /* Light grey-blue for even rows */
  .pub-table tbody tr:nth-child(even) {
    background-color: #f4f7f9; 
  }

  /* Hover effect for better readability */
  .pub-table tbody tr:hover {
    background-color: #e8eff4 !important;
    transition: background-color 0.2s ease;
  }

  .pub-table th {
    background-color: #eceff1; 
    font-weight: bold;
    color: #333;
    white-space: nowrap;
    border-bottom: 2px solid #cfd8dc;
  }

  .pub-table th, .pub-table td {
    padding: 18px 15px;
    border-bottom: 1px solid #e1e8ed;
    vertical-align: top;
    word-wrap: break-word;
  }

  /* Specific Column Widths */
  .pub-table th:nth-child(1), .pub-table td:nth-child(1) { width: 85px; }
  .pub-table th:nth-child(2), .pub-table td:nth-child(2) { width: 28%; }
  .pub-table th:nth-child(3), .pub-table td:nth-child(3) { width: 18%; }
  .pub-table th:nth-child(4), .pub-table td:nth-child(4) { width: auto; }
  .pub-table th:nth-child(5), .pub-table td:nth-child(5) { width: 85px; text-align: center; }

  .lead-author {
    color: #2c3e50;
    font-weight: bold;
    border-bottom: 1px solid #3498db;
  }
</style>

{% raw %}
<input type="text" id="pubSearch" onkeyup="filterTable()" placeholder="Search by author, title, journal, or year...">

<div class="table-responsive">
  <table class="pub-table" id="myTable">
    <thead>
      <tr>
        <th>Year</th>
        <th>Authors</th>
        <th>Journal</th>
        <th>Title</th>
        <th>Link</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>2026</td>
        <td><b>Barberena-Jonas C</b>, <b>Medina-Muñoz SG</b>, <b>Cedillo-Castelán V</b>,..., <b>Moreno-Estrada A</b></td>
        <td><i>Nature Medicine</i></td>
        <td>Clinical genetic variation across Hispanic populations in the Mexican Biobank</td>
        <td><a href="https://doi.org/10.1038/s41591-025-04100-z">DOI</a></td>
      </tr>
      <tr>
        <td>2025</td>
        <td><b>Espinosa-Jaime A</b>, <b>Zambada-Moreno O</b>, <b>Corona-Gomez JA</b>,..., <b>Moreno-Estrada A</b> and Ortiz-Ramírez C</td>
        <td><i>bioRxiv</i></td>
        <td>SiteCELL enables on-site PBMCs purification and cryopreservation for immune single cell profiling of diverse ancestries</td>
        <td><a href="https://doi.org/10.1101/2025.09.30.679317">DOI</a></td>
      </tr>
      <tr>
        <td>2025</td>
        <td>Taylor K,..., <b>Moreno-Estrada A</b>, et al.</td>
        <td><i>medRxiv</i></td>
        <td>Improving type 2 diabetes polygenic risk scores by incorporating rare, low-frequency, and population-specific variants</td>
        <td><a href="https://doi.org/10.1101/2025.11.24.25340878">DOI</a></td>
      </tr>
      <tr>
        <td>2025</td>
        <td>Struck TJ,..., <b>Moreno-Estrada A</b>, et al.</td>
        <td><i>Mol Biol Evol</i></td>
        <td>GHIST 2024: The First Genomic History Inference Strategies Tournament</td>
        <td><a href="https://doi.org/10.1093/molbev/msaf257">DOI</a></td>
      </tr>
      <tr>
        <td>2025</td>
        <td>Possik PA,..., <b>Moreno-Estrada A</b>, et al.</td>
        <td><i>Cell</i></td>
        <td>Exploring Latin America one cell at a time</td>
        <td><a href="https://doi.org/10.1016/j.cell.2025.09.013">DOI</a></td>
      </tr>
      <tr>
        <td>2025</td>
        <td><b>Barberena-Jonas C</b>,..., <b>Moreno-Estrada A</b>, et al.</td>
        <td><i>Genes &amp; Diseases</i></td>
        <td>Genetic analysis of APOE reveals distinct origins and distribution of ancestry-enrichment haplotypes in the Mexican Biobank</td>
        <td><a href="https://doi.org/10.1016/j.gendis.2025.101542">DOI</a></td>
      </tr>
      <tr>
        <td>2025</td>
        <td>Struck TJ,..., <b>Moreno-Estrada A</b>, et al.</td>
        <td><i>bioRxiv</i></td>
        <td>GHIST 2024: The 1st Genomic History Inference Strategies Tournament</td>
        <td><a href="https://doi.org/10.1101/2025.08.05.668560">DOI</a></td>
      </tr>
      <tr>
        <td>2025</td>
        <td>Huerta-Chagoya A,..., <b>Moreno-Estrada A</b>, et al.</td>
        <td><i>medRxiv</i></td>
        <td>Multi-ancestry polygenic risk scores for the prediction of type 2 diabetes and complications in diverse ancestries</td>
        <td><a href="https://doi.org/10.1101/2025.07.21.25331778">DOI</a></td>
      </tr>
      <tr>
        <td>2025</td>
        <td>Lin M,..., <b>Nigenda-Morales SF</b>, Beichman AC,<b>Nuñez-Valencia PG</b>,..., <b>Moreno-Estrada A</b>, et al.</td>
        <td><i>bioRxiv</i></td>
        <td>The distribution of fitness effects varies phylogenetically across animals</td>
        <td><a href="https://doi.org/10.1101/2025.05.13.653358">DOI</a></td>
      </tr>
      <tr>
        <td>2025</td>
        <td>Gusareva ES,..., <b>Moreno-Estrada A</b>, et al.</td>
        <td><i>Science</i></td>
        <td>From North Asia to South America: Tracing the longest human migration through genomic sequencing</td>
        <td><a href="https://doi.org/10.1126/science.adk5081">DOI</a></td>
      </tr>
      <tr>
        <td>2025</td>
        <td>Yang Z,..., <b>Moreno-Estrada A</b>, <b>Sohail M</b>, et al.</td>
        <td><i>Am J Hum Genet</i></td>
        <td>Fine-mapping in admixed populations using CARMA-X, with applications to Latin American studies</td>
        <td><a href="https://doi.org/10.1016/j.ajhg.2025.02.020">DOI</a></td>
      </tr>
      <tr>
        <td>2025</td>
        <td>Schwartz-Marin E,..., <b>Moreno-Estrada A</b>, et al.</td>
        <td><i>Front Genet</i></td>
        <td>Genetic ancestry and the colonial legacies of race in genomics: a cross-disciplinary dialogue</td>
        <td><a href="https://doi.org/10.3389/fgene.2024.1523406">DOI</a></td>
      </tr>
      <tr>
        <td>2024</td>
        <td>Loh L,..., <b>Barberena-Jonas C</b>, Oceanian Genome Variation Project Consortium, <b>Moreno-Estrada A</b>, et al.</td>
        <td><i>Cell</i></td>
        <td>An archaic HLA class I receptor allele diversifies natural killer cell-driven immunity in First Nations peoples of Oceania</td>
        <td><a href="https://doi.org/10.1016/j.cell.2024.10.005">DOI</a></td>
      </tr>
      <tr>
        <td>2024</td>
        <td><b>González-Buenfil R</b>, <b>Vieyra-Sánchez S</b>, <b>Quinto-Cortés CD</b>,...,<b>Barberena-Jonas C</b>,..., <b>Moreno-Estrada A</b>.</td>
        <td><i>Genome Biol Evol</i></td>
        <td>Genetic Signatures of Positive Selection in Human Populations Adapted to High Altitude in Papua New Guinea</td>
        <td><a href="https://doi.org/10.1093/gbe/evae161">DOI</a></td>
      </tr>
      <tr>
        <td>2024</td>
        <td><b>Sohail M</b> &amp; <b>Moreno-Estrada A</b></td>
        <td><i>Dis Model Mech</i></td>
        <td>The Mexican Biobank Project promotes genetic discovery, inclusive science and local capacity building</td>
        <td><a href="https://doi.org/10.1242/dmm.050522">DOI</a></td>
      </tr>
      <tr>
        <td>2024</td>
        <td>Chong AY, Brenner N, <b>Jimenez-Kaufmann A</b>,..., <b>Moreno-Estrada A</b>, et al.</td>
        <td><i>Am J Hum Genet</i></td>
        <td>A common NFKB1 variant detected through antibody analysis in UK Biobank predicts risk of infection and allergy</td>
        <td><a href="https://doi.org/10.1016/j.ajhg.2023.12.013">DOI</a></td>
      </tr>
      <tr>
        <td>2023</td>
        <td><b>Sohail M</b>, <b>Palma-Martínez MJ</b>, Chong AY, <b>Quinto-Cortés CD</b>, <b>Barberena-Jonas C</b>, <b>Medina-Muñoz SG</b>, <b>Ragsdale A</b>,..., <b>Moreno-Estrada A</b>.</td>
        <td><i>Nature</i></td>
        <td>Mexican Biobank advances population and medical genomics of diverse ancestries</td>
        <td><a href="https://doi.org/10.1038/s41586-023-06560-0">DOI</a></td>
      </tr>
      <tr>
        <td>2023</td>
        <td>Beichman AC, Robinson J, Lin M, <b>Moreno-Estrada A</b>, <b>Nigenda-Morales S</b>, Harris K</td>
        <td><i>Mol Biol Evol</i></td>
        <td>Evolution of the Mutation Spectrum Across a Mammalian Phylogeny</td>
        <td><a href="https://doi.org/10.1093/molbev/msad213">DOI</a></td>
      </tr>
      <tr>
        <td>2023</td>
        <td><b>Medina-Muñoz SG</b>,..., <b>Moreno-Estrada A</b>, <b>Ragsdale AP</b>.</td>
        <td><i>Am J Hum Genet</i></td>
        <td>Demographic modeling of admixed Latin American populations from whole genomes</td>
        <td><a href="https://doi.org/10.1016/j.ajhg.2023.08.015">DOI</a></td>
      </tr>
      <tr>
        <td>2023</td>
        <td><b>Nigenda-Morales SF</b>, Lin M,<b>Nuñez-Valencia PG</b>,..., <b>Ragsdale AP</b>,..., <b>Moreno-Estrada A</b>, et al.</td>
        <td><i>Nat Commun</i></td>
        <td>The genomic footprint of whaling and isolation in fin whale populations</td>
        <td><a href="https://doi.org/10.1038/s41467-023-40052-z">DOI</a></td>
      </tr>
      <tr>
        <td>2023</td>
        <td>Beichman AC, Robinson J, Lin M, <b>Moreno-Estrada A</b>, <b>Nigenda-Morales S</b>, Harris K</td>
        <td><i>bioRxiv</i></td>
        <td>"Evolution of the mutation spectrum across a mammalian phylogeny"</td>
        <td><a href="https://doi.org/10.1101/2023.05.31.543114">DOI</a></td>
      </tr>
      <tr>
        <td>2023</td>
        <td>Villa-Islas V,..., <b>Rodríguez-Rodríguez JE</b>,..., <b>Sandoval K</b>, <b>Nieves-Colón MA</b>,..., <b>Moreno-Estrada A</b>, et al.</td>
        <td><i>Science</i></td>
        <td>Demographic history and genetic structure in pre-Hispanic Central Mexico</td>
        <td><a href="https://doi.org/10.1126/science.add6142">DOI</a></td>
      </tr>
      <tr>
        <td>2023</td>
        <td>Huerta-Chagoya A,..., <b>Moreno-Estrada A; Mexican Biobank; Aguilar-Salinas CA</b>, et al.</td>
        <td><i>Diabetologia</i></td>
        <td>The power of TOPMed imputation for the discovery of Latino-enriched rare variants associated with type 2 diabetes</td>
        <td><a href="https://doi.org/10.1007/s00125-023-05912-9">DOI</a></td>
      </tr>
      <tr>
        <td>2023</td>
        <td>Beichman AC,..., <b>Moreno-Estrada A</b>, et al.</td>
        <td><i>Mol Ecol</i></td>
        <td>Genomic analyses reveal range-wide devastation of sea otter populations</td>
        <td><a href="https://doi.org/10.1111/mec.16334">DOI</a></td>
      </tr>
      <tr>
        <td>2022</td>
        <td>Caro-Consuegra R, <b>Nieves-Colón MA</b>,..., <b>Sandoval K</b>, <b>Moreno-Estrada A</b>, et al.</td>
        <td><i>Mol Biol Evol</i></td>
        <td>Uncovering Signals of Positive Selection in Peruvian Populations from Three Ecological Regions</td>
        <td><a href="https://doi.org/10.1093/molbev/msac158">DOI</a></td>
      </tr>
      <tr>
        <td>2022</td>
        <td>Liu YC,..., <b>Quinto-Cortés CD</b>,..., <b>Moreno-Estrada A</b>, et al.</td>
        <td><i>Science</i></td>
        <td>Ancient DNA reveals five streams of migration into Micronesia and matrilocality in early Pacific seafarers</td>
        <td><a href="https://doi.org/10.1126/science.abm6536">DOI</a></td>
      </tr>
      <tr>
        <td>2022</td>
        <td><b>Nieves-Colón MA</b>, Badillo Rivera KM, <b>Sandoval K</b>,..., <b>González-Buenfil R</b>,...,<b>Moreno-Estrada A</b>.</td>
        <td><i>Am J Hum Genet</i></td>
        <td>Clotting factor genes are associated with preeclampsia in high-altitude pregnant women in the Peruvian Andes</td>
        <td><a href="https://doi.org/10.1016/j.ajhg.2022.04.014">DOI</a></td>
      </tr>
      <tr>
        <td>2022</td>
        <td>Mendoza-Revilla J,...,<b>Nieves-Colón MA</b>,..., <b>Moreno-Estrada A</b>, et al.</td>
        <td><i>Mol Biol Evol</i></td>
        <td>Disentangling Signatures of Selection Before and After European Colonization in Latin Americans</td>
        <td><a href="https://doi.org/10.1093/molbev/msac076">DOI</a></td>
      </tr>
      <tr>
        <td>2022</td>
        <td>Bastard P,..., <b>Sandoval K</b>, <b>Barberena-Jonas C</b>, <b>Quinto-Cortés CD</b>,..., <b>Moreno-Estrada A</b>, et al.</td>
        <td><i>J Exp Med</i></td>
        <td>A loss-of-function IFNAR1 allele in Polynesia underlies severe viral diseases in homozygotes</td>
        <td><a href="https://doi.org/10.1084/jem.20220028">DOI</a></td>
      </tr>
      <tr>
        <td>2022</td>
        <td><b>Rodríguez-Rodríguez JE</b>, Ioannidis AG, <b>Medina-Muñoz SG</b>, <b>Barberena-Jonas C</b>, <b>Blanco-Portillo J</b>, <b>Quinto-Cortés CD</b>, <b>Moreno-Estrada A</b>.</td>
        <td><i>Philos Trans R Soc Lond B Biol Sci</i></td>
        <td>The genetic legacy of the Manila galleon trade in Mexico</td>
        <td><a href="https://doi.org/10.1098/rstb.2020.0419">DOI</a></td>
      </tr>
      <tr>
        <td>2022</td>
        <td><b>Jiménez-Kaufmann A</b>, Chong AY, Cortés A, <b>Quinto-Cortés CD</b>,..., <b>Medina-Muñoz SG</b>, <b>Sohail M</b>, <b>Palma-Martinez MJ</b>,..., <b>Moreno-Estrada A</b>.</td>
        <td><i>Front Genet</i></td>
        <td>Imputation Performance in Latin American Populations: Improving Rare Variants Representation With the Inclusion of Native American Genomes</td>
        <td><a href="https://doi.org/10.3389/fgene.2021.719791">DOI</a></td>
      </tr>
      <tr>
        <td>2022</td>
        <td>Ojeda-Granados C,..., <b>Jiménez-Kaufmann A</b>,..., <b>Moreno-Estrada A</b>, et al.</td>
        <td><i>Mol Biol Evol</i></td>
        <td>Dietary, Cultural, and Pathogens-Related Selective Pressures Shaped Differential Adaptive Evolution among Native Mexican Populations</td>
        <td><a href="https://doi.org/10.1093/molbev/msab290">DOI</a></td>
      </tr>
      <tr>
        <td>2021</td>
        <td>Ongaro L,..., <b>Moreno-Estrada A</b>, et al.</td>
        <td><i>Genes (Basel)</i></td>
        <td>Evaluating the Impact of Sex-Biased Genetic Admixture in the Americas through the Analysis of Haplotype Data</td>
        <td><a href="https://doi.org/10.3390/genes12101580">DOI</a></td>
      </tr>
      <tr>
        <td>2021</td>
        <td>Ioannidis AG, <b>Blanco-Portillo J</b>, <b>Sandoval K</b>, Hagelberg E, <b>Barberena-Jonas C</b>, Hill AVS, <b>Rodríguez-Rodríguez JE</b>,..., <b>Quinto-Cortés CD</b>,..., <b>Moreno-Estrada A</b>.</td>
        <td><i>Nature</i></td>
        <td>Paths and timings of the peopling of Polynesia inferred from genomic networks</td>
        <td><a href="https://doi.org/10.1038/s41586-021-03902-8">DOI</a></td>
      </tr>
      <tr>
        <td>2021</td>
        <td>Ongaro L,..., <b>Moreno-Estrada A</b>, et al.</td>
        <td><i>Hum Mol Genet</i></td>
        <td>Continental-scale genomic analysis suggests shared post-admixture adaptation in the Americas</td>
        <td><a href="https://doi.org/10.1093/hmg/ddab177">DOI</a></td>
      </tr>
      <tr>
        <td>2020</td>
        <td>Bravo-Lopez M,..., <b>Moreno-Estrada A</b>, <b>Nieves-Colón MA</b>,..., <b>Sandoval K</b>, et al.</td>
        <td><i>Philos Trans R Soc Lond B Biol Sci</i></td>
        <td>Paleogenomic insights into the red complex bacteria Tannerella forsythia in Pre-Hispanic and Colonial individuals from Mexico</td>
        <td><a href="https://doi.org/10.1098/rstb.2019.0580">DOI</a></td>
      </tr>
      <tr>
        <td>2020</td>
        <td>Ioannidis AG, <b>Blanco-Portillo J</b>, <b>Sandoval K</b>,..., <b>Rodríguez-Rodríguez JE</b>, <b>Quinto-Cortés CD</b>,..., <b>Moreno-Estrada A</b>.</td>
        <td><i>Nature</i></td>
        <td>Native American gene flow into Polynesia predating Easter Island settlement</td>
        <td><a href="https://doi.org/10.1038/s41586-020-2487-2">DOI</a></td>
      </tr>
      <tr>
        <td>2020</td>
        <td>Verdugo RA,..., <b>Moreno-Estrada A</b>,..., <b>Sandoval K</b>, et al.</td>
        <td><i>Biol Res</i></td>
        <td>Development of a small panel of SNPs to infer ancestry in Chileans that distinguishes Aymara and Mapuche components</td>
        <td><a href="https://doi.org/10.1186/s40659-020-00284-5">DOI</a></td>
      </tr>
      <tr>
        <td>2020</td>
        <td>Ávila-Arcos MC, McManus KF, <b>Sandoval K</b>, <b>Rodríguez-Rodríguez JE</b>,...,<b>Moreno-Estrada A</b>.</td>
        <td><i>Mol Biol Evol</i></td>
        <td>Population History and Gene Divergence in Native Mexicans Inferred from 76 Human Exomes</td>
        <td><a href="https://doi.org/10.1093/molbev/msz282">DOI</a></td>
      </tr>
      <tr>
        <td>2019</td>
        <td>Ongaro L,..., <b>Moreno-Estrada A</b>, et al.</td>
        <td><i>Curr Biol</i></td>
        <td>The Genomic Impact of European Colonization of the Americas</td>
        <td><a href="https://doi.org/10.1016/j.cub.2019.09.076">DOI</a></td>
      </tr>
      <tr>
        <td>2019</td>
        <td>Wojcik GL,..., <b>Moreno-Estrada A</b>,..., <b>Sandoval K</b>, et al.</td>
        <td><i>Nature</i></td>
        <td>Genetic analyses of diverse populations improves discovery for complex traits</td>
        <td><a href="https://doi.org/10.1038/s41586-019-1310-4">DOI</a></td>
      </tr>
      <tr>
        <td>2019</td>
        <td>Huerta-Chagoya A,..., <b>Salazar-Fernandez EP</b>,<b>Moreno-Estrada A</b>, et al.</td>
        <td><i>BMC Genet</i></td>
        <td>A panel of 32 AIMs suitable for population stratification correction and global ancestry estimation in Mexican mestizos</td>
        <td><a href="https://doi.org/10.1186/s12863-018-0707-7">DOI</a></td>
      </tr>
      <tr>
        <td>2019</td>
        <td>Spear ML,..., <b>Sandoval K</b>, et al.</td>
        <td><i>Pharmacogenomics J</i></td>
        <td>A genome-wide association and admixture mapping study of bronchodilator drug response in African Americans with asthma</td>
        <td><a href="https://doi.org/10.1038/s41397-018-0042-4">DOI</a></td>
      </tr>
      <tr>
        <td>2019</td>
        <td>Gignoux CR,..., <b>Moreno-Estrada A</b>, <b>Sandoval K</b>, et al.</td>
        <td><i>J Allergy Clin Immunol</i></td>
        <td>An admixture mapping meta-analysis implicates genetic variation at 18q21 with asthma susceptibility in Latinos</td>
        <td><a href="https://doi.org/10.1016/j.jaci.2016.08.057">DOI</a></td>
      </tr>
      <tr>
        <td>2018</td>
        <td>Belbin GM, <b>Nieves-Colón MA</b>, Kenny EE, <b>Moreno-Estrada A</b>, Gignoux CR</td>
        <td><i>Curr Opin Genet Dev</i></td>
        <td>Genetic diversity in populations across Latin America: implications for population and medical genetic studies</td>
        <td><a href="https://doi.org/10.1016/j.gde.2018.07.006">DOI</a></td>
      </tr>
      <tr>
        <td>2018</td>
        <td>de la Fuente C,..., <b>Moreno-Estrada A</b>, et al.</td>
        <td><i>Proc Natl Acad Sci U S A</i></td>
        <td>Genomic insights into the origin and diversification of late maritime hunter-gatherers from the Chilean Patagonia</td>
        <td><a href="https://doi.org/10.1073/pnas.1715688115">DOI</a></td>
      </tr>
      <tr>
        <td>2018</td>
        <td>Mak ACY,..., <b>Moreno-Estrada A</b>, <b>Sandoval K</b>, et al.</td>
        <td><i>Am J Respir Crit Care Med</i></td>
        <td>Whole-Genome Sequencing of Pharmacogenetic Drug Response in Racially Diverse Children with Asthma</td>
        <td><a href="https://doi.org/10.1164/rccm.201712-2529OC">DOI</a></td>
      </tr>
      <tr>
        <td>2016</td>
        <td>Alarcón-Riquelme ME,..., <b>Moreno-Estrada A</b>, et al.</td>
        <td><i>Arthritis Rheumatol</i></td>
        <td>Genome-Wide Association Study in an Amerindian Ancestry Population Reveals Novel Systemic Lupus Erythematosus Risk Loci and the Role of European Admixture</td>
        <td><a href="https://doi.org/10.1002/art.39504">DOI</a></td>
      </tr>
      <tr>
        <td>2016</td>
        <td>Mallick S,..., <b>Moreno-Estrada A</b>, et al.</td>
        <td><i>Nature</i></td>
        <td>The Simons Genome Diversity Project: 300 genomes from 142 diverse populations</td>
        <td><a href="https://doi.org/10.1038/nature18964">DOI</a></td>
      </tr>
      <tr>
        <td>2015</td>
        <td>Arteaga MC,..., <b>Moreno-Estrada A</b>, et al.</td>
        <td><i>Genom Data</i></td>
        <td>Genomic variation in recently collected maize landraces from Mexico</td>
        <td><a href="https://doi.org/10.1016/j.gdata.2015.11.002">DOI</a></td>
      </tr>
      <tr>
        <td>2015</td>
        <td>Homburger JR, <b>Moreno-Estrada A</b>, et al.</td>
        <td><i>PLoS Genet</i></td>
        <td>Genomic Insights into the Ancestry and Demographic History of South America</td>
        <td><a href="https://doi.org/10.1371/journal.pgen.1005602">DOI</a></td>
      </tr>
      <tr>
        <td>2015</td>
        <td>Raghavan M,..., <b>Moreno-Estrada A</b>, et al.</td>
        <td><i>Science</i></td>
        <td>POPULATION GENETICS. Genomic evidence for the Pleistocene and recent population history of Native Americans</td>
        <td><a href="https://doi.org/10.1126/science.aab3884">DOI</a></td>
      </tr>
      <tr>
        <td>2015</td>
        <td>Pino-Yanes M,..., <b>Moreno-Estrada A</b>, <b>Sandoval K</b>, et al.</td>
        <td><i>J Allergy Clin Immunol</i></td>
        <td>Genome-wide association study and admixture mapping reveal new loci associated with total IgE levels in Latinos</td>
        <td><a href="https://doi.org/10.1016/j.jaci.2014.10.033">DOI</a></td>
      </tr>
      <tr>
        <td>2015</td>
        <td>Pino-Yanes M,..., <b>Moreno-Estrada A</b>, <b>Sandoval K</b>, et al.</td>
        <td><i>J Allergy Clin Immunol</i></td>
        <td>Genetic ancestry influences asthma susceptibility and lung function among Latinos</td>
        <td><a href="https://doi.org/10.1016/j.jaci.2014.07.053">DOI</a></td>
      </tr>
      <tr>
        <td>2014</td>
        <td><b>Moreno-Estrada A</b>,..., <b>Sandoval K</b>, et al.</td>
        <td><i>Science</i></td>
        <td>Human genetics. The genetics of Mexico recapitulates Native American substructure and affects biomedical traits</td>
        <td><a href="https://doi.org/10.1126/science.1251688">DOI</a></td>
      </tr>
      <tr>
        <td>2014</td>
        <td>Sikora M,..., <b>Moreno-Estrada A</b>, et al.</td>
        <td><i>PLoS Genet</i></td>
        <td>Population genomic analysis of ancient and modern genomes yields new insights into the genetic ancestry of the Tyrolean Iceman and the genetic structure of Europe</td>
        <td><a href="https://doi.org/10.1371/journal.pgen.1004353">DOI</a></td>
      </tr>
      <tr>
        <td>2014</td>
        <td>Galanter JM,...,<b>Moreno-Estrada A</b>,<b>Sandoval K</b>, et al.</td>
        <td><i>J Allergy Clin Immunol</i></td>
        <td>Genome-wide association study and admixture mapping identify different asthma-associated loci in Latinos: the Genes-environments &amp; Admixture in Latino Americans study</td>
        <td><a href="https://doi.org/10.1016/j.jaci.2013.08.055">DOI</a></td>
      </tr>
      <tr>
        <td>2014</td>
        <td>Drake KA,...,<b>Moreno-Estrada A</b>, <b>Sandoval K</b>, et al.</td>
        <td><i>J Allergy Clin Immunol</i></td>
        <td>A genome-wide association study of bronchodilator response in Latinos implicates rare variants</td>
        <td><a href="https://doi.org/10.1016/j.jaci.2013.06.043">DOI</a></td>
      </tr>
      <tr>
        <td>2013</td>
        <td>Carpenter ML,..., <b>Sandoval K</b>, <b>Moreno-Estrada A</b>, et al.</td>
        <td><i>Am J Hum Genet</i></td>
        <td>Pulling out the 1%: whole-genome capture for the targeted enrichment of ancient DNA sequencing libraries</td>
        <td><a href="https://doi.org/10.1016/j.ajhg.2013.10.002">DOI</a></td>
      </tr>
      <tr>
        <td>2013</td>
        <td>Gravel S,..., <b>Moreno-Estrada A</b>, <b>Sandoval K</b>, et al.</td>
        <td><i>PLoS Genet</i></td>
        <td>Reconstructing Native American migrations from whole-genome and whole-exome data</td>
        <td><a href="https://doi.org/10.1371/journal.pgen.1004023">DOI</a></td>
      </tr>
      <tr>
        <td>2013</td>
        <td><b>Moreno-Estrada A</b>,...,<b>Sandoval K</b>, et al.</td>
        <td><i>PLoS Genet</i></td>
        <td>Reconstructing the population genetic history of the Caribbean</td>
        <td><a href="https://doi.org/10.1371/journal.pgen.1003925">DOI</a></td>
      </tr>
      <tr>
        <td>2013</td>
        <td>Kumar R,..., <b>Moreno-Estrada A</b>, <b>Sandoval K</b>, et al.</td>
        <td><i>J Allergy Clin Immunol</i></td>
        <td>Factors associated with degree of atopy in Latino children in a nationwide pediatric sample: the Genes-environments and Admixture in Latino Asthmatics (GALA II) study</td>
        <td><a href="https://doi.org/10.1016/j.jaci.2013.02.046">DOI</a></td>
      </tr>
      <tr>
        <td>2012</td>
        <td>Kidd JM,..., <b>Moreno-Estrada A</b>, et al.</td>
        <td><i>Am J Hum Genet</i></td>
        <td>Population genetic inference from personal genome data: impact of ancestry and admixture on human genomic variation</td>
        <td><a href="https://doi.org/10.1016/j.ajhg.2012.08.025">DOI</a></td>
      </tr>
      <tr>
        <td>2012</td>
        <td>Antolin MF,..., <b>Moreno-Estrada A</b>, et al.</td>
        <td><i>Evolution</i></td>
        <td>Evolution and medicine in undergraduate education: a prescription for all biology students</td>
        <td><a href="https://doi.org/10.1111/j.1558-5646.2011.01552.x">DOI</a></td>
      </tr>
      <tr>
        <td>2012</td>
        <td><b>Sandoval K</b>, <b>Moreno-Estrada A</b>, et al.</td>
        <td><i>Am J Phys Anthropol</i></td>
        <td>Y-chromosome diversity in Native Mexicans reveals continental transition of genetic structure in the Americas</td>
        <td><a href="https://doi.org/10.1002/ajpa.22062">DOI</a></td>
      </tr>
      <tr>
        <td>2012</td>
        <td>Kenny EE,..., <b>Moreno-Estrada A</b>, et al.</td>
        <td><i>Science</i></td>
        <td>Melanesian blond hair is caused by an amino acid change in TYRP1</td>
        <td><a href="https://doi.org/10.1126/science.1217849">DOI</a></td>
      </tr>
      <tr>
        <td>2012</td>
        <td>Chen R,..., <b>Moreno-Estrada A</b>, et al.</td>
        <td><i>PLoS Genet</i></td>
        <td>Type 2 diabetes risk alleles demonstrate extreme directional differentiation among human populations, compared to other diseases</td>
        <td><a href="https://doi.org/10.1371/journal.pgen.1002621">DOI</a></td>
      </tr>
      <tr>
        <td>2012</td>
        <td>Keller A,..., <b>Moreno-Estrada A</b>, et al.</td>
        <td><i>Nat Commun</i></td>
        <td>New insights into the Tyrolean Iceman's origin and phenotype as inferred by whole-genome sequencing</td>
        <td><a href="https://doi.org/10.1038/ncomms1701">DOI</a></td>
      </tr>
      <tr>
        <td>2012</td>
        <td>Henn BM,..., <b>Moreno-Estrada A</b>, et al.</td>
        <td><i>PLoS Genet</i></td>
        <td>Genomic ancestry of North Africans supports back-to-Africa migrations</td>
        <td><a href="https://doi.org/10.1371/journal.pgen.1002397">DOI</a></td>
      </tr>
      <tr>
        <td>2010</td>
        <td>Henn BM, Gravel S, <b>Moreno-Estrada A</b>, Acevedo-Acevedo S, Bustamante CD</td>
        <td><i>Hum Mol Genet</i></td>
        <td>Fine-scale population structure and the era of next-generation sequencing</td>
        <td><a href="https://doi.org/10.1093/hmg/ddq403">DOI</a></td>
      </tr>
      <tr>
        <td>2010</td>
        <td><b>Moreno-Estrada A</b>,..., et al.</td>
        <td><i>BMC Evol Biol</i></td>
        <td>African signatures of recent positive selection in human FOXI1</td>
        <td><a href="https://doi.org/10.1186/1471-2148-10-267">DOI</a></td>
      </tr>
      <tr>
        <td>2010</td>
        <td>Bryc K,..., <b>Moreno-Estrada A</b>, et al.</td>
        <td><i>Proc Natl Acad Sci U S A</i></td>
        <td>Colloquium paper: genome-wide patterns of population structure and admixture among Hispanic/Latino populations</td>
        <td><a href="https://doi.org/10.1073/pnas.0914618107">DOI</a></td>
      </tr>
      <tr>
        <td>2010</td>
        <td>Acuña-Alonzo V,..., <b>Moreno-Estrada A</b>, et al.</td>
        <td><i>Hum Mol Genet</i></td>
        <td>A functional ABCA1 gene variant is associated with low HDL-cholesterol levels and shows evidence of positive selection in Native Americans</td>
        <td><a href="https://doi.org/10.1093/hmg/ddq173">DOI</a></td>
      </tr>
      <tr>
        <td>2009</td>
        <td>Bosch E,..., <b>Moreno-Estrada A</b>, et al.</td>
        <td><i>BMC Genomics</i></td>
        <td>Decay of linkage disequilibrium within genes across HGDP-CEPH human samples: most population isolates do not show increased LD</td>
        <td><a href="https://doi.org/10.1186/1471-2164-10-338">DOI</a></td>
      </tr>
      <tr>
        <td>2009</td>
        <td><b>Moreno-Estrada A</b>,..., et al.</td>
        <td><i>Mol Biol Evol</i></td>
        <td>Interrogating 11 fast-evolving genes for signatures of recent positive selection in worldwide human populations</td>
        <td><a href="https://doi.org/10.1093/molbev/msp134">DOI</a></td>
      </tr>
      <tr>
        <td>2008</td>
        <td>Morcillo-Suarez C,..., <b>Moreno-Estrada A</b>, et al.</td>
        <td><i>Bioinformatics</i></td>
        <td>SNP analysis to results (SNPator): a web-based environment oriented to statistical genomics analyses upon SNP data</td>
        <td><a href="https://doi.org/10.1093/bioinformatics/btn241">DOI</a></td>
      </tr>
      <tr>
        <td>2008</td>
        <td><b>Moreno-Estrada A</b>,..., et al.</td>
        <td><i>Mol Biol Evol</i></td>
        <td>Signatures of selection in the human olfactory receptor OR5I1 gene</td>
        <td><a href="https://doi.org/10.1093/molbev/msm240">DOI</a></td>
      </tr>
    </tbody>
  </table>
</div>

<script>
function filterTable() {
  var input = document.getElementById("pubSearch");
  var filter = input.value.toUpperCase();
  var table = document.getElementById("myTable");
  var tr = table.getElementsByTagName("tr");
  for (var i = 1; i < tr.length; i++) {
    var text = tr[i].textContent || tr[i].innerText;
    tr[i].style.display = text.toUpperCase().indexOf(filter) > -1 ? "" : "none";
  }
}
</script>
{% endraw %}
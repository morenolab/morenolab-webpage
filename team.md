---
layout: page
title: ""
description: "CINVESTAV Sede Sur, Mexico"
feature_image: "/assets/images/team/portada2026.png"
order: 2
---

<style>
  /* 1. Full-width centering fix for team sections */
  .team-section {
    width: 98vw;
    position: relative;
    left: 50%;
    transform: translateX(-50%);
    max-width: 1700px; /* Limits expansion on very large monitors */
    margin-top: 40px;
    margin-bottom: 60px;
  }

  /* 2. Create the 3-column grid */
  .team-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 40px 60px;
    align-items: start;
  }

  /* 3. Member Card Styling */
  .member-card {
    display: flex;
    flex-direction: column;
    text-align: left;
    background: #fff;
    padding-bottom: 20px;
    border-bottom: 1px solid #f0f0f0;
  }

  /* Center the image and name */
  .member-header {
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    margin-bottom: 15px;
  }

  .member-header img {
    margin-bottom: 10px;
    border-radius: 50%;
    object-fit: cover;
  }

  .member-header h2 {
    margin: 0 !important;
    border-bottom: none !important;
    font-size: 1.4em;
    color: #333;
  }

  .member-bio {
    font-size: 0.95em;
    line-height: 1.6;
    color: #444;
  }

  /* Variante: 2 columnas (Masters Students) */
  .team-grid--two {
    grid-template-columns: repeat(2, 1fr);
  }

  /* Variante: centrado (Data Scientist) */
  .team-grid--centered {
    grid-template-columns: minmax(0, 400px);
    justify-content: center;
  }

  /* 4. Responsive: 2 columnas en pantallas medianas, 1 en pequeñas */
  @media (max-width: 1200px) {
    .team-grid {
      grid-template-columns: repeat(2, 1fr);
    }
  }

  @media (max-width: 700px) {
    .team-section {
      width: 100%;
      left: 0;
      transform: none;
    }
    .team-grid {
      grid-template-columns: 1fr;
    }
  }
</style>

## Principal Investigator

<div style="display: flex; align-items: center; margin-bottom: 20px; margin-top: 40px;">
  <img src="/assets/images/team/Andres_Moreno.png" alt="Andrés Moreno Estrada" style="width: 200px; height: 200px; object-fit: cover; border-radius: 50%; margin-right: 25px; margin-bottom: 0;">
  <h2 style="margin: 0; border-bottom: none;">Andrés Moreno Estrada</h2>
</div>

I am a medical doctor and population geneticist whose work integrates genomics, evolution, and precision medicine. Our group focuses on human evolution, adaptation, and population history, alongside the biomedical implications of genetic diversity in underserved populations across the Americas and the Pacific.

[Email](mailto:popgenlab@cinvestav.mx) · [Twitter](https://twitter.com/morestrada) · [Google Scholar](https://scholar.google.com.mx/citations?user=e8sFFesAAAAJ&hl=en)


## Laboratory Manager

<div style="display: flex; align-items: center; margin-bottom: 20px; margin-top: 40px;">
  <img src="/assets/images/team/Flor.png" alt="Flor Montes de Oca" style="width: 200px; height: 200px; object-fit: cover; border-radius: 50%; margin-right: 25px; margin-bottom: 0;">
  <h2 style="margin: 0; border-bottom: none;">Flor Montes de Oca</h2>
</div>

I am the Lab Manager at the Moreno Lab, overseeing coordination and day-to-day operations to ensure smooth research development. I hold a Master’s degree in Human Rights and bring over 20 years of project management and institutional coordination experience across government and international organizations.

[Email](mailto:popgenlab@cinvestav.mx)

---

## Postdoctoral Fellows

<div class="team-section">
<div class="team-grid">

  <div class="member-card">
    <div class="member-header">
      <img src="/assets/images/team/Carmina.png" style="width: 180px; height: 180px; object-fit: cover; border-radius: 50%;">
      <h2>Carmina Barberena-Jonas</h2>
    </div>
    <div class="member-bio">
    My current project in MorenoLab involves the analysis of identity-by-descent genomic segments to determine the population structure of Mexico and their implications in biomedical traits using the data from the Mexican BioBank (MXB). I’m developing the tool MexVar to explore and query the MXB biomedical data. I am also involved in other projects such as the Oceanian Genome Variation Project and LatinCells.
    <br><br>
      <a href="mailto:carmina.barberena@cinvestav.mx">Email</a> · <a href="https://x.com/BarjonCar">Twitter</a> · <a href="https://scholar.google.com/citations?user=W39_jzcAAAAJ&hl=es">Google Scholar</a>
    </div>
  </div>

  <div class="member-card">
    <div class="member-header">
      <img src="/assets/images/team/Daniel.jpeg" style="width: 180px; height: 180px; object-fit: cover; border-radius: 50%;">
      <h2>Edder Daniel Bustos Diaz</h2>
    </div>
    <div class="member-bio">
      I have a scientific interest in multiple things, but the PacBio and Illumina of it (pun intended) is that I am passionate about everything sequencing related, IT infrastructure and running experiments. I am currently working on the Latin Pangenome project, managing data and working with assemblies. I am in charge of Kexol, our HPC cluster, some of the lab's websites and general IT/wet lab stuff, working alongside Flor, the lab manager, to make sure that bits and tips are working as intended.
      <br><br>
      <a href="mailto:edder.bustos@cinvestav.mx">Email</a>
    </div>
  </div>

  <div class="member-card">
    <div class="member-header">
      <img src="/assets/images/team/Josian.jpeg" style="width: 180px; height: 180px; object-fit: cover; border-radius: 50%;">
      <h2>José Antonio Corona-Gomez (Josian)</h2>
    </div>
    <div class="member-bio">
    I lead Bioinformatics Research for LatinCells, an international initiative funded by the Chan Zuckerberg Initiative. LatinCells aims to map single-cell gene expression diversity across Indigenous and underrepresented populations in Latin America.
    My current research focuses on the analysis of single-cell RNA sequencing data from Latin American communities. I study how genetic background, particularly Native American ancestry influences immune cell composition and gene expression patterns.
    <br><br>
      <a href="mailto:jose.corona@cinvestav.mx">Email</a> · <a href="https://x.com/JAntonioCorona">Twitter</a>
    </div>
  </div>

  <div class="member-card">
    <div class="member-header">
      <img src="/assets/images/team/Diego.jpg" style="width: 180px; height: 180px; object-fit: cover; border-radius: 50%;">
      <h2>Diego Hartasánchez</h2>
    </div>
    <div class="member-bio">
    I am a physicist-turned-evolutionary biologist with a PhD from Universitat Pompeu Fabra, and postdoctoral experience across France and Switzerland. My research spans evolutionary modeling, comparative genomics, and computer simulations, covering topics from recombination evolution to flower morphogenesis to structural variation in clownfish.
    Now back in my home city, I join the Human Evolutionary Population Genomics Group, where I will contribute to understanding the evolutionary history and diversity of Latin American populations.
    <br><br>
      <a href="mailto:diegoharta@gmail.com">Email</a> · <a href="https://scholar.google.com/citations?user=qztY5fAAAAAJ&hl=en">Google Scholar</a>
    </div>
  </div>

  <div class="member-card">
    <div class="member-header">
      <img src="/assets/images/team/Marisol.jpeg" style="width: 180px; height: 180px; object-fit: cover; border-radius: 50%;">
      <h2>Marisol Naydú Espitia Fajardo</h2>
    </div>
    <div class="member-bio">
    I am a biologist with a Master's and Doctorate in Biological Sciences from Universidad del Valle, Colombia, specializing in population genetics and human genomic diversity. My research has focused on genetic diversity and population structure in Colombian indigenous communities, exploring their demographic dynamics and evolutionary relationships with other Amerindian populations.
    Currently, I am a postdoctoral researcher in Dr. Moreno's lab, where I apply bioinformatics and genomic tools — including whole genome analysis and demographic inference — to study human diversity across Latin America, with a commitment to representing historically underrepresented populations.
<br><br>
      <a href="mailto:marisol.espitia@cinvestav.mx">Email</a> · <a href="https://x.com/Marisolbiologie">Twitter</a>
    </div>
  </div>

  <div class="member-card">
    <div class="member-header">
      <img src="/assets/images/team/Consuelo.jpeg" style="width: 180px; height: 180px; object-fit: cover; border-radius: 50%;">
      <h2>Consuelo Dayzú Quinto Cortés</h2>
    </div>
    <div class="member-bio">
      I am human population genomicist with a PhD in Genetics from the University of Arizona. I have always been passionate about human history, population genetics, and programming. I am currently the project manager of the project ‘A Latin American pangenome for mapping structural variation of medical relevance in underrepresented indigenous ancestries’, funded by the Wellcome Trust Institute.
      <br><br>
      <a href="mailto:consuelo.quinto@cinvestav.mx">Email</a> · <a href="https://scholar.google.com/citations?user=qJvrhPoAAAAJ&hl=es&oi=ao">Google Scholar</a>
    </div>
  </div>

  <div class="member-card">
    <div class="member-header">
      <img src="/assets/images/team/Camila.png" style="width: 180px; height: 180px; object-fit: cover; border-radius: 50%;">
      <h2>Camila Tamburrini</h2>
    </div>
    <div class="member-bio">
      I am a bioanthropologist graduated from the University of Buenos Aires, Argentina. During my PhD, I investigated genetic variation among ancient hunter-gatherer populations that inhabited central Patagonia during the Holocene, always approaching the associated communities with respect for their cultural and spiritual heritage. From the early stages of my career, I have had a keen interest in forensic genetics. I believe that methodological advancements in ancient DNA research hold significant potential for application in the forensic field. I am passionate about furthering my academic training at the intersection of these two disciplines.
      <br><br>
      <a href="mailto:camila.tamburrini@cinvestav.mx">Email</a> · <a href="https://x.com/camitamburrini">Twitter</a>
    </div>
  </div>

</div>
</div>

---

## PhD Students

<div class="team-section">
<div class="team-grid">

  <div class="member-card">
    <div class="member-header">
      <img src="/assets/images/team/Fernanda.jpeg" style="width: 180px; height: 180px; object-fit: cover; border-radius: 50%;">
      <h2>Maria Fernanda Elias Navarro</h2>
    </div>
    <div class="member-bio">
      My research integrates paleogenomics and archaeology to explore the histories of past populations. I specifically focus on ancient DNA recovered from skeletal remains at Teotihuacan to understand social organization and diversity.
      <br><br>
      <a href="mailto:maria.eliasn@cinvestav.mx">Email</a> · <a href="https://x.com/fherelias04">Twitter</a>
    </div>
  </div>

  <div class="member-card">
    <div class="member-header">
      <img src="/assets/images/team/Aaron.jpg" style="width: 180px; height: 180px; object-fit: cover; border-radius: 50%;">
      <h2>Aarón E. Jaime</h2>
    </div>
    <div class="member-bio">
      I am interested in computational human genomics. My current research uses long-read sequencing kinetics to describe novel ageing-associated DNA methylation patterns in Latin American populations for the LatinGenomes project.
      <br><br>
      <a href="mailto:aaron.espinosa@cinvestav.mx">Email</a>
    </div>
  </div>

  <div class="member-card">
    <div class="member-header">
      <img src="/assets/images/team/Ram.jpeg" style="width: 180px; height: 180px; object-fit: cover; border-radius: 50%;">
      <h2>Ram González Buenfil</h2>
    </div>
    <div class="member-bio">
      I am a computational biologist working at the intersection of population genomics and evolutionary theory. My research investigates how natural selection, admixture, and local adaptation have shaped populations in Latin America and Oceania.
      <br><br>
      <a href="mailto:ram.gonzalez@cinvestav.mx">Email</a> · <a href="https://twitter.com/ramgonzalezb">Twitter</a>
    </div>
  </div>

  <div class="member-card">
    <div class="member-header">
      <img src="/assets/images/team/Santiago.png" style="width: 180px; height: 180px; object-fit: cover; border-radius: 50%;">
      <h2>Santiago Medina</h2>
    </div>
    <div class="member-bio">
      I am a computational biologist focused on evolutionary genetics. My research aims to understand population history and migration dynamics in Indigenous populations from Mexico.
      <br><br>
      <a href="mailto:santiago.medina@cinvestav.mx">Email</a> · <a href="https://scholar.google.com/citations?user=XW3Sz1kAAAAK&hl=es&oi=ao">Google Scholar</a>
    </div>
  </div>

  <div class="member-card">
    <div class="member-header">
      <img src="/assets/images/team/Daniela.png" style="width: 180px; height: 180px; object-fit: cover; border-radius: 50%;">
      <h2>Daniela Orozco</h2>
    </div>
    <div class="member-bio">
      My ancient DNA research focuses on the genetic history of elite individuals buried at the Cañada de la Virgen archaeological site in Mexico. I specialize in turning complex data into clear stories through maps and data visualization.
      <br><br>
      <a href="mailto:daniela.orozco@cinvestav.mx">Email</a>
    </div>
  </div>

  <div class="member-card">
    <div class="member-header">
      <img src="/assets/images/team/Octavio.png" style="width: 180px; height: 180px; object-fit: cover; border-radius: 50%;">
      <h2>Octavio Zambada Moreno</h2>
    </div>
    <div class="member-bio">
      I am a genomic biotechnologist characterizing immune cell variation in Indigenous Latin American populations. I combine single-cell transcriptomics, population genomics, and computational modeling to see how genetic background influences immune responses.
      <br><br>
      <a href="mailto:octavio.zambadam@cinvestav.mx">Email</a> · <a href="https://x.com/Octavirus23">Twitter</a>
    </div>
  </div>

</div>
</div>

---

## Masters Students

<div class="team-section">
<div class="team-grid team-grid--two">

  <div class="member-card">
    <div class="member-header">
      <img src="/assets/images/team/Yuberlis.png" style="width: 180px; height: 180px; object-fit: cover; border-radius: 50%;">
      <h2>Yuberlis González Ipuana</h2>
    </div>
    <div class="member-bio">
      I am a Wayuu indigenous biologist from Colombia. My work focuses on population genetics and the study of diversity and genetic kinship among indigenous peoples of Colombia to help recognize our biological and cultural diversity.
      <br><br>
      <a href="mailto:gonzayube16@gmail.com">Email</a>
    </div>
  </div>

  <div class="member-card">
    <div class="member-header">
      <img src="/assets/images/team/Ricardo_Rodriguez.png" style="width: 180px; height: 180px; object-fit: cover; border-radius: 50%;">
      <h2>Ricardo Rodríguez Ojeda</h2>
    </div>
    <div class="member-bio">
      I specialize in computational biology and human population genomics. I analyze genomic data to explore demographic history and the genetic impact of colonization and admixture processes in modern Mexican populations.
      <br><br>
      <a href="mailto:ricardo.rodriguez.o@cinvestav.mx">Email</a>
    </div>
  </div>

</div>
</div>

---

## Data Scientist

<div class="team-section">
<div class="team-grid team-grid--centered">

  <div class="member-card">
    <div class="member-header">
      <img src="/assets/images/team/Vianka.png" style="width: 180px; height: 180px; object-fit: cover; border-radius: 50%;">
      <h2>Viankail Cedillo Castelán</h2>
    </div>
    <div class="member-bio">
      I am a data scientist focused on biomedical data visualization and UX-oriented design. I develop interactive Shiny applications and AI-powered virtual assistants to translate complex population-genetic data into accessible tools for researchers and clinicians.
      <br><br>
      <a href="mailto:viancastelan.edu@gmail.com">Email</a>
    </div>
  </div>

</div>
</div>

---

## Collaborators

- Karla Sandoval — [CINVESTAV](#)
- Cei Abreu — [University of Edinburgh](https://cei.bio.ed.ac.uk/)
- Selene Fernández Valverde — [UNSW Sydney](https://research.unsw.edu.au/people/dr-selene-fernandez-valverde)
- María Ávila Arcos — [LIIGH](http://www.liigh.unam.mx/mavila)
- Diego Cortez — [UNAM](http://www.ccg.unam.mx/en/Genome_Dynamics/TheProgram)
- Samuel Canizales — [UNAM](http://www.pdcb.unam.mx/tutor/90/canizales-quinteros-samuel)
- Carlos Bustamante — [Stanford University](https://bustamantelab.stanford.edu/)
- Mark Stoneking — [Max Planck Institute for Evolutionary Anthropology](http://www.eva.mpg.de/genetics/index.html)
- Martin Sikora — [Centre for GeoGenetics](http://geogenetics.ku.dk/staff/?pure=en/persons/475540)
- Elena Bosch — [Institut de Biologia Evolutiva Barcelona](http://biologiaevolutiva.org/ebosch/)
- David Comas — [Institut de Biologia Evolutiva Barcelona](http://www.biologiaevolutiva.org/dcomas/)
- Guido Barbujani — [University of Ferrara](http://www.guidobarbujani.it/index.php/1-genetica)
- John Novembre — [University of Chicago](http://jnpopgen.org)
- Simon Gravel — [McGill University](http://simongravel.lab.mcgill.ca/Home.html)
- Eimear Kenny — [Mount Sinai](http://research.mssm.edu/kennylab/)
- Anne Stone — [Arizona State University](https://stone.lab.asu.edu/)
- Mauricio Moraga — [Universidad de Chile](http://www.facso.uchile.cl/antropologia/departamento-de-antropologia/70868/mauricio-leonardo-moraga-vergara)
- Ricardo Verdugo — [Universidad de Chile](http://genomed.med.uchile.cl/home/)
- Sandra Romero — [INMEGEN](http://www.inmegen.gob.mx/es/investigacion/investigadores/curriculum-vitae/?perfil=536)
- Víctor Acuña — [ENAH](http://www.enah.edu.mx/index.php/moleculab)
- Lourdes García-García — [INSP](https://siid.insp.mx/v2/linea_investigacion/detalle/investigador/1813)
- Teresa Tusie-Luna — [INCMNSZ](https://www.biomedicas.unam.mx/personal-academico/maria-teresa-tusie-luna/)
- Carla Gallo — [Universidad Peruana Cayetano Heredia](http://www.upch.edu.pe/vrinve/investigacion/unmg-bbm)

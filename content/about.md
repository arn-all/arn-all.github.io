---
layout: about
title: "Arnaud Allera"
math: false
hide_title: true
description: "Arnaud Allera is a research scientist at ASNR Cadarache focusing on advanced simulations of steel ageing and atomic-scale processes in metals."
keywords: ["Arnaud Allera", "IRSN", "ASNR", "Cadarache", "materials science", "research scientist", "atomic-scale processes", "steel ageing", "molecular dynamics", "machine learning", "PhD thesis", "computational materials science", "defect formation", "phase transformations"]
---

# About me
<!-- Wrap your content in a container div -->
<div class="content-container">

  <div class="text-container">
  <!-- Add your text inside a paragraph -->
  <p>
  I am a permanent research scientist at ASNR Cadarache, in charge of studies on steel ageing using advanced simulation methods. 

  My research is at the interface of condensed matter physics, metallurgy and machine learning to analyze processes happening at the atomic scale🔬 in metals: 
  defect formation, thermally activated process, phase transformations, materials evolution in environment, etc. 

  We use massively parallel computational methods such as molecular dynamics to study solid state physics problems at different scales, using both classical and ML-based methods.
  An example is the [simulation of dislocation mediated plasticity in metals](https://www.nature.com/articles/s41467-025-62390-w), which we showed can be accurately reproduced through atomistic simulations only with the aid of best-in-class machine learning–based simulation methods.

I currently lead the joint ASNR/CNRS project SIMILAR, which aims at accelerating simulations of irradiation damage at the atomic scale and beyond, benefiting from geometric feature representation. This work is carried out by Raynol Dsouza at ASNR Cadarache as part of his postdoc, co-supervised with TD. Swinburne (Univ Michigan, CNRS) and D. Rodney (Univ Lyon 1).

  Previously, I worked at CEA Saclay-SRMP, where I developed efficient, GNN-inspired atomic descriptors for geometric and chemical analysis of atomic arrangements called Neighbors Maps, as well as machine-learned force-fields, as a postdoc with M.-C. Marinica and A. M. Goryaeva.

  For my PhD, I worked with David Rodney (Univ. Lyon), Michel Perez (INSA) and Fabienne Ribeiro (IRSN) on the [depinning of dislocations from interstitial solutes](https://doi.org/10.1103/PhysRevMaterials.6.013608), introducing a new [potential for Fe-C](https://github.com/arn-all/FeC-EAM-potential). 
  I defended in Dec. 2021 at Université de Lyon--UCBL.

  </p>
  </div>
    <!-- Add the image and give it a class for styling -->
  <img class="side-image" src="/images/mountains.jpeg" alt="" />

</div>

<!-- Add a style tag with CSS to control the layout -->
<style>
  .content-container {
    display: flex;
    align-items: flex-start;
  }
  .text-container {
    flex-grow: 1;
    /* text-align: justify; */
  }

  .side-image {
    margin-top: 70px;
    margin-left: 25px; /* Adjust the space between the image and the text */
    max-width: 40%; /* Adjust the width of the image */
    border-radius: 2%; /* Make the image circular */
    overflow: invisible; /* Hide anything outside of the circle */
  }

  /* Responsive design for smaller screens */
  @media (max-width: 768px) {
    .side-image {
      max-width: 100%;
      margin-left: 0;
      margin-bottom: 20px;
    }

    .content-container {
      flex-direction: column;
      align-items: center;
    }
  }
</style>

---
layout: about
title: "About me"
math: false
hide_title: true
---


<!-- Wrap your content in a container div -->
<div class="content-container">

  <div class="text-container">
  <!-- Add your text inside a paragraph -->
  <p>
  I work as a post-doc at CEA Saclay, where I use machine learning / deep learning methods to analyze processes that happen at the atomic scale 🔬 in metals: 
  defects formation, thermally activated process, phase transformations, materials evolution in environment, ... 

  For this, we developed novel atomic descriptors and machine-learning force-fields together with [Mihai-Cosmin Marinica](https://scholar.google.com/citations?user=Yfj9RqUAAAAJ&hl=en) and [Alexandra M. Goryaeva](https://scholar.google.fr/citations?user=3VPSML8AAAAJ&hl=en).

  I intensively use computational methods such as molecular dynamics to study solid state physics problems at different scales, such as [simulations of plasticity in metals](https://journals.aps.org/prmaterials/abstract/10.1103/PhysRevMaterials.6.013608), which is mediated by dislocation motion -actually the subject of [my thesis](https://theses.hal.science/tel-03728547).   

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
  }

  .side-image {
    margin-top: 50px;
    margin-left: 20px; /* Adjust the space between the image and the text */
    max-width: 40%; /* Adjust the width of the image */
    border-radius: 2%; /* Make the image circular */
    overflow: hidden; /* Hide anything outside of the circle */
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
    }
  }
</style>

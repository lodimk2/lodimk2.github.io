---
layout: default
title: About
---

<style>
  :root {
    --text-color-light: #333; /* Text color for light background */
    --text-color-dark: #fff; /* Text color for dark background */
    --background-color-light: #f9f9f9; /* Background color for light mode */
    --background-color-dark: #333; /* Background color for dark mode */
    --border-color: #ccc; /* Border color */
  }

  .timeline {
    position: relative;
    padding: 20px 0;
  }

  .timeline-item {
    position: relative;
    margin: 10px 0;
  }

  .timeline-icon {
    font-size: 24px;
    margin-right: 10px;
  }

  .timeline-content {
    padding: 10px;
    border: 1px solid var(--border-color);
    border-radius: 5px;
    color: var(--text-color-light); /* Default text color for light background */
    background-color: var(--background-color-light); /* Default background color for light mode */
  }

  /* Adjust text and background color for dark mode */
  @media (prefers-color-scheme: dark) {
    .timeline-content {
      color: var(--text-color-dark); /* Text color for dark background */
      background-color: var(--background-color-dark); /* Background color for dark mode */
    }
  }

  .timeline-content h3 {
    margin: 0;
  }

  .timeline-content p {
    margin: 5px 0;
  }
</style>
<div style="border: 1px solid #e0e0e0; padding: 10px;">
<h3>About Me</h3>

I am an Integrative Life Sciences PhD student at Virginia Commonwealth University with experience in single-cell genomic method development, multi-omic data integration, computational biology, and precision medicine. I am a member of the Biological Networks Laboratory in the VCU Department of Computer Science, under the supervision of Dr. Preetam Ghosh.

I enjoy playing cricket, reading fiction, and listening/playing all types of music. 
</div>

<div style="padding: 10px;">
  <p align="left">
    <img src="https://github.com/user-attachments/assets/43b09c22-ecea-4088-bcbe-7ba45af0d1bb" width="650" height="400" style="border: 3px solid #ccc; object-fit: cover; margin-right: 20px; display: block; margin-left: auto; margin-right: auto;">
  </p>
</div>


<div class="timeline">
  <div class="timeline-item">
    <div class="timeline-icon">&#127891;</div>
    <div class="timeline-content">
      <h3>2023 - Present</h3>
      <p>PhD | Integrative Life Sciences, Concentration in Bioinformatics | Virginia Commonwealth University</p>
    </div>
    <div class="timeline-content">
      <h3>2023 - 2023</h3>
      <p>M.S | Bioinformatics | Virginia Commonwealth University</p>
    </div>
      <div class="timeline-content">
      <h3>2019 - 2023</h3>
      <p>B.S | Bioinformatics | Virginia Commonwealth University</p>
    </div>
  </div>
  <!-- Add more timeline items as needed -->
</div>

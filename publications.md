---
layout: default
title: Publications
---

<style>
  :root {
    --text-color-light: #333; /* Text color for light background */
    --text-color-dark: #fff; /* Text color for dark background */
    --background-color-light: #f9f9f9; /* Background color for light mode */
    --background-color-dark: #333; /* Background color for dark mode */
    --border-color: #ccc; /* Border color */
  }

  .publication {
    padding: 20px;
    border: 1px solid var(--border-color);
    border-radius: 5px;
    margin-bottom: 20px;
    color: var(--text-color-light); /* Default text color for light background */
    background-color: var(--background-color-light); /* Default background color for light mode */
  }

  /* Adjust text and background color for dark mode */
  @media (prefers-color-scheme: dark) {
    .publication {
      color: var(--text-color-dark); /* Text color for dark background */
      background-color: var(--background-color-dark); /* Background color for dark mode */
    }
  }

  .publication h3 {
    margin: 0;
  }

  .publication p {
    margin: 5px 0;
  }

  .btn {
    display: inline-block;
    padding: 5px 10px;
    margin-right: 10px;
    background-color: #007bff; /* Button background color */
    color: #fff; /* Button text color */
    text-decoration: none;
    border-radius: 5px;
  }
  .publication strong {
    font-weight: bold;
    background-color: yellow; /* Set the background color to yellow for highlight effect */
    font-color: black;
  }
</style>
<h1> Publications </h1>
<div class="publication">
  <h2>COFFEE: consensus single cell-type specific inference for gene regulatory networks </h2>
  <p>Authors: <strong>Musaddiq K. Lodi</strong>, Anna Chernikov, Preetam Ghosh</p>
  <p>Abstract: The inference of gene regulatory networks (GRNs) is crucial to understanding the regulatory mechanisms that govern biological processes. GRNs may be represented as edges in a graph, and hence, it have been inferred computationally for scRNA-seq data. A wisdom of crowds approach to integrate edges from several GRNs to create one composite GRN has demonstrated improved performance when compared with individual algorithm implementations on bulk RNA-seq and microarray data. In an effort to extend this approach to scRNA-seq data, we present COFFEE (COnsensus single cell-type speciFic inFerence for gEnE regulatory networks), a Borda voting-based consensus algorithm that integrates information from 10 established GRN inference methods. We conclude that COFFEE has improved performance across synthetic, curated, and experimental datasets when compared with baseline methods. Additionally, we show that a modified version of COFFEE can be leveraged to improve performance on newer cell-type specific GRN inference methods. Overall, our results demonstrate that consensus-based methods with pertinent modifications continue to be valuable for GRN inference at the single cell level. While COFFEE is benchmarked on 10 algorithms, it is a flexible strategy that can incorporate any set of GRN inference algorithms according to user preference.</p>
  <a href="https://github.com/lodimk2/coffee" class="btn" target="_blank">GitHub Repo</a>
  <a href="https://academic.oup.com/bib/article/25/6/bbae457/7765455" class="btn" target="_blank">Paper Link</a>
</div>

<div class="publication">
  <h2>CHAI: consensus clustering through similarity matrix integration for cell-type identification </h2>
  <p>Authors: <strong>Musaddiq K. Lodi</strong>, Muzammil Lodi, Kezie Osei, Vaishnavi Ranganathan, Priscilla Hwang, Preetam Ghosh</p>
  <p>Abstract: Several methods have been developed to computationally predict cell-types for single cell RNA sequencing (scRNAseq) data. As methods are developed, a common problem for investigators has been identifying the best method they should apply to their specific use-case. To address this challenge, we present CHAI (consensus Clustering tHrough similArIty matrix integratIon for single cell-type identification), a wisdom of crowds approach for scRNAseq clustering. CHAI presents two competing methods which aggregate the clustering results from seven state-of-the-art clustering methods: CHAI-AvgSim and CHAI-SNF. CHAI-AvgSim and CHAI-SNF demonstrate superior performance across several benchmarking datasets. Furthermore, both CHAI methods outperform the most recent consensus clustering method, SAME-clustering. We demonstrate CHAI’s practical use case by identifying a leader tumor cell cluster enriched with CDH3. CHAI provides a platform for multiomic integration, and we demonstrate CHAI-SNF to have improved performance when including spatial transcriptomics data. CHAI overcomes previous limitations by incorporating the most recent and top performing scRNAseq clustering algorithms into the aggregation framework. It is also an intuitive and easily customizable R package where users may add their own clustering methods to the pipeline, or down-select just the ones they want to use for the clustering aggregation. This ensures that as more advanced clustering algorithms are developed, CHAI will remain useful to the community as a generalized framework.</p>
  <a href="https://github.com/lodimk2/chai" class="btn" target="_blank">GitHub Repo</a>
  <a href="https://academic.oup.com/bib/article/25/5/bbae411/7745034" class="btn" target="_blank">Paper Link</a>
</div>

<!-- Add more publication entries as needed -->

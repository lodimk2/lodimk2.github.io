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
</style>
<h1> Publications </h1>
<div class="publication">
  <h3>COFFEE: consensus single cell-type specific inference for gene regulatory networks </h3>
  <p>Authors: <strong>Musaddiq K. Lodi</strong>, Anna Chernikov, Preetam Ghosh</p>
  <p>Description: Consensus regulatory network inference for single cell genomics data. </p>
  <a href="https://github.com/lodimk2/coffee" class="btn" target="_blank">GitHub Repo</a>
  <a href="https://academic.oup.com/bib/article/25/6/bbae457/7765455" class="btn" target="_blank">Paper Link</a>
</div>

<div class="publication">
  <h3>CHAI: consensus clustering through similarity matrix integration for cell-type identification </h3>
  <p>Authors:<strong>Musaddiq K. Lodi<\strong>, Muzammil Lodi, Kezie Osei, Vaishnavi Ranganathan, Priscilla Hwang, Preetam Ghosh</p>
  <p>Description: Consensus clustering through similarity matrix integration for single cell genomics data.</p>
  <a href="https://github.com/lodimk2/chai" class="btn" target="_blank">GitHub Repo</a>
  <a href="ttps://academic.oup.com/bib/article/25/5/bbae411/7745034" class="btn" target="_blank">Paper Link</a>
</div>

<!-- Add more publication entries as needed -->

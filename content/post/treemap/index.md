---
title: The Manuscript Browser
subtitle: A user-friendly approach to digital publications

# Summary for listings and search engines
summary: O 

# Link this post with a project
projects: [Making & Knowing Project]

# Date published
date: "2021-06-20T16:00:00Z"

# Date updated
lastmod: "2021-06-20T17:00:00Z"

# Is this an unpublished draft?
draft: true

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: ''
  focal_point: ""
  placement: 1
  preview_only: true

authors:
- admin

tags:
- Digital Humanities
- Data Visualization
- Archival research

categories:
- Notes
---
Digital editions suffer from a paradox: while they make complex archival fonds available to a wider public, the loss of sensorial input resulting from their dematerialization tends to disorient and discourage readers. They make the navigation of vast document repositories cumbersome, especially among users affected with cognitive impairments. However, interactive visualizations of archival metadata can provide readers with an alternative sensorial input, making digital scholarly editions more ergonomic, and accessible to a wider and neurodiverse audience.

  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title></title>
    <link rel="preconnect" href="https://fonts.gstatic.com" />
    <link
      href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;700&display=swap"
      rel="stylesheet" />
    <link rel="stylesheet" href="css/index.css" />
    <link rel="stylesheet" href="css/vis-treemap.css" />
    <link rel="stylesheet" href="css/vis-tooltip.css" />
  </head>
  <body>
    <p>Click any cell to zoom in, or the top to zoom out.</p>
    <div id="treemap"></div>
    <script src="https://d3js.org/d3.v7.min.js"></script>
    <script src="js/vis-treemap.js"></script>
    <script src="js/vis-tooltip.js"></script>
    <script src="js/index.js"></script>
  </body>
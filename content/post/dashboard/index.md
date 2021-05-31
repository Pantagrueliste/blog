---
title: The Archive at a Glance
subtitle: How interactive data visualization can enhance archival research

# Summary for listings and search engines
summary: Plotly Dash apps enable researchers to navigate the archive and make better decisions.

# Link this post with a project
projects: [Filippo Cavriana's Secret Correspondence, 1568—1589.]

# Date published
date: "2021-05-24T16:00:00Z"

# Date updated
lastmod: "2021-01-28T20:34:00Z"

# Is this an unpublished draft?
draft: true

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: ''
  focal_point: ""
  placement: 2
  preview_only: false

authors:
- admin

tags:
- Digital Humanities
- Data Visualization
- Archival research

categories:
- Notes
---

# The Problem 
Historical archives can be dauntingly messy. The *Mediceo del Principato* at the State Archives of Florence is a case in point. Indeed, only a small part of it is inventoried, and many of its documents are scattered through more than 6500 volumes for no apparent reason. To further complicate things, the archives only let you consult a limited number of volumes (or *filze* as they call them). In "normal" times, the limit is set to 4 *filze* per day. In times of pandemic, however, that number has gone down to 4 every two weeks. In the absence of detailed inventories, the archive's considerable size forces researchers to devise strategies in order to find the documents they are looking for.

# The Solution
Some may privilege chance, others will also try to make educated guesses on the grounds of chronology, addressees, authors, origin of the archival fonds, language, etc. These variables can be arbitrary, but they can also be reasonably conjectured using interactive data visualization. Indeed, the metadata researchers may gather about an archive increase situational awareness in the archive ultimately improving decision-making. Often kept as a spreadsheet, this metadata may reveal patterns or clues about the archive's structure only when it is graphed.

# Example
My current research focuses on the correspondence of a 16th-century spy. His letters are spread out through hundreds of *filze*. They are written under different identities, to different and sometimes unexpected addressees, from different places, etc. To find *filze* that are more likely to contain the expected letters, I have set-up a dashboard, an interactive data visualization web application ([Plotly Dash](https://plotly.com/dash/)) that connects geographical and chronological information with the graphic representation of the archival fonds. The dashboard tells me at a glance what has already been found, how much this represents, and gives me a rough idea of where I could possibly look for new letters.

# Next steps
Perhaps more importantly, this dashboard can be repurposed as a visual index, when the critical edition of the letters will be published on-line. It will be an alternative entry point, from where readers will be able to navigate the data. For reasons of confidentiality, I will release the dashboard when my monograph will be published. In the meantime you can look at the screenshot, and soon I will post on this blog a number of prototypes. Stay tuned!
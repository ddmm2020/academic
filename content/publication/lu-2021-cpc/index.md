---
title: "86 PFLOPS Deep Potential Molecular Dynamics simulation of 100 million atoms with ab initio accuracy"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Denghui Lu    
- Han Wang
- Mohan Chen
- Lin Lin
- Roberto Car
- Weinan E
- Weile Jia
- Linfeng Zhang
 
# Author notes (optional)
author_notes:
-  
- 
- 
- 
- 
- 
- "通讯作者"
- "通讯作者"

date: "2021-02-01T00:00:00Z"
doi: "10.17632/phyn4kgsfx.1"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-02-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Computer Physics Communications, 2021*
publication_short: In *Comput Phys Commun2021*

abstract:   Plane wave pseudopotential (PWP) density functional theory (DFT) calculation
  is the most widely used material science simulation, and the PWP DFT codes are
  arguably the most important material science codes. We have implemented a PWP
  DFT code PEtot on a multi-node GPU machine. Starting from a previous work, we
  have further improved the speed of the code, and achieved x13-x22 speedups
  over the CPU calculations for a typical 512 atom system. Such speedups are
  much higher than other similar works for this important class of material
  simulation codes on GPU clusters. The current achievement is obtained by (1)
  moving the calculation fully into the GPU; (2) adopting a new algorithm to
  reduce the data amount for MPI communication; and (3) using new GPU and CPU
  numerical libraries. We have also provided a detail quantitative analysis of
  the computational times for different physical systems and number of GPU
  units, which helps one to understand the challenges and bottlenecks of the PWP
  DFT simulations on GPU machines. Based on the analysis, we listed the machine
  and library requirements in order to further improve the performances of the
  PWP DFT calculations.

# Summary. An optional shortened abstract.
summary: ""

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---



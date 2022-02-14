---
title: "Fast real-time time-dependent density functional theory calculations with the parallel transport gauge"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Weile Jia    
- Dong An
- Lin-Wang Wang
- Lin Lin


 
# Author notes (optional)
author_notes:
-  
- 
- 
- "通讯作者"

date: "2018-10-23T00:00:00Z"
doi: "https://doi.org/10.1021/acs.jctc.8b00580"

# Schedule page publish date (NOT publication's date).
publishDate: "2018-10-23T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Computer Physics Communications, 2021*
publication_short: In *Comput Phys Commun2021*

abstract:  Real-time time-dependent density functional theory (RT-TDDFT) is known to be
  hindered by the very small time step (attosecond or smaller) needed in the
  numerical simulation, because of the fast oscillation of electron wave
  functions, which significantly limits its range of applicability for the study
  of ultrafast dynamics. In this paper, we demonstrate that such oscillation can
  be considerably reduced by optimizing the gauge choice using the parallel
  transport formalism. RT-TDDFT calculations can thus be significantly
  accelerated using a combination of the parallel transport gauge and implicit
  integrators, and the resulting scheme can be used to accelerate any electronic
  structure software that uses a Schrödinger representation. Using absorption
  spectrum, ultrashort laser pulse, and Ehrenfest dynamics calculations for
  example, we show that the new method can utilize a time step that is on the
  order of 10–100 attoseconds using a planewave basis set. Thanks to the
  significant increase of the size of the time step, we also demonstrate that
  the new method is more than 10 times faster, in terms of the wall clock time,
  when compared to the standard explicit fourth-order Runge–Kutta time
  integrator for silicon systems ranging from 32 to 1024 atoms.

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



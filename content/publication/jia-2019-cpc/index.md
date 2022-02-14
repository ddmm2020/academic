---
title: "Fast real-time time-dependent hybrid functional calculations with the parallel transport gauge and the adaptively compressed exchange formulation."

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Weile Jia 
- Lin Lin
 
# Author notes (optional)
author_notes:
- 
- "通讯作者"

date: "2019-07-01T00:00:00Z"
doi: "https://doi.org/10.1016/j.cpc.2019.02.009"

# Schedule page publish date (NOT publication's date).
publishDate: "2019-07-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Computer Physics Communications, 2019*
publication_short: In *Comput Phys Commun2019*

abstract:     We present a new method to accelerate real-time time-dependent density
  functional theory (rt-TDDFT) calculations with hybrid exchange–correlation
  functionals. In the context of a large basis set such as planewaves and real
  space grids, the main computational bottleneck for large scale calculations is
  the application of the Fock exchange operator to the time-dependent orbitals.
  Our main goal is to reduce the frequency of applying the Fock exchange
  operator, without loss of accuracy. We achieve this by combining the recently
  developed parallel transport (PT) gauge formalism (Jia et al. J. Chem. Theory
  Comput. 2018) and the adaptively compressed exchange operator (ACE) formalism
  (Lin, J. Chem. Theory Comput. 2016). The PT gauge yields the slowest possible
  dynamics among all choices of gauge. When coupled with implicit time
  integrators such as the Crank–Nicolson (CN) scheme, the resulting PT–CN scheme
  can significantly increase the time step from sub-attoseconds to  attoseconds.
  At each time step , PT–CN requires the self-consistent solution of the
  orbitals at time . We use ACE to delay the update of the Fock exchange
  operator in this nonlinear system, while maintaining the same self-consistent
  solution. We verify the performance of the resulting PT–CN–ACE method by
  computing the absorption spectrum of a benzene molecule and the response of
  bulk silicon systems to an ultrafast laser pulse, using the planewave basis
  set and the HSE exchange–correlation functional. We report the strong and weak
  scaling of the PT–CN–ACE method for silicon systems ranging from 32 to 1024
  atoms, on a parallel computer with up to 2048 computational cores. Compared to
  standard explicit time integrators such as the  order Runge–Kutta method
  (RK4), we find that the PT–CN–ACE can reduce the frequency of the Fock
  exchange operator application by nearly 70 times, and the thus reduce the
  overall wall clock time by 46 times for the system with 1024 atoms. Hence our
  work enables hybrid functional rt-TDDFT calculations to be routinely performed
  with a large basis set for the first time.

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



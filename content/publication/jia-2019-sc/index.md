---
title: "Parallel transport time-dependent density functional theory calculations with hybrid functional on summit"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Weile Jia        
- Lin-Wang Wang    
- Lin Lin    
 

date: "2019-11-17T00:00:00Z"
doi: "10.1109/SC41405.2020.00009"

# Schedule page publish date (NOT publication's date).
publishDate: "2019-11-17T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *International Conference for High Performance Computing, Networking, Storage and Analysis, 2019*
publication_short: In *SC2019*

abstract:   Real-time time-dependent density functional theory (rt-TDDFT) with hybrid
  exchange-correlation functional has wide-ranging applications in chemistry and
  material science simulations. However, it can be thousands of times more
  expensive than a conventional ground state DFT simulation, and hence is
  limited to small systems. In this paper, we accelerate hybrid functional
  rt-TDDFT calculations using the parallel transport gauge formalism, and the
  GPU implementation on Summit. Our implementation can efficiently scale to 786
  GPUs for a large system with 1536 silicon atoms, and the wall clock time is
  only 1.5 hours per femtosecond. This unprecedented speed enables the
  simulation of large systems with more than 1000 atoms using rt-TDDFT and
  hybrid functional.

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



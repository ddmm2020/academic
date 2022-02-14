---
title: "Extending the limit of molecular dynamics with ab initio accuracy to 10 billion atoms"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Zhuoqiang Guo
- Denghui Lu
- Yujin Yan
- Siyu Hu
- Rongrong Liu
- Guangming Tan
- Ninghui Sun
- Wanrun Jiang
- Lijun Liu
- Yixiao Chen
- Linfeng Zhang
- Mohan Chen
- Han Wang
- Weile Jia    
 
# Author notes (optional)
author_notes:
- []

date: "2022-01-05T00:00:00Z"
doi: "10.1145/3503221.3508425"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-01-05T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Principles and Practice of Parallel Programming 2022*
publication_short: In *PPoPP 2022*

abstract:   High-performance computing, together with a neural network model trained from
  data generated with first-principles methods, has greatly boosted applications
  of ab initio molecular dynamics in terms of spatial and temporal scales on
  modern supercomputers. Previous state-of-the-art can achieve 1 − 2 nanoseconds
  molecular dynamics simulation per day for 100-million atoms on the entire
  Summit supercomputer. In this paper, we have significantly reduced the memory
  footprint and computational time by a comprehensive approach with both
  algorithmic and system innovations. The neural network model is compressed by
  model tabulation, kernel fusion, and redundancy removal. Then optimizations
  such as acceleration of customized kernel, tabulation of activation function,
  MPI+OpenMP parallelization are implemented on GPU and ARM architectures.
  Testing results of the copper system show that the optimized code can scale up
  to the entire machine of both Fugaku and Summit, and the corresponding system
  size can be extended by a factor of 134 to an unprecedented 17 billion atoms.
  The strong scaling of a 13.5- million atom copper system shows that the
  time-to-solution can be 7 times faster, reaching 11.2 nanoseconds per day.
  This work opens the door for unprecedentedly large-scale molecular dynamics
  simulations based on ab initio accuracy and can be potentially utilized in
  studying more realistic applications such as mechanical properties of metals,
  semiconductor devices, batteries, etc. The optimization techniques detailed in
  this paper also provide insight for relevant high-performance computing
  applications.

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



---
title: "Pushing the limit of molecular dynamics with ab initio accuracy to 100 million atoms with machine learning"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Weile Jia∗
- Han Wang
- Mohan Chen
- Denghui Lu
- Lin Lin
- Roberto Car
- Weinan E
- Linfeng Zhang
 
# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2020-11-01T00:00:00Z"
doi: "10.1109/SC41405.2020.00009"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-11-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *International Conference for High Performance Computing, Networking, Storage and Analysis, 2020*
publication_short: In *SC2020*

abstract: For 35 years, ab initio molecular dynamics (AIMD)
has been the method of choice for modeling complex atomistic phenomena from first principles. However, most AIMD
applications are limited by computational cost to systems with
thousands of atoms at most. We report that a machine learningbased simulation protocol (Deep Potential Molecular Dynamics),
while retaining ab initio accuracy, can simulate more than 1
nanosecond-long trajectory of over 100 million atoms per day,
using a highly optimized code (GPU DeePMD-kit) on the Summit
supercomputer. Our code can efficiently scale up to the entire
Summit supercomputer, attaining 91 PFLOPS in double precision
(45.5% of the peak) and 162/275 PFLOPS in mixed-single/half
precision. The great accomplishment of this work is that it opens
the door to simulating unprecedented size and time scales with ab
initio accuracy. It also poses new challenges to the next-generation
supercomputer for a better integration of machine learning and
physical modeling.

# Summary. An optional shortened abstract.
summary: ""

tags: []

# Display this page in the Featured widget?
featured: False

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/9355242/'
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

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).

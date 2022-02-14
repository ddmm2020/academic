---
title: "Robust determination of the chemical potential in the pole expansion and selected inversion method for solving Kohn-Sham density functional theory"

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

date: "2017-10-11T00:00:00Z"
doi: "https://doi.org/10.1063/1.5000255"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-10-11T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *The Journal of Chemical Physics, 2017*
publication_short: In *J. Chem. Phys2017*

abstract:  Fermi operator expansion (FOE) methods are powerful alternatives to diagonalization type methods for solving Kohn-Sham density functional theory (KSDFT). One example is the pole expansion and selected inversion (PEXSI) method, which approximates the Fermi operator by rational matrix functions and reduces the computational complexity to at most quadratic scaling for solving KSDFT. Unlike diagonalization type methods, the chemical potential often cannot be directly read off from the result of a single step of evaluation of the Fermi operator. Hence multiple evaluations are needed to be sequentially performed to compute the chemical potential to ensure the correct number of electrons within a given tolerance. This hinders the performance of FOE methods in practice. In this paper, we develop an efficient and robust strategy to determine the chemical potential in the context of the PEXSI method. The main idea of the new method is not to find the exact chemical potential at each self-consistent-field (SCF) iteration but to dynamically and rigorously update the upper and lower bounds for the true chemical potential, so that the chemical potential reaches its convergence along the SCF iteration. Instead of evaluating the Fermi operator for multiple times sequentially, our method uses a two-level strategy that evaluates the Fermi operators in parallel. In the regime of full parallelization, the wall clock time of each SCF iteration is always close to the time for one single evaluation of the Fermi operator, even when the initial guess is far away from the converged solution. We demonstrate the effectiveness of the new method using examples with metallic and insulating characters, as well as results from ab initio molecular dynamics.

# Summary. An optional shortened abstract.
summary: ""

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://aip.scitation.org/doi/pdf/10.1063/1.5000255'
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



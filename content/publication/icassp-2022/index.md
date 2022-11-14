---
title: 'From Shallow to Deep: Compositional Reasoning over Graphs for Visual Question Answering'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-04-01'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-04-01'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *IEEE International Conference on Acoustics, Speech and Signal Processing 2022*
publication_short: In *ICASSP 2022*

abstract: In order to achieve a general visual question answering (VQA) system, it is essential to learn to answer deeper questions that require compositional reasoning on the image and external knowledge. Meanwhile, the reasoning process should be explicit and explainable to understand the working mechanism of the model. It is effortless for human but challenging for machines. In this paper, we propose a Hierarchical Graph Neural Module Network (HGNMN) that reasons over multi-layer graphs with neural modules to address the above issues. Specifically, we first encode the image by multi-layer graphs from the visual, semantic and commonsense views since the clues that support the answer may exist in different modalities. Our model consists of several well-designed neural modules that perform specific functions over graphs, which can be used to conduct multi-step reasoning within and between different graphs. Compared to existing modular networks, we extend visual reasoning from one graph to more graphs. We can explicitly trace the reasoning process according to module weights and graph attentions. Experiments show that our model not only achieves state-of-the-art performance on the CRIC dataset but also obtains explicit and explainable reasoning procedures.
# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: ''
# url_code: 'https://github.com/SCLBD/backdoorbench'
# url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_poster: ''
# url_project: 'https://backdoorbench.github.io'
# url_slides: ''
# url_source: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
<!-- 
{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->

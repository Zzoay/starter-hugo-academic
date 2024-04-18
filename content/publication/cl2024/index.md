---
title: 'LLM-Assisted Data Augmentation for Chinese Dialogue-Level Dependency Parsing'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Meishan Zhang
  - admin
  - Shuang Liu
  - Jing Chen
  - Min Zhang

# Author notes (optional)
author_notes:
  # - 'Equal contribution'

# date: '2013-07-01T00:00:00Z'
date: '2024-03-12'
doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'
publishDate: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Computational Linguistics  (2024)*
# publication_short: In *Computational Linguistics*

abstract: Dialogue-level dependency parsing, despite its growing academic interest, often encounters underperformance issues due to resource shortages. A potential solution to this challenge is data augmentation. In recent years, large language models (LLMs) have demonstrated strong capabilities in generation which can facilitate data augmentation greatly. In this study, we focus on Chinese dialogue-level dependency parsing, presenting three simple and effective strategies with LLM to augment the original training instances, namely word-level, syntax-level and discourse-level augmentations, respectively. These strategies enable LLMs to either preserve or modify dependency structures, thereby assuring accuracy while increasing the diversity of instances at different levels.We conduct experiments on the benchmark dataset released by Jiang et al. (2023) to validate our approach. Results show that our method can greatly boost the parsing performance in various settings, particularly in dependencies among elementary discourse units (EDUs). Lastly, we provide in-depth analysis to show the key points of our data augmentation strategies.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: ['Dependency Parsing', 'Natural Language Processing', 'Large Language Model']

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://direct.mit.edu/coli/article/doi/10.1162/coli_a_00515/120014/LLM-Assisted-Data-Augmentation-for-Chinese'
url_code: 'https://github.com/Zzoay/DialogDepAug'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
# url_source: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
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

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->

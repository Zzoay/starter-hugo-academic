---
title: "Fake news detection via knowledgeable prompt learning"
authors:
- admin
- Shuang Liu
- Yu Zhao
- Yueheng Sun
- Meishan Zhang
author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2022-09-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-09-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "In *Information Processing & Management, 2022*"
# publication_short: "IPM"

abstract: The spread of fake news has become a significant social problem, drawing great concern for fake news detection (FND). Pretrained language models (PLMs), such as BERT and RoBERTa can benefit this task much, leading to state-of-the-art performance. The common paradigm of utilizing these PLMs is fine-tuning, in which a linear classification layer is built upon the well-initialized PLM network, resulting in an FND mode, and then the full model is tuned on a training corpus. Although great successes have been achieved, this paradigm still involves a significant gap between the language model pretraining and target task fine-tuning processes. Fortunately, prompt learning, a new alternative to PLM exploration, can handle the issue naturally, showing the potential for further performance improvements. To this end, we propose knowledgeable prompt learning (KPL) for this task. First, we apply prompt learning to FND, through designing one sophisticated prompt template and the corresponding verbal words carefully for the task. Second, we incorporate external knowledge into the prompt representation, making the representation more expressive to predict the verbal words. Experimental results on two benchmark datasets demonstrate that prompt learning is better than the baseline fine-tuning PLM utilization for FND and can outperform all previous representative methods. Our final knowledgeable model (i.e, KPL) can provide further improvements. In particular, it achieves an average increase of 3.28% in F1 score under low-resource conditions compared with fine-tuning.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Fake News Detection
- Prompt Learning
- Few-shot Learning
- Natural Language Processing
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://www.sciencedirect.com/science/article/abs/pii/S030645732200139X'
url_code: 'https://github.com/Zzoay/disinformation_detection'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->

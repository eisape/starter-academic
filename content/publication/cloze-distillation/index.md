---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Cloze Distillation Improves Psychometric Predictive Power"
authors: [Tiwalayo Eisape, Noga Zaslavsky, Roger Levy]
date: 2020-09-21T09:51:54-04:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-09-21T09:51:54-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Cloze Distillation Improves Psychometric Predictive Power"
publication_short: ""

abstract: "Training models on next word prediction (NWP) has led to significant developments in general-purpose language models (LMs). However, this objective lacks cognitive motivation under theories of language processing that show human prediction to be graded, parallel, and scaffolded. Here, we present new evidence that challenge the ability of the NWP task to generate LMs with human-like predictive capacities. First, we compare state-of-the-art transformer LMs with a simple LSTM model, and show that while the transformer models achieve better performance in both NWP and prediction of human cloze completions for the Provo corpus, the LSTM model provides a better account of human reading times on the same corpus. This reveals a disassociation between human language processing and NWP.
On that basis, we propose Cloze Distillation: a novel method for distilling the linguistic information that is implicit in human cloze completions into pre-trained LMs. We apply this method to the LSTM model and show substantial improvement in reading time prediction, word frequency estimation, and generalization to held-out human cloze data. Our results identify the direct modeling of human psychometric data as an effective potential method for creating more psychometrically-valid LMs."

# Summary. An optional shortened abstract.
summary: ""

tags: [Deep Learning, NLP, Prediction]
categories: [Artificial Intelligence]
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf:
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

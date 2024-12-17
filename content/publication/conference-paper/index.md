---
title: 'Scaffold Splits Overestimate Virtual Screening Performance'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Saiveth Hernandez-Hernandez
  - Pedro J. Ballester

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-09-18T00:00:00Z'
doi: 'https://doi.org/10.1007/978-3-031-72359-9_5'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-09-18T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Artificial Neural Networks and Machine Learning*
publication_short: In *ICANN 2024*

# abstract: Virtual Screening (VS) of vast compound libraries guided by Artificial Intelligence (AI) models is a highly productive approach to early drug discovery. Data splitting is crucial for better benchmarking of such AI models. Traditional random data splits produce similar molecules between training and test sets, conflicting with the reality of VS libraries which mostly contain structurally distinct compounds. Scaffold split, grouping molecules by shared core structure, is widely considered to reflect this real-world scenario. However, here we show that the scaffold split also overestimates VS performance. The reason is that molecules with different chemical scaffolds are often similar, which hence introduces unrealistically high similarities between training molecules and test molecules following a scaffold split. Our study examined three representative AI models on 60 NCI-60 datasets, each with approximately 30,000 to 50,000 molecules tested on a different cancer cell line. Each dataset was split with three methods: scaffold, Butina clustering and the more accurate Uniform Manifold Approximation and Projection (UMAP) clustering. Regardless of the model, model performance is much worse with UMAP splits from the results of the 2100 models trained and evaluated for each algorithm and split. These robust results demonstrate the need for more realistic data splits to tune, compare, and select models for VS. For the same reason, avoiding the scaffold split is also recommended for other molecular property prediction problems. The code to reproduce these results is available at https://github.com/ScaffoldSplitsOverestimateVS

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://github.com/user-attachments/files/16088126/Qianrong_ScaffoldSplitsOverestimateVirtualScreeningPerformance.1.pdf'
url_code: 'https://github.com/ScaffoldSplitsOverestimateVS'
# url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
url_poster: ''
# url_project: ''
# url_slides: ''
url_source: 'https://link.springer.com/chapter/10.1007/978-3-031-72359-9_5'
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
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
# slides: ""
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

<!-- {{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->

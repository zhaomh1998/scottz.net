---
title: 'Anemoi: A Low-cost Sensorless Indoor Drone System for Automatic Mapping of 3D Airflow Fields'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Stephen Xia
  - Charuvahan Adhivarahan
  - Kaiyuan Hou
  - Yuyang Chen
  - Jingping Nie
  - Eugene Wu
  - Karthik Dantu
  - Xiaofan (Fred) Jiang

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2023-10-02T00:00:00Z'
doi: '10.1145/3570361.3613292'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 29th Annual International Conference on Mobile Computing And Networking*
publication_short: In *MobiCom '23*

abstract: Mapping 3D airflow fields is important for many HVAC, industrial, medical, and home applications. However, current approaches are expensive and time-consuming. We present Anemoi, a sub-$100 drone-based system for autonomously mapping 3D airflow fields in indoor environments. Anemoi leverages the effects of airflow on motor control signals to estimate the magnitude and direction of wind at any given point in space. We introduce an exploration algorithm for selecting optimal waypoints that minimize overall airflow estimation uncertainty. We demonstrate through microbenchmarks and real deployments that Anemoi is able to estimate wind speed and direction with errors up to 0.41 m/s and 25.1 degree lower than the existing state of the art and map 3D airflow fields with an average RMS error of 0.73 m/s.

# Summary. An optional shortened abstract.
summary: Anemoi's sub-$100 drone-based system autonomously maps 3D indoor airflow fields without the need for any external sensor, leveraging airflow effects on motor control signals and outperforming existing methods with significantly reduced errors in wind speed and direction estimation.

tags: []

# Display this page in the Featured widget?
featured: true

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
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

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
slides: ""
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).

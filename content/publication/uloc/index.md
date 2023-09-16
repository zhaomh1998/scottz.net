---
title: 'ULoc: Low-Power, Scalable and cm-Accurate UWB-Tag Localization and Tracking for Indoor Applications'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Tyler Chang
  - Aditya Arun
  - Roshan Ayyalasomayajula
  - Chi Zhang
  - Dinesh Bharadia

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2021-09-14T00:00:00Z'
doi: '10.1145/3478124'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies*
publication_short: In *IMWUT / Ubicomp 2021*

abstract: A myriad of IoT applications, ranging from tracking assets in hospitals, logistics, and construction industries to indoor tracking in large indoor spaces, demand centimeter-accurate localization that is robust to blockages from hands, furniture, or other occlusions in the environment. With this need, in the recent past, Ultra Wide Band (UWB) based localization and tracking has become popular. Its popularity is driven by its proposed high bandwidth and protocol specifically designed for localization of specialized "tags". This high bandwidth of UWB provides a fine resolution of the time-of-travel of the signal that can be translated to the location of the tag with centimeter-grade accuracy in a controlled environment. Unfortunately, we find that high latency and high-power consumption of these time-of-travel methods are the major culprits which prevent such a system from deploying multiple tags in the environment. Thus, we developed ULoc, a scalable, low-power, and cm-accurate UWB localization and tracking system. In ULoc, we custom build a multi-antenna UWB anchor that enables azimuth and polar angle of arrival (henceforth shortened to '3D-AoA') measurements, with just the reception of a single packet from the tag. By combining multiple UWB anchors, ULoc can localize the tag in 3D space. The single-packet location estimation reduces the latency of the entire system by at least 3×, as compared with state of art multi-packet UWB localization protocols, making UWB based localization scalable. ULoc's design also reduces the power consumption per location estimate at the tag by 9×, as compared to state-of-art time-of-travel algorithms. We further develop a novel 3D-AoA based 3D localization that shows a stationary localization accuracy of 3.6 cm which is 1.8× better than the state-of-the-art two-way ranging (TWR) systems. We further developed a temporal tracking system that achieves a tracking accuracy of 10 cm in mobile conditions which is 4.3× better than the state-of-the-art TWR systems.

# Summary. An optional shortened abstract.
summary: ULoc’s design uses 3D Angle of Arrival (AoA) to estimate low-power, low-latency, cm-accurate UWB tag location, a shift from traditional timing-based methods.


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
url_video: 'https://youtube.com'

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

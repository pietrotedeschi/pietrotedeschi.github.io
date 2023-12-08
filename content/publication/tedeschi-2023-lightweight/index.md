---
title: 'Lightweight Privacy-Preserving Proximity Discovery for Remotely-Controlled Drones'

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Pietro Tedeschi
- Savio Sciancalepore
- Roberto Di Pietro

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2023-12-04'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2023-12-07T07:05:01.235747Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- paper-conference

# Publication name and optional abbreviated publication name.
publication: '*ACSAC 23 - Annual Computer Security Applications Security Conference*'
publication_short: ''

doi: '10.1145/3627106.3627174'

abstract: 'Discovering mutual proximity and avoiding collisions is one of the most critical services needed by the next generation of Unmanned Aerial Vehicles (UAVs). However, currently available solutions either rely on sharing mutual locations, neglecting the location privacy of involved parties, or are applicable for fully autonomous vehicles only—leaving unaddressed Remotely-Piloted UAVs’ safety needs. Alternatively, proximity can be discovered by adding sensing capabilities. However, in addition to the cost of the sensors, the complexity of integration, and the toll on the energy budget, the effectiveness of such solutions is usually limited by short detection ranges, making them hardly useful in high-mobility scenarios. In this paper, we propose LPPD (an acronym for Lightweight Privacy-preserving Proximity Discovery), a unique solution for privacy-preserving proximity discovery among remotely piloted UAVs based on the exchange of wireless messages. LPPD integrates two main building blocks: (i) a custom space tessellation technique based on randomized spheres; and, (ii) a lightweight cryptographic primitive for private-set intersection. Another feature enjoyed by LPPD is that it does not require online third parties. LPPD is rooted in sound theoretical results and is supported by an experimental assessment performed on a real drone. In particular, experimental results show that LPPD achieves 100% proximity discovery while taking only 39.66 milliseconds in the most lightweight configuration and draining only the 5 · 10− 6% of the UAV’s battery capacity. In addition, LPPD’s security properties are formally verified.'

# Summary. An optional shortened abstract.
summary: ''

tags: []

# Display this page in a list of Featured pages?
featured: true

# Links
url_pdf: 'https://dl.acm.org/doi/pdf/10.1145/3627106.3627174'
url_code: 'https://github.com/pietrotedeschi/lppd/'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# Publication image
# Add an image named `featured.jpg/png` to your page's folder then add a caption below.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects: ['internal-project']` links to `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
---
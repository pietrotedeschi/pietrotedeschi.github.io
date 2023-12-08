---
title: 'PPCA-Privacy-Preserving Collision Avoidance for Autonomous Unmanned Aerial Vehicles'

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

date: '2022-03-16'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2023-12-07T07:05:01.201645Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Dependable and Secure Computing*'
publication_short: ''

doi: '10.1109/TDSC.2022.3159837'

abstract: 'Current collision avoidance techniques deployed on Unmanned Aerial Vehicles (UAVs) rely on short-range sensors, such as proximity sensors, cameras, and microphones. Unfortunately, their efficiency is significantly limited in several situations; for instance, when a remote UAV approaches at high velocity, or when the surrounding environment is impaired (e.g., fog, noise). In the cited cases, to avoid collisions and maintain self-separation, UAVs often rely on the indiscriminate broadcast of their location. Therefore, an adversary could easily identify the location of the UAV and attack it, e.g., by physically shutting it down, launching wireless jamming attacks, or continuing tracking its movements. To address the above-introduced threats, in this article we present PPCA, a lightweight, distributed, and privacy-preserving scheme to avoid collisions among UAVs. Our solution, based on an ingenious tessellation of the space, is accompanied by a thorough analytical model and is supported by an extensive experimental campaign performed on a real 3DR-Solo drone. The achieved results are striking: PPCA can efficiently and effectively avoid collisions among UAVs, by requiring a limited bandwidth and computational overhead (84.85% less than traditional privacy-preserving proximity testing approaches), while providing unique benefits in terms of privacy of the participating UAVs.'

# Summary. An optional shortened abstract.
summary: ''

tags: []

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: 'https://ieeexplore.ieee.org/abstract/document/9736583/'
url_code: 'https://github.com/pietrotedeschi/ppca'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=2LW_ZFk6ZS0'

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# Publication image
# Add an image named `featured.jpg/png` to your page's folder then add a caption below.
image:
  caption: 'Privacy-Preserving Collision Avoidance for Autonomous Unmanned Aerial Vehicles'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects: ['internal-project']` links to `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
---
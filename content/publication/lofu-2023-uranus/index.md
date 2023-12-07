---
title: 'URANUS: Radio Frequency Tracking, Classification and Identification of Unmanned Aircraft Vehicles'

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Domenico Lofù
- Pietro Di Gennaro
- Pietro Tedeschi
- Tommaso Di Noia
- Eugenio Di Sciascio

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2023-11-17'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2023-12-07T07:05:01.209263Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Open Journal of Vehicular Technology*'
publication_short: ''

doi: '10.1109/OJVT.2023.3333676'

abstract: 'Safety and security issues for Critical Infrastructures are growing as attackers adopt drones as an attack vector flying in sensitive airspaces, such as airports, military bases, city centers, and crowded places. Despite the use of UAVs for logistics, shipping recreation activities, and commercial applications, their usage poses severe concerns to operators due to the violations and the invasions of the restricted airspaces. A cost-effective and real-time framework is needed to detect the presence of drones in such cases. In this contribution, we propose an efficient radio frequency-based detection framework called URANUS. We leverage real-time data provided by the Radio Frequency/Direction Finding system, and radars in order to detect, classify and identify drones (multi-copter and fixed-wings) invading no-drone zones. We adopt a Multilayer Perceptron neural network to identify and classify UAVs in real-time, with 90% accuracy. For the tracking task, we use a Random Forest model to predict the position of a drone with an MSE≈0.29, MAE≈0.04, and R2≈0.93. Furthermore, coordinate regression is performed using Universal Transverse Mercator coordinates to ensure high accuracy. Our analysis shows that URANUS is an ideal framework for identifying, classifying, and tracking UAVs that most Critical Infrastructure operators can adopt.'

# Summary. An optional shortened abstract.
summary: ''

tags: []

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: 'https://ieeexplore.ieee.org/document/10320374'
url_code: 'https://github.com/pdigennaro/uranus2/'
url_dataset: 'https://github.com/pdigennaro/uranus2/tree/main/datasets'
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

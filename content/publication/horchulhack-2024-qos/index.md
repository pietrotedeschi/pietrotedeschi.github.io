---
title: Detection of quality of service degradation on multi-tenant containerized services

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Pietro Tedeschi

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-02-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-02-01T07:05:01.213124Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Elsevier Journal of Network and Computer Applications*'
publication_short: ''

doi: '10.1016/j.jnca.2024.103839'

abstract: 'Computational services are progressively migrating to container-based solutions due to their faster provision time and lower resource allocation overhead. Service providers rely on container multi-tenancy to share their computing infrastructure and pave their way to profit. Yet, the Quality of Service (QoS) impact due to container multi-tenancy on deployed services is still widely overlooked in the literature. This paper proposes a new service provider monitoring model for detecting container multi-tenancy that can lead to QoS degradation, split into two phases. First, we monitor the container resource usage through the container engine and the associated process namespace, thus, keeping container isolation. The main assumption is that the assessment of resource utilization, as measured by the container engine, should be complemented by the concurrent reporting of resource utilization from the container processes. Second, we detect QoS degradation of distributed containerized services through a time-series classification approach coped with a feature reduction technique. The feature reduction selects the prominent performance features from the deployed distributed service, whereas the time-series classifier ensures the evaluation of the deployed service over time, improving the system detection accuracy. Thanks to an extensive experimental assessment considering a containerized distributed Big Data processing platform, we show that container multi-tenancy can affect the processing performance and the QoS of deployed services. In addition, we show that the proposed model can detect QoS degradation at the service provider domain with a true-positive rate up to 90%, a false-positive rate of 8%, and an average F1-Score up to 0.94.'

# Summary. An optional shortened abstract.
summary: ''

tags: []

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: 'https://www.sciencedirect.com/science/article/abs/pii/S108480452400016X'
url_code: ''
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

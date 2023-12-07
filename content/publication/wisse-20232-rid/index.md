---
title: $A^ 2RID$--Anonymous Direct Authentication and Remote Identification of Commercial Drones

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Eva Wisse
- Pietro Tedeschi
- Savio Sciancalepore
- Roberto Di Pietro

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2023-01-30'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2023-12-07T07:05:01.213124Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Internet of Things Journal*'
publication_short: ''

doi: '10.1109/JIOT.2023.3240477'

abstract: 'The recent worldwide introduction of RemoteID (RID) regulations forces all unmanned aircrafts (UAs), also known as drones, to broadcast in plaintext on the wireless channel their identity and real-time location, for accounting and monitoring purposes. Although improving drones’ monitoring and situational awareness, the RID rule also generates significant privacy concerns for UAs’ operators, threatened by the ease of tracking of UAs and related confidentiality and privacy concerns connected with the broadcasting of plaintext identity information. In this article, we propose anonymous direct authentication and remote identification ( A2RID ), a protocol suite for A2RID of heterogeneous commercial UAs. A2RID integrates and adapts protocols for anonymous message signing to work in the UA domain, coping with the constraints of commercial drones and the tight real-time requirements imposed by the RID regulation. Overall, the protocols in the A2RID suite allow a UA manufacturer to pick the configuration that best suits the capabilities and constraints of the drone, i.e., either a processing-intensive but memory-lightweight solution (namely, CS−A2RID ) or a computationally friendly but memory-hungry approach (namely, DS−A2RID ). Besides formally defining the protocols and formally proving their security in our setting, we also implement and test them on real heterogeneous hardware platforms, i.e., the Holybro X-500 and the ESPcopter, releasing open-source the produced code. For all the protocols, we demonstrated experimentally the capability of generating anonymous RemoteID messages well below the time bound of 1 s required by RID, while at the same time having quite a limited impact on the energy budget of the drone.'

# Summary. An optional shortened abstract.
summary: ''

tags: []

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: 'https://ieeexplore.ieee.org/abstract/document/10029376'
url_code: 'https://github.com/pietrotedeschi/arid2'
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

---
title: Policy Verification Using Metagraphs

event: XX International School on Foundations of Security Analysis and Design
event_url: https://sites.google.com/uniurb.it/fosad/home/fosad20

location: Bertinoro
address:
  street: Via Frangipane 6
  city: Bertinoro
  region: Emilia-Romagna
  postcode: 47032
  country: Italy

summary: ""
abstract: "Business processes can be modeled as workflows, where the owner of the data at risk interacts with contractors to realize a sequence of tasks on the data to be secured.

In practice, access control is an essential building block to deploy these secured workflows.
This component is generally managed by administrators using high-level policies meant to represent the requirements and restrictions put on the workflow.
Handling access control with a high-level scheme comes with the benefit of separating the problem of specification, i.e. defining the desired behavior of the system, from the problem of implementation, i.e. enforcing this desired behavior.
However, translating such high-level policies into a deployed implementation can be error-prone.

Even though semi-automatic and automatic tools have been proposed to assist this translation, policy verification remains highly challenging in practice.
In this paper, our aim is to define and propose constructs assisting the checking and correction of potential errors introduced on the ground due to a faulty translation or corrupted deployments.
In particular, we investigate structures with formal foundations able to naturally model policies.
Metagraphs, a generalized graph theoretic structure, fulfill those requirements: their usage enables to compare high-level policies to their implementation (in practice we consider Rego as a valuable representative of most common policy languages).
We propose a suite of tools transforming and checking policies as metagraphs, and use them in a global framework to show how policy verification can be achieved with such constructs.
Finally, we evaluate the performance of our verification method."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2021-08-31T17:15:00"
date_end: "2021-08-31T17:35:00"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2021-08-31T00:00:00Z"

authors: [Loïc Miller, Pascal Mérindol, Antoine Gallais, Cristel Pelsser]
tags: [Policy verification, Metagraphs, Policy modeling, Rego, Access control, Authorization]

# Is this a featured talk? (true/false)
featured: false

image:
  caption: ""
  focal_point: ""

#links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: "policy-verification-using-metagraphs-slides.pdf"
url_video: ""

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

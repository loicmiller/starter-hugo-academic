---
title: "Securing Workflows Using Microservices and Metagraphs"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Pascal Mérindol
  - Antoine Gallais
  - Cristel Pelsser

# Author notes (optional)
#author_notes:
#  - "Equal contribution"
#  - "Equal contribution"

date: "2021-12-11"
doi: "https://doi.org/10.3390/electronics10243087"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-12-11T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "[Multidisciplinary Digital Publishing Institute](https://www.mdpi.com/) (MDPI)"
publication_short: In *MDPI*

abstract: "Companies such as Netflix increasingly use the cloud to deploy their business processes.
Those processes often involve partnerships with other companies, and can be modeled as workflows where the owner of the data at risk interacts with contractors to realize a sequence of tasks on the data to be secured.
In this paper, we first show how those workflows can be deployed and enforced while preventing data exposure.
Second, this paper provides a global framework to enable the verification of workflow policies.
Following the principles of zero-trust, we develop an infrastructure using the isolation provided by a microservice architecture to enforce owner policy.
We implement a workflow with our infrastructure in a publicly available proof of concept.
This work allows us to verify that the specified policy is correctly enforced by testing the deployment for policy violations, and find the overhead cost of authorization to be reasonable for the benefits.
In addition, this paper presents a way to verify policies using a suite of tools transforming and checking policies as metagraphs.
It is evident from the results that our verification method is very efficient regarding the size of the policies.
Overall, this infrastructure and the mechanisms that verify the policy is correctly enforced, and then correctly implemented, help us deploy workflows in the cloud securely."

# Summary. An optional shortened abstract.
summary: ""

tags: [Data leak, Workflow, Microservices, Authorization, Access Control, Policy Verification, Metagraphs, YAWL, Rego]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ""
url_code: ""
url_dataset: ""
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
#image:
#  caption: "Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)"
#  focal_point: ""
#  preview_only: false

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

<!--
{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}
-->

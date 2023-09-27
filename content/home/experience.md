---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Software Engineer
    company: Trilogy Innovations (Codenation)
    company_url: ''
    company_logo: org-x
    location: Dubai/Online
    date_start: '2022-08-01'
    date_end: '2023-05-05'
    description: |2-
        - Process Best Practices
        	- A platform for internal project management that serves as a repository for various batteries included’ project templates.
        	- Worked on platform integration with Google, GitHub and AWS APIs for user authentication and project level resource creation and deletion.
        	- Authored the React project template and integrated the Open-Chakra template developed by another team to be accessible via the platform.
        - Engine Yard Kontainers
        	- Worked on the implementation of multi-tenancy for the EYK Kubernetes cluster offering and suggested architectural changes for the same.
        	- Did comparative feature analysis of various cloud deployment offerings provided by cloud providers as well as solutions for building event-driven applications in Kubernetes ecosystem such as KEDA and KNative.
        	- Analysed the metrics collection system in the cluster offering to identify and discard the redundant metrics and bring down costs.
        - Devflows Compiler
        	- A proposed compiler for optimizing the architecture used for flow execution in DevFlows based on JIT compilation techniques.
        	- Used Apache NiFi to handle execution of multiple flow nodes within a single AWS Lambda instance.
  - title: Full Stack Developer (Intern)
    company: Couture.ai
    company_url: ''
    company_logo: org-x
    location: Online
    date_start: '2021-12-01'
    date_end: '2022-01-31'
    description: |2-
        - Worked on migration and deployment of the JupyterHub server from an EC2 instance to a Kubernetes cluster.<br>
        - Made minor configuration changes which enabled the use of remote spark clusters in Jupyter Notebooks.
  - title: Backend Developer (Intern)
    company: MiBi Services
    company_url: ''
    company_logo: org-x
    location: Online
    date_start: '2021-02-01'
    date_end: '2021-03-31'
    description: |2-
        - Implemented resolvers for GraphQL queries and mutations.<br>
        - Suggested changes in the data models of the application.
design:
  columns: '2'
---

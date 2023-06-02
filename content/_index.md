---
# Leave the homepage title empty to use the site title
title:
date: 2023-06-01
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Development Intern
          company: WuXi Biologics
          company_url: 'https://www.wuxibiologics.com/'
          company_logo: wuxi
          location: Shanghai
          date_start: '2022-09-01'
          date_end: '2022-12-01'
          description: |2-
              Data Technology and Analysis Department - Data Technology AI Team

              Responsibilities include:

              * Graph-based and language model development for Protein-protein Interaction (PPI) prediction and antibiotic discovery
        - title: Professor of Semiconductor Physics
          company: University X
          company_url: ''
          company_logo: org-x
          location: California
          date_start: '2016-01-01'
          date_end: '2020-12-31'
          description: Taught electronic engineering and researched semiconductor physics.
    design:
      columns: '2'
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      # Contact (add or remove contact options as necessary)
      email: q.guo22@imperial.ac.uk
      address:
        street: 86 Wood Ln
        city: London
        postcode: 'W12 0BZ'
        country: United Kindom
      directions: U301/05, 3rd Floor, Building E - Sir Michael Uren, White City Campus
      # Automatically link email and phone or display as text?
    design:
      columns: '2'
---
---

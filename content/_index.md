---
# Leave the homepage title empty to use the site title
title: Pablo Gómez-Abajo
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: features
    content:
      title: Skills
      items:
        - name: Java
          description: 90%
          icon: java
          icon_pack: fab
        - name: Eclipse
          description: 100%
          icon: gear
          icon_pack: fas
        - name: Software Engineering
          description: 80%
          icon: uncharted
          icon_pack: fab
  - block: experience
    id: experience
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
        - title: Assistant Professor
          company: Universidad Autónoma de Madrid
          company_url: 'https://www.uam.es'
          company_logo: org-uam
          location: Madrid
          date_start: '2023-01-01'
          date_end: ''
          description: |2-
              Taught courses:
              * Operating systems
              * Internet and advanced networks
        - title: Pre-doctoral Assistant Professor
          company: Universidad Autónoma de Madrid
          company_url: 'https://www.uam.es'
          company_logo: org-uam
          location: Madrid
          date_start: '2019-09-01'
          date_end: '2023-01-01'
          description: |2-
              Taught courses:
              * Compilers
              * Automata and languages theory
              * Software analysis and design
        - title: Research Project Associate
          company: Universidad Autónoma de Madrid
          company_url: 'https://www.uam.es'
          company_logo: org-uam
          location: Madrid
          date_start: '2015-03-01'
          date_end: '2019-09-01'
          description: |2-
              Design and development of:
              * Domain-specific languages
              * Domain-independent solutions
        - title: IT Manager
          company: Ingeniería y Prevención de Riesgos, S.L.
          company_url: 'https://imasp.net'
          company_logo: org-imasp
          location: Madrid
          date_start: '2008-07-21'
          date_end: '2015-03-01'
          description: |2-
              Responsibilities include:
              * Requirements Engineering
              * Analysis and Design
              * Development
              * Deploying
              * IT Support
    design:
      columns: '2'
  - block: accomplishments
    id: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://www.coursera.org
          date_end: ''
          date_start: '2021-01-25'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Neural Networks and Deep Learning
          url: ''
        - certificate_url: https://www.edx.org
          date_end: ''
          date_start: '2021-01-01'
          description: Formulated informed blockchain models, hypotheses, and use cases.
          organization: edX
          organization_url: https://www.edx.org
          title: Blockchain Fundamentals
          url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
        - certificate_url: https://www.datacamp.com
          date_end: '2020-12-21'
          date_start: '2020-07-01'
          description: ''
          organization: DataCamp
          organization_url: https://www.datacamp.com
          title: 'Object-Oriented Programming in R'
          url: ''
    design:
      columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Wodel
          tag: Wodel
        - name: Gotten
          tag: Gotten
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: collection
    id: publications
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        You can use the below data to contact Pablo Gómez-Abajo whenever you like.
      # Contact (add or remove contact options as necessary)
      email: pablo.gomeza@uam.es
      phone: +34 91 497 2358
      appointment_url: 'https://calendly.com'
      address:
        street: C/ Francisco Tomás y Valiente, 11
        city: Madrid
        region: 
        postcode: '28049'
        country: Spain
        country_code: ES
      directions: Office B-424
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/GomezAbajo_en'
        - icon: skype
          icon_pack: fab
          name: Skype Me
          link: 'skype:pgomez.imasp?call'
        - icon: video
          icon_pack: fas
          name: Zoom Me
          link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---

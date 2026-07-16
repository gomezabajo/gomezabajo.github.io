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
        - name: Model-Driven Engineering
          description: Metamodeling, domain-specific languages, and code generation with EMF
          icon: diagram-project
          icon_pack: fas
        - name: Java & Eclipse
          description: Eclipse plug-in development and domain-specific languages built with Xtext
          icon: java
          icon_pack: fab
        - name: Software Testing
          description: Mutation testing and metamorphic testing (Wodel-Test, Gotten)
          icon: vial
          icon_pack: fas
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
              * Operating Systems
              * Internet and Advanced Networks
        - title: Predoctoral Assistant Professor
          company: Universidad Autónoma de Madrid
          company_url: 'https://www.uam.es'
          company_logo: org-uam
          location: Madrid
          date_start: '2019-09-01'
          date_end: '2023-01-01'
          description: |2-
              Taught courses:
              * Compilers
              * Automata and Language Theory
              * Software Analysis and Design
        - title: Research Project Associate
          company: Universidad Autónoma de Madrid
          company_url: 'https://www.uam.es'
          company_logo: org-uam
          location: Madrid
          date_start: '2015-03-01'
          date_end: '2019-09-01'
          description: |2-
              Designed and developed:
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
              Responsibilities included:
              * Requirements engineering
              * Analysis and design
              * Software development
              * Deployment
              * IT support
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
      text: |-
        A selection of courses most relevant to my research and teaching.
        See the [complete list of attended courses and seminars](courses/).
      items:
        - certificate_url: 'https://www.gomezabajo.es/pablo/pdf/courses/2026_Math_Thinking.pdf'
          date_end: ''
          date_start: '2026-01-01'
          description: '90h. · Coursera'
          icon: 'org-stanford'
          organization: 'Stanford University'
          organization_url: 'https://www.stanford.edu'
          title: 'Introduction to Mathematical Thinking'
          url: ''
        - certificate_url: 'https://www.gomezabajo.es/pablo/pdf/courses/2025_Algorithms.pdf'
          date_end: ''
          date_start: '2025-12-01'
          description: '100h. · Coursera'
          icon: 'org-stanford'
          organization: 'Stanford University'
          organization_url: 'https://www.stanford.edu'
          title: 'Algorithms'
          url: ''
        - certificate_url: 'https://www.gomezabajo.es/pablo/pdf/courses/2025_Docencia_Universidad_IA-gen.pdf'
          date_end: ''
          date_start: '2025-09-01'
          description: '25h.'
          icon: 'org-uam-full'
          organization: 'Universidad Autónoma de Madrid'
          organization_url: 'https://www.uam.es'
          title: 'Aplicación de la Inteligencia Artificial Generativa para la práctica docente en Educación Superior'
          url: ''
        - certificate_url: 'https://www.gomezabajo.es/pablo/pdf/courses/2025_Linear_Optimization.pdf'
          date_end: ''
          date_start: '2025-03-01'
          description: '40h. · edX'
          icon: 'org-epfl'
          organization: 'Ecole Polytechnique Federale de Lausanne'
          organization_url: 'https://www.epfl.ch'
          title: 'Linear Optimization'
          url: ''
        - certificate_url: 'https://www.gomezabajo.es/pablo/pdf/courses/2024_Automated_Software_Testing.pdf'
          date_end: ''
          date_start: '2024-11-01'
          description: '50h. · edX'
          icon: 'org-tudelft'
          organization: 'Delft University of Technology'
          organization_url: 'https://www.tudelft.nl'
          title: 'Automated Software Testing'
          url: ''
        - certificate_url: 'https://www.gomezabajo.es/pablo/pdf/courses/2024_Software_Testing_I.pdf'
          date_end: ''
          date_start: '2024-09-01'
          description: '30h. · Coursera'
          icon: 'org-umn'
          organization: 'University of Minnesota'
          organization_url: 'https://www.umn.edu'
          title: 'Introduction to Software Testing'
          url: ''
        - certificate_url: 'https://www.gomezabajo.es/pablo/pdf/courses/2024_Design_patterns.pdf'
          date_end: ''
          date_start: '2024-05-01'
          description: '40h. · Coursera'
          icon: 'org-ualberta'
          organization: 'University of Alberta'
          organization_url: 'https://www.ualberta.ca'
          title: 'Design patterns'
          url: ''
        - certificate_url: 'https://www.gomezabajo.es/pablo/pdf/courses/2024_Object_oriented_design.pdf'
          date_end: ''
          date_start: '2024-02-01'
          description: '32h. · Coursera'
          icon: 'org-ualberta'
          organization: 'University of Alberta'
          organization_url: 'https://www.ualberta.ca'
          title: 'Object-oriented design'
          url: ''
        - certificate_url: 'https://www.gomezabajo.es/pablo/pdf/courses/2023_IBM_IT_support_professional_certificate.pdf'
          date_end: ''
          date_start: '2023-07-01'
          description: '120h. · Coursera'
          icon: 'org-ibm'
          organization: 'IBM'
          organization_url: 'https://www.ibm.com'
          title: 'IBM IT support professional certificate'
          url: ''
        - certificate_url: 'https://www.gomezabajo.es/pablo/pdf/courses/2023_Writing_sciences_honors.pdf'
          date_end: ''
          date_start: '2023-01-01'
          description: '30h. · Coursera'
          icon: 'org-stanford'
          organization: 'Stanford University'
          organization_url: 'https://www.stanford.edu'
          title: 'Writing in the sciences'
          url: ''
        - certificate_url: 'https://www.gomezabajo.es/pablo/pdf/courses/2021_Compilers.pdf'
          date_end: ''
          date_start: '2021-12-01'
          description: '70h. · edX'
          icon: 'org-stanford'
          organization: 'Stanford University'
          organization_url: 'https://www.stanford.edu'
          title: 'Compilers'
          url: ''
        - certificate_url: 'https://www.gomezabajo.es/pablo/pdf/courses/2021_Automata_theory.pdf'
          date_end: ''
          date_start: '2021-11-01'
          description: '70h. · edX'
          icon: 'org-stanford'
          organization: 'Stanford University'
          organization_url: 'https://www.stanford.edu'
          title: 'Automata Theory'
          url: ''
        - certificate_url: 'https://www.gomezabajo.es/pablo/pdf/courses/2020_Deep_Learning.pdf'
          date_end: ''
          date_start: '2020-05-01'
          description: '60h. · Coursera'
          icon: 'org-hse'
          organization: 'National Research University Higher School of Economics'
          organization_url: 'https://www.hse.ru'
          title: 'Introduction to Deep Learning'
          url: ''
        - certificate_url: 'https://www.gomezabajo.es/pablo/pdf/courses/2019_Process_Mining_Data_Science.pdf'
          date_end: ''
          date_start: '2019-07-01'
          description: '24h. · Coursera'
          icon: 'org-tue'
          organization: 'Eindhoven University of Technology'
          organization_url: 'https://www.tue.nl'
          title: 'Process Mining: Data Science in Action'
          url: ''
        - certificate_url: 'https://www.gomezabajo.es/pablo/pdf/courses/2016_DSM-TP_Universite_de_Geneve.pdf'
          date_end: ''
          date_start: '2016-08-01'
          description: '50h.'
          organization: 'Université de Genève'
          organization_url: 'https://www.unige.ch'
          title: 'DSM-TP International Summer School 2016 on Domain-Specific Modeling'
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
        You may use the contact information below to reach Pablo Gómez-Abajo.
      # Contact (add or remove contact options as necessary)
      email: pablo.gomeza@uam.es
      phone: +34 91 497 2358
      # To re-enable appointment booking, set your personal Calendly URL below:
      # appointment_url: 'https://calendly.com/your-username'
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
          name: Message Me
          link: 'https://twitter.com/GomezAbajo_en'
        # Skype was discontinued in May 2025, and the Zoom link below was a
        # generic placeholder. Restore with a personal meeting URL if desired:
        # - icon: video
        #   icon_pack: fas
        #   name: Zoom Me
        #   link: 'https://zoom.us/my/your-meeting-room'
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

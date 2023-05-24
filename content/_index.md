---
# Leave the homepage title empty to use the site title
title:
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
        - name: R
          description: 90%
          icon: r-project
          icon_pack: fab
        - name: Statistics
          description: 100%
          icon: chart-line
          icon_pack: fas
        - name: Photography
          description: 10%
          icon: camera-retro
          icon_pack: fas
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
        - title: Teaching Assistant
          company: University of Michigan - Shanghai Jiao Tong University Joint Institute
          company_url: "https://www.ji.sjtu.edu.cn/"
          company_logo: sjtu
          location: Shanghai
          date_start: "2023-05-08"
          date_end: ""
          description: Teaching Assistant for ECE3730J, Design of Microprocessor Based Systems.
        - title: Research Assistant
          company: ROAHM Lab, University of Michigan
          company_url: "https://www.roahmlab.com/"
          company_logo: umich-pms
          location: Michigan
          date_start: "2022-05-20"
          date_end: ""
          description: Developed efficient GPU algorithm and CUDA implementation for RTD safe motion planning of bipedal robot.
        - title: Instructor Aide (EECS 482, Intro. to Operating Systems)
          company: CSE Division, University of Michigan
          company_url: "https://cse.engin.umich.edu/"
          company_logo: umich-pms
          location: Michigan
          date_start: "2023-01-01"
          date_end: "2023-04-30"
          description: |2-
              Responsibilities include:

              * Holding Lab Sections
              * Holding Office Hours
              * Design and Grade Exams
    design:
      columns: "2"
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: "Accomplish&shy;ments"
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
          date_end: ""
          date_start: "2021-01-25"
          description: ""
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Neural Networks and Deep Learning
          url: ""
        - certificate_url: https://www.edx.org
          date_end: ""
          date_start: "2021-01-01"
          description: Formulated informed blockchain models, hypotheses, and use cases.
          organization: edX
          organization_url: https://www.edx.org
          title: Blockchain Fundamentals
          url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
        - certificate_url: https://www.datacamp.com
          date_end: "2020-12-21"
          date_start: "2020-07-01"
          description: ""
          organization: DataCamp
          organization_url: https://www.datacamp.com
          title: "Object-Oriented Programming in R"
          url: ""
    design:
      columns: "2"
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ""
      text: ""
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: "2"
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
          tag: "*"
        - name: Deep Learning
          tag: Deep Learning
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: "1"
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  # - block: collection
  #   id: featured
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     columns: "2"
  #     view: card
  # - block: collection
  #   content:
  #     title: Recent Publications
  #     text: |-
  #       {{% callout note %}}
  #       Quickly discover relevant content by [filtering publications](./publication/).
  #       {{% /callout %}}
  #     filters:
  #       folders:
  #         - publication
  #       exclude_featured: true
  #   design:
  #     columns: "2"
  #     view: citation
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     columns: "2"
  #     view: compact
  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: "2"
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        If you would like to, you can leave a message here or contact me via the email provided.
      # Contact (add or remove contact options as necessary)
      email: bhqin@umich.edu
      address:
        street: 1301 Beal Avenue
        city: Ann Arbor
        region: MI
        postcode: "48109-2122"
        country: United States
        country_code: US
      directions: Enter the EECS Building
      office_hours:
        - "Monday 10:00 to 13:00"
        - "Wednesday 09:00 to 10:00"
      contact_links:
        - icon: video
          icon_pack: fas
          name: Zoom Me
          link: "https://zoom.com"
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: true
    design:
      columns: "2"
---

---
# Leave the homepage title empty to use the site title
title: BeBetter
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        BeBetter
      image:
        filename: asam_logo.jpg
      text: |
        <br>
        Empower Your Mental Well-being at Work!
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: skills
    content:
      title: Skills
      text: ""
      # Choose a user to display skills from (a folder name within `content/authors/`)
      username: admin
    design:
      columns: "1"
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: CEO
          company: GenCoin
          company_url: ""
          company_logo: org-gc
          location: California
          date_start: "2021-01-01"
          date_end: ""
          description: |2-
              Responsibilities include:

              * Analysing
              * Modelling
              * Deploying
        - title: Professor of Semiconductor Physics
          company: University X
          company_url: ""
          company_logo: org-x
          location: California
          date_start: "2016-01-01"
          date_end: "2020-12-31"
          description: Taught electronic engineering and researched semiconductor physics.
    design:
      columns: "2"
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: "Accomplish&shy;ments"
      subtitle:
      # Date format: https://docs.hugoblox.com/customization/#date-format
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
          icon: coursera
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Neural Networks and Deep Learning
          url: ""
        - certificate_url: https://www.edx.org
          date_end: ""
          date_start: "2021-01-01"
          description: Formulated informed blockchain models, hypotheses, and use cases.
          icon: edx
          organization: edX
          organization_url: https://www.edx.org
          title: Blockchain Fundamentals
          url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
        - certificate_url: https://www.datacamp.com
          date_end: "2020-12-21"
          date_start: "2020-07-01"
          description: ""
          icon: datacamp
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
  - block: markdown
    content:
      title: Video
      subtitle: <iframe width="560" height="315" src="https://www.youtube.com/embed/jA5p3RAxGPU?si=--rcGL0TJTaPm7H8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
    design:
      columns: "1"
  - block: people
    id: authors
    content:
      title:
        Meet the Team
        # Choose which groups/teams of users to display.
        #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
        - Supervisor
        - Software Developers
      sort_by: Params.last_name
      sort_ascending: true
---

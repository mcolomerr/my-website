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
        - name: Bioinformatics
          icon: r-project
          icon_pack: fab
        - name: Molecular Biology
          icon: chart-line
          icon_pack: fas
        - name: Scientific outreach
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
        - title: PhD student
          company: Schier lab, Biozentrum
          company_url: ''
          company_logo: org-gc
          location: Basel, CH
          date_start: '2023-06-02'
          date_end: ''
          description: Graduate student in developmental biology at Prof. Schier's lab.
        - title: PhD rotation
          company: van Nimwegen lab, Biozentrum
          company_url: ''
          company_logo: org-gc
          location: Basel, CH
          date_start: '2023-03-15'
          date_end: '2023-06-02'
          description: PhD rotation at Prof. van Nimwegen's lab investigating promoter-enhancer interactoins.
        - title: PhD rotation
          company: Schier lab, Biozentrum
          company_url: ''
          company_logo: org-gc
          location: Basel, CH
          date_start: '2023-01-15'
          date_end: '2023-03-15'
          description: Graduate student in developmental biology at Prof. Schier's lab studying gene regulatory networks of early zebrafish embryogenesis.
        - title: Master thesis
          company: Donato lab, Biozentrum
          company_url: ''
          company_logo: org-x
          location: Basel, CH
          date_start: '2022-05-09'
          date_end: '2022-12-01'
          description: Master thesis project at Prof. Donato's lab in brain-machine interfaces on rodents using 2-photon imaging.
        - title: Master thesis
          company: Donato lab, Biozentrum
          company_url: ''
          company_logo: org-x
          location: Basel, CH
          date_start: '2022-05-09'
          date_end: '2022-12-01'
          description: Master thesis project at Prof. Donato's lab in brain-machine interfaces on rodents using 2-photon imaging.
        - title: Master rotation
          company: Treutlein lab, ETH Zurich
          company_url: ''
          company_logo: org-x
          location: Basel, CH
          date_start: '2022-05-09'
          date_end: '2022-02-01'
          description: research project in Prof. Treutlein's lab characterizing cerebral organoids through image analysis.
        - title: Master rotation
          company: Müller lab, ETH Zurich
          company_url: ''
          company_logo: org-x
          location: Basel, CH
          date_start: '2022-10-01'
          date_end: '2022-01-01'
          description: research project at the Department of Biosystems Science and Engineering in Prof. D.J. Müller's biophysics group where I used atomic force microscopy to study cell adhesion.
         - title: Undergraduate researcher
          company: Wieser lab, ICFO
          company_url: ''
          company_logo: org-x
          location: Barcelona, ES
          date_start: '2018-06-01'
          date_end: '2020-07-01'
          description: Undergraduate researcher at Dr. Wieser and Dr. Ruprecht labs working on cell migration.
         - title: Summer research student
          company: Manley lab, EPFL
          company_url: ''
          company_logo: org-x
          location: Lausanne, CH
          date_start: '2019-07-01'
          date_end: '2019-08-01'
          description: Research internship in the Laboratory of Experimental Biophysics from Prof. Manley. Granted by the EPFL Life Sciences Summer Research Program.
    design:
      columns: '2'
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
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
        - name: Deep Learning
          tag: Deep Learning
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: collection
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
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
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
      text: |-
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: m(dot)colomerrosell(at)unibas(dot)ch
    design:
      columns: '2'
---

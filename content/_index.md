---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: features
    content:
      title: Skills
      items:
        - name: Experimental designs
          description: 
          icon: flask
          icon_pack: fas
        - name: Project oversight
          description: 
          icon: list-check
          icon_pack: fas
        - name: Grant writing
          description: 
          icon: pen
          icon_pack: fas
        - name: Statistics and Programming
          description:
          icon: r-project
          icon_pack: fab
        - name: fMRI data analysis
          description: 
          icon: brain
          icon_pack: fas
        - name: Qualitative analysis
          description: 
          icon: clipboard-question
          icon_pack: fas


  - block: experience
    content:
      title: Academic path
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
          company: Leiden University
          company_url: 'www.leidenuniv.nl'
          company_logo: leiden
          location: Leiden, the Netherlands
          date_start: '2024-02-01'
          date_end: ''
          description: I teach several courses to bachelor and master Psychology students (e.g., Health and Medical psychology, Clinical Neuropsychology, Innovations in Neuropsychology). As well, as I do research on placebo and nocebo effects in food metabolims and communication in serious illness.
        - title: Postdoctoral Researcher
          company: Leiden University
          company_url: 'www.leidenuniv.nl'
          company_logo: leiden
          location: Leiden, the Netherlands
          date_start: '2023-03-01'
          date_end: '2024-02-01'
          description: I work as a scientific university partner of TNO (Netherlands Organisation for Applied Scientific Research) in the consortium  "Preparedness for pandemics". Additionally, I am involved in several research projects on placebo and nocebo effects. 
        - title: Postdoctoral Researcher
          company: McGill University, Alan Edwards Centre for Research on Pain
          company_url: 'https://www.mcgill.ca/painresearch'
          company_logo: mcgill
          location: Montreal, Canada
          date_start: '2021-03-01'
          date_end: '2023-03-01'
          description: As a part of the Rubicon fellowship from NWO, I investigated the neuroendocrine mechanisms of nocebo hyperalgesia in human and animal models.
        - title: Postdoctoral Researcher
          company: Leiden University
          company_url: 'www.leidenuniv.nl'
          company_logo: leiden
          location: Leiden, the Netherlands
          date_start: '2020-11-01'
          date_end: '2021-03-01'
          description: I taught working groups for the course "Health psychology"; lead a randomized controlled trial on the conditioning of insulin responses in diabetes type-2; and worked on the knowledge exploration for Diabetes Fonds.
        - title: PhD candidate
          company: Leiden University
          company_url: 'www.leidenuniv.nl'
          company_logo: leiden
          location: Leiden, the Netherlands
          date_start: '2015-11-01'
          date_end: '2020-11-01'
          description: Wrote a PhD thesis on classical conditioning of oxytocin responses; supervised multiple master and bachelor students.
        - title: Research Master in Behavioural Sciences
          company: Radboud University
          company_url: 'www.ru.nl'
          company_logo: radboud
          location: Nijmegen, the Netherlands
          date_start: '2013-09-01'
          date_end: '2015-06-01'
          description:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: Other roles
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: 
          date_end: ''
          date_start: '2022-01-01'
          description: Replications & Reversals project aims to build a crowd-driven database that describes the replications of widely known effects across social sciences.
          organization: Framework for Open and Reproducible Research Training (FORRT)
          organization_url: https://forrt.org/reversals/
          title: Project Manager
          url: 'https://forrt.org/reversals/'
        - certificate_url: 
          date_end: ''
          date_start: '2022-11-01'
          description: Health & Help is a small charity organization which provides essential medical care to underserved communities in Central America. I am leading the grant writing team, searching for the applicable grats and preparing the grant applications.
          organization: Health & Help
          organization_url: https://www.he-he.org
          company_logo: radboud
          title: Grant Writer
          url: 'https://www.he-he.org'
        - certificate_url: 
          date_end: ''
          date_start: '2022-01-01'
          description: Touch Medical Intelligence is a start-up creating a digital AI health assistant. I consult the company on the the scientifically proven behavioral health interventions. 
          organization: Touch Medical Intelligence
          organization_url: https://www.touchmedical.ca
          title: Scientific Advisor
          url: https://www.touchmedical.ca
    design:
      columns: '2'
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 1
      # Filter on criteria
      filters:
        folders:
          - post
        author: ""
        category: ""
        tag: ""
#        exclude_featured: false
#        exclude_future: false
#        exclude_past: false
#        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
#      order: desc
#    design:
      # Choose a layout view
#      view: compact
#      columns: '2'
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
      # buttons:
      #  - name: All
      #    tag: '*'
      #  - name: Medical Communication when Breaking Bad News
      #    tag: Communication
      #  - name: Physiological Mechanisms of Placebo & Nocebo
      #    tag: Physiology
      #  - name: Replications & Reversals
      #    tag: FORRT
      #  - name: Health & Help
      #    tag: Health



    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
#  - block: markdown
#    content:
#      title: Gallery
#      subtitle: ''
#      text: |-
#        {{< gallery album="demo" >}}
#    design:
#      columns: '1'
#  - block: collection
#    id: featured
#    content:
#      title: Featured Publications
#      filters:
#        folders:
#          - publication
#        featured_only: true
#    design:
#      columns: '2'
#      view: card
  - block: collection
    content:
      title: Publications
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
#  - block: collection
#    id: talks
#    content:
#      title: Recent & Upcoming Talks
#      filters:
#        folders:
#          - event
#    design:
#      columns: '2'
#      view: compact
#  - block: tag_cloud
#    content:
#      title: Popular Topics
#    design:
#      columns: '2'
#  - block: contact
#    id: contact
#    content:
#      title: Contact
#      subtitle:
#      text: |-
#        Are you a student searching for a research internship or thesis placement? Or a researcher interested in one of the topics I am working on? I am always happy to collaborate! 
#       Contact (add or remove contact options as necessary)
#      email: a.skvortsova@fsw.leidenuniv.nl
#      phone: 888 888 88 88
#      appointment_url: 'https://calendly.com'
#      address:
#        street: Wassenaarseweg 52
#        city: Leiden
#        region: CA
#        postcode: '2333 AK'
#        country: the Netherlands
#        country_code: NL
#      directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
#      office_hours:
#        - 'Monday 10:00 to 13:00'
#        - 'Wednesday 09:00 to 10:00'
#      contact_links:
#        - icon: twitter
#          icon_pack: fab
#          name: DM Me
#          link: 'https://twitter.com/Twitter'
#        - icon: skype
#          icon_pack: fab
#          name: Skype Me
#          link: 'skype:echo123?call'
#        - icon: video
#          icon_pack: fas
#          name: Zoom Me
#          link: 'https://zoom.com'
#       Automatically link email and phone or display as text?
#      autolink: true
#       Email form provider
#      form:
#        provider: netlify
#        formspree:
#          id:
#        netlify:
#           Enable CAPTCHA challenge to reduce spam?
#          captcha: false#
#    design:
#      columns: '2'
---

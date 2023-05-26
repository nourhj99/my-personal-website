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
        - name: Python
          description: 60%
          icon: python
          icon_pack: fab
        - description: 70%
          icon: java
          icon_pack: fab
          name: Java
        - description: 40%
          icon: database
          icon_pack: fas
          name: SQL & NoSQL
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
        - title: Software engineer intern
          company: CBRE
          company_url: 'https://www.cbre.com/'
          company_logo: org-gc
          location: Remote
          date_start: '2023-05-06'
          date_end: '2023-11-08'
          description: |2-
              Responsibilities include:

              * Testing
              * Configuration
              * Maintenance
        - title: Research Assistant
          company: University of Michigan Dearborn
          company_url: 'https://umdearborn.edu/'
          company_logo: org-x
          location: Michigan
          date_start: '2023-05-01'
          date_end: '2023-30-05'
          description: 
          • Analyze comment changes in machine learning projects to help find the solution to automatize comments.
          • Use Java, Maven, and Git tools to automatically extract the reasons behind updating comments from commit to commit using different machine projects well rated from GitHub.
        - title: Data Scientist Intern
          company: Tunisian Cloud
          company_url: 'https://www.tunisiancloud.com/'
          company_logo: org-x
          location: Tunis
          date_start: '2022-05-05'
          date_end: '2022-30-07'
          description: 
          • Developed a web application with PostgreSQL for my database, python for the backend along with Flask to connect the front and the back, and HTML, CSS, and bootstrap for my front end to predict email validation.
          • Collected data using Web Scrapping with Selenium and applied multiple machine algorithms mainly the decision tree to find out the one with the best accuracy. To be able to use manage the data and run the algorithms, I used NumPy, Seaborn and Scikit learn libraries.
        - title: Research Assistant
          company: University of Michigan Dearborn
          company_url: 'https://umdearborn.edu/'
          company_logo: org-x
          location: Michigan
          date_start: '2021-01-09'
          date_end: '2021-30-12'
          description: 
          • Implement an intelligent and dynamic scheduler for software containers in edge devices in collaboration with Ford Motor company using search-based techniques such as genetic algorithms.
          • Contributed to a research project by creating an Angular front-end to visualize real time containers metrics such as memory consumption, CPU, and network input/output usage using charts and graphs along with cAdvisor, Prometheus, and node exporter.
        - title: Software Engineer Intern
          company: L'Equipement Moderne
          company_url: 'https://www.equipementmoderne.com.tn/en/'
          company_logo: org-x
          location: Tunis
          date_start: '2021-06-06'
          date_end: '2021-15-08'
          description: 
          • Contributed to the code migration of the enterprise resource planning (ERP) from an old programming language Delphi to modern ones; Angular, Spring Boot, and MySQL.
          • Managed car part inventory and employee data to ensure efficient resource utilization within the company.
          • Implemented new features to the system and worked closely with the testing team to test and debug the code.
        - title: Software Project Manager Intern
          company: MediaNet
          company_url: 'https://www.medianet.tn/fr/'
          company_logo: org-x
          location: Tunis
          date_start: '2020-06-07'
          date_end: '2020-15-08'
          description: 
          • Acquired in-depth knowledge of Agile methodologies to streamline project delivery as well as interacting with multiple project managers to learn about their experience.
          • Gained knowledge about all the steps of building a website such as structure, zoning, benchmarking, A/B testing, and referencing.
        - title: Web Developer
          company: Youth Mediterranean Consulting at SMU
          company_url: ''
          company_logo: org-x
          location: Tunis
          date_start: '2018-06-09'
          date_end: '2019-15-08'
          description: 
          • Created multiple websites using HTML, CSS, Bootstrap, and WordPress for clients.
          • Organized job fairs through organizations to provide job opportunities to students.
    design:
      columns: '2'
  - block: accomplishments
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
  - block: markdown
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
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
      email: test@example.org
      phone: 888 888 88 88
      appointment_url: 'https://calendly.com'
      address:
        street: 450 Serra Mall
        city: Stanford
        region: CA
        postcode: '94305'
        country: United States
        country_code: US
      directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      office_hours:
        - 'Monday 10:00 to 13:00'
        - 'Wednesday 09:00 to 10:00'
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/Twitter'
        - icon: skype
          icon_pack: fab
          name: Skype Me
          link: 'skype:echo123?call'
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

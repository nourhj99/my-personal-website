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
        - title: Software engineer intern
          company: CBRE
          company_url: 'https://www.cbre.com/'
          company_logo: cbre
          location: Remote
          date_start: '2023-06-05'
          date_end: '2023-08-11'
          description: |2-
              Responsibilities include:

              * Testing
              * Configuration
              * Maintenance
        - title: Research Assistant
          company: University of Michigan Dearborn
          company_url: 'https://umdearborn.edu/'
          company_logo: michigan
          location: Michigan
          date_start: '2023-01-05'
          date_end: '2023-05-30'
          description: |2-
              Responsibilities include:

              * Analyze comment changes in machine learning projects to help find the solution to automatize comments.
              * Use Java, Maven, and Git tools to automatically extract the reasons behind updating comments from commit to commit using different machine projects well rated from GitHub.
        - title: Data Scientist Intern
          company: Tunisian Cloud
          company_url: 'https://www.tunisiancloud.com/'
          company_logo: tunisiancloud
          location: Tunis
          date_start: '2022-05-05'
          date_end: '2022-07-30'
          description: |2-
              Responsibilities include:

              * Developed a web application with PostgreSQL for my database, python for the backend along with Flask to connect the front and the back, and HTML, CSS, and bootstrap for my front end to predict email validation.
              * Collected data using Web Scrapping with Selenium and applied multiple machine algorithms mainly the decision tree to find out the one with the best accuracy. To be able to use manage the data and run the algorithms, I used NumPy, Seaborn and Scikit learn libraries.
        - title: Research Assistant
          company: University of Michigan Dearborn
          company_url: 'https://umdearborn.edu/'
          company_logo: michigan
          location: Michigan
          date_start: '2021-09-01'
          date_end: '2021-12-30'
          description: |2-
              Responsibilities include:

              * Implement an intelligent and dynamic scheduler for software containers in edge devices in collaboration with Ford Motor company using search-based techniques such as genetic algorithms.
              * Contributed to a research project by creating an Angular front-end to visualize real time containers metrics such as memory consumption, CPU, and network input/output usage using charts and graphs along with cAdvisor, Prometheus, and node exporter.
        - title: Software Engineer Intern
          company: L'Equipement Moderne
          company_url: 'https://www.equipementmoderne.com.tn/en/'
          company_logo: l_equipement
          location: Tunis
          date_start: '2021-06-06'
          date_end: '2021-08-15'
          description: |2-
              Responsibilities include:

              * Contributed to the code migration of the enterprise resource planning (ERP) from an old programming language Delphi to modern ones; Angular, Spring Boot, and MySQL.
              * Managed car part inventory and employee data to ensure efficient resource utilization within the company.
              * Implemented new features to the system and worked closely with the testing team to test and debug the code.
        - title: Software Project Manager Intern
          company: MediaNet
          company_url: 'https://www.medianet.tn/fr/'
          company_logo: medianet
          location: Tunis
          date_start: '2020-07-06'
          date_end: '2020-08-15'
          description: |2-
              Responsibilities include:

              * Acquired in-depth knowledge of Agile methodologies to streamline project delivery as well as interacting with multiple project managers to learn about their experience.
              * Gained knowledge about all the steps of building a website such as structure, zoning, benchmarking, A/B testing, and referencing.
        - title: Web Developer
          company: Youth Mediterranean Consulting at SMU
          company_url: ''
          company_logo: youth
          location: Tunis
          date_start: '2018-09-06'
          date_end: '2019-08-15'
          description: |2-
              Responsibilities include:

              * Created multiple websites using HTML, CSS, Bootstrap, and WordPress for clients.
              * Organized job fairs through organizations to provide job opportunities to students.
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
        - certificate_url: https://coursera.org/share/caaa2a3bfa26cca3bfc360fe50b74245
          date_end: ''
          date_start: '2022-05-08'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Machine Learning Foundations A Case Study Approach
          url: ''
        - certificate_url: https://coursera.org/share/fdffdf000bf4adae8cc032c52a8f7cb2
          date_end: ''
          date_start: '2022-05-20'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Research Data Management and Sharing
          url: ''
        - certificate_url: https://coursera.org/share/e9c4cc8d33dcd25b7e139614c06adcb7
          date_end: ''
          date_start: '2022-06-06'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Ethics, Technology and Engineering
          url: ''
    design:
      columns: '2'
  - block: experience
    id : Extracurricularactivities
    content:
      title: Extracurricular activities
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: IT committee head 
          company: Professional Co-ed Business Fraternity Alpha Kappa Psi
          company_url: ''
          company_logo: akpsi
          location: Michigan
          date_start: '2023-01-05'
          date_end: '2023-08-11'
          description: |2-
              Promoted the fraternity on social media. Attended and organized career development workshops.
        - title: Member
          company: UNICEF
          company_url: ''
          company_logo: unicef
          location: Michigan
          date_start: '2022-09-05'
          date_end: '2023-04-30'
          description: |2-
              Ensured that children have the essentials for a safe and healthy childhood through volunteering and fundraising.
        - title: President
          company: Rotaract Carthage Amilcar
          company_url: ''
          company_logo: rotaract
          location: Tunis
          date_start: '2020-09-05'
          date_end: '2021-06-30'
          description: |2-
              Organized, prepared, and supervised 15 actions such as building homes for homeless families.Chaired the club and communicated with the team members while using the club’s time efficiently and productively.
        - title: Board Member
          company: Google Affiliate Developer Student Club of South Mediterranean University
          company_url: ''
          company_logo: google
          location: Tunis
          date_start: '2019-09-01'
          date_end: '2020-05-30'
          description: |2-
              Organized tech talks, events, and workshops while collaborating with others to accomplish these goals.
        
    design:
      columns: '2'
  - block: features
    content:
      title: Hobbies
      items:
        - name: Dance
          description:  Danced for 10 years multiple type of dance, created choreographies and taught kids and teenagers.
          icon: dance
          icon_pack: fab
        - description: Traveled to more than 10 countries including ; France, Italy, Canada, and Thailand...
          icon: plane
          icon_pack: fab
          name: Travel
        - description: Took classes in photography and been taking pictures of all the places I visited.
          icon: camera-retro
          icon_pack: fas
          name: Photography
  - block: markdown
    content:
      title: Personal accomplishments
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
     
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Please don't hesitate to reach out to me if my profile captures your interest. I am always open to connecting, exchanging ideas, or exploring potential collaborations. I look forward to hearing from you and discussing how we can work together.
      # Contact (add or remove contact options as necessary)
      email: nourhj@umich.edu
      appointment_url: 'https://calendly.com'
      address:
        street: 780 Town Center dr
        city: Dearborn
        region: MI
        country: United States
        country_code: US
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

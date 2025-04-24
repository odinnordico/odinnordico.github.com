---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: odin
  - block: skills
    content:
      title: Skills
      text: ""
      # Choose a user to display skills from (a folder name within `content/authors/`)
      username: odin
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
        - title: Senior software Engineer - Golang
          company: Wizeline
          company_url: https://www.wizeline.com/
          company_logo: wizeline
          location: Remote - Colombia
          date_start: "2025-02-10"
          date_end:
          description: |2-
              Responsibilities include:

              * Architect and implement features for a customer in media business using Go.
              * Support operation of the authentication and authorization process for users of a media platform on services implemented in Go.
              * Update partners configuration on a media platform databases.
        - title: Independent Golang Engineer Consultant
          company: Self-Employed}
          company_url: https://odinnordico.github.io/
          company_logo:
          location: Remote - Colombia
          date_start: "2021-07-01"
          date_end: "2025-01-31"
          description: |2-
              Responsibilities include:

              *Architect and implement robust Go applications for Kubernetes controllers, CLI tools, and microservice APIs.
              * Write clean, efficient Go code, integrating with relevant libraries, APIs (Kubernetes, external services), and system interfaces.
              * Implement testing strategies (unit, integration) and participate in code reviews to ensure reliability and correctness across project types.
              * Design and implement deployment artifacts and configurations for containerized applications (controllers, microservices) and package CLIs.
              * Identify and resolve performance issues and resource bottlenecks specific to each application type.
              * Diagnose and fix technical problems in development and production environments.
              * Clearly document designs, code, and usage, and communicate effectively with teams and stakeholders.
        - title: Senior Member of Technical Staff
          company: VMWare By Broadcom
          company_url: https://docs.vmware.com/en/VMware-Tanzu/index.html
          company_logo: tanzu
          location: Remote - Colombia
          date_start: "2021-08-09"
          date_end: "2024-06-03"
          description: |2-
              Responsibilities include:

              * Build an maintain the CLI and some of its plugins for the VMware Tanzu Platform.
              * Designed build and maintain different kubernetes controllers.
              * Built and maintain automated CI/CD pipelines on GitHub and internal Concourse CI/CD Pipelines using Docker, GCP and gitops.
              * Build and maintain several internal tools to help the development of the products.
              * Release and generate documentation for different team products.
              * Mentored junior developers and conducted code reviews to ensure adherence to best practices and maintain high‐quality standards.
        - title: Backend JVM Engineer
          company: Addi
          company_url: https://co.addi.com/
          company_logo: addi
          location: Remote - Colombia
          date_start: "2021-04-01"
          date_end: "2021-08-01"
          description: |2-
              Responsibilities include:

              * Owns the pieces of the platform that you architect, implement, test, deploy, monitor and fix on production.
              * Coordinate services using async queues and reactive programming with Java and Quarkus
              * Maintains and builds the required technical skills to fulfill the responsibilities.
              * Be a team level expert of a particular domain or specific components of the platform.
              * Design, propose and implement new features or fixed in the platform.
              * Build an maintain the back‐end of a digital payments.
              * Help in the shaping of the bets on each cycle
        - title: Senior Software Engineer
          company: Blanc Labs
          company_url: https://blanclabs.com/
          company_logo: blanclabs
          location: Remote - Colombia
          date_start: "2019-04-01"
          date_end: "2021-04-01"
          description: |2-
              Responsibilities include:

              * Cloud development, using PCF (Pivotal Cloud Foundry), also Spring micro‐services technology.
              * Design proposals for commercial lending platforms under architectural procedures and standards established.
              * Development and implementation of a software product for the banking sector. Participation in different phases of the implementation and development of it.
              * Definition of architecture, best practices and guideline of development for different micro‐services used in this project.
              * Develop UI using Angular 8+
              * Coordinate with business the task to be aligned with requirements and current development
        - title: Senior Java Software Engineer
          company: Globant
          company_url: https://www.globant.com/
          company_logo: globant
          location: Remote - Colombia
          date_start: "2015-10-01"
          date_end: "2019-04-01"
          description: |2-
              Responsibilities include:

              * Develop integration components with strong design patterns bases
              * Lead internal projects for sub components developed with Spring Integration
              * Development of micro-services with Java and Spring/Boot for aircraft maintenance
              * Development of different components to interact with async messaging services
              * Design and orchestration of different components
              * Coordinate with other teams the architecture and solutions proposals to be aligned where commons components exist
              * Create microservices, batch, lambdas for the client, this integrated with AWS services, artifacts and projects configuration, maintain legacy projects, integrate services with internal project libraries and services, support of teammates with problem solving and guide on the structure for the projects, document technical process and implementation.
              * BDD and TDD
              * Mentoring junior colleages
        - title: Senior Product Engineer
          company: DragonTech Latinoamerica
          company_url: https://www.linkedin.com/in/dragon-tech-a35aa780/
          company_logo: dragontech
          location: Bogota - Colombia
          date_start: "2013-04-01"
          date_end: "2015-09-01"
          description: |2-
              Responsibilities include:

              * Improve and upgrade the current features in the platform for Contact Centers
              * Keep Asterisk and Java integration upgraded with latest stable releases
              * Add features to the existing in-house platform for Contact Center
              * Develop different contact center IVR flows with an in‐house solution based on jBPM
              * On‐site support
              * Maintain the PostgreSQL Database updated based on the requirements
              * Migrate the front end from jsp to jQuery libraries
              * Design and implement new modules for the in-house platform
              * R&D for new products to offer to Contact Centers
              * Development of a Licencing server for a subscription-based model
              * Lead internal projects
        - title: Ingeniero Junior
          company: ITAC CO
          company_url: https://itac.co
          company_logo: itac
          location: Bogota - Colombia
          date_start: "2012-11-01"
          date_end: "2013-03-01"
          description: |2-
              Responsibilities include:

              * Meet the BAs and QAs so the development will be sync with the requirements
              * Development of user interfaces using Prime Faces for financial institutions 
              * Develop integration back end modules between the platform and the banks using Java with different design patterns
              * Develop SQL scripts for the platform (SQL Server) and the corresponding JPA communications
              * Implement a full workflow for a process in my early days in the project
        - title: Software Engineer
          company: SMS Americas
          company_url: https://products.mobile-americas.com/
          company_logo: smsa
          location: Bogota - Colombia
          date_start: "2011-02-01"
          date_end: "2012-11-01"
          description: |2-
              Responsibilities include:

              * Maintain the infrastructure (Apache, PostgreSQL, Linux Servers) and base scripts (PHP / Python) for each in/out message and the batch processing for massive messages generation
              * Update and develop new flows for SMS depending on the providers requests (games, trivia, subscriptions)
              * Monitoring and analysis of the platform performance and design strategies to improve it
              * Started the migration of the whole platform from PHP to JAVA to run in JBOSS server
              * Design and implement an interface to communicate with a TV provider to show interactive messages
              * Design and implement a mobile application for restaurant promotions
              * Support
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
        - certificate_url: https://www.credly.com/badges/9f1e662a-fe94-4de7-8865-892a6dd2ecf9
          date_end: "2022-10-14"
          date_start: "2022-10-14"
          description: |2-
            Earners of this designation demonstrated the skills, knowledge and competencies to perform the responsibilities of a Kubernetes Application Developer. Earners are able to define application resources and use core primitives to build, monitor, and troubleshoot scalable applications and tools in Kubernetes. The skills and knowledge demonstrated by earners include Core Concepts, Configuration, Multi-Container Pods, Observability, Pod Design, Services & Networking, State Persistence.
          icon: ckad
          organization: The Linux Foundation
          organization_url: https://www.coursera.org
          title: "CKAD: Certified Kubernetes Application Developer"
          url: https://www.credly.com/badges/9f1e662a-fe94-4de7-8865-892a6dd2ecf9
        - certificate_url: https://www.udemy.com/certificate/UC-64d1cc47-7b2d-433c-8c38-47fec846eae7/
          date_end: "2024-06-07"
          date_start: "2024-06-07"
          description: |2-
            Streamline your development by learning how common design patterns are implement in Go.
          icon: udemy
          organization: Udemy
          organization_url: https://www.udemy.com/
          title: "Working with Design Patterns in Go (Golang)"
          url: "https://www.udemy.com/course/working-with-design-patterns-in-go-golang"
        - certificate_url: https://www.udemy.com/certificate/UC-c60e8396-2a0c-4797-9319-ba0ed9f804dc/
          date_end: "2021-05-14"
          date_start: "2021-05-14"
          description: |2-
            The most comprehensive guide that will make you a Software Architect, the most desired role in the software industry.
          icon: udemy
          organization: Udemy
          organization_url: https://www.udemy.com/
          title: "The Complete Guide to Becoming a Software Architect"
          url: "https://www.udemy.com/course/the-complete-guide-to-becoming-a-software-architect"
        - certificate_url: https://www.udemy.com/certificate/UC-2944e6c4-b674-4011-a303-9a3b58f5c529/
          date_end: "2020-09-08"
          date_start: "2020-09-08"
          description: |2-
            Master the fundamentals and advanced features of the Go Programming Language (Golang)
          icon: udemy
          organization: Udemy
          organization_url: https://www.udemy.com/
          title: "Go: The Complete Developer`s Guide (Golang)"
          url: "https://www.udemy.com/course/go-the-complete-developers-guide"
        - certificate_url: https://www.udemy.com/certificate/UC-3eb6b571-cc7c-4a10-a1ab-a52073410c3a/
          date_end: "2020-06-22"
          date_start: "2020-06-22"
          description: |2-
            Learn, build and implement the most powerful AI model at home. Compete with multi-billion dollars companies using ARS.
          icon: udemy
          organization: Udemy
          organization_url: https://www.udemy.com/
          title: "Artificial Intelligence (ARS): Build the Most Powerful AI"
          url: "https://www.udemy.com/course/artificial-intelligence-ars"
    design:
      columns: "2"
  # - block: collection
  #   id: posts
  #   content:
  #     title: Recent Posts
  #     subtitle: ''
  #     text: ''
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       folders:
  #         - post
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: compact
  #     columns: '2'
  # - block: portfolio
  #   id: projects
  #   content:
  #     title: Projects
  #     filters:
  #       folders:
  #         - project
  #     # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  #     default_button_index: 0
  #     # Filter toolbar (optional).
  #     # Add or remove as many filters (`filter_button` instances) as you like.
  #     # To show all items, set `tag` to "*".
  #     # To filter by a specific tag, set `tag` to an existing tag name.
  #     # To remove the toolbar, delete the entire `filter_button` block.
  #     buttons:
  #       - name: All
  #         tag: '*'
  #       - name: Deep Learning
  #         tag: Deep Learning
  #       - name: Other
  #         tag: Demo
  #   design:
  #     # Choose how many columns the section has. Valid values: '1' or '2'.
  #     columns: '1'
  #     view: showcase
  #     # For Showcase view, flip alternate rows?
  #     flip_alt_rows: false
  - block: markdown
    content:
      title: Gallery
      subtitle: ""
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: "1"
  # - block: collection
  #   id: featured
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     columns: '2'
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
  #     columns: '2'
  #     view: citation
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     columns: '2'
  #     view: compact
  # - block: tag_cloud
  #   content:
  #     title: Popular Topics
  #   design:
  #     columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Lets get in contact
      # Contact (add or remove contact options as necessary)
      email: odin.nordico90@gmail.com
      # phone: 888 888 88 88
      appointment_url: "https://calendly.com/dlalfonso/30min"
      # address:
      #   street:
      #   city:
      #   region:
      #   postcode: ''
      #   country: Colombia
      #   country_code: CO
      # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      office_hours:
        - "Monday 09:00 to 17:00"
        - "Tuesday 09:00 to 17:00"
        - "Wednesday 09:00 to 17:00"
        - "Thursday 09:00 to 17:00"
        - "Friday 09:00 to 17:00"
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      coordinates:
        latitude: "4.7248712"
        longitude: "-73.9629956"
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: "https://twitter.com/diego_alfonso_"
        - icon: video
          icon_pack: fas
          name: Zoom Me
          link: "https://us04web.zoom.us/j/3037994640"
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
      columns: "2"
---

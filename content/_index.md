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
  - block: experience
    id: teaching
    content:
      title: Teaching experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Teaching Assistant of Monetary and Financial Macroeconomics
          company: Universidad Carlos III de Madrid
          company_url: 'https://aplicaciones.uc3m.es/cpa/generaFicha?est=202&plan=398&asig=13664&idioma=2'
          company_logo: org-y
          location: Madrid, Spain
          date_start: '2021-09-01'
          date_end: ''
          description: |2-
              Responsibilities include:

              * The course was designed to teach the role of money and other ﬁnancial assets in the economy, the determinants of money                      demand and supply, the role of monetary policy, and the functioning of the money and ﬁnancial markets
              * Teaching 90 minutes per week by reviewing the lecture and solving problem sets and hold weekly oﬃce hours for 50 students.                 Additionally, I prepared a midterm and ﬁnal exams for the course all by myself and graded all their exams
    design:
      columns: '2'    
  - block: contact
    id: contact
    content:
      title: Contact
      email: skocabas@eco.uc3m.es
      address:
        street: Calle Madrid, 126
        city: Getafe, Madrid
        postcode: '28903'
        country: Spain
        country_code: ES
      directions: Economics Department, Universidad Carlos III de Madrid
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/serkankocabas17'
        - icon: skype
          icon_pack: fab
          name: Skype Me
          link: 'skype:serkan.kocabas'
        - icon: video
          icon_pack: fas
          name: Zoom Me
          link: 'https://us05web.zoom.us/j/3089067331?pwd=WlBRbG9Qb3c4SDVJenZTeStzeFR5QT09'
    design:
      columns: '2'
---

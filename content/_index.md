---
date: "2022-10-24"
sections:

- block: about.avatar
  content:
    text: null
    username: admin
  id: about
- block: features
  content:
    items:
    - description: 
      icon: chart-line
      icon_pack: fas
      name: Statistics
    - description: 
      icon: r-project
      icon_pack: fab
      name: R
    - description:
      icon: python
      icon_pack: fab
      name: Python
    - description:
      icon: question
      icon_pack: fas
      name: Analytical Thinking
    - description:
      icon: paragraph
      icon_pack: fas
      name: Academic Writing
    - description: 
      icon: music
      icon_pack: fas
      name: Bass Guitar
    title: Skills
- block: experience
  content:
    date_format: Jan 2006
    items:
    - company: Institute of Strategic Management
      company_logo: 
      company_url: ""
      date_end: ""
      date_start: "2017-07-01"
      description: |2-
          Dissertation: *Content Creation in the Digital Economy - Perspectives on User Behavior*

          * Grade: *summa cum laude*
        
            &nbsp;
        
          The focus of the dissertation was to study various behavioral aspects of users operating on content platforms:
          {style="text-align: justify;"}
          * How do amateurs and (nascent) professional content creators react to change in opportunity costs for content creation?
          {style="text-align: justify;"}
          * How do professional content creators on Twitch compete with each others?
          * How do live streams and tweets affect the market success of video games?
          * How do CEOs communicate on sociopolitical issues and how do their recipients react to their content?
          {style="text-align: justify;"}
          
          
      location: Münster, Germany
      title: PhD Candidate
    - company: University of Osnabrück
      company_logo: 
      company_url: ""
      date_end: "2017-03-31"
      date_start: "2014-04-01"
      description: |2-
        Master Thesis: *On the phenomenon of missing women in South Asia: An overview of the empirical literature* &nbsp;
        {style="text-align: justify;"}
        
        "Missing women" is a term to describe a statistical deficit of women compared to men that should not exist given natural the birth rates of boys and girls.         An explanation for this phenomenon is active discrimination by families who view males as more "valuable" than females, which results in an overtly death          of females and/or unnaturally high birth rates for boys. &nbsp;
        {style="text-align: justify;"}
        
        Main aspects of the thesis:
        * describing reasons and methods for gender discrimination in South Asian countries
        * descriptive analysis of missing women in South Asia
        * an update of the estimates for missing women
        * derivation of policy implications to effectively combat female deficits
        
      location: Osnabrück, Germany
      title: Master of Science in Empirical Economics
    - company: University of Münster
      company_logo: 
      company_url: ""
      date_end: "2013-12-31"
      date_start: "2010-10-01"
      description: |2-
          Bachelor Thesis: *Ökonomische Erklärungsansätze für das bis 2012 gültige Fernreisemonopol der Deutschen Bahn*
          {style="text-align: justify;"}
      
          Main aspects of the thesis:
        * Analyse of competition in the German railway market
        * Description of the formation of the "long-distance travel" monopoly for the *Deutsche Bahn*
        {style="text-align: justify;"}
        * Discussion of the monopoly's continued existence until 2012 despite clear criticism from policy advisors
        {style="text-align: justify;"}
     
      location: Münster, Germany
      title: Bachelor of Science in  Economics
    title: Education
  design:
    columns: "2"
- block: accomplishments
  content:
    date_format: Jan 2006
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
      title: Object-Oriented Programming in R
      url: ""
    subtitle: null
    title: Experience
  design:
    columns: "2"
- block: collection
  content:
    count: 5
    filters:
      author: ""
      category: ""
      exclude_featured: false
      exclude_future: false
      exclude_past: false
      folders:
      - post
      publication_type: ""
      tag: ""
    offset: 0
    order: desc
    subtitle: ""
    text: ""
    title: Recent Posts
  design:
    columns: "2"
    view: compact
  id: posts
- block: portfolio
  content:
    buttons:
    - name: All
      tag: '*'
    - name: Deep Learning
      tag: Deep Learning
    - name: Other
      tag: Demo
    default_button_index: 0
    filters:
      folders:
      - project
    title: Projects
  design:
    columns: "1"
    flip_alt_rows: false
    view: showcase
  id: projects
- block: markdown
  content:
    subtitle: ""
    text: '{{< gallery album="demo" >}}'
    title: Gallery
  design:
    columns: "1"
- block: collection
  content:
    filters:
      featured_only: true
      folders:
      - publication
    title: Featured Publications
  design:
    columns: "2"
    view: card
  id: featured
- block: collection
  content:
    filters:
      exclude_featured: false
      folders:
      - publication
    text: |-
      {{% callout note %}}
      Quickly discover relevant content by [filtering publications](./publication/).
      {{% /callout %}}
    title: Recent Publications
  design:
    columns: "2"
    view: citation
- block: collection
  content:
    filters:
      folders:
      - event
    title: Recent & Upcoming Talks
  design:
    columns: "2"
    view: compact
  id: talks

- block: contact
  content:
    
      
    email: philipwollborn@gmx.de
   
    title: Contact
  design:
    columns: "2"
  id: contact
title: null
type: landing
---

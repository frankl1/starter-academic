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
        - name: Machine/Deep Learning
          description: 90%
          icon: chip
          icon_pack: custom
        - name: Python
          description: 90%
          icon: python
          icon_pack: fab
        - name: Pytorch
          description: 90%
          icon: pytorch
          icon_pack: custom
        - name: TensorFlow
          description: 90%
          icon: tensorflow
          icon_pack: custom
        - name: Analytics
          description: 90%
          icon: chart-line
          icon_pack: fas
        - name: Java
          description: 90%
          icon: java
          icon_pack: fab
  - block: experience
    id: experiences
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
        - title: "Machine Learning Researcher "
          company: "Huawei Ireland Research"
          company_url: "https://limos.fr"
          location: "Dublin, Ireland"
          date_start: "2022-12-12"
          date_end: ""
          description: "Use machine learning to achieve the Autonomous Driving Network (ADN). This position implies techniques such as time series analysis, anomaly detection and explainable artificial intelligence."
        - title: "Machine Learning Researcher "
          company: "Laboratory of Informatic, Modelling and Optimization of System - LIMOS"
          company_url: "https://limos.fr"
          location: "Aubiere, France"
          date_start: "2019-10-01"
          date_end: "2022-10-31"
          description: "
          Design and build innovative algorithms for the analysis of uncertain time series. The first step focuses on the classification of uncertain time series."
        - title: "Machine Learning Junior Researcher"
          company: "Laboratory of Informatic, Modelling and Optimization of System - LIMOS"
          company_url: "https://limos.fr"
          location: "Aubiere, France"
          date_start: "2019-04-01"
          date_end: "2019-09-30"
          description: "Develop a new shapelet algorithm for the classification of uncertain time series data. Here I used the techniques of uncertainty propagation and adapted the well known and appreciated Shapelet Transform algorithm to the context of uncertain time series classification. This experience has succesfully ended with a communication at the *Learning From Data Stream and Time Series* workshop"
        - title: "Machine Learning Junior Researcher"
          company: "Department of Computer Science - University of Yaounde I "
          company_url: ""
          location: "Yaounde, Cameroon"
          date_start: "2017-06-01"
          date_end: "2018-09-01"
          description: "Design and build a novel framework for named entity recognition in low-resource languages. In this experience, I build a novel approach using distributional word representation coupled to neural network"
        - title: "Applied Researcher"
          company: "Ibaas Labs"
          company_url: ""
          location: "Yaounde, Cameroon"
          date_start: "2016-06-01"
          date_end: "2019-09-01"
          description: |2- 
            I worked in a team in order to:
            
            1. Build a professional social network to improve job delivery. The system must help project owners to quickly find the best experts for their job. For experts, the system must help them find the most appropriate tools given a job. 
            
            2. Build an entertainment social network application.  

            We have developed the android application Jooka and a Software Delivery Engine platform.
    design:
      columns: '2'
  - block: accomplishments
    id: accomplishements
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
        - organization: "Coursera"
          organization_url: "https://www.coursera.org"
          title: "Deep Learning Specialization"
          url: "https://www.coursera.org/specializations/deep-learning"
          certificate_url: "https://www.coursera.org/account/accomplishments/specialization/certificate/9KPM47PGQAN2"
          date_start: "2020-07-06"
          date_end: "2020-07-21"
          description: "In five courses, you will learn the foundations of Deep Learning, understand how to build neural networks, and learn how to lead successful machine learning projects. You will learn about Convolutional networks, RNNs, LSTM, Adam, Dropout, BatchNorm, Xavier/He initialization, and more. You will work on case studies from healthcare, autonomous driving, sign language reading, music generation, and natural language processing. You will master not only the theory, but also see how it is applied in industry. You will practice all these ideas in Python and in TensorFlow, which we will teach."
        - organization: "Fun-Mooc"
          organization_url: "https://www.fun-mooc.fr"
          title: "Research integrity in scientific professions"
          url: "https://www.fun-mooc.fr/courses/course-v1:Ubordeaux+28007+session02/info"
          certificate_url: "https://www.fun-mooc.fr/media/attestations/attestation_suivi_course-v1:Ubordeaux+28007+session02_68b961fdec62869fa1ff0e7828f60288.pdf"
          date_start: "2020-06-01"
          date_end: "2020-07-01"
          description: "Learn the integrity principles (Reliability, Honesty, Respect and Responsibility) that must gouvern any scientific reasearch"
        - organization: "Coursera"
          organization_url: "https://www.coursera.org"
          title: "Practical Time Series Analysis"
          url: "https://www.coursera.org/learn/practical-time-series-analysis"
          certificate_url: ""
          date_start: "2020-03-20"
          date_end: "2020-05-10"
          description: "This course starts by teaching the stochastic processes behind any time series. I have learnt to estimate the parameters of such stochastic processes. I have finally learnt time series analysis models MA(q), AR(p), ARMA(p,q), ARIMA(p,q,d), SARIMA(p,q,d,s) and Holt-Winters, and applied them on different datasets using the R programming language"
        - organization: "Udacity"
          organization_url: "https://www.udacity.com"
          title: "Intro to TensorFlow for Deep Learning"
          url: "https://www.udacity.com/course/intro-to-tensorflow-for-deep-learning--ud187"
          certificate_url: ""
          date_start: "2019-10-01"
          date_end: "2020-02-01"
          description: "A practical introduction to deep learning using tensorflow. In this course, I learnt how do feedforward neural network, convotional neural network and recurrent neural network work. I have also learnt about data augmentation and time series forecasting. I use the Kera api through tensorflow to build all my models"
        - organization: "Fun-Mooc"
          organization_url: "https://www.fun-mooc.fr"
          title: "Reproducible Research: Methodological Principles for Transparent Science"
          url: "https://www.fun-mooc.fr/courses/course-v1:inria+41016+session02/about"
          certificate_url: "https://www.fun-mooc.fr/media/attestations/attestation_suivi_course-v1:inria+41016+session02_4a1aa17674400f80452c7d0202eb0a83.pdf"
          date_start: "2019-04-01"
          date_end: "2019-06-01"
          description: "In this course, I have enjoyed learning about reproducibility in science. And also, about the importance of transparent science. After this course, I was able to correctly share all the necessary materials in order to let anyone to reproduce my work"
        - organization: "Coursera"
          organization_url: "https://www.coursera.org"
          title: "Machine Learning"
          url: "https://www.coursera.org/learn/machine-learning"
          certificate_url: ""
          date_start: "2017-06-01"
          date_end: "2017-08-30"
          description: "I discovered Machine Learning with this course, taught by the amazing professor Andrew Ng. I have learnt the fundamental of machine learning. I have learnt regression, classification and clustering models. I have also studied anomaly detection and recommender systems."
    design:
      columns: '2'
  # - block: collection
  #   id: posts
  #   content:
  #     title: Recent Posts
  #     subtitle: ''
  #     text: ''
  #     # Choose how many pages you would like to display (0: all pages)
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
        - name: Time series
          tag: Time series
        - name: Android
          tag: Android app
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  # - block: markdown
  #   content:
  #     title: Gallery
  #     subtitle: ''
  #     text: |-
  #       {{< gallery album="demo" >}}
  #   design:
  #     columns: '1'
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
  # - block: contact
  #   id: contact
  #   content:
  #     title: Contact
  #     subtitle:
  #     text: |-
  #       Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
  #     # Contact (add or remove contact options as necessary)
  #     email: test@example.org
  #     phone: 888 888 88 88
  #     appointment_url: 'https://calendly.com'
  #     address:
  #       street: 450 Serra Mall
  #       city: Stanford
  #       region: CA
  #       postcode: '94305'
  #       country: United States
  #       country_code: US
  #     directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
  #     office_hours:
  #       - 'Monday 10:00 to 13:00'
  #       - 'Wednesday 09:00 to 10:00'
  #     contact_links:
  #       - icon: twitter
  #         icon_pack: fab
  #         name: DM Me
  #         link: 'https://twitter.com/Twitter'
  #       - icon: skype
  #         icon_pack: fab
  #         name: Skype Me
  #         link: 'skype:echo123?call'
  #       - icon: video
  #         icon_pack: fas
  #         name: Zoom Me
  #         link: 'https://zoom.com'
  #     # Automatically link email and phone or display as text?
  #     autolink: true
  #     # Email form provider
  #     form:
  #       provider: netlify
  #       formspree:
  #         id:
  #       netlify:
  #         # Enable CAPTCHA challenge to reduce spam?
  #         captcha: false
  #   design:
  #     columns: '2'
---

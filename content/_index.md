---
# Leave the homepage title empty to use the site title
title:
date: 2023-08-16
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: markdown
    id: announcement
    content:
      title: Group Announcements
      subtitle:
      text: Full list of announcements <a href="./announcements/">here</a><br /><br /><b>02/2026</b><br />Congratulations to Nathan Erickson and Evan Sudler for winning presentation awards at the recent AMS Annual Meeting! The CHAOS group had over 10 presentations at the recent national meeting<br /><br />In January, former undergraduate researcher Evan White had his work on postprocessing AI weather prediction models published in AIES - <a href="https://journals.ametsoc.org/view/journals/aies/5/1/AIES-D-25-0065.1.xml">read more here!</a><br /><br /><b>08/01/2025</b><br />Congratulations to Christian McGinty for winning a presentation award for his poster on TORFF outlooks at the recent AMS Mesoscale conference! Hanna McDaniel and Kelly Geiger also presented their M.S. work at AMS Mesoscale for their first graduate school conference presentations!<br /><br /> In July, Evan White became the first student in the CHAOS group to submit a manuscript to a science journal, AIES - Evan’s project on postprocessing AI weather prediction models adds to a growing list of prediction systems for severe weather hazards.<br /><br /> Our summer REU student Ian Shank presented his final REU project in late July before we had to say goodbye for the summer. Ian completed an in-depth quantitative analysis of machine learning-based forecasts of severe weather and their utility at extended ranges.<br /><br /><b>05/22/2025</b><br />This summer, Ian Shank from UNC Charlotte will be an REU student in the group! Ian will be evaluating machine learning forecasts of severe weather to generate additional statistics and value for our operational partners.<br /><br /><b>04/25/2025</b><br />Welcome Mandy Voth and Braelyn Long to the group, two new undergraduate researchers! Both will be working on understanding the environmental evolution preceeding tornadogenesis with QLCS mesovortices.


#  - block: features
#    content:
#      title: Skills
#      items:
#        - name: R
#          description: 90%
#          icon: r-project
#          icon_pack: fab
#        - name: Statistics
#          description: 100%
#          icon: chart-line
#          icon_pack: fas
#        - name: Photography
#          description: 10%
#          icon: camera-retro
#          icon_pack: fas
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
        - title: Assistant Professor
          company: University of Oklahoma
          company_logo: OU-Logo
          location: Norman, Oklahoma
          date_start: '2023-08-16'
          date_end: ''
          description: |2-
              Classes taught:
              * METR 4970/5970: Numerical Weather Prediction (Fall 2025)
              * METR 1313: Introduction to Programming for Meteorology (Spring 2024, 2025, 2026)
              * METR 5970: AI for Environmental Science (Fall 2024, 2026)
        - title: Research Scientist (I/II)
          company: Colorado State University
          company_url: ''
          company_logo: CSU_Logo
          location: Fort Collins, CO
          date_start: '2021-07-01'
          date_end: '2023-08-11'
#           description: |2-
#              Responsibilities included:
#
#              * Deploying
        - title: Postdoctoral Research Fellow
          company: Colorado State University
          company_url: ''
          company_logo: CSU_Logo
          location: Fort Collins, CO
          date_start: '2019-07-01'
          date_end: '2021-06-30'
          description: ''
        # - title: Graduate Research Assistant
        #   company: Texas Tech University
        #   company_url: ''
        #   company_logo: TTU_Logo
        #   location: Lubbock, TX
        #   date_start: '2012-09-01'
        #   date_end: '2019-08-15'
        # - title: Instructor
        #   company: Texas Tech University
        #   company_url: ''
        #   company_logo: TTU_Logo
        #   location: Lubbock, TX
        #   date_start: '2019-07-01'
        #   date_end: '2021-06-30'
        #   description: |2-
        #       Classes taught:

        #       * ATMO 1300: Introduction to Atmospheric Science
        # - title: Graduate Student Visitor
        #   company: National Center for Atmospheric Research
        #   company_url: ''
        #   company_logo: NCAR_Logo
        #   location: Boulder, CO
        #   date_start: '2018-06-01'
        #   date_end: '2018-08-31'
        #   description: ''
        # - title: Graduate Writing Tutor
        #   company: Texas Tech University
        #   company_url: ''
        #   company_logo: TTU_Logo
        #   location: Lubbock, TX
        #   date_start: '2016-07-01'
        #   date_end: '2018-06-01'
        #   description: ''            
    design:
      columns: '2'
#  - block: accomplishments
#    content:
#      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
#      title: 'Accomplish&shy;ments'
#      subtitle:
#      # Date format: https://wowchemy.com/docs/customization/#date-format
#      date_format: Jan 2006
#      # Accomplishments.
#      #   Add/remove as many `item` blocks below as you like.
#      #   `title`, `organization`, and `date_start` are the required parameters.
#      #   Leave other parameters empty if not required.
#      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
#      items:
#        - certificate_url: https://www.coursera.org
#          date_end: ''
#          date_start: '2021-01-25'
#          description: ''
#          organization: Coursera
#          organization_url: https://www.coursera.org
#          title: Neural Networks and Deep Learning
#          url: ''
#        - certificate_url: https://www.edx.org
#          date_end: ''
#          date_start: '2021-01-01'
#          description: Formulated informed blockchain models, hypotheses, and use cases.
#          organization: edX
#          organization_url: https://www.edx.org
#          title: Blockchain Fundamentals
#          url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
#        - certificate_url: https://www.datacamp.com
#          date_end: '2020-12-21'
#          date_start: '2020-07-01'
#          description: ''
#          organization: DataCamp
#          organization_url: https://www.datacamp.com
#          title: 'Object-Oriented Programming in R'
#          url: ''
#    design:
#      columns: '2'
#  - block: collection
#    id: posts
#    content:
#      title: Recent Posts
#      subtitle: ''
#      text: ''
#      # Choose how many pages you would like to display (0 = all pages)
#      count: 5
#      # Filter on criteria
#      filters:
#        folders:
#          - post
#        author: ""
#        category: ""
#        tag: ""
#        exclude_featured: false
#        exclude_future: false
#        exclude_past: false
#        publication_type: ""
#      # Choose how many pages you would like to offset by
#      offset: 0
#      # Page order: descending (desc) or ascending (asc) date.
#      order: desc
#    design:
#      # Choose a layout view
#      view: compact
#      columns: '2'
  - block: portfolio
    id: research
    content:
      title: Research Areas
      filters:
        folders:
          - research
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: AI/ML Applications
          tag: Machine Learning
        - name: Predictability
          tag: predictability
        - name: Convection Dynamics
          tag: dynamics

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
    id: rec_pubs
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '2'
      view: citation
  - block: collection
    id: presentations
    content:
      title: Recent Presentations
      text: |-
        Full list of presentations <a href="./presentations/">here</a>

        Shank, I. and <b>A. J. Hill</b>, 2026: <u>Assessing Machine Learning Probabilistic Forecast Utility for Severe Weather Forecasting</u>. 25th Annual Student Conference, Houston, TX.

        Sudler, E., <b>A. J. Hill</b>, and C. R. Homeyer, 2026: <u>Artificial Intelligence Weather Prediction Model Performance for Hurricane Helene (2024)</u>. 25th Conference on Artificial Intelligence for Environmental Science, Houston, TX.

        Schumacher, R. S., <b>A. J. Hill</b>, A. J. Tomanek, and J. A. Smith, 2026: <u>Extreme Short-Term Precipitation in Gridded Precipitation Analyses and the CONUS404 Regional Climate Simulation</u>. 40th Conference on Hydrology, Houston, TX.

        McDaniel, H. J. and <b>A. J. Hill</b>, 2026: <u>An Assessment of Mesovortices in Quasi-Linear Convective Systems from 2013-2023 Using GridRad-Severe</u>. 16th Conference on Transition of Research to Operations, Houston, TX. 

        Vicens-Miquel, M., A. McGovern, <b>A. J. Hill</b>, E. G. Foufoula-Georgiou, C. Guilloteau, and S. S. Shen, 2026: <u>A Diffusion-Based Framework for 1-km Spatial Resolution Precipitation Forecasting over CONUS</u>. 25th Conference on Artificial Intelligence for Environmental Science, Houston, TX.

        Spicer, E., P. M. Klein, <b>A. J. Hill</b>, and C. Wang, 2026: <u>A Novel Approach to Nocturnal Heat Risk Analysis Using Machine Learning and the Unrestricted Mesoscale Analysis</u>. 16th Symposium on Urban Environment, Houston, TX.

        <b>Hill, A. J.</b>, M. Voth, and B. Long, 2026: <u>Characterizing Environmental Evolution in Advance of Tornadic and Non-Tornadic Mesovortices with PERiLS Field Campaign Datasets and High-Resolution Simulations</u>. 16th Conference on Transition of Research to Operations, Houston, TX. 

        Erickson, N., A. McGovern, and <b>A. J. Hill</b>, 2026: <u>Deep Learning for Probabilistic Nowcasting of Radar Reflectivity in Tornadic Storms</u>. 25th Conference on Artificial Intelligence for Environmental Science, Houston, TX.

        Geiger, K. M., <b>A. J. Hill</b>, and R. S. Schumacher, 2026: <u>Environmental Influences on Extreme and Less-Extreme Nocturnal Summertime Extreme Rainfall Events in the United States</u>. 40th Conference on Hydrology, Houston, TX.

        Fellman, B. J., H. E. Brooks, J. T. Ripberger, P. T. Marsh, S. R. Ernst, <b>A. J. Hill</b>, and M. Krocak, 2026: <u>The Calm Before the Storm: A Climatological Overview of the Storm Prediction Center's Day 4-8 Severe Weather Outlook</u>. Third Symposium on the Future of Weather, Forecasting and Practice, Houston, TX.

        White, E. and <b>A. J. Hill</b>, 2026: <u>AI-MLP: Severe Weather Probabilities from Global AI Weather Models</u>. 16th Conference on Transition of Research to Operations, Houston, TX. 

        Williams, J. K., A. McGovern, P. E. Tissot, J. L. Demuth, D. J. Gagne, D. R. Harrison, <b>A. J. Hill</b>, K. Musgrave, and C. D. Wirz, 2026: <u>R2O lessons learned from the NSF AI Institute AI2ES</u>. 16th Conference on Transition of Research to Operations, Houston, TX. 

      filters:
        folders:
          - presentations
    design:
      columns: '2'
      view: citation
#  - block: tag_cloud
#    content:
#      title: Popular Topics
#    design:
#      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
#      text: |-
#        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: ahill@ou.edu
#      phone: 888 888 88 88
#      appointment_url: 'https://calendly.com'
      address:
        street: 120 David L. Boren Blvd Suite 5900
        city: Norman
        region: OK
        postcode: '73072'
        country: United States
        country_code: US
#      directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
#      office_hours:
#        - 'Monday 10:00 to 13:00'
#        - 'Wednesday 09:00 to 10:00'
#      contact_links:
#        - icon: twitter
#          icon_pack: fab
#          name: DM Me
#          link: 'https://twitter.com/DrAaronHill'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
#      form:
#        provider: netlify
#        formspree:
#          id:
#        netlify:
#          # Enable CAPTCHA challenge to reduce spam?
#          captcha: false
    design:
      columns: '2'
---

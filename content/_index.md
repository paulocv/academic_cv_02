---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "1rem"

sections:
#  # Hero Block – A hero I designed with a landing sentence
#  # ===================================
#  - block: hero
#    id: landing-page
#    content:
##      title: Combining computational and theoretical skills to study epidemics
#      title: Mathematical and computational skills to inform policymaking
#      text: Paulo Cesar Ventura, Postdoctoral Fellow at Indiana University
#      primary_action:
#        text: About me
#        url: /#my-resume
#        icon: arrow-down
#      secondary_action:
#        text: My experience
#        url: /experience
##      announcement:
##        text: "Announcing the release of version 1."
##        link:
##          text: "Read more"
##          url: "/blog/"
#    design:
#      spacing:
#          # Customize the section spacing. Order is top, right, bottom, left.
#        padding: ['0px', '0', '0px', '0']
#        margin:  ['50px', '500px', 0, 0]  # Not working so far...
#      css_class: dark  # Use this to force the dark style (e.g. for always-white text)
#      background:
#        color: black
#        image:
#          # Add your image background to `assets/media/`.
##          filename: stacked-peaks.svg
#          filename: symbols_bg.svg
#          filters:
#            brightness: 1.0
#          size: cover
#          position: center
#          parallax: false
#    

    # Resume block
    # ===================================
  - block: resume-biography-3
    id: my-resume
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
#      button:
#        text: Download CV
#        url: uploads/resume.pdf
    design:
#      css_class: dark
#      background:
#        color: rgb(59 130 246)
#        image:
#          # Add your image background to `assets/media/`.
#          filename: stacked-peaks.svg
#          filters:
#            brightness: 1.0
#          size: cover
#          position: center
#          parallax: true
      spacing:
      # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['50px', '00px', '200px', '00px']
#        margin: ['0px','0px','900px','0px',]
    
    
#    # =======================================
#    # Just a striking sentence markdown block
#    # =======================
#  - block: markdown
#    content:
#      title: ''
#      subtitle: ''
#      text: |-
#            ## "Striking sentence can come here"
#            - [Check my experience and skills](/publication)
#      
#    design:
#      
#        spacing:    
#            # Customize the section spacing. Order is top, right, bottom, left.
#            padding: ['10px', '00px', '200px', '00px']


    # "My research" block
    # =======================
  - block: markdown
    content:
      title: 'Research interests (active)'
      subtitle: ''
      text: |-
        
        - Computational modeling of infectious diseases, with applications to ongoing public health concerns
        - Vector-borne diseases and mosquito population dynamics
        - Respiratory diseases forecasting and scenario projection

    design:
      columns: '1'
      spacing:
      # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['20px', '20px', '0px', '20px']
      


#    # "Current projects" block
#    # =======================
#  - block: markdown
#    content:
#      title: 'Current Projects'
#      subtitle: ''
#      text: |-
#
#        - **Respiratory infectious diseases modeling** through agent-based and compartmental approaches.
#        - **Forecasting of respiratory diseases** incidence through a Bayesian approach, collaborating with forecasting initiatives of the CDC.
#        - **Forecasting of relative mosquito abundance** in urban areas, using a Bayesian approach adapted from the method for respiratory diseases.
#        - Daily patterns of **human exposure to mosquito bites**, through a statistical analysis of human time use and mosquito diel activity data.
#        
#  #        - Agent-based modeling of respiratory infectious diseases, aimed at understanding transmission patterns, addressing the impact of interventions (e.g. contact tracing, individual isolation, vaccination) and testing new modeling frameworks. 
#
##        I am a Computational Epidemiology researcher specializing in data-driven models to help addressing public health challenges. With a PhD in Physics, I bring expertise in programming and advanced tools for modeling contagion dynamics through agent-based, age-structured and metapopulation simulations, as well as statistical analysis. My work is fueled by curiosity and a commitment to efficiency, so I am continuously learning new skills and tools that enhance productivity for myself and my team. My goal is to improve public wellbeing delivering precise evidence to inform decision-making on infectious diseases.
#        
##        Use this area to speak to your mission. I'm a research scientist in the Moonshot team at DeepMind. I blog about machine learning, deep learning, and moonshots.
##
##        I apply a range of qualitative and quantitative methods to comprehensively investigate the role of science and technology in the economy.
#        
#    design:
#      columns: '1'
#      spacing:
#      # Customize the section spacing. Order is top, right, bottom, left.
#        padding: ['70px', '20px', '0px', '20px']
##        margin: ['10px','20px','0px','0px',]
      
  # Featured Publications / Papers 
  # =====================================
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
      spacing:
      # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['70px', '20px', '0px', '20px']
      

  - block: cta-card
    demo: false # Only display this section in the Hugo Blox Builder demo site
    content:
      title: Theory meets practice
      text: |-
        Combining my theoretical background with my experience in applied computational modeling,
        I help our research team to provide evidence-based insights in epidemiology. 
        
        At the CEPH lab, we have worked with public health institutions by providing 
        <a href="/project/forecasting-respiratory/">forecasts of respiratory diseases</a>. 
         We also developed a <a href="/project/mosquito-forecasts/">mosquito abundance forecasting tool</a>, 
        in partnership with local health and vector control authorities in the USA. 
        We also work on fundamental research, unveilling transmission patterns of respiratory infections
        using <a href="/project/vibes/">mechanistic</a> and statistical modeling approaches.
        
        I have also developed an <a href="https://episimu-dash2025.netlify.app/">educational tool</a> 
        for students to practice their decision-makers skills during class, used since 2023 at IU. 
        
        <b>I am driven by curiosity and I'm always eager to work on new topics and improve my skills.</b> 
        
      button:
        text: Check all my projects
        url: /projects
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-900"
        css_style: ""
        

    # ==========================
    # Recent publications
    # ==========================
    
  - block: collection
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
      spacing:
      # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['100px', '20px', '0px', '20px']
  
#  # Talks
#  # =====================================
#  - block: collection
#    id: talks
#    content:
#      title: Talks
#      filters:
#        folders:
#          - event
#    design:
#      view: article-grid
#      columns: 1
  
  # News (OMITTED)
  # =====================================
#  - block: collection
#    id: news
#    content:
#      title: Recent News
#      subtitle: ''
#      text: ''
#      # Page type to display. E.g. post, talk, publication...
#      page_type: post
#      # Choose how many pages you would like to display (0 = all pages)
#      count: 5
#      # Filter on criteria
#      filters:
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
#      view: date-title-summary
#      # Reduce spacing
#      spacing:
#        padding: [0, 0, 0, 0]


#  - block: cta-card
#    demo: false # Only display this section in the Hugo Blox Builder demo site
#    content:
#      title: I 
#      text: |-
#        This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.
#        
#        <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>
#
#        Easily build anything with blocks - no-code required!
#        
#        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
#      button:
#        text: Get Started
#        url: https://hugoblox.com/templates/
#    design:
#      card:
#        # Card background color (CSS class)
#        css_class: "bg-primary-900"
#        css_style: ""

---

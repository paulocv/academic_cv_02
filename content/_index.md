---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "1rem"

sections:
  # Hero Block
  # ===================================
  - block: hero
    id: landing-page
    content:
#      title: Combining computational and theoretical skills to study epidemics
      title: Mathematical and computational skills to inform policymaking
      text: Paulo Cesar Ventura, Postdoctoral Fellow at Indiana University
      primary_action:
        text: About me
        url: /#my-resume
        icon: arrow-down
#      secondary_action:
#        text: Read the docs
#        url: https://docs.hugoblox.com
#      announcement:
#        text: "Announcing the release of version 1."
#        link:
#          text: "Read more"
#          url: "/blog/"
    design:
      spacing:
          # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['0px', '0', '0px', '0']
        margin:  ['50px', '500px', 0, 0]  # Not working so far...
      css_class: dark  # Use this to force the dark style (e.g. for always-white text)
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
#          filename: stacked-peaks.svg
          filename: symbols_bg.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  
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
      background:
#        color: black
#        image:
#          # Add your image background to `assets/media/`.
#          filename: stacked-peaks.svg
#          filters:
#            brightness: 1.0
#          size: cover
#          position: center
#          parallax: true


    # "My research" block
    # =======================
  - block: markdown
    content:
      title: 'My Research'
      subtitle: ''
      text: |-
        
        - Agent-based modeling of respiratory infectious diseases, aimed at understanding transmission patterns, addressing the impact of interventions (e.g. contact tracing, individual isolation, vaccination) and testing new modeling frameworks. 
        - Bayesian approach to forecast the incidence of respiratory diseases, collaborating with the CDC forecasting initiatives.
        - Statistical analysis of human time use data and mosquito diel activity, revealing daily patterns and social determinants of human exposure to mosquito bites. 
        - Bayesian approach to forecast the abundance of _Aedes aegypti_ in urban areas of the United States – adapted from the methodology used for respiratory diseases. 
        
        

#        I am a Computational Epidemiology researcher specializing in data-driven models to help addressing public health challenges. With a PhD in Physics, I bring expertise in programming and advanced tools for modeling contagion dynamics through agent-based, age-structured and metapopulation simulations, as well as statistical analysis. My work is fueled by curiosity and a commitment to efficiency, so I am continuously learning new skills and tools that enhance productivity for myself and my team. My goal is to improve public wellbeing delivering precise evidence to inform decision-making on infectious diseases.
        
#        Use this area to speak to your mission. I'm a research scientist in the Moonshot team at DeepMind. I blog about machine learning, deep learning, and moonshots.
#
#        I apply a range of qualitative and quantitative methods to comprehensively investigate the role of science and technology in the economy.
        
    design:
      columns: '1'
      spacing:
      # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['70px', '20px', '0px', '20px']
#        margin: ['10px','20px','0px','0px',]
      
  # Publications / Papers 
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
  
  # Talks
  # =====================================
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1
  
  # News
  # =====================================
  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
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
      view: date-title-summary
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]

#  - block: cta-card
#    demo: true # Only display this section in the Hugo Blox Builder demo site
#    content:
#      title: 👉 Build your own academic website like this
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
#        css_class: "bg-primary-700"
#        css_style: ""
---

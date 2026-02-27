---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: bingkai
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/CV.pdf
      headings:
        about: ''
        education: 'Education and Training'
        interests: 'Research Topics'
    design:
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      background:
        gradient_mesh:
          enable: true

      # Name heading sizing to accommodate long or short names
      name:
        size: md # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    id: papers
    content:
      title: 'Selected publications'
      text: |
        - **Bingkai Wang**, Michael O. Harhay, Jiaqi Tong, Dylan S. Small, Tim P. Morris, and Fan Li.  
        On the mixed-model analysis of covariance in cluster-randomized trials.
        _Statistical Science_, 41(1), 49–68, 2026.
        - **Bingkai Wang**, Fan Li, and Rui Wang.  
        Handling incomplete outcomes and covariates in cluster-randomized trials: doubly-robust estimation, efficiency considerations, and sensitivity analysis.  
        _Biometrics_, in press, 2026.
        - **Bingkai Wang** and Fan Li. 
        On flexible covariate adjustment under covariate-constrained randomization.
        _Clinical Trials_, in press 2026.
        - Fan Li, Jiaqi Tong, Chao Cheng, Xi Fang, Brennan Kahan, and **Bingkai Wang**.  
        Model-robust standardization in cluster-randomized trials.  
        _Statistics in Medicine_, in press, 2025.
        - Mengxin Yu, Kendrick Qijun Li, Nicholas Jewell, Eric Tchetgen Tchetgen, Dylan Small, Xu Shi, and **Bingkai Wang**.  
        Test-negative designs with various reasons for testing: statistical bias and solution.  
        *Epidemiology*, in press, 2025.
        - **Bingkai Wang** and Yu Du.  
         Improving the mixed model for repeated measures to robustly increase precision in randomized trials.  
         *The International Journal of Biostatistics*, 20(2), 585–598, 2024.
        - **Bingkai Wang**, Chan Park, Dylan S. Small, and Fan Li.  
         Model-robust and efficient covariate adjustment for cluster-randomized experiments.  
         *Journal of the American Statistical Association*, 2024, 1–13.
        - **Bingkai Wang**, Xueqi Wang, and Fan Li.  
         How to achieve model-robust inference in stepped wedge trials with model-based methods?  
         *Biometrics*, 80(4), ujae123, 2024.
        - **Bingkai Wang**, Suzanne M. Dufault, Dylan S. Small, and Nicholas P. Jewell.  
         Randomization inference for cluster-randomized test-negative designs with application to Dengue studies: Unbiased estimation, partial compliance, and stepped-wedge design.  
         *The Annals of Applied Statistics*, 17(2), 1592–1614, 2023.
        - **Bingkai Wang**, Ryoko Susukida, Ramin Mojtabai, Masoumeh Amin-Esmaeili, and Michael Rosenblum.  
         Model-robust inference for clinical trials that improve precision by stratified randomization and covariate adjustment.  
         *Journal of the American Statistical Association*, 118(542), 1152–1163, 2023.  
        - **Bingkai Wang**, Brian S. Caffo, Xi Luo, Chin-Fu Liu, Andreia V. Faria, Michael I. Miller, and Yi Zhao.  
          Regularized regression on compositional trees with application to MRI analysis.  
          *Journal of the Royal Statistical Society: Series C*, 71(3), 541–561, 2022.
        - **Bingkai Wang**, Xi Luo, Yi Zhao, and Brian Caffo.  
          Semiparametric partial common principal component analysis for covariance matrices.  
          *Biometrics*, 77(4), 1175–1186, 2021.
        - **Bingkai Wang**, Elizabeth L. Ogburn, and Michael Rosenblum.  
          Analysis of covariance in randomized trials: More precision and valid confidence intervals, without model assumptions.  
          *Biometrics*, 75(4), 1391–1400, 2019.
    design:
      columns: '1'

  # - block: collection
  #   id: papers
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publications
  #       featured_only: true
  #   design:
  #     view: article-grid
  #     columns: 2
  # - block: collection
  #   content:
  #     title: Selected Publications
  #     text: ''
  #     filters:
  #       folders:
  #         - publications
  #       # exclude_featured: false
  #   design:
  #     view: citation
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - events
  #   design:
  #     view: card
  - block: collection
    id: news
    content:
      title: Blogs
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: blog
      # Choose how many pages you would like to display (0 = all pages)
      count: 10
      # Filter on criteria
      filters:
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ''
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: card
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
  # - block: cta-card
  #   demo: true # Only display this section in the HugoBlox Kit demo site
  #   content:
  #     title: 👉 Build your own academic website like this
  #     text: |-
  #       This site is generated by HugoBlox Kit - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.
  # 
  #       <a class="github-button" href="https://github.com/HugoBlox/kit" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/kit on GitHub">Star</a>
  # 
  #       Easily build anything with blocks - no-code required!
  # 
  #       From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
  #     button:
  #       text: Get Started
  #       url: https://hugoblox.com/templates/
  #   design:
  #     card:
  #       # Card background color (CSS class)
  #       css_class: 'bg-primary-300 dark:bg-primary-700'
  #       css_style: ''
---

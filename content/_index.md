---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: hero
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: Hugo Academic Theme
      image:
        filename: hero-academic.png
      cta:
        label: '**Get Started**'
        url: https://hugoblox.com/templates/
      cta_alt:
        label: Ask a question
        url: https://discord.gg/z8wNYzb
      cta_note:
        label: >-
          <div style="text-shadow: none;"><a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star Hugo Blox Builder</a></div><div style="text-shadow: none;"><a class="github-button" href="https://github.com/HugoBlox/theme-academic-cv" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star the Academic template</a></div>
      text: |-
        **Generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 500,000+ sites.**

        **Easily build anything with blocks - no-code required!**

        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.

        <!--Custom spacing-->
        <div class="mb-3"></div>
        <!--GitHub Button JS-->
        <script async defer src="https://buttons.github.io/buttons.js"></script>
    design:
      background:
        gradient_end: '#1976d2'
        gradient_start: '#004ba0'
        text_color_light: true
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  # - block: news
  #     content:
  #       # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
  #       title: 'News&shy;ments'
  #       subtitle:
  #       # Date format: https://docs.hugoblox.com/customization/#date-format
  #       date_format: Jan 2006
  #       # Accomplishments.
  #       #   Add/remove as many `item` blocks below as you like.
  #       #   `title`, `organization`, and `date_start` are the required parameters.
  #       #   Leave other parameters empty if not required.
  #       #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #       items:
  #         - organization: Neurips 2023 Workshop on Diffusion Models
  #           date_end: ''
  #           date_start: '2023-10-28'
  #           title: Our paper "Denoising Heat-inspired Diffusion with Insulators for Collision Free Motion Planning" has been accepted to NeurIPS 2023 Workshop on Diffusion Models.
  #           url: 'https://neurips.cc/virtual/2023/74866 '
  #     design:
  #       columns: '2'
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
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      # Contact (add or remove contact options as necessary)
      email: skysood97@gmail.com, junwoochang@yonsei.ac.kr
      address:
        street: Yonsei University ASIC Laboratory
        city: Seoul
        postcode: '03722'
        country: South Korea
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

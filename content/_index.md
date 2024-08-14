---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    design:
      background:
        image:
          filename: slider/slider-1.jpg
      css_class: 'hero-image'
    content:
      title: PedScience

  
  - block: hero
    # design:
    #   background:
    #     image:
    #       filename: slider/slider-1.jpg
    #   css_class: 'hero-image'
    content:
      # title: PedScience
      text: |
        Wir sind eine gemeinnützige Forschungseinrichtung.

        Unser Ziel ist eine zielgerichtete Forschung zur Verbesserung der Behandlung von Kindern und Jugendlichen
  
  - block: collection
    content:
      title: Neuste Publikationen
      subtitle:
      text:
      count: 5
      order: desc
      page_type: publication
    design:
      view: compact
      columns: '1'
  
  - block: collection
    content:
      title: Projekte
      count: 5
      order: desc
      page_type: project
    design:
      view: card
      columns: '1'
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: image-end.jpg
          filters:
            brightness: 1
          parallax: true
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---

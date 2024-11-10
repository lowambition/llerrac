---
title: Llerrac
date: 2024-11-10
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: Llerrac
      text: <p class="lead mt-5">Cocoa and muesli &mdash; in the cloud</p>
      primary_action:
        text: Turning sun
        url: "/turning sun/"
        icon: rocket-launch
      secondary_action:
        text: Notes
        url: /docs/
      announcement:
        text: "Latest"
        link:
          text: "Read more"
          url: "/blog/"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: ""
      background:
        color: ""
        image:
          # Add your image background to `assets/media/`.
          filename: ""
          filters:
            brightness: 0.5
  - block: stats
    content:
      items:
        - statistic: "1"
          description: |
            ?
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-800"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  - block: features
    id: content
    content:
      title: Contents
      text: Overview
      items:
        - name: Notes
          icon: magnifying-glass
          description: Notes I find handy
        - name: Blog
          icon: bolt
          description: To read later, maybe they points will stand the test of time.
        - name: Turning sun
          icon: sparkles
          description: A strory rewritten countless times.
        
  - block: cta-card
    content:
      title: "??"
      text: cta-card
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
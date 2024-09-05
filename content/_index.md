---
title: 'Home'
date: 2024-08-20
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: Build your teams with complete impartiality!
      text: Optimize your training sessions with our mobile application, completely objective and fair!
      primary_action:
        text: Get Started
        url: https://marcleroy.github.io/Orionde.FairTeams
        icon: rocket-launch
      secondary_action:
        text: Read the docs
        url: https://docs.hugoblox.com
      announcement:
        text: "Announcing the release of version 1."
        link:
          text: "Read more"
          url: "/blog/"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "red"
        image:
          # Add your image background to `assets/media/`.
          filename: bg-triangles.svg
          filters:
            brightness: 0.5
  - block: stats
    content:
      items:
        - statistic: "1M+"
          description: |
            Websites built  
            with Hugo Blox
        - statistic: "10k+"
          description: |
            GitHub stars  
            since 2016
        - statistic: "3k+"
          description: |
            Discord community  
            for support
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  - block: features
    id: features
    content:
      title: Features
      text: Build your site with blocks 🧱
      items:
        - name: Optimized SEO
          icon: magnifying-glass
          description: Automatic sitemaps, RSS feeds, and rich metadata take the pain out of SEO and syndication.
        - name: Fast
          icon: bolt
          description: Super fast page load with Tailwind CSS and super fast site building with Hugo.
        - name: Easy
          icon: sparkles
          description: One-click deployment to GitHub Pages. Have your new website live within 5 minutes!
        - name: No-Code
          icon: code-bracket
          description: Edit and design your site just using rich text (Markdown) and configurable YAML parameters.
        - name: Highly Rated
          icon: star
          description: Rated 5-stars by the community.
        - name: Swappable Blocks
          icon: rectangle-group
          description: Build your pages with blocks - no coding required!

  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: Setup your teams with complete impartiality!
          text: As easy as 1, 2, 3!
          feature_icon: check
          features:
            - "Choose the number of players"
            - "Choose the number of teams"
            - "And change team colors if you really want to"
          # Upload image to `assets/media/` and reference the filename here
          # image: "Screenshot 2024-08-20 105928.png"
          image: "{{< resize-image src="Screenshot 2024-08-20 105928.png" width="800x" alt="Setup your teams" >}}"
          button:
            text: Download
            url: https://hugoblox.com/templates/
        - title: Generate a unique draw for each session
          text: Just a click to assign the players, and you're ready to play
          feature_icon: bolt
          features:
            - "Choose a player oin a row"
            - "Click on the pull button"
            - "Assign the player to the pulled team, with team number or color"
          # Upload image to `assets/media/` and reference the filename here
          # image: "Screenshot 2024-08-20 105956.png"
          image: "{{< resize-image src="Screenshot 2024-08-20 105956.png" width="800x" alt="Setup your teams" >}}"
          button:
            text: Try it now!
            url: https://discord.gg/z8wNYzb
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: testimonials
    content:
      title: ""
      text: ""
      items:
        - name: "Hugo Smith"
          role: "Marketing Executive at X"
          # Upload image to `assets/media/` and reference the filename here
          image: "testimonial-1.jpg"
          text: "Awesome, so easy to use and saved me so much work with the swappable pre-designed sections!"
    design:
      spacing:
        # Reduce bottom spacing so the testimonial appears vertically centered between sections
        padding: ["6rem", 0, 0, 0]
  - block: cta-card
    content:
      title: Build your future-proof website
      text: As easy as 1, 2, 3!
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---

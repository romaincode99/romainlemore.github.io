---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing 

design:
  # Default section spacing
  spacing: "2rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
#       button:
#         text: Download CV
#         url: uploads/resume.pdf
    design:
      css_class: dark
      # Avatar customization
      avatar:
        size: medium  # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  # - block: collection
  #   id: papers
  #   content:
  #     title: Publications
  #     text: ""
  #     filters:
  #       folders:
  #         - publication
  #       exclude_featured: false
  #   design:
  #     view: citation
  #     spacing:
  #       padding: ['6rem', '0', '3rem', '0']  # haut, droite, bas, gauche

#   - block: collection
#     id: talks
#     content:
#       title: Scientific talks
#       filters:
#         folders:
#           - event
#     design:
#       view: grid # citation # article-grid
#       columns: 1
#   - block: collection
#     # id: talks
#     content:
#       title: Scientific Talks
# #       partial: "blocks/talks_list.html"
#       filters:
#         folders:
#           - event
# #     design:
# #       view: citation # article-grid
# #       columns: 1

  - block: markdown
    id: talks
    content:
      title: Scientific talks
      subtitle: ''
      text: |-
        <ul style="text-align: center; list-style-position: inside; white-space: nowrap;">
          <li>12th biennial of SMAI, France, June 2025, talk in mini symposium</li>
          <!-- <li>Fluid-structure-contact interaction</li> -->
        </ul>
    design:
      columns: '1'
      spacing:
        padding: ['3rem', '0', '3rem', '0']  # haut, droite, bas, gauche
---

---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/CV_Maisha_Rahman_Mim.pdf
    design:
      css_class: dark
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
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        
        I am so passionate about research. Though I have a full time job, I love to manage time for my research.
        Besides, my research interests align to my job. I leverage my extensive industry experience  to enrich my ongoing research endeavors. By integrating real-world challenges and insights gained from my professional work, I ensure that my research remains relevant, practical, and impactful. 
        
        
        Please reach out to collaborate 😃
    design:
      columns: '1'
  - block: collection
    id: research
    content:
      title: Research Experience
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: resume-awards
    id : honors
    content:
      title: Honors & Achievements
      username: admin
---

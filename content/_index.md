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
        url: uploads/resume.pdf
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
      title: '📚 My Goal'
      subtitle: ''
      text: |-
        As a Computer Science student, I aim to build a strong technical foundation and specialize in cybersecurity to create impactful solutions for data safety. My focus is on gaining hands-on experience, contributing to innovative projects, and preparing to make a meaningful impact in the tech industry.
    
        I apply a range of qualitative and quantitative methods to comprehensively investigate the role of science and technology in the economy.
        
        Please reach out to collaborate 😃
    design:
      columns: '1'
 
 
  - block: collection
    id: talks
    content:
      title: Certificate
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1

  - block: markdown
    id: papers
    content:
      title: contact me
      text: |-
        You can reach me out here
    
          email: parvinsultana@gmail.com    
          phone:017****66    
          facebook: https://www.facebook.com/faria.sultana.18041
          LinkedIn: https://www.linkedin.com/
          GitHub: https://github.com/Ananya394
    
    design:     
      columns: 1
  
---

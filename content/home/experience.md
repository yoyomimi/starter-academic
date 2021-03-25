---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Research Assistant
    company: University at Buffalo-SUNY and Chinese University of Hong Kong, Shenzhen
    company_url: ''
    location: Shenzhen, China
    date_start: '2019-07-01'
    date_end: '2019-11-01'
    description: |2-
        Project: Cross-modal Video Retrieval (Vision Language):
        
        * Addressed the natural language video retrieval efficiency and effectiveness problem as the primary researcher.
        * Devised a temporal anchor-free structure that performed retrieval directly on each temporal location within the target region. Built a top-down pyramid structure to make use of diverse temporal receptive fields, and a dilated convolutional module to integrate vision-language features more comprehensively.
        * The new method reduces retrieval time by a factor of 5 and outperforms previous work by 10% on retrieval accuracy.
        
  - title: Research Intern
    company: ByteDance
    company_url: ''
    location: Shenzhen, China
    date_start: '2019-09-01'
    date_end: '2020-04-01'
    description: |2-     
        
        * Reconstructed the hand pose detection network with a lightweight backbone. Finetuned and validated the new model based on millions of real-life user data, ensuring the high run speed while maintaining the comparatively robust detection precision.
        * Used foreground/background segmentation and human detection to discover all the human bodies in the video.
        * Applied guided filter, detection to improve the segmentation performance, especially under distant multi-person scenarios. 

  - title: Research Intern
    company: ByteDance
    company_url: ''
    location: Shenzhen, China
    date_start: '2019-09-01'
    date_end: '2020-04-01'
    description: |2-     
        
        * Reconstructed the hand pose detection network with a lightweight backbone. Finetuned and validated the new model based on millions of real-life user data, ensuring the high run speed while maintaining the comparatively robust detection precision.
        * Used foreground/background segmentation and human detection to discover all the human bodies in the video.
        * Applied guided filter, detection to improve the segmentation performance, especially under distant multi-person scenarios.


---

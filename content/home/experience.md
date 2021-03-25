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
      company: Sensetime and Beihang University
      company_url: ''
      location: Beijing, China
      date_start: '2020-07-01'
      date_end: '2020-11-01'
      description: |2-     
          Project: Human-object Interaction (HOI)
          * Formulated HOI detection as a set prediction problem as the primary researcher. The new formulation breaks the instance-centric and location limitations of the existing methods.
          * Proposed a novel one-stage HOI framework with transformer to adaptively aggregate the most suitable features.
          * Designed an instance-aware attention module to introduce the instance information into the interaction branch.
          * Without introducing any extra features, our method achieves 31% relative improvement over the second-best one-stage method on the HICO-DET dataset especially.


  - title: Research Intern
      company: Sensetime and University of Washington
      company_url: ''
      location: Seattle, WA
      date_start: '2020-11-01'
      date_end: ''
      description: |2-     
          Project: Online Multi-object Tracking (MOT)
          * Addressed the challenges of the online multi-object tracking problem as the primary researcher.
          * Proposed a novel online MOT framework that allowed the detection and association process to aggregate features according to their different requirements respectively.
          * Designed a reliable track association module that predicted the motion and representative appearance embedding for each track, and then jointly performed the location and appearance matching based on them.
          * The new method improves the association effectiveness and also keeps competitive detection accuracy, reaches SOTA performance on MOT17 as an online MOT tracker.
---

+++
# Experience widget.
widget = "experience"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 40  # Order that this section will appear.

title = "Experience"
subtitle = ""

# Date format for experience
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format = "Jan 2006"

# Experiences.
#   Add/remove as many `[[experience]]` blocks below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin/end multi-line descriptions with 3 quotes `"""`.
[[experience]]
  title = "Research Assistant"
  company = "University at Buffalo-SUNY & Chinese University of Hong Kong, Shenzhen"
  company_url = ""
  location = "Shenzhen, China"
  date_start = "2019-07"
  date_end = "2019-11"
  description = """
Project: Cross-modal Video Retrieval (Vision Language)

- Addressed the natural language video retrieval efficiency and effectiveness problem as the primary researcher.  
- Devised a temporal anchor-free structure that performed retrieval directly on each temporal location within the target region. Built a top-down pyramid structure to make use of diverse temporal receptive fields, and a dilated convolutional module to integrate vision-language features more comprehensively. 
- The new method reduces retrieval time by a factor of 5 and outperforms previous work by 10% on retrieval accuracy. 
- Outstanding undergraduate graduation thesis.

  """

[[experience]]
  title = "Professor"
  company = "ByteDance"
  company_url = ""
  location = "Shenzhen, China"
  date_start = "2019-09"
  date_end = "2020-04"
  
  description = """
- Reconstructed the hand pose detection network with a lightweight backbone. Finetuned and validated the new model based on millions of real-life user data, ensuring the high run speed while maintaining the comparatively robust detection precision.
- Used foreground/background segmentation and human detection to discover all the human bodies in the video.
- Applied guided filter, detection to improve the segmentation performance, especially under distant multi-person scenarios.
  
  """

+++

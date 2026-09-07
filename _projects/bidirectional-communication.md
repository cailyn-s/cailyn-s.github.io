---
title: "Bidirectional Communication for Disambiguating Mobile Manipulation Requests"
subtitle: "Group Project, Mobile Manipulation (ROB 762)"
nav_title: "Bidirectional Communication"
anchor: bidirectional-communication
order: 2
excerpt: |-
  Designed a bidirectional communication system to resolve ambiguous fetch and return tasks. Used VLMs to determine whether a request is ambiguous based on the current scene and request more information if it is. Implemented object detection and mobile pick and place on a Stretch 3 mobile robot.

  Evaluated our pipeline with tasks related to grabbing a drink as well as more general tasks that had a variety of objects. Clarification was correctly requested 100% of the time for the drink tasks but only 20% of the time on general tasks. This demonstrates the potential for out-of-the-box VLMs to clarify requests in simple tasks, but this can fail in more complex and ambiguous scenarios.
details_same_size: true
# details: |-
#   Evaluated our pipeline with tasks related to grabbing a drink as well as more general tasks, with a variety of objects including spray bottles, water bottles, and cups. Clarification was correctly requested 100% of the time for the drink tasks but only 20% of the time on general tasks.

#   Example *failure cases* of clarification on the general tasks include:

#   - “What is the color of the yellow object”
#   - “What is the first object you see in the image?”
#   - “What is the color of the object on the table?” (after asking for a ‘blue object’)

#   This demonstrates the potential for out-of-the-box VLMs to clarify requests in simple tasks, but this can fail in more complex and ambiguous scenarios.
media_dir: bidirectional-communication
media:
  # Pipeline figure first
  - width: "60%"
    items:
      - {src: "pipeline.png", alt: "Bidirectional communication pipeline"}
  # Silent clips. The narrated builds sit beside them as *.withaudio.mp4 if you
  # want to try sound again -- swap the src and add `muted: false`.
  - width: "45%"
    items:
      - {src: "MM Demo 1.mp4", caption: "Drink objects. Successful clarification.", autoplay: false}
      - {src: "MM Demo 2.mp4", caption: "General objects. Failed clarification.", autoplay: false}
collection: projects
---

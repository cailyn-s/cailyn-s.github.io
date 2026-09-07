---
title: "Blended Shared Control for Interactive Imitation Learning"
subtitle: "Research Project, in Submission as First Author"
nav_title: "Blended Control for Imitation Learning"
anchor: blended-shared-control
order: 1
excerpt: |-
  Novel approach for collecting data to fine-tune imitation learning policies using blended shared control during interventions for better autonomous performance. In comparison to full human control during interventions (HG-DAgger), our approach results in:

  - Higher *autonomous performance* by over 30 percentage points on two long horizon real-world tasks
  - ~15% faster data collection
  - 40% smoother transitions from autonomous rollouts to human interventions and 63% smoother transitions from interventions to rollouts
  <!-- - X% higher trajectory similarity to training data -->
media_dir: blended-shared-control
media:
  # Method figure first, kept small
  - width: "55%"
    items:
      - {src: "pipeline.png", alt: "Blended shared control method diagram"}
  # All four evaluation clips on one line, each task's base beside its blended run
  - - {src: "almond_base_eval_demo14_3x.mp4",              caption: "Base policy (40 demonstrations)"}
    - {src: "almond_round5_blended_eval_demo14_3x.mp4",    caption: "Policy fine-tuned with blended shared control", gap_after: "2.5em"}
    - {src: "cupboard_base_eval_demo14_3x.mp4",            caption: "Base policy (40 demonstrations)"}
    - {src: "cupboard_round5_blended_eval_demo14_3x.mp4",  caption: "Policy fine-tuned with blended shared control"}
collection: projects
---

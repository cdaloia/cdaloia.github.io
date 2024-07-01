---
title: People
date: 2022-10-24

type: landing

sections:
  - block: people
    content:
      title: Meet the Team
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          - Principal Investigator
          - Current Researchers
          - Undergraduate Students
          - Lab Pets
          - Visitors
          - Alumni - Grads
          - Alumni - Undergrads
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="/join/" cta_text="Join Us →" %}}
    design:
      columns: '1'
---
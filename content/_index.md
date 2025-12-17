---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "4rem"

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: biography
    content:
      username: admin
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download Resume
        url: /uploads/CV.pdf
    design:
      banner:
        # Upload your cover image to the `assets/media/` folder and reference it here
        filename: kalen-emsley-Bkci_8qcdvQ-unsplash.jpg
      biography:
        # Customize the style of your biography text
        style: 'text-align: justify; font-size: 0.8em;'
  - block: markdown
    content:
      username: admin
      title: News
      text: |
        **2026-01** 🧠 Participated in the **Alan Turing Institute Data Study Group (DSG)**.

        **2025-09** 🤝 Served as a **Volunteer for PVLDB**.

        **2025-04** 🎉 Paper accepted at **SIGIR 2025**.

        **2024-05** 🏆 Won CFA China Future Financial Analyst Competition.
      design:
        columns: '1'
        background:
          color: 'gray'
        spacing:
          padding: ['0.5rem', '0', '0.5rem', '0']
  - block: collection
    content:
      title: Publications
      page_type: publication
      sort_by: date
      sort_ascending: false
    design:
      view: citation
  #- block: markdown
  #   content:
  #  title: Publications
  #  text: |
   #   **[1]** Min Zhang, Weiren Yu.  
   #   *UPPR+: Scaling Uncertain Personalized PageRank on Large Graphs.*  
   #   Proceedings of SIGIR 2025.  
   #   [[PDF]](/files/sigir25.pdf)

  - block: experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: true
  - block: skills
    content:
      title: Skills & Hobbies
      username: admin
  - block: awards
    content:
      title: Awards
      username: admin
  - block: languages
    content:
      title: Languages
      username: admin
---

---
title: 'Home'
date: 2023-10-24
type: landing

sections:
  - block: hero
    content:
      announcement:
        text: "New MSc thesis topics are online."
        link:
          text: "See the topics"
          url: "/join/#theses"
      title: Biomedicine, Engineering & AI Research Lab
      text: "We design AI-based clinical decision support systems at the University of Trento: models that learn from medical images, clinical and biological data to make diagnosis faster, more accurate and more personal."
      primary_action:
        text: Meet the team
        url: /people/
      secondary_action:
        text: Thesis topics
        url: /join/#theses
    design:
      spacing:
        padding: [0, 0, 0, 0]

  - block: facts
    content:
      # count: members | theses are computed automatically at build time
      items:
        - count: members
          description: Members
          url: /people/
        - count: theses
          description: Open MSc theses
          url: /join/#theses
        - statistic: "4"
          description: Clinical domains
          url: "#research"
    design:
      spacing:
        padding: [0, 0, 0, 0]

  - block: text-section
    id: about
    content:
      subtitle: About
      title: Why we do it
      text: |
        We are the **BEAR group** (Biomedicine, Engineering & AI Research) at the Department of Information Engineering and Computer Science (DISI), University of Trento, together with the Diagnostic Imaging Lab. We plan, design and develop **AI-based clinical decision support systems**.

        Our goal is to **reduce** diagnostic delays, doctors' workload and the risk of cognitive biases, and to **increase** diagnostic accuracy, access to care and support in complex decisions. In practice, this means standardizing image interpretation, reducing variability between diagnoses, making sure critical findings are consistently reported, and building the foundation for personalized therapeutic strategies and more targeted patient management.
    design:
      spacing:
        padding: ["6rem", 0, "2rem", 0]

  - block: research-list
    id: research
    content:
      title: What we work on
      subtitle: Research
      text: Four research lines in medical imaging, from methods to clinical impact. Each one comes with open MSc thesis topics.
      columns: 2
      items:
        - name: Multimodal learning
          description: Combining complementary imaging modalities, clinical and biological data into robust and interpretable models, even when some acquisitions are missing or corrupted.
          topics: [MRI · CT · PET, Clinical data, Missing data]
          theses: [multimodal-fusion, missing-modality-reconstruction]
        - name: Generative AI for medical imaging
          description: Generating anatomically plausible medical images conditioned on disease and treatment, to augment data and simulate clinical scenarios.
          topics: [Diffusion models, Image synthesis]
          theses: [clinically-conditioned-generation]
        - name: Disease progression & prognosis
          description: Forecasting how a disease evolves from longitudinal scans and combining diagnosis with prognostic prediction for personalized care.
          topics: [Longitudinal data, Forecasting, Prognosis]
          theses: [disease-progression-forecasting, multi-task-learning]
        - name: Trustworthy & explainable AI
          description: Systems that recognise low-quality inputs and uncertain cases, and that explain their outputs with reports grounded in visual evidence.
          topics: [Quality control, Uncertainty, Vision-language]
          theses: [quality-awareness, image-to-text-grounding]
      domains_title: Clinical domains
      domains: [Radiology, Neuro-radiology, Neuro-oncology, Ophthalmology]
    design:
      spacing:
        padding: ["6rem", 0, "6rem", 0]

  - block: projects-list
    id: projects
    content:
      subtitle: Projects
      title: Current projects
      status: [active]
      count: 3
      hide_if_empty: true
      link:
        text: All projects
        url: /projects/
    design:
      spacing:
        padding: ["2rem", 0, "4rem", 0]

  - block: news-list
    id: news
    content:
      subtitle: News
      title: Latest updates
      section: post
      count: 3
      link:
        text: All news
        url: /news/
    design:
      spacing:
        padding: ["4rem", 0, "6rem", 0]

  - block: text-section
    id: opportunities
    content:
      subtitle: Join us
      title: Work with us
      text: |
        We are always happy to hear from motivated people interested in AI for medicine: **open positions**, **spontaneous applications** for PhD and postdoc roles, **MSc thesis projects** for UniTn students, **visiting researchers** and **clinical collaborations** with hospitals and companies.
      link:
        text: Open positions & theses
        url: /join/
    design:
      spacing:
        padding: ["2rem", 0, "7rem", 0]
---

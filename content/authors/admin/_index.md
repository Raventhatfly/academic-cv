---
# Display name
title: Feiyang Wu(邬飞扬)

# Name pronunciation (optional)
name_pronunciation:

# Full name (for SEO)
first_name: Feiyang
last_name: Wu

# Status emoji
status:
  icon: ☕️

# Is this the primary user of the site?
superuser: true

# Highlight the author in author lists? (true/false)
highlight_name: true

# Role/position/tagline
role: Master's Student in Computational Science & Engineering

# Organizations/Affiliations to display in Biography blox
organizations:
  # - name: Zhejiang University
  #   url: https://zju.edu.cn/
  # - name: Univeristy of Illinois
  #   url: https://illinois.edu
  - name: Harvard University
    url: https://harvard.edu

# Social network links
# Need to use another icon? Simply download the SVG icon to your `assets/media/icons/` folder.
profiles:
  - icon: at-symbol
    url: 'mailto:feiyangwu@fas.harvard.edu'
    label: E-mail Me
  # - icon: brands/x
    # url: https://twitter.com/GetResearchDev
  # - icon: brands/instagram
    # url: https://www.instagram.com/
  - icon: brands/github
    url: https://github.com/raventhatfly
  - icon: brands/linkedin
    url: https://www.linkedin.com/in/feiyang-wu
  - icon: academicons/google-scholar
    url: https://scholar.google.com/citations?user=7d2oto0AAAAJ
  # - icon: academicons/orcid
  #   url: https://orcid.org/

interests:
  - Vision-Language-Action Models
  - Large Language Models
  - World Models & Generative Models
  - Imitation & Reinforcement Learning
  - Robotics & Control
  - Embedded Systems

education:
  - area: ME Computational Science and Engineering
    institution: Harvard University
    date_start: 2025-09-01
    date_end: 2027-05-01
    summary: |
      Expected May 2027. Cambridge, MA.

  - area: BS Computer Engineering
    institution: University of Illinois Urbana-Champaign
    date_start: 2021-09-01
    date_end: 2025-05-31
    summary: |
      Graduated with High Honors. GPA: 3.97/4.00

      Courses included:
      - ECE385 Digital Systems Laboratory
      - ECE391 Computer Systems Engineering
      - ECE479 Internet of Things and Cognitive Computing
      - ECE408 Applied Parallel Programming
      - CS446 Machine Learning
    # button:
    #   text: 'Read Thesis'
    #   url: 'https://example.com'

  - area: BEng Electronic and Computer Engineering
    institution: Zhejiang University
    date_start: 2021-09-01
    date_end: 2025-06-25
    summary: |
      Dual degree through the ZJU-UIUC Institute, Haining, China. Class rank 1/64.

work:
  - position: Software Development Engineer Intern
    company_name: Amazon
    company_url: 'https://www.amazon.jobs/'
    company_logo: ''
    date_start: 2026-06-01
    date_end: 2026-08-31
    summary: |2-
      Boston, MA.
      - Designed and built a computer-vision-based testing pipeline in Rust for Amazon's next-generation dashcart, connecting edge devices to AWS IoT Core over MQTT, using gRPC for inter-module communication, and resolving credential provisioning for newly onboarded cart units via AWS Lambda.
      - Built and deployed an automated agentic testing workflow on AWS AgentCore that reads the cart's on-screen display to flag anomalies during rollout and streams results to a real-time monitoring pipeline, with the goal of removing the need for on-site engineers during beta provisioning on the test fleet.

  - position: Machine Learning Engineer Intern (Manipulation)
    company_name: LimX Dynamics
    company_url: 'https://www.limxdynamics.com/en'
    company_logo: ''
    date_start: 2025-07-01
    date_end: 2025-08-31
    summary: |2-
      Beijing, China.
      - Contributed to the pre-release FluxVLA Engine, an end-to-end VLA engineering platform spanning data processing, fine-tuning, evaluation and real-robot deployment across 7 mainstream VLA models (OpenVLA, GR00T, π0/π0.5 and more) on Franka, UR3 and ALOHA hardware; now open-sourced (500+ stars, 60+ forks) and deployed on Alibaba Cloud to serve VLA training and inference.
      - Built a unified codebase for several VLA models including OpenVLA and π0, resolving environment inconsistencies between them and transplanting OpenVLA-OFT onto the LIBERO benchmark.

  - position: Project Leader, Diffusion and Flow Matching Policy with Torque Modality
    company_name: ZJU-UIUC Institute
    company_url: ''
    company_logo: ''
    date_start: 2024-09-01
    date_end: 2025-06-01
    summary: |2-
      - Built an ARX robotic-arm teleoperation data collection, training and evaluation pipeline to replicate results from Diffusion Policy (DP) and Flow Matching on basic and contact-demanding wiping and flipping tasks.
      - Incorporated joint torque modality into raw DP, observing improved action performance on contact-rich tasks.

  - position: Teaching Assistant, CS 101 Introduction to Computing for Engineering & Science
    company_name: ZJU-UIUC Institute
    company_url: ''
    company_logo: ''
    date_start: 2024-09-01
    date_end: 2025-01-15
    summary: |2-
      - Taught Python-based computational problem solving; ran weekly labs and discussion sections on programming exercises, debugging and algorithm design.
      - Mentored students with little or no prior programming background through office hours, applying programming to data analysis, modelling and simulation.

  - position: Contributor, MovieChat-1K Benchmark
    company_name: Zhejiang University
    company_url: ''
    company_logo: ''
    date_start: 2023-03-01
    date_end: 2023-12-31
    summary: |2-
      - Co-authored the CVPR 2024 paper MovieChat (700+ citations), a widely adopted benchmark for multimodal LLMs and vision-language models in long-form video understanding requiring video memory.
      - Built the data collection software stack and annotated a high-quality benchmark with Q&A pairs and 100-word summaries for 1000+ ten-thousand-frame videos, released on the Hugging Face Hub.

  - position: Teaching Assistant, ECE 120 Introduction to Computing
    company_name: ZJU-UIUC Institute
    company_url: ''
    company_logo: ''
    date_start: 2023-02-01
    date_end: 2023-06-30
    summary: |2-
      - Led weekly discussion sections on Boolean algebra, sequential logic and finite state machines, reinforcing theory with applied problem solving.
      - Supervised laboratory sessions on circuit simulation, C programming and system-level design, covering hardware–software integration and LC-3 assembly.

# Skills
# Add your own SVG icons to `assets/media/icons/`
skills:
  - name: Programming Languages
    items:
      - name: Python
        description: ''
        percent: 90
        icon: fa/python
      - name: C / C++
        description: ''
        percent: 85
        icon: logo/cplusplus
      - name: Rust
        description: ''
        percent: 60
        icon: ''
      - name: CUDA
        description: ''
        percent: 75
        icon: logo/nvidia
      - name: MySQL
        description: ''
        percent: 50
        icon: logo/mysql
      - name: Verilog / x86 Assembly
        description: ''
        percent: 65
        icon: ''
      - name: JavaScript / Node.js
        description: ''
        percent: 55
        icon: ''
  - name: Frameworks & Tools
    items:
      - name: PyTorch
        description: ''
        percent: 90
        icon: ''
      - name: ROS2
        description: ''
        percent: 80
        icon: logo/ros
      - name: JAX / TensorFlow
        description: ''
        percent: 60
        icon: ''
      - name: TensorRT
        description: ''
        percent: 70
        icon: logo/nvidia
      - name: MuJoCo
        description: ''
        percent: 70
        icon: ''
      - name: YOLO / OpenCV
        description: ''
        percent: 80
        icon: ''
      - name: AWS
        description: ''
        percent: 65
        icon: ''
  - name: Hobbies
    color: '#eeac02'
    color_border: '#f0bf23'
    items:
      - name: Hiking
        description: ''
        percent: 60
        icon: /fa/person-hiking
      - name: Cats
        description: ''
        percent: 100
        icon: /fa/cats
      - name: Game
        description: ''
        percent: 80
        icon: /fa/gamepad
      - name: Lego
        description: ''
        percent: 80
        icon: /fa/car-side

languages:
  - name: Chinese
    percent: 100
  - name: English
    percent: 90
  - name: Spanish
    percent: 5
  - name: Japanese
    percent: 0.5
  - name: German
    percent: 0.1

# Awards.
#   Add/remove as many awards below as you like.
#   Only `title`, `awarder`, and `date` are required.
#   Begin multi-line `summary` with YAML's `|` or `|2-` multi-line prefix and indent 2 spaces below.
awards:
  - title: B.S. with High Honors
    awarder: University of Illinois Urbana-Champaign
    date: '2025-05-31'
    summary: ''
  - title: Dean's List
    awarder: Grainger College of Engineering, UIUC
    date: '2024-05-01'
    summary: |
      Awarded in 2023 and 2024.
  - title: Second Prize, RoboMaster University League
    awarder: RoboMaster, Shanghai
    date: '2023-08-01'
    summary: ''
  - title: National Scholarship of China
    awarder: Ministry of Education of China
    date: '2023-10-01'
    summary: |
      Awarded in 2022 and 2023.
  - title: First Prize Scholarship
    awarder: Zhejiang University
    date: '2023-10-01'
    summary: ''
  - title: Second Prize Scholarship
    awarder: ZJU-UIUC Institute
    date: '2023-10-01'
    summary: ''
  - title: National Gold Prize, 'Internet+' Innovation and Entrepreneurship Competition
    awarder: Ministry of Education of China
    date: '2022-11-01'
    summary: ''
---

## About Me

Feiyang Wu is a Master's student in Computational Science and Engineering at Harvard University. He received his undergraduate degrees through the dual-degree program of the ZJU-UIUC Institute, holding a B.S. in Computer Engineering from the University of Illinois Urbana-Champaign (High Honors) and a B.Eng. in Electronic and Computer Engineering from Zhejiang University.

His research focuses on embodied artificial intelligence — vision-language-action models, world models and imitation learning — and how these methods transfer to real robotic manipulation, particularly in contact-rich settings.

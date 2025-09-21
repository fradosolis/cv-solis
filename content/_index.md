---
# Leave the homepage title empty to use the site title
title: ""
date: 2025-03-08
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    demo: false # Only display this section in the Hugo Blox Builder demo site
    content:
      title: <br/><br/>Data - Driven Machines Analytical ML Systems
    design:
      background:
        image:
          filename: Backcfd.png
          filters:
            brightness: 0.5
        text_color_light: true
  - block: resume-biography-3
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    # design:
    #   css_class: dark
    #   background:
    #     color: '#242424'
    design:
      background:
        image:
          filename: iot1.png
          filters:
            brightness: 0.5
        text_color_light: true
        # image:
        #   # Add your image background to `assets/media/`.
        #   filename: stacked-peaks.svg
        #   filters:
        #     brightness: 1.0
        #   size: cover
        #   position: center
        #   parallax: false
  # - block: markdown
  #   content:
  #     title: 'My Research'
  #     subtitle: ''
  #     text: |-
  #       Use this area to speak to your mission. I'm a research scientist in the Moonshot team at DeepMind. I blog about machine learning, deep learning, and moonshots.

  #       I apply a range of qualitative and quantitative methods to comprehensively investigate the role of science and technology in the economy.
        
  #       Please reach out to collaborate 
  #   design:
  #     columns: '1'
  # - block: collection
  #   id: news
  #   content:
  #     title: News
  #     subtitle: ''
  #     text: ''
  #     # Page type to display. E.g. post, talk, publication...
  #     page_type: post
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 0
  #     # Filter on criteria
  #     filters:
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: date-title-summary
  #     # Reduce spacing
  #     spacing:
  #       padding: [0, 0, 0, 0]
  - block: markdown
    id: professional_timeline
    content:
      title: Professional Journey
      text: |-
        <div>
          <!-- Current Role -->
          <details open>
            <summary><strong>2025 | Mechanical Engineer – EPCM Company (Lima, Peru)</strong></summary>
            <div style="margin-left:6px; padding-left:20px; border-left:1px solid #3498db;">
              <ul>
                <li><strong>Material Handling Systems:</strong> Supervised and validated engineering calculations for belt conveyors, apron feeders, chutes, and steel structures</li>
                <li><strong>Dust Control:</strong> Designed air extraction and injection systems to mitigate dust emissions</li>
                <li><strong>Equipment Selection:</strong> Defined mechanical equipment for material handling and dispatch zones at Matarani Port</li>
                <li><strong>Planning:</strong> Coordinated interdisciplinary schedules and deliverables for Zafranal’s copper concentrate facility</li>
              </ul>
            </div>
          </details>

          <!-- BYV Project -->
          <details open>
            <summary><strong>2024 | Mechanical Engineer – BYV IESEMIN Company (Lima, Peru)</strong></summary>
            <div style="margin-left:6px; padding-left:20px; border-left:1px solid #e67e22;">
              <ul>
                <li><strong>Structural Analysis:</strong> Conducted mechanical verification for buildings supporting crushing equipment</li>
                <li><strong>Equipment Foundations:</strong> Engineered support structures for vibrating screens and crushers</li>
                <li><strong>Infrastructure:</strong> Evaluated conveyor belt structures and designed compressed air tank installations</li>
                <li><strong>Documentation:</strong> Managed technical drawings, engineering records, and project schedules</li>
              </ul>
            </div>
          </details>

          <!-- Freelance -->
          <details>
            <summary><strong>2023–2024 | Freelance Design Engineer – Independent (Arequipa, Peru)</strong></summary>
            <div style="margin-left:6px; padding-left:20px; border-left:1px solid #16a085;">
              <ul>
                <li><strong>DEM Simulation:</strong> Optimized lime solids handling for Yura Cement Company</li>
                <li><strong>Structural Design:</strong> Designed gantry and cantilever beams for mining crane systems (Caylloma Mining)</li>
                <li><strong>Tooling:</strong> Developed specialized tools for Ferreyros CAT truck maintenance</li>
                <li><strong>Industrial Facilities:</strong> Performed structural calculations for warehouses, roofing, and maintenance platforms</li>
                <li><strong>Scaffolding Systems:</strong> Modeled and reported on ringlock scaffolding for maintenance operations</li>
              </ul>
            </div>
          </details>

          <!-- IMCO Supervisor -->
          <details>
            <summary><strong>2022–2023 | Engineering Supervisor – IMCO Services (Arequipa, Peru)</strong></summary>
            <div style="margin-left:6px; padding-left:20px; border-left:1px solid #c0392b;">
              <ul>
                <li><strong>Project Leadership:</strong> Directed platform design, feasibility, and interference analyses for 30-ton installations</li>
                <li><strong>Heavy Structures:</strong> Executed calculations for pipe assemblies and steelwork (100 tonnes)</li>
                <li><strong>API Tank:</strong> Led detailed engineering of a 60-ton API 650 tank for copper concentrate storage</li>
                <li><strong>Team Coordination:</strong> Supervised multidisciplinary teams ensuring compliance with milestones</li>
                <li><strong>Progress Tracking:</strong> Managed engineering databases, metrics, and reporting systems</li>
              </ul>
            </div>
          </details>

          <!-- IMCO Assistant -->
          <details>
            <summary><strong>2020–2022 | Engineering Assistant – IMCO Services (Arequipa, Peru)</strong></summary>
            <div style="margin-left:6px; padding-left:20px; border-left:1px solid #2980b9;">
              <ul>
                <li><strong>Project Coordination:</strong> Tracked schedules and supervised mechanical installations on-site</li>
                <li><strong>Design:</strong> Produced 3D models and technical alternatives for scaffolding and steel structures</li>
                <li><strong>Major Projects:</strong>
                  <ul>
                    <li>50-ton gantry crane for autoclave transfer (70 tonnes)</li>
                    <li>Industrial building with heavy-duty crane systems (500 tonnes)</li>
                    <li>1.5M-gallon water storage tank for Southern Peru (186 tonnes)</li>
                    <li>Conveyor structures (50 tonnes) and tailings chute (20 tonnes)</li>
                    <li>Electrical rooms designed under AISC & UBC97 codes (300 tonnes)</li>
                  </ul>
                </li>
              </ul>
            </div>
          </details>

          <!-- Internship -->
          <details>
            <summary><strong>2018–2020 | Mechanical Engineering Intern – IMCO Services (Arequipa, Peru)</strong></summary>
            <div style="margin-left:6px; padding-left:20px; border-left:1px solid #8e44ad;">
              <ul>
                <li><strong>Field Work:</strong> Supported site measurements, take-offs, and structural verifications</li>
                <li><strong>Documentation:</strong> Prepared engineering progress reports and project records</li>
              </ul>
            </div>
          </details>

          <!-- Education -->
          <details>
            <summary><strong>Academic Milestones</strong></summary>
            <div style="margin-left:6px; padding-left:20px; border-left:1px solid #9b59b6;">
              <ul>
                <li><strong>Diploma:</strong> ASME B31 – Piping Systems for Industrial Plants (DMIA, 2022)</li>
                <li><strong>Diploma:</strong> Strategic Maintenance Management (TECSUP, 2021–2022)</li>
                <li><strong>Certification:</strong> Certified Associate in Project Management (PMI, 2021)</li>
                <li><strong>B.Eng. Mechanical Engineering</strong> (UNSA, 2019) – High Academic Standing</li>
                <li>Student Mobility Scholarship (2019) – UNSA</li>
                <li>Permanence Scholarship (2017) – PRONABEC</li>
              </ul>
            </div>
          </details>
        </div>
    design:
      columns: 2
      css_class: professional-timeline
  - block: collection
    id: publications
    content:
      title: Featured Publications
      count: 0
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
  # - block: collection
  #   content:
  #     title: Recent Publications
  #     text: ""
  #     count: 0
  #     filters:
  #       folders:
  #         - publication
  #       exclude_featured: false
  #   design:
  #     view: citation
  - block: resume-experience
    id: experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     count: 0
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     view: article-grid
  #     columns: 2
  # - block: collection
  #   id: platforms
  #   content:
  #     title: Robotic Platforms
  #     subtitle: I Learned and Grew up with
  #     count: 0
  #     filters:
  #       folders:
  #         - platform
  #   design:
  #     view: article-grid
  #     columns: 2
  - block: markdown
    id: contact
    content:
      title: Contact Me
    design:
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
  - block: cta-button-list
    content:
      buttons:
        - text: E-mail
          icon: at-symbol
          url: mailto:frado.solis@gmail.com
        - text: Connect
          icon: brands/linkedin
          url: https://www.linkedin.com/in/franciscosolis/
    design:
      columns: 2

  # - block: cta-card
  #   demo: true # Only display this section in the Hugo Blox Builder demo site
  #   content:
  #     title: 👉 Build your own academic website like this
  #     text: |-
  #       This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

  #       <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

  #       Easily build anything with blocks - no-code required!
        
  #       From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
  #     button:
  #       text: Get Started
  #       url: https://hugoblox.com/templates/
  #   design:
  #     card:
  #       # Card background color (CSS class)
  #       css_class: "bg-primary-700"
  #       css_style: ""
---

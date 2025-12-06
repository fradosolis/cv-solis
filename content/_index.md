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
      title: <br/><br/>BIM-Driven Engineering Intelligent Maintenanceee
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
          filename: Backcfd.png
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
          <!-- EPCM Company -->
          <details open>
          <details>
            <summary><strong>2025 | Project Mechanical Engineer – EPCM Company</strong></summary>
            <div style="margin-left:6px; padding-left:20px; border-left:1px solid #3498db;">
              <ul>
                <li><strong>Material Handling Systems:</strong> Validated engineering calculations for belt conveyors, apron feeders, chutes, and steel structures, enhancing reliability and constructability</li>
                <li><strong>Dust Control:</strong> Designed and implemented air extraction and injection systems to improve operational safety</li>
                <li><strong>Equipment Selection:</strong> Defined mechanical equipment for material handling and dispatch zones</li>
                <li><strong>Planning & Coordination:</strong> Prepared engineering deliverables schedules and coordinated interdisciplinary planning for Zafranal’s copper concentrate facility</li>
              </ul>
            </div>
          </details>

          <!-- BYV IESEMIN Company -->
          <details>
            <summary><strong>2024 | Mechanical Engineer – BYV IESEMIN Company</strong></summary>
            <div style="margin-left:6px; padding-left:20px; border-left:1px solid #e67e22;">
              <ul>
                <li><strong>Structural Analysis:</strong> Developed engineering calculations for conveyors, feeders, chutes, and steel structures ensuring accuracy and constructability</li>
                <li><strong>Dust Control & Equipment Selection:</strong> Designed dust control systems and selected mechanical equipment for material handling and dispatch zones</li>
                <li><strong>Project Coordination:</strong> Managed engineering deliverables and interdisciplinary planning to maintain schedule alignment</li>
              </ul>
            </div>
          </details>

          <!-- Freelance -->
          <details>
            <summary><strong>2024 | Freelance Design Engineer – Independent</strong></summary>
            <div style="margin-left:6px; padding-left:20px; border-left:1px solid #16a085;">
              <ul>
                <li><strong>DEM Simulation:</strong> Optimized material-handling components (Midwest sleeve) for Yura Cement Company</li>
                <li><strong>Structural Design:</strong> Designed gantry and cantilever beams for mining crane systems (Caylloma Mining)</li>
                <li><strong>Tooling Development:</strong> Created specialized maintenance tools for Ferreyros CAT</li>
                <li><strong>Industrial Facilities:</strong> Performed structural calculations for warehouses, metal roofing, maintenance platforms, and ringlock scaffolding</li>
              </ul>
            </div>
          </details>

          <!-- BISA -->
          <details>
            <summary><strong>2023 | Mechanical Design Engineer – BISA</strong></summary>
            <div style="margin-left:6px; padding-left:20px; border-left:1px solid #9b59b6;">
              <ul>
                <li><strong>Tank & Equipment Design:</strong> Designed and calculated API 650 tanks, compressed air tanks, and mechanical equipment for assembly</li>
                <li><strong>Conveyors & Feeders:</strong> Performed mechanical calculations for feeders, hoppers, and conveyor systems</li>
                <li><strong>Engineering Supervision:</strong> Oversaw basic engineering activities and technical compliance</li>
              </ul>
            </div>
          </details>

          <!-- IMCO Services -->
          <details>
            <summary><strong>2018–2023 | Engineering Supervisor & Junior Engineer – IMCO Services</strong></summary>
            <div style="margin-left:6px; padding-left:20px; border-left:1px solid #c0392b;">
              <ul>
                <li><strong>Project Leadership:</strong> Supervised platform designs, interference studies, and feasibility analyses; led detailed engineering of API 650 tank for copper concentrate storage</li>
                <li><strong>Structural Calculations:</strong> Pipe assemblies, steel installations, conveyor systems, tailings chutes, and water storage tanks (1.5M gallons)</li>
                <li><strong>Design & On-site Support:</strong> Engineered gantry cranes, industrial buildings with heavy-duty cranes, electrical rooms, and scaffolding structures under AISC & UBC97 codes</li>
                <li><strong>Team & Progress Management:</strong> Coordinated multidisciplinary teams, managed engineering databases, tracked progress, and produced reports</li>
              </ul>
            </div>
          </details>


          <!-- Education -->
          <details open>
            <summary><strong>Academic Milestones</strong></summary>
            <div style="margin-left:6px; padding-left:20px; border-left:1px solid #9b59b6;">
              <ul>
                <li><strong>Bachelor - Mechanical Engineering</strong> (UNSA, 2019) – Top 5% | Thesis: Mechanical and structural design of a 420 TPH conveyor belt verified with DEM</li>
                <li><strong>Diploma:</strong> Steel Structure Design and Analysis (CINGCIVIL, 2020) – Top 5%</li>
                <li><strong>Advanced Specialization:</strong> Strategic Maintenance Management (TECSUP, 2022) – Top 5%</li>
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

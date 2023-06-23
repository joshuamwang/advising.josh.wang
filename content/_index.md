---
# Leave the homepage title empty to use the site title
title: Joshua Wang
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Hello! 
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
    # design:
    #   background:
    #     image:
    #       filename: mountains.jpg
    #       position: center
    #       size: contain
      # spacing:
        # padding: ["20px", "20px", "210px", "0"]
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      # buttons:
      #   - name: All
      #     tag: '*'
      #   - name: Deep Learning
      #     tag: Deep Learning
      #   - name: Other
      #     tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: masonry
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: collection
    id: publications
    content:
      title: Publications
      count: 4
      filters:
        folders:
          - publication
        exclude_featured: false
        featured_only: true
      offset: 0
      sort_by: "Date"
      sort_ascending: false
    design:
      columns: '2'
      view: citation 
    
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Digital Pathology Summer Intern
          company: Merck
          company_url: 'https://www.merck.com/'
          company_logo: 'MRK'
          location: California
          date_start: '2022-06-01'
          date_end: '2022-08-31'
          description: |2-
              ●	Trained U-Net models on immunohistochemistry images to quantify tumor associated antigens. </br>
              ●	Compared stain deconvolution methods and transfer learning approaches to improve segmentation performance.</br>
              ●	Applied multiple-instance learning to identify histology features predictive of MSI-H in colorectal cancer. 

        - title: Undergraduate Student Researcher
          company: Brown University
          company_url: ''
          company_logo: 'brown'
          location: Rhode Island
          date_start: '2014-01-01'
          date_end: '2017-05-31'
          description: |2-
            ●	Designed and developed Python scripts to identify genomic regions with mutation patterns violating inheritance by descent in Candida albicans: http://snpmap.asc.ohio-state.edu  </br>
            ●	Developed R library to perform Gene Ontology enrichment for C. albicans research. Uses Selenium to request, pull and web scrape results from a canonical database lacking API access.  </br>
            ●	Led a systematic investigation of RNA-Seq data to annotate novel untranslated regions and construct gene expression networks using weighted gene correlation network analysis.  </br>

        - title: Bioinformatics Intern
          company: Regeneron Pharmaceuticals
          company_url: ''
          company_logo: 'REGN'
          location: New York
          date_start: '2015-06-01'
          date_end: '2015-08-31'
          description: |2-
            ●	Applied unsupervised clustering techniques to single-cell transcriptomics to identify biomarkers predictive of proprietary disease conditions.   </br>
            ●	Created a visualization platform to analyze single-cell transcriptome data: http://scap.josh.wang  </br>
            ●	Presented internship project to Senior VP of Research as one of four interns selected out of 175.

          
    design:
      columns: '2'



  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      # text: |-
      #   Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: joshuamwang [at] gmail.com
      # phone: 888 888 88 88
      # appointment_url: 'https://calendly.com'
      # address:
      #   street: 450 Serra Mall
      #   city: Stanford
      #   region: CA
      #   postcode: '94305'
      #   country: United States
      #   country_code: US
      # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      # office_hours:
      #   - 'Monday 10:00 to 13:00'
      #   - 'Wednesday 09:00 to 10:00'
      # contact_links:
      #   - icon: twitter
      #     icon_pack: fab
      #     name: DM Me
      #     link: 'https://twitter.com/Twitter'
      #   - icon: skype
      #     icon_pack: fab
      #     name: Skype Me
      #     link: 'skype:echo123?call'
      #   - icon: video
      #     icon_pack: fas
      #     name: Zoom Me
      #     link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      # autolink: true
      # Email form provider
      # form:
      #   provider: netlify
      #   # formspree:
      #   #   id:
      #   netlify:
      #     # Enable CAPTCHA challenge to reduce spam?
      #     captcha: true
    design:
      columns: '2'
---

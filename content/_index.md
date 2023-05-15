---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
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
        - title: Officer Trainee, Flying (Pilot)
          company: Indian Air Force
          company_url: 'https://indianairforce.nic.in/'
          company_logo: iaf
          location: Hyderabad, Telangana, India
          date_start: '2022-01-15'
          date_end: '2022-12-21'
          description: 'I served as a Flying Branch Officer Trainee in the IAF. Apart from flying, I was tasked with sortie preparation, Meteorological study, crew briefing and overlooking aerospace safety. I was trained on various military administration traits like planning & organizing, leadership, time and resource management, group planning and mental endurance.'
        - title: Graduate Analyst BA3
          company: Barclays
          company_url: 'https://home.barclays/'
          company_logo: Barclays
          location: Pune, Maharashtra, India
          date_start: '2021-08-31'
          date_end: '2021-12-25'
          description: 'I worked in the Wholesale Onboarding and Group FCO team. I was trained to work on projects related to KYC, financial crimes, anti-money laundering, etc. I worked on PEGA PRPC to develop BPM applications'
        - title: Project Intern
          company: Avaya
          company_url: 'https://www.avaya.com/en/'
          company_logo: Avaya
          location: Pune, Maharashtra, India
          date_start: '2020-11-01'
          date_end: '2021-06-15'
          description: 'Worked on a project to develop a telecommunication support system with knowledge management features.'
        - title: Research Intern
          company: Andy InfoSec
          company_url: 'https://andyinfosec.com/'
          company_logo: andy
          location: Pune, Maharashtra, India
          date_start: '2020-07-01'
          date_end: '2021-12-15'
          description: 'Worked on a project to analyse the aspects of IoT security and the emerging trends in IoT security. The focus of my research was on the evolution in attack methods, changing dimensions of security requirements, state sponsored attacks targeting critical infrastructure and case study of major IoT security incidents.'
        - title: Research Intern
          company: Pune Institute of Computer Technology
          company_url: 'https://pict.edu/'
          company_logo: pict
          location: Pune, Maharashtra, India
          date_start: '2019-06-01'
          date_end: '2019-09-15'
          description: 'Internship in Cloud Security, project on study of side channel attacks and their detection in multi-tenant cloud environment.'
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: 
          date_end: 
          date_start: '2022-11-27' 
          description: 'Scored 98.39 percentile, 99.57 percentile in DI&LR'
          organization: CAT 2022
          organization_url: https://iimcat.ac.in
          title: CAT 2022
          url: 
        
        - certificate_url: https://afcat.cdac.in/AFCAT/assets/images/news/jan22/first_merit_list-JAN22.pdf
          date_end: ''
          date_start: '2022-01-01'
          description: 'I scored 231/300 in the written exam. After a 6-day long interview process involving
Personal Interviews, Group Tasks, Psychological Tests, Physical tests and Psychomotor Tests, I was recommended by 2 AFSB Mysore for the Flying (Pilot) branch of the IAF.'
          organization: Indian Air Force
          organization_url: https://indianairforce.nic.in/
          title: 'AIR 17 out 200k+ candidates in AFCAT 1 2021.'
          url: 

        - certificate_url: 
          date_end: ''
          date_start: '2022-01-01'
          description: 'Successfully cleared Combined Defence Services Examination (CDS) conducted by UPSC for selection of officer trainees into defence forces. Managed to clear the cut-off for Indian Air Force twice [CDS 2 2020](https://www.upsc.gov.in/sites/default/files/WR-CDS-II-20-NameList-Engl-161220R.pdf) and [CDS 1 2021](https://www.upsc.gov.in/sites/default/files/WR-CDS-I-21-NameList-230321-Engl.pdf)'
          organization: Union Public Service Commission
          organization_url: https://www.upsc.gov.in/
          title: 'Cleared Combined Defence Services Examination (CDS) TWICE'
          url: 


        - certificate_url: 
          date_end: 
          date_start: '2021-06-01'
          description: 'Secured 9.08 CGPA in B.E. Computer Engineering course at Pune Institute of Computer Technology (affiliated to Savitribai Phule Pune University)'
          organization: Pune Institute of Computer Technology, Pune.
          organization_url: https://pict.edu
          title: '9.08 CGPA in B.E. Computer Engineering'
          url: 

    design:
      columns: '2'
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '2'
  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'
  #- block: portfolio
  #  id: projects
  #  content:
  #    title: Projects
  #    filters:
  #      folders:
  #        - project
  #    # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  #    default_button_index: 0
  #    # Filter toolbar (optional).
  #    # Add or remove as many filters (`filter_button` instances) as you like.
  #    # To show all items, set `tag` to "*".
  #    # To filter by a specific tag, set `tag` to an existing tag name.
  #    # To remove the toolbar, delete the entire `filter_button` block.
  #    buttons:
  #      - name: All
  #        tag: '*'
  #      - name: Deep Learning
  #        tag: Deep Learning
  #      - name: Other
  #        tag: Demo
  #  design:
  #    # Choose how many columns the section has. Valid values: '1' or '2'.
  #    columns: '1'
  #    view: showcase
  #    # For Showcase view, flip alternate rows?
  #    flip_alt_rows: false
  - block: markdown
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
  #- block: collection
  #  id: featured
  #  content:
  #    title: Featured Publications
  #    filters:
  #      folders:
  #        - publication
  #      featured_only: true
  #  design:
  #    columns: '2'
  #    view: card
  #- block: collection
  #  content:
  #    title: Recent Publications
  #    text: |-
  #      {{% callout note %}}
  #      Quickly discover relevant content by [filtering publications](./publication/).
  #      {{% /callout %}}
  #    filters:
  #      folders:
  #        - publication
  #      exclude_featured: true
  #  design:
  #    columns: '2'
  #    view: citation
  #- block: collection
  #  id: talks
  #  content:
  #    title: Recent & Upcoming Talks
  #    filters:
  #      folders:
  #        - event
  #  design:
  #    columns: '2'
  #    view: compact
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: Feel free to get in touch with me!       
      # Contact (add or remove contact options as necessary)
      email: hrishikesh.padhye@gmail.com
      #appointment_url: 'https://calendly.com'
      address:
        #street: 450 Serra Mall
        city: Pune
        region: MH
        #postcode: '94305'
        country: India
        country_code: IN
      #directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      #office_hours:
      #  - 'Monday 10:00 to 13:00'
      #  - 'Wednesday 09:00 to 10:00'
      contact_links:
        #- icon: twitter
        #  icon_pack: fab
        #  name: DM Me
        #  link: 'https://twitter.com/Twitter'
        #- icon: skype
        #  icon_pack: fab
        #  name: Skype Me
        #  link: 'skype:echo123?call'
        #- icon: video
        #  icon_pack: fas
        #  name: Zoom Me
        #  link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
    #  form:
    #    provider: netlify
    #    formspree: 
    #      id: hrishikesh.padhye@gmail.com
    #    netlify:
    #      # Enable CAPTCHA challenge to reduce spam?
    #      captcha: true
    design:
      columns: '2'
---

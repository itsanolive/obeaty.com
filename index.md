---
layout: home
header:
  title: Web design and development
  text: >
    for people who have better things to do

sections:
  - type: grid-section.html
    section_id: ''
    services:
      - title: Shopify Services
        icon: fab fa-shopify text-dark
        background_style: bg-info
        text-style: text-dark
        text: I have or want a Shopify site and need help with updating components, improving performance, or streamlining how I manage my web business.
        actions:
          - title: Shopify servies
            url: '#shopify'
            class: btn-dark
      - title: Custom Static Site
        icon: fab fas fa-rocket text-warning
        background_style: bg-dark
        text-style: text-warning
        text: I need something new and fantastic with editing capabilities and low recuring costs
        actions:
          - title: Hook me up!
            url: '#custom-site'
            class: btn-warning

  - type: call-to-action.html
    section_id: about
    background_style: bg-primary
    title: I'm here to help!
    text: If you're excited about your project, I'm excited about it. Please fill out my intake form to help me understand your goals and I will respond with a proposal based on your needs.
    actions:
      - title: See Services
        url: '#services'
        class: btn-danger

  - type: services.html
    section_id: services
    #background_style: bg-info
    title: At Your Service
    services:
      - title: Shopify E-comm
        text: Consulting or Initial Setup for Shopify E-Commerce Sites
        icon: fab fa-shopify text-info
        url:
      - title: Wordpress
        text: Modify or create a new Wordpress Site
        icon: fab fa-wordpress text-info
      - title: Style/Design Updates
        text: We update dependencies to keep things fresh.
        icon: fas fa-code text-info
      - title: Graphic Design
        text: Branding, creative artwork, and layout design
        icon: fas fa-pen-nib text-info

  - type: portfolio.html
    # this section has always ID 'portfolio'
    #section_id: portfolio
    #background_style: bg-dark
    projects:
      - title: Press Kit
        text: Third Coast Percussion's latest press kit highlighting events, programs, and philanthropic initiatives
        # the images are located in:
        # img/portfolio/fullsize
        # img/portfolio/thumbnails
        icon: 1-tcp-press-kit.jpg
        url: '#'
      - title: Meeting At The Well
        text: Unused branding of women's ministry recurring meetings
        icon: 2-meeting-well.jpg
        url: '#'
      - title: Stained Glass - Sermon Series
        text: One of 3 program covers developed for church sermon series
        icon: 3-stained-glass.jpg
        url: '#'
      - title: Dream Weaver Podast
        text: The Sigourney Weaver podcast you didn't know you needed. Logo, branding, hosting, occasional editing, and social media
        icon: 4-dream-weaver-pod.jpg
        url: 'https://feeds.transistor.fm/dream-weaver-podcast'
        new_window: true
      - title: Holiday Cards
        text: Third Coast Percussion holiday cards
        icon: 5-tcp-holiday-cards.jpg
        url: '#'
      - title: Billboard Grammy Nomination Ad
        text: Full-page ad for Billboard magazine showcasing Third Coast Percussion's nomination
        icon: 6-tcp-billboard-ad.jpg
        url: '#'

  - type: intake-form.html
    section_id: form
    title: Start your project today
    actions:
      - title: Fill out Form
        url: https://startbootstrap.com/themes/creative/
        class: btn-light
    inputs:
      - title: name
        label: Full Name
        type: text
        required: true
      - title: email
        label: Email Address
        type: email
        required: true
      - title: tel
        label: Phone Number
        type: tel
        required: true
      - title: company
        label: Company
        type: text
        required: true
      - title: goals
        label: Project summary and goal
        type: text
        required: true
        placeholder: New e-commerce website, update to existing site, branding help, simple one-page site, etc...
      - title: type
        label: Type of service needed
        type: text
        required: true
        placeholder: Web Design, Graphic Design...

  - type: contact.html
    section_id: contacts
    title: Let's Get In Touch!
    text: >-
      Ready to start your next project with us? Give us a call or send us an email
      and we will get back to you as soon as possible!
    actions:
    - title: E-Mail
      icon: fa-paper-plane
      url: mailto:info@obeaty.com
    - title: Instagram
      icon: fa-instagram
      icon_type: fab
      url: 'https://www.instagram.com/oliviabeaty/'
      new_window: true
    - title: GitHub
      icon: fa-github
      icon_type: fab
      url: 'https://github.com/itsanolive'
      new_window: true

---

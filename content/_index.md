---
# Leave the homepage title empty to use the site title
title:  
date: 2024-06-27
type: landing

sections:

  - block: hero
    content:
      title: "Tegla Loroupe Peace Foundation"
      text:  |
        <div style="width: 90%; margin: 0 auto;">
          <h4 style="font-size: 1.5rem;">Peace</h4>
          <p style="font-size: 1.5rem;">The Tegla Loroupe Peace Foundation is dedicated to bring peace to conflict zones by the power of sport. <br> <br> By calling upon the most admired athletes in every community to act in the Olympic spirit of peace, personal examples can transform how a community sees itself and its neighbors.</p><br>
        </div> 
      # Add your Call-To-Action (CTA) button and optional icon
      cta:
        label: Visit our Facebook page for latest news
        url: https://www.facebook.com/teglapeacefoundation/  
    design:
      # Choose an optional background color, gradient, image, or video
      columns:  '1'
      css_class: "hero-wide-text"
      background:
        image: 
          filename: tlhome.jpg
          filters:
            brightness: 1
          parallax: true
 #         position: center
          size: cover
        text_color_light: true
      spacing:
        padding: ['10%', '5%', '10%', '5%']
      css_class: fullscreen
        
        

  
 
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        # The folders to display content from
        folders:
          - post
        author: ""
        category: ""
        tag: ""
        publication_type: ""
        featured_only: false
        exclude_featured: false
        exclude_future: false
        exclude_past: false
      # Choose how many pages you would like to offset by
      # Useful if you wish to show the first item in the Featured widget
      offset: 0
      # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: false
    design:
      # Choose a listing view
      view: compact
      # Choose single or dual column layout
      columns: '1'
  
 


  - block: people
    content:
      title: Our Athletes, Our Leaders, Our Students
      user_groups:
        - Staff
        - Board
        - Management
        - Visitors
        - Alumni
        - Athletes
        - South Sudan
        - Ngong Training Camp
        - Kapenguria Academy
        - Olympics
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true 

  

  

  - block: collection
    id: project
    content:
      title: Projects
      subtitle: ''
      text: 'Check out my recent blog posts below!'
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        # The folders to display content from
        folders:
          - project
        author: ""
        category: ""
        tag: ""
        publication_type: ""
        featured_only: false
        exclude_featured: false
        exclude_future: false
        exclude_past: false
      # Choose how many pages you would like to offset by
      # Useful if you wish to show the first item in the Featured widget
      offset: 0
      # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: false
    design:
      # Choose a listing view
      view: compact
      # Choose single or dual column layout
      columns: '1'

  - block: collection
    id: events
    content:
      title: Events
      subtitle: ''
      text: 'Check out events below!'
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        # The folders to display content from
        folders:
          - event
        author: ""
        category: ""
        tag: ""
        publication_type: ""
        featured_only: false
        exclude_featured: false
        exclude_future: false
        exclude_past: false
      # Choose how many pages you would like to offset by
      # Useful if you wish to show the first item in the Featured widget
      offset: 0
      # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: false
    design:
      # Choose a listing view
      view: compact
      # Choose single or dual column layout
      columns: '1'

  - block: collection
    id: blog
    content:
      title: Recent Blogs
      subtitle: ''
      text: 'Check out my recent blog posts below!'
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        # The folders to display content from
        folders:
          - blog
        author: ""
        category: ""
        tag: ""
        publication_type: ""
        featured_only: false
        exclude_featured: false
        exclude_future: false
        exclude_past: false
      # Choose how many pages you would like to offset by
      # Useful if you wish to show the first item in the Featured widget
      offset: 0
      # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: false
    design:
      # Choose a listing view
      view: compact
      # Choose single or dual column layout
      columns: '1'

  - block: collection
    id: slides
    content:
      title: Recent Slides
      subtitle: 'Adding Swahili, Pokot, Marakwet, Turkana versions of these slides'
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        # The folders to display content from
        folders:
          - slides
        author: ""
        category: ""
        tag: ""
        publication_type: ""
        featured_only: false
        exclude_featured: false
        exclude_future: false
        exclude_past: false
      # Choose how many pages you would like to offset by
      # Useful if you wish to show the first item in the Featured widget
      offset: 0
      # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: false
    design:
      # Choose a listing view
      view: compact
      # Choose single or dual column layout
      columns: '1'

  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'

  - block: markdown
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="gallery" >}}
    design:
      columns:  '2'

  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

# - block: markdown
#    content:
#      title:
#      subtitle:
#      text: |
#        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
#    design:
#      columns: '1'


    
  - block: hero
    content:
      title: |
        Rebuilding TL Peace
      image:
        filename: tlpf.logo.new.jpg
      text: |
        <br>
        
        Move content, assets, and static files.

  
  
---

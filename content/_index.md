---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
# note: the following format can be used in publications. It underscores the text when the cursor is on it. 
#      cta_alt:
#        label: Ask a question
#        url: https://discord.gg/z8wNYzb

  - block: about.biography
    id: about
    content:
      title: ""
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
 
#  - block: collection
#    id: posts
#    content:
#      title: Recent Posts
#      subtitle: ''
#      text: ''
#      # Choose how many pages you would like to display (0 = all pages)
#      count: 1
#      # Filter on criteria
#      filters:
#        folders:
#          - post
#        author: ""
#        category: ""
#        tag: ""
#        exclude_featured: false
#        exclude_future: false
#        exclude_past: false
#        publication_type: ""
#      # Choose how many pages you would like to offset by
#      offset: 0
#      # Page order: descending (desc) or ascending (asc) date.
#      order: desc
#    design:
#      # Choose a layout view
#      view: compact
#      columns: '2'

  - block: portfolio
    id: publications
    content:
      title: Publications
      filters:
        folders:
          - publications
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.

    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      view: compact
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false

  - block: portfolio
    id: workingpapers
    content:
      title: Working Papers
      filters:
        folders:
          - workpaper
        exclude_featured: True
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.

    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      view: compact
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false

#  - block: collection
#    id: workingpapers
#    content:
#      title: Working Papers
#      filters:
#        folders:
#          - workpaper
#        exclude_featured: True
#    design:
#      columns: '2'
#      view: compact
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      # Contact (add or remove contact options as necessary)
      email: zyiliang@ucdavis.edu
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: My Twitter
          link: "https://twitter.com/LiangZhengyi"

      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
#      form:
#        provider: netlify
#        formspree:
#          id:
#        netlify:
          # Enable CAPTCHA challenge to reduce spam?
#          captcha: false
    design:
      columns: '2'
---

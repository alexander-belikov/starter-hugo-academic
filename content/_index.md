---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
#      text:
  - block: collection
    id: posts
    content:
      title: Posts
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
  - block: collection
    id: publications
    content:
      title: Publications
      subtitle: 
      text: 
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - publication
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
    design:
      columns: '2'
  - block: collection
    id: talks
    content:
      title: Recent Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: contact
    id: contact
    content:
      title: Contact
      text: |-
        Feel free to contact me. I am open to collaborations.
      # Contact (add or remove contact options as necessary)
      email: a.belikov@gmail.com
      # Automatically link email and phone or display as text?
    design:
      columns: '2'
---

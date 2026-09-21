---
title: Courses
summary: My courses
type: landing

# Template demo content - hidden from the built site.
build:
  render: never
  list: never

cascade:
  - target:
      path: '{/courses/**}'
    build:
      render: never
      list: never
  - target:
      path: '{/courses/*/**}'
    type: docs
    params:
      show_breadcrumb: true

sections:
  - block: collection
    id: courses
    content:
      title: Courses
      filters:
        tag: Course
        kinds:
          - section
    design:
      view: article-grid
      show_read_time: false
      show_date: false
      show_read_more: false
      columns: 1
---

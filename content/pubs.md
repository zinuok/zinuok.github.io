---
title: "Publications"
slug: "pubs"        # 이 페이지의 URL = /pubs/
type: landing       # 블록(섹션)을 쓰는 랜딩 페이지 타입

sections:
  - block: collection
    id: all-publications
    content:
      title: "All Publications"
      subtitle: ""
      text: ""
      count: 0

      filters:
        folders:
          - publication
        author: ""
        category: ""
        tag: ""
        publication_type: ""
        featured_only: false
        exclude_featured: false
        exclude_future: false
        exclude_past: false

      offset: 0
      sort_by: "Date"
      sort_ascending: false

    design:
      view: card
      columns: "3"
---

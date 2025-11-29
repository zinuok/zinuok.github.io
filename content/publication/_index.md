---
title: "Publications"
type: landing   # 섹션/블록을 쓸 수 있는 랜딩 페이지

sections:
  - block: collection
    id: publications
    content:
      title: "All Publications"
      subtitle: ""
      text: ""
      count: 0              # 0 = 모든 논문 다 보여주기

      filters:
        folders:
          - publication     # content/publication/ 아래 폴더들
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
      view: card            # 카드 뷰
      columns: "3"          # 한 줄에 3개
---

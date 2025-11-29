---
title: "Publications"
type: landing   # 블록(섹션)을 쓸 수 있는 일반 페이지 타입

sections:
  - block: collection
    id: all-publications
    content:
      title: "All Publications"
      subtitle: ""
      text: ""
      # 0 = 모든 페이지 다 보여주기
      count: 0

      filters:
        folders:
          - publication   # content/publication/ 아래의 논문들
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
      view: card      # 여기서 카드 뷰!
      columns: "3"    # 한 줄에 카드 3개
---

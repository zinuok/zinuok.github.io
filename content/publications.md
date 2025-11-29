---
title: "Publications"
type: landing   # 블록(섹션)들을 쓸 수 있는 페이지 타입

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
        # 각 논문이 들어있는 폴더
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
      # 여기서 카드 레이아웃 선택
      view: card      # card, compact, article-grid 등 가능
      columns: "3"    # 한 줄에 카드 3개
---

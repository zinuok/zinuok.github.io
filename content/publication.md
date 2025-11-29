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
      count: 0  # 0 = 모든 publication 다 보여주기

      filters:
        folders:
          - publication   # content/publication/ 아래 파일들
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
      view: card      # ★ 여기서 카드 뷰 선택
      columns: "3"    # 한 줄에 카드 3개
---

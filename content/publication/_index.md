---
title: "Publications"
type: landing

sections:
  - block: page_collection
    id: publications-grid
    content:
      title: "All Publications"
      text: ""
      # 0 = 모든 페이지 다 보여주기
      count: 0
      filters:
        folders:
          - publication   # content/publication 아래 모두
        exclude_featured: false
    design:
      view: card          # grid 형태 카드 레이아웃
      columns: 3          # 최대 3열 그리드
---

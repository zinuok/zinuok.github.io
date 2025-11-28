---
title: "Publications"
type: landing

sections:
  - block: collection
    id: publications-grid
    content:
      title: "All Publications"
      subtitle: ""
      text: ""
      # 0 = 모든 페이지 다 보여주기
      count: 0
      # 어떤 컨텐츠를 모을지 필터
      filters:
        folders:
          - publication     # content/publication/ 아래의 모든 글
        author: ""
        category: ""
        tag: ""
        publication_type: ""
        featured_only: false
        exclude_featured: false
        exclude_future: false
        exclude_past: false
      # 정렬 옵션
      offset: 0
      sort_by: "Date"
      sort_ascending: false
    design:
      # 카드/그리드 스타일 뷰
      view: card
      # 컬럼 수 (문서에선 문자열로 씀)
      columns: "3"
---

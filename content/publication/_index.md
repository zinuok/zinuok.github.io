---
title: "Publications"
type: landing   # 중요! 카드 섹션을 쓸 수 있는 랜딩 페이지 타입

sections:
  - block: collection
    id: publications
    content:
      title: "All Publications"
      subtitle: ""
      text: ""
      # 0 = 모든 페이지 다 보여주기
      count: 0
      filters:
        # 어떤 폴더에서 컨텐츠를 가져올지
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
      # 정렬 옵션 (최신순)
      offset: 0
      sort_by: "Date"
      sort_ascending: false
    design:
      # 여기서 카드 스타일 지정
      view: card      # 'card', 'compact', 'article-grid' 등 중 선택
      columns: "3"    # 한 줄에 카드 3개
---

```mermaid
gantt
    dateFormat  YYYY-MM-DD
    axisFormat  %Y-%m-%d
    title       프로젝트 일정표
    excludes    weekends saturday,sunday
    
    section 문서화
    제안서 작성     :done,    a, 2023-08-15, 2d
    구성도 작성     :active,    b, 2023-08-17, 1d
    설치 메뉴얼     :c, after b, 5d
    시연 PPT        :after c, 2d

    section 구현
    
```

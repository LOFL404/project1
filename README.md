```mermaid
gantt
    dateFormat  YYYY-MM-DD
    axisFormat  %Y-%m-%d
    title       프로젝트 일정표
    excludes    weekends saturday,sunday
    
    section 문서화
    제안서 작성     :done,    a, 2023-08-15, 2d
    구성도 작성     :active,    b, 2023-08-17, 1d
    설치 메뉴얼     :c, after b, 4d
    시연 PPT        :after c, 1d

    section 구현
    http            :done,    d, 2023-08-18, 1d
    도커            :done,    e, 2023-08-19, 1d
    sonarqube       :done,    f, 2023-08-20, 1d
    jenkins         :done,    g, 2023-08-21, 2d
     
    
```

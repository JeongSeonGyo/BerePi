

  - 전력측정 방법
    - JSON 인터페이스
    - 시스템 통합
    - CT 센서
    
  - 미터기 API
    - http://125.7.128.53:4242/api/query?start=2015/06/26-00:00:00&m=sum:gyu_RC1_etype.t_current{nodeid=911}
    - http://125.7.128.53:4242/#start=24h-ago&m=sum:gyu_RC1_thl.temperature{nodeid=924}&o=axis%20x1y2&m=sum:gyu_RC1_thl.batt{nodeid=923}&o=&m=sum:gyu_RC1_thl.temperature{nodeid=916}&o=axis%20x1y2&yrange=[2000:3100]&key=out%20bottom%20center&wxh=400x300&autoreload=15


    - http://125.7.128.53:4242/api/query?start=1m-ago&m=sum:gyu_RC1_etype.t_current{nodeid=911}
    
  - 월간 소비량 계산
    - Recent Value access 구현 필요
    

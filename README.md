# 조용현 | Backend / Software Engineer

대용량 데이터 환경에서 문제를 재현하고, 데이터 접근 구조와 동시 요청 처리 방식을 개선해 성능과 안정성을 높여온 백엔드 엔지니어입니다.
게시글 100만 건, 댓글 1,000만 건, 좋아요 450만 건 규모를 가정한 환경에서 병목을 수치로 확인하고 해결 방식을 선택해왔습니다.
단순한 성능 개선에 그치지 않고, 배포 자동화, 문서 자동화, 모니터링과 장애 알림까지 직접 구성하며 개발과 운영이 이어지는 흐름을 다뤄왔습니다.

## Featured Projects

### [Popping Server](https://github.com/Popping-community/Popping-Server)

Spring Boot 기반 커뮤니티 서비스입니다. EC2 단일 인스턴스 환경에서 대용량 조회 병목과 동시성 문제를 부하 테스트로 재현하고, 쿼리 로그와 모니터링 지표로 원인을 분석해 개선했습니다.

- 인기 게시글에서 반복 수행되던 댓글 트리 생성을 인메모리 캐시로 줄여 응답 지연을 완화
- 동시 좋아요 요청에서 유니크 제약 예외가 발생하던 문제를 멱등 처리로 안정화
- 대용량 좋아요 데이터에서 집계와 개인화 조회를 분리해 느린 응답과 에러율을 동시에 해소

### [PoppingOps](https://github.com/Popping-community/popping-openclaw-ops-agent)

EC2에서 운영 중인 서비스를 Railway 외부 환경에서 감시하고, Discord로 상태 조회와 장애 알림을 제공하는 운영 모니터링 시스템입니다.

- 로컬 PC에 의존하던 모니터링을 외부 상시 감시 구조로 전환
- 정기 감지와 해석 경로를 분리해 비용과 장애 전파 범위를 줄이는 구조로 설계
- snapshot freshness, self-monitoring, runbook-first 대응으로 감지 신뢰성을 높임

### [FINNA](https://github.com/Finna-GDSC/DoFarming_SERVER)

4인 팀 프로젝트에서 백엔드 전체를 맡아 문서화와 배포 자동화를 구축한 경험을 담은 저장소입니다.

- 테스트 기반 API 문서화를 도입해 코드와 문서의 어긋남을 줄임
- GitHub Actions, Jib, EC2 배포 자동화로 팀이 기능 개발과 검증에 더 집중할 수 있게 함

## Tech

`Java` `Spring Boot` `Spring Data JPA` `Spring Security` `MySQL` `In-Memory Cache` `AWS EC2` `Docker` `GitHub Actions` `JMeter` `Prometheus` `Grafana` `Railway` `Bash` `Spring REST Docs`

## Links

- Portfolio: https://chooh1010.github.io/resume/portfolio.html
- Blog: https://velog.io/@chooh1010/posts
- Email: chooh1010@gmail.com

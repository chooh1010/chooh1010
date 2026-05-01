# 조용현 | Backend / Software Engineer

문제의 원인을 측정하고, 구조를 바꿔 성능과 안정성을 개선하는 백엔드 엔지니어입니다.
대용량 조회, 동시성 제어, 운영 자동화를 직접 설계하고 수치로 검증하는 방식으로 일합니다.
Spring Boot, MySQL, 캐시, 모니터링을 중심으로 서비스가 실제로 느려지는 지점을 찾아 개선해왔습니다.
코드 구현에 그치지 않고 배포, 모니터링, 장애 대응까지 이어지는 개발 흐름을 중요하게 봅니다.

## 대표 성과

- 좋아요 집계와 개인화 조회를 분리해 평균 응답시간 `10,460ms -> 167ms`
- 부하 테스트 환경에서 에러율 `15.53% -> 0%`
- 좋아요 동시 요청 경쟁을 멱등 처리로 바꿔 유니크 예외 `0건`

## Featured Projects

### [Popping Server](https://github.com/Popping-community/Popping-Server)

Spring Boot 기반 커뮤니티 서비스입니다. 대용량 조회 병목, 동시성 문제, COUNT 쿼리 제거, 캐시 스탬피드 방지까지 실제 성능 이슈를 직접 해결했습니다.

- 댓글 첫 페이지 캐싱: `152ms -> 43ms`
- 좋아요 집계/개인화 분리: `10,460ms -> 167ms`
- 게시글 목록 `Page -> Slice` 전환으로 COUNT 쿼리 제거

### [PoppingOps](https://github.com/Popping-community/popping-openclaw-ops-agent)

EC2에서 운영 중인 서비스를 Railway 외부 환경에서 감시하고, Discord로 상태 조회와 장애 알림을 제공하는 운영 자동화 시스템입니다.

- 로컬 PC 의존 모니터링 제거
- 감지와 분석 경로 분리
- snapshot freshness, self-monitoring, runbook-first 대응 설계

### [FINNA](https://github.com/Finna-GDSC/DoFarming_SERVER)

팀 프로젝트에서 백엔드 전체를 맡아 API 문서화와 CI/CD 자동화를 구축한 경험을 담은 저장소입니다.

- Spring REST Docs 기반 문서화
- GitHub Actions + Jib 기반 자동 배포

## Tech

`Java` `Spring Boot` `Spring Data JPA` `Spring Security` `MySQL` `In-Memory Cache` `AWS EC2` `Docker` `GitHub Actions` `JMeter` `Prometheus` `Grafana` `Railway` `Bash` `Spring REST Docs`

## Links

- Portfolio: https://chooh1010.github.io/resume/portfolio.html
- Blog: https://velog.io/@chooh1010/posts
- Email: chooh1010@gmail.com

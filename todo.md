# Web Image Downloader Project Todo List

## 1. 프로젝트 초기 설정 및 환경 구성
- [x] Task 1.1: GitHub 리포지토리 초기 설정
- [x] Task 1.2: Python 가상 환경 설정 및 의존성 설치
- [x] Task 1.3: `.env` 기반 설정 관리 구현

## 2. 데이터 관리 (MySQL on OCI)
- [ ] Task 2.1: OCI MySQL DB System (HA) 구축 계획 수립
- [ ] Task 2.2: MySQL 스키마 설계 및 초기화
- [ ] Task 2.3: Python-MySQL 연동 모듈 개발

## 3. 크롤러 코어 개발
- [ ] Task 3.1: Playwright 기반 웹 페이지 탐색 및 로그인 (선택 사항)
- [ ] Task 3.2: 게시글 목록 파싱 및 새 글 감지
- [ ] Task 3.3: 게시글 본문 이미지/첨부파일 URL 추출
- [ ] Task 3.4: 사용자 필터링 로직 구현 (화이트리스트/블랙리스트)
- [ ] Task 3.5: 이미지 다운로드 및 중복 처리
- [ ] Task 3.6: NAS 저장 모듈 개발 (임시 로컬 디렉토리 우선)

## 4. 모니터링 및 로깅
- [ ] Task 4.1: Python 애플리케이션 로깅 설정
- [ ] Task 4.2: Logstash 설정 및 OCI Object Storage 연동 계획
- [ ] Task 4.3: Grafana 설정 및 로그 시각화 계획

## 5. 배포 및 운영 (OCI)
- [ ] Task 5.1: OCI 컴퓨트 인스턴스 프로비저닝 계획
- [ ] Task 5.2: 애플리케이션 컨테이너화 (Docker)
- [ ] Task 5.3: OCI Container Registry (OCIR) 사용 계획

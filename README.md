# SQL Lab 🧪

SQL 학습 및 실험을 위한 환경을 제공하는 레포지토리입니다. 이 레포지토리는 SQL 쿼리 작성 및 최적화 기술을 연습하고 탐구하기 위한 공간으로, 다양한 데이터베이스 환경에서 실습할 수 있도록 설계되었습니다.

## 📚 주요 내용

현재 이 레포지토리는 다음과 같은 내용을 포함하고 있습니다:

- **sql-levelup**: SQL 레벨업 책을 기반으로 한 실습 환경
  - **sql-levelup-db-setting**: PostgreSQL 데이터베이스 환경 설정을 위한 Docker Compose 파일

## 🚀 시작하기

### 사전 요구사항

- [Docker](https://www.docker.com/get-started)
- [Docker Compose](https://docs.docker.com/compose/install/)

### PostgreSQL 실행하기

1. 레포지토리를 클론합니다:
   ```bash
   git clone https://github.com/Livenow14/sql-lab.git
   cd sql-lab
   ```

2. PostgreSQL 컨테이너를 실행합니다:
   ```bash
   cd sql-levelup/sql-levelup-db-setting
   docker-compose -f sql-levelup-compose.yml up -d
   ```

3. 데이터베이스 접속 정보:
   - **호스트**: localhost
   - **포트**: 5432
   - **데이터베이스명**: pgsql
   - **사용자명**: root
   - **비밀번호**: root

## 📋 실습 내용

### SQL 레벨업 학습

`sql-levelup` 디렉토리에서는 『SQL 레벨업』 책의 예제와 연습문제를 실습할 수 있는 환경을 제공합니다. 이 책은 SQL 성능 최적화와 효율적인 쿼리 작성법에 중점을 둡니다.

#### 주요 학습 주제:
- SQL 기본 문법 및 심화
- 인덱스 활용 및 최적화
- 서브쿼리와 조인 최적화
- 윈도우 함수 활용
- 실행 계획 분석

## 🛠️ 사용 도구

- **PostgreSQL 15**: 강력한 오픈소스 관계형 데이터베이스
- **Docker & Docker Compose**: 일관된 환경 구성을 위한 컨테이너 기술

## 🔍 향후 계획

- MariaDB, MySQL 등 다양한 RDBMS 환경 추가
- 실제 데이터셋을 활용한 SQL 실습 예제 추가
- SQL 퍼포먼스 튜닝 가이드라인 문서화
- SQL 고급 기법 및 패턴 라이브러리 구축

## 👨‍💻 기여하기

기여는 언제나 환영합니다! 새로운 예제나 개선 사항이 있으면 Pull Request를 보내주세요.

## 📝 라이센스

이 프로젝트는 [MIT 라이센스](LICENSE) 하에 배포됩니다.

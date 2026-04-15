# 윤태구 포트폴리오

백엔드 / 서버 운영

AWS EC2 환경에서 서버를 직접 구축하고 외부에서 접근 가능한 형태로 운영한 경험이 있습니다.
DB를 구성하고 서버와 연결하여 API가 정상 동작하는 환경을 설정하고 테스트한 경험이 있습니다.

## Portfolio

- 🌐 웹 포트폴리오: [바로 보기](https://sfhk1234.github.io/sfhk1234/)
  
- 📄 PDF 포트폴리오: [바로 보기](./portfolio.pdf)

## 소개

안녕하세요. 컴퓨터소프트웨어학과에 재학 중인 윤태구입니다.
백엔드 및 서버 운영 직무에 관심이 있으며, AWS EC2 기반 서버 구축, DB 연결, 외부 접근 설정, Linux 환경에서의 서버 실행 및 관리 경험이 있습니다.

## 주요 프로젝트

### 1. 군 장병 상벌점 관리 시스템

**역할:** 백엔드 & 인프라 담당
**기술 스택:** NestJS, TypeScript, AWS EC2, Supabase(PostgreSQL), Linux

* EC2 인스턴스 생성 및 Node.js 서버 실행 환경 구성
* 보안 그룹 인바운드 규칙 설정으로 외부 API 접근 허용
* Supabase DB 생성 및 환경 변수 기반 연결 설정
* API 요청/응답 테스트 및 서버 동작 확인

**문제 해결**

* 외부 접속 불가 → 보안 그룹 인바운드 규칙 수정
* DB 연결 실패 → DB URL 환경 변수 재설정 및 연결 테스트

**성과**

* 종이 없이 온라인으로 상벌점 관리 가능
* 기록이 남아 상벌점 부여 과정의 투명성 확보

### 2. AI 기반 부동산 계약 분석 시스템

**역할:** 졸업작품 / 인프라 배포 담당
**기술 스택:** FastAPI, Python, AWS EC2, PostgreSQL, Linux

* 팀원이 작성한 FastAPI 서버를 EC2 환경에 배포
* 포트 오픈 및 보안 그룹 설정으로 외부 접근 구성
* PostgreSQL 연결 후 데이터 저장·조회 동작 확인
* 팀원 접근 가능하도록 SSH 접근 방식 추가 구성

**문제 해결**

* 배포 후 접근 불가 → 보안 그룹·포트 설정 수정
* DB 조회 불가 → 조회 관련 코드 수정으로 해결
* 특정 키 보유자만 접근 가능 → SSH 접근 방식 추가로 협업 환경 개선

**성과**

* 요청 → FastAPI 서버 → DB 저장 흐름을 EC2에서 정상 실행
* 팀원 전원 서버 접근 가능

### 3. Raspberry Pi 기반 NFC 출석 시스템

**역할:** 하드웨어-서버 연동 경험
**기술 스택:** Raspberry Pi, AWS EC2, Linux

* NFC 태그 인식 데이터를 AWS EC2 서버로 전송
* Linux 서버에서 데이터 처리 및 저장 환경 구성
* 하드웨어와 클라우드 서버 간 데이터 흐름 확인

## 기술 스택

**Backend**

* FastAPI (배포 및 실행)
* NestJS (테스트 및 수정)

**Cloud / Infra**

* AWS EC2
* Linux
* 보안 그룹 / 네트워크 설정

**Database**

* Supabase / PostgreSQL
* MySQL

**Language**

* Python
* TypeScript
* JavaScript
* C

## 자격증

* 정보처리기능사
* 네트워크 전문가 2급
* 리눅스마스터 2급
* 인터넷보안전문가 2급

## Contact

* Email: [xorngnlrn13@gmail.com](mailto:xorngnlrn13@gmail.com)
* Phone: 010-9125-1528

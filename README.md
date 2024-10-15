# IT 중고거래 통합 플랫폼 ITGO

[프로젝트 소개] 

- IT전용 중고거래 통합 플랫폼

[역할] 

- 이충민(팀장, 프론트엔드, CI/CD)
- 박재용(백엔드)
- 전주호(백엔드, CI/CD)

[기능] 
- 회원
  - 회원가입 
- 프로필
  - 프로필 조회
  - 프로필 수정
- 기기
  - 전체 기기 리스트 조회
  - 기기 카테고리 조회
  - 카테고리별 기기 리스트 조회
  - 모바일 기기 정보 조회
  - 노트북 기기 정보 조회
- 중고 게시글
  - 전체 게시글 리스트 조회
  - 좋아요한 게시글 리스트 조회
  - 카테고리별 게시글 리스트 조회
  - 위치별 게시글 리스트 조회
  - 게시글 세부 조회
  - 게시글 검색
    - 키워드로 검색
    - 최근 검색 키워드 리스트 조회
- 관심
  - 관심 기기 등록
  - 관심 게시글 등록
  - 관심 위치 등록
  - 관심 기기 삭제
  - 관심 게시글 삭제
  - 관심 위치 삭제
  - 관심 기기 리스트 조회
  - 관심 게시글 리스트 조회
  - 관심 위치 리스트 조회
  - 관심 기기 검색
  - 관심 위치 검색

<br/>

#### 중고 거래 게시글 자동 스크래퍼
- 중고 거래 게시글 스크래핑
  - 게시글에서 GPT를 사용해 제품명 추출
  - 중복을 제외한 게시글 데이터베이스에 저장

[기술 스택]
- Server
  - Java 17
  - Spring Boot 3.1.4
  - Spring Data JPA
- Testing
  - Mockito
  - Junit 5
  - Postman
- Scrapper
  - Python 3
  - FastAPI
- DB
  - MySQL
  - MongoDB
- DevOps
  - AWS EC2 (Ubuntu)
  - AWS RDS
  -  MongoDB Atlas
  -  Nginx
  -  Jenkins
  -  Docker
  -  Github
- Communication
  - Notion
  - Swagger



##Backend System Architecture
SystemArchitecture
![SystemArchitecture drawio](https://github.com/user-attachments/assets/da378ddc-c498-4f32-8428-7fee6acb3104)


##Backend Deploy Architecture
DeployArchitecture
![DeployArchitecture drawio](https://github.com/user-attachments/assets/e5aeef39-ea4b-41fa-8242-984fe58f5036)

## 구성한 페이지

https://www.figma.com/design/U98Pt2xI8Leu7aiasFlznH/Untitled?node-id=0-1&t=Eb9Zr1Tfvp6GLiVT-1
